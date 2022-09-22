# memodemo.cop

## Places
* heliAM:   
-appraiser platform
* bootMem:  
-region of protected memory used for storing the booted seL4 image loaded onto the groundstation target platform
* platAM:   
-priviledged native seL4 (CAmkES) partition on groundstation target platform that has read access to memory at userAM and bootMem
* userAM:   
-linux VM running inside its own CAmkES partition on the target