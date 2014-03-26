Mini-vMac-Unix
==============

Unix/Linux fork for Mini vMac, 64-bit only version.   
   
##How it works
I just generated it from original source .dsk using my own PowerBook 5300c, and turns out it wants the ROM file be in the same spot as the program is which seemed a liitle bit silly...   
   
So basically I patched the source and pointed it into "/usr/share", to make it make somewhat more sense. Still working into making it dynamic but not hard coded in a single header file.   

##How to compile
This source only works with Unix/Linux under x86_64 architecture, just simply apply the patch in the source root and make... I packaged it for AOSC distros so you can just apt-get to obtain the software.   

##Who maintains it
Jeff Bai <jeffbaichina@members.fsf.org>
