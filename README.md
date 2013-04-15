broodROM Jellybean Manifest
===========================
Version: Release 4
-------------

You may clone broodROM JB manifest for educational purposes only.
Releasing broodROM JB is not allowed, unless you ask me permission to build it for an other device

- Main Site: www.broodplank.net
- XDA Topic: http://forum.xda-developers.com/showthread.php?t=2171292




Download:
===========================
- mkdir ~/broodROM
- cd ~/broodROM
- repo init -u git://github.com/broodplank/android -b jellybean
- repo sync

(Advised is repo sync, using the -j option can cause timeouts while downloading from github)
 
 

 
Initialize, Build, Pack, Sign:
===========================
- cd ~/broodROM
- ./build.sh

The output will be a ready to install CWM zip in the root folder. (i9001 based)


