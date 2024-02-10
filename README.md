# HorizonDroid

![HorizonDroid](https://github.com/HorizonDroid-13/.github/blob/main/Vega%20Update%20ROM%20A14.png)

Getting Started
---------------
To get started with the HorizonDroid sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

 To initialize your local repository, use this command:
-----------------------------------------------------

    repo init -u https://github.com/HorizonDroidLab/manifest.git -b 14 --git-lfs

To sync the repository, use this command:
-----------------------------------------

    repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune

To Build, use following commands:
---------------------------------
    
    . build/envsetup.sh
    lunch aosp_<devicecodename>-userdebug
    m bacon

### Important Links

- [Telegram channel](https://t.me/horizondroid)
- [Telegram group](https://t.me/HorizonDroidChat)

---------------------------------------------------------------------------------------------------------

Special thanks to All ROM Developers in this community
