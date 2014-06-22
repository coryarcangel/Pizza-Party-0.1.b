                                                         ._
                                                       ,(  `-.
                                                     ,': `.   `.
                                                   ,` *   `-.   \
                                                 ,'  ` :+  = `.  `.
                                               ,-  (o):  .,   `.  `.
                                             ,'  ; :   ,(--) x;`.  ;
                                           ,'  :'  itz  ;  ; ; _,-'
                                         .'O ; = _' C ; ;'_,_ ;
                                       ,;  _;   ` : ;'_,-'   i'
                                     ,` `;(_)  0 ; ','       :
                                   .';6     ; ' ,-'-
                                 ,' Q  ,& ;',-.'
                               ,( :` ; _,-'-  ;
                             ,-.`c _','
                           .';^_,-' -
                         ,'_;-''
                        ,,-
                        i'
                        :
 ____                   			
/    \                              //\        PPPPP IIII ZZZZZ ZZZZZ    A
  u  u|      _______               // O \      PP  PP II    ZZ    ZZ    A A
    \ |  .-''#%&#&%#``-.          || O o  \    PPPPP  II   ZZ    ZZ    AAAAA
   = /  ((%&#&#&%&VK&%&))         ||__o__O__\  PP    IIII ZZZZZ ZZZZZ A     A
    |    `-._#%&##&%_.-'   			
 /\/\`--.   `-."".-'				
 |  |    \   /`./          			
 |\/|  \  `-'  /					
 || |   \     /            VK		
 

Pizza Party (0.1 beta)

Cory Arcangel & Michael Frumin, 2004

http://www.coryarcangel.com
http://www.frumin.net/ation/

Introduction
------------
pizza_party is a command-line utility for ordering customized Domino's Pizza (tm) to your door.


Overview
--------
This software is written for people who spend so much time at the command-line that they don't have time to pick up the phone and call Domino's, or even to go thru the many-step process of using Domino's web interface.  

pizza_party comes with one executable, written in Perl, and a man page.


Installation
------------
As pizza_party is written for command-line junkies, so too are these installation instructions.

1) presumably, you've already downloaded and extracted the .tar.gz file which contained this README.

2) make sure you've got the following Perl modules (and all their dependencies) installed:

      LWP::UserAgent;
      HTTP::Request;
      HTTP::Response;
      HTTP::Cookies;
      URI::Escape;
      Getopt::Mixed;

   if you don't know how to install Perl modules, you're clearly not hard enough to be ordering pizza at the command line.

3) place the pizza_party executable (./pizza_party) somewhere in your path -- /usr/local/bin should work fine.

4) place the man page (./man/pizza_party.1) in the usual man location -- /usr/local/man/man1/ is typical.

5) go to http://www.dominos.quikorder.com/ and get an account

6) if you want to, make a .pizza_partyrc file in your home directory with your username and password and, optionally, other default settings.  The structure of this file described in the man page.

7) order pizza, pay for it, tip your delivery guy well, and enjoy.

Licensing
---------
pizza_party, is distributed under the GPL.

See http://www.gnu.org/copyleft/gpl.html if you don't know what the GPL is.

                                                                 ___
                                                                 |  ----.
                                                                 |%=@%%/
                                                                 |o%%%/
                     __                                          |%%o/
               _,---- |      ._                                  |(_/
            ,/'  m%%%%|     /  `\.                               |o/
           /' m%%o(_)%|    /o%%m `\                              |/
         /' %%@=%o%%%o|   /(_)o%%% `\
        /  %o%%%%%=@%%|  /%%o%%@=%%  \
       |  (_)%(_)%%o%%| /%%%=@(_)%%%  |
       | %%o%%%%o%%%(_|/%o%%o%%%%o%%% |
       | %%o%(_)%%%%%o%(_)%%%o%%o%o%% |
       |  (_)%%=@%(_)%o%o%%(_)%o(_)%  |
        \ -%%o%%%%%o%o%=@%%o%%@%%o%- /
         \. -o%%(_)%%%o%(_)%%(_)o- ,/
           \_ -o%=@%(_)%o%%(_)%- _/
             `\_--o%%%o%%%%%--_/'
                `--..____,,--'

"I always wanted to be a basketball player." - Ronnie James Dio
