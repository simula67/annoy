# annoy

When I was working for Hewlett-Packard, I had to work on machines that ran HP-UX on Itanium and SunOS on SPARC. I could not get package managers to work on these systems due to the peculiarities of the HP network

The purpose of this script was to setup bash on these really old machines which ran HP-UX and SunOS. HP-UX did not have wget installed by default, so I had to implement a simple web get functionality in this script

This script could simply be copied and pasted into a vi editor, saved, and run.

It would :

* Detect machine architecture ( Itanium, Sparc etc )
* Download and save a statically linked version of bash
* Download and install a sane bashrc

From here, you can have a more pleasant experience on the machine

This project is abandoned, since I no longer work at HP and I no longer have to deal with these types of machines. This project does not work anymore since Google Code and Gitorious has been abandoned and there seems to be no other way to store versioned source code without HTTPS. Since I do not want to implement HTTPS in Perl, I am abandoning this project
