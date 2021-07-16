# TWRP Device Tree for Samsung Galaxy J4 (j4lte)

### How To Build

```
# Create workspace folder
$ mkdir ~/twrp-9
$ cd ~/twrp-9

# Clone TWRP source
$ repo init --depth=1 -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-9.0
$ repo sync

# Clone device tree
$ git clone https://github.com/HendraLab/device_samsung_j4lte -b android-9.0 device/samsung/j4lte

# Start build!
$ . build/envsetup.sh
$ lunch omni_j4lte-eng
$ mka recoveryimage
```

### License

```
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0
```
