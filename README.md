PS2 Intro Loader - Pubic Releases
------------------------------------------------------------------------------------------------------------------------------


Description
---------------------
PS2 Intro Loader is a homebrew application that enables you to play a custom intro video file on your PlayStation 2. It will then exit to a specified ELF stored on your Memory Card.

It is designed to be launched on console boot as AUTO E1 Launch Key via FMCB/FHDB.

Basic Usage
---------------------
Place a video file named 'intro.avi' onto the root of USB device. E.g. mass:/intro.avi
Place INTROLDR.ELF on either MC, when first launched it will create an 'INTRO' folder containing a config file on MC.
The default ELF that will be launched on exit is mc1:/BOOT/BOOT.ELF - if not found, the Browser will be launched.
If launched from any device other than MC, the default settings will be used and the Browser will be launched on exit.
Run INTROLDR.ELF - via FMCB, LaunchELF or any other homebrew ELF launcher.

Advanced Usage
---------------------
The config file can be customised and either USB or HDD can be specified for source of video.
If using internal HDD, ensure that video is stored in the 'common' partition. E.g. pfs:/__common/intro.avi
The video mode can also be specified in the config file, the options are: AUTO, NTSC, PAL, and 720p.
The exit path can be customised to launch any ELF stored on your MC in either slot.
The intro video filename can also be changed by editing the config file.

Support Media Types
---------------------
Only media files supported by Simple Media System(SMS) can be used.  For the AVI container (.avi), SMS supports DivX and Xvid codecs. SMS also supports MPEG-2 video.

It is advisable to test any videos in SMS v2.9 R4 before using them with PS2 Intro Loader. 

There are many tools freely available to convert any videos to XVID format.

Credits
---------------------
PS2 Intro Loader was developed using a heavily modified version of Simple Media System (2.9 R4). Full credit and thanks to the original author Eugene Plotnikov (http://members.casema.nl/eugene_plotnikov/) for his work and sharing the original source code.

Thanks to doctorxyz and belek666 for updating it to compile with the lasest PS2SDK (https://github.com/doctorxyz/sms) (https://github.com/belek666/sms).

Thanks to sp193 for his time, advice and dedication to PS2 homebrew in general.

Thanks to UniqueUserName R.I.P. for keeping together all the different SMS repositories and his enthusiasm for both the PS2 and SMS (http://psx-scene.com/forums/f111/sm...hread-actively-seeking-new-developers-157677/).

Note
---------------------
This is one of our first attempts at customising a C/C++ program on dedicated PS2 hardware, so feedback is welcome at the official release site: https://www.psx-place.com/threads/ps2-intro-loader-v1-0.23004/ 

This is NOT an attempt to bypass the FMCB logo. In fact, FMCB/FHDB is required for this application to function as intended.

Please distribute freely. The creators of this application are not liable for any damage that may be caused.

Development Team
---------------------
Krah.Johlito, Dekkit, Tupakaveli.






Please note psx-place is the official thread for any questions, general support, or future versions.
https://www.psx-place.com/threads/ps2-intro-loader-v1-0.23004/ 
