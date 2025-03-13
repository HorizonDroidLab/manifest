# HorizonDroid

## Getting Started

To get started with the HorizonDroid sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

To initialize your local repository, use command:

```bash
repo init -u https://github.com/HorizonDroidLab/manifest.git -b fifteen --git-lfs
```

Then sync up:

```bash
repo sync
```

## Building the System

Initialize the ROM environment with the envsetup.sh script.

```bash
. build/envsetup.sh
```

Lunch your device after cloning all device sources if needed.

```bash
lunch horizon_devicecodename-bp1a-buildtype
```

Start compilation

```bash
mka horizon
```