![banner](https://raw.githubusercontent.com/AfterlifeOS/vendor_AfterUI/14/banner/manifest.jpg)
# AfterlifeOS

## Getting Started ##
---------------
To get started with the AfterLife sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

### Requirements
- Around 500GB disk space.
- Around 16GB RAM running Linux.

To initialize your local repository, use command:

```bash
repo init --depth=1 -u https://github.com/AfterlifeOS/manifest.git -b 14 --git-lfs
```

## Then sync up: ##

```bash
repo sync -c --no-clone-bundle --no-tags --optimized-fetch --prune --force-sync -j8
```

### Build our source ###

```bash
. build/envsetup.sh
goafterlife <device-codename>
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
