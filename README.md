
![banner](https://raw.githubusercontent.com/Old-Crocs/script/main/afterlife_banner.png)
# AfterLife Project

## Getting Started ## 
---------------
To get started with the ClownUI sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

### Requirements
- Around 500GB disk space.
- Around 16GB RAM running Linux.

To initialize your local repository, use command:

```bash
repo init -u https://github.com/AfterLifePrjkt13/android_manifest.git -b tiramisu
```

## Then sync up: ##

```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build our source ###

```bash
. build/envsetup.sh
lunch afterlife_$devicecodename-userdebug
make afterlife -j$
```

-----------------------------------------------------------------------------
Credits:
=======
 * [**CAF**](https://source.codeaurora.org)
 * [**AOSP**](https://android.googlesource.com)
 * [**ProtonPlus**](https://github.com/protonplus-org)
 * [**SuperiorOS**](https://github.com/SuperiorOS)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**ArrowOS**](https://github.com/ArrowOS)
 * [**Xdroid OSS**](https://github.com/xdroid-oss)
 * [**AncientOS**](https://github.com/ancient-lab)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**PixelOS**](https://github.com/PixelOS-AOSP)
 * [**ProjectBlaze**](https://github.com/ProjectBlaze)
-----------------------------------------------------------------------------
