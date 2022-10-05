# Firmware Binaries

This repository contains various UEFI firmwares extracted using https://github.com/theopolis/uefi-firmware-parser

## How to reproduce

```
uefi-firmware-parser -O -b -g {name that the folder is gonna have} ./11
```

Where ```./11``` is an UEFI image.

Note: Open up the folders and see if there's an .obj about 2MB, if there is and it isn't extracted(check with 7zip), then use the program on that file
Note2: To see the revision string open up .te files in 7zip, you'll find them somewhere :P
