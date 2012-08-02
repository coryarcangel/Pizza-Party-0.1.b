pizza_party 0.1 beta

2004

---------------

Introduction
------------
pizza_party is a command-line utility for ordering customized Domino's Pizza (tm) to your door.


Overview
--------
This software is written for people who spend so much time at the command-line that they don't have
time to pick up the phone and call Dominos, or even to go thru the many-step process of using Dominos
web interface.  

pizza_party comes with one executable, written in Perl, and a man page.


Installation
------------
As pizza_party is written for command-line junkies, so too are these installation instructions.

1) presumably, you've already downloaded and extracted the .tar.gz file which contained this README.
2) make sure you're got the following Perl modules (and all their dependecies) installed:

      LWP::UserAgent;
      HTTP::Request;
      HTTP::Response;
      HTTP::Cookies;
      URI::Escape;
      Getopt::Mixed;

   if you don't know how to install Perl modules, you're clearly not hard enough to be ordering pizza
   at the command line.

3) place the pizza_party executable (./pizza_party) somewhere in your path -- /usr/local/bin should work fine.
4) place the man page (./man/pizza_party.1) in the usual man location -- /usr/local/man/man1/ is typical.
5) go to http://www.dominos.quikorder.com/ and get an account
6) if you want to, make a .pizza_partyrc file in your home directory with your username and password and,
   optionally, other default settings.  The structure of this file described in the man page.
7) order pizza, pay for it, tip your delivery guy well, and enjoy.

Licensing
---------
pizza_party, is distributed under the GPL.

See http://www.gnu.org/copyleft/gpl.html if you don't know what the GPL is.


Credits
-------
Cory Arcangel
Michael Frumin, Eyebeam R&D
