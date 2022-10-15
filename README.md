# Franxx-OS

 To initialize your local repository, use command:

```bash
repo init -u https://github.com/Franxx-OS/manifest.git -b 13
```
### Sync ###
```
repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```

### Build ###

```
$ . build/envsetup.sh
$ lunch aosp_$device-user
$ mka bacon -j$(nproc --all)
```
For becoming an official FranxxOS Maintainer get in touch
with the dev on telegram:@kickout_765 

## Thanks section ##

Here's my thanks to people who made this possible:
* PixelOS 
* VoidUI
* LessAOSP 
* DerpFest
* Crdroid
* Pixel experience
* Chrish OS
