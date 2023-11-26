
![banner](https://raw.githubusercontent.com/Old-Crocs/script/main/afterlife_banner.png)
# AfterLife Project

## Getting Started ## 
---------------
To get started with the AfterLife sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

### Requirements
- Around 500GB disk space.
- Around 16GB RAM running Linux.

To initialize your local repository, use command:

```bash
repo init --depth=1 --no-repo-verify -u https://github.com/AfterLifePrjkt13/android_manifest.git -b LTS -g default,-mips,-darwin,-notdefault
```

## Then sync up: ##

```bash
repo sync -c --no-clone-bundle --no-tags --optimized-fetch --prune --force-sync -j8
```

### Build our source ###

```bash
. build/envsetup.sh
lunch afterlife_$devicecodename-userdebug
m afterlife -j$
```

-----------------------------------------------------------------------------
Credits:
=======
 * [**CAF**](https://source.codeaurora.org)
 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**ArrowOS**](https://github.com/ArrowOS)
 * [**DroidX-UI**](https://github.com/DroidX-UI)
-----------------------------------------------------------------------------
