broodROM Jellybean Manifest
===========================
Version: Release 3
-------------

You may clone broodROM JB manifest for educational purposes only. 
Releasing broodROM JB is not allowed, unless you ask me permission to port it to an other device

- www.broodplank.net




Download:
===========================
- mkdir ~/broodROM
- cd ~/broodROM
- repo init -u https://github.com/broodplank/android -b jellybean
- repo sync -j16 (for 100mbit)
 
 
 
Initialize:
===========================
- . build/envsetup.sh
- lunch > choose full_ariesve-userdebug
 
 

Build: 
===========================
- make (-k) -j#



