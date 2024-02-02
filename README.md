# HorizonDroid

![HorizonDroid](https://github.com/HorizonDroid-13/.github/blob/main/Vega%20Update%20ROM%20A14.png)

 Getting Started
---------------
To get started with the HorizonDroid sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

 To initialize your local repository, use command:

```bash
repo init -u https://github.com/HorizonDroidLab/manifest.git -b 14 --git-lfs
```

Then sync up:

```bash
repo sync -c --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune -j$(nproc --all)
```

Building the System
-------------------
 Initialize the ROM environment with the envsetup.sh script.

```bash
. build/envsetup.sh
```

Lunch your device after cloning all device sources if needed.

```bash
lunch aosp_devicecodename-buildtype
```

Start compilation

```bash
make bacon
```
-----------------------------------------------------------------------------

### Important Links

- [Telegram channel](https://t.me/horizondroid)
- [Telegram group](https://t.me/HorizonDroidChat)

-----------------------------------------------------------------------------
Credits:
=======
 * [**PixelOS**](https://github.com/PixelOS-Fourteen)
 * [**CAF**](https://source.codeaurora.org)
 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**DroidX-UI**](https://github.com/DroidX-UI)
 * [**AfterlifeOS**](https://github.com/AfterLifePrjkt13)
 * [**AOSP for Nabu/Marble**](https://github.com/Nabu-upsidedowncake)
 * [**Evolution-X**](https://github.com/Evolution-X)
-----------------------------------------------------------------------------
