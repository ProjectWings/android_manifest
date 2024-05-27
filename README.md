### WingsOS

### Requirements
- Around 100G disk space.
- A computer with at least 16GB RAM running Linux (recommended) or MacOS.
- Build environment [setup](https://github.com/akhilnarang/scripts).

### Create a directory for the source files & Go into created directory

```
mkdir wings
cd wings
```

### Run the following commands to sync source

```
repo init -u https://github.com/ProjectWings/android_manifest -b ursa --git-lfs
```
### To sync source, enter

```
repo sync -c --no-clone-bundle --optimized-fetch --prune --force-sync -j$(nproc --all)
```

### Once the source is downloaded/synced, prepare your device trees, dependencies and start the build by the following commands

```
source build/envsetup.sh
lunch wings_<devicecodename>-usertype
make bacon -j$(nproc --all)
```

### Compilation Help
To get help with build errors, please visit [**Android Building Help**](https://t.me/AndroidBuildingHelp).

## Credits

 * [**AospExtended**](https://github.com/AospExtended)
 * [**ArrowOS**](https://github.com/ArrowOS)
 * [**ABC-ROM**](https://github.com/ezio84)
 * [**CodeAurora Forum**](https://source.codeaurora.org/quic/la)
 * [**Krypton Open Source Project**](https://github.com/Aosp-Krypton)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**PixelOS-AOSP**](https://github.com/PixelOS-AOSP)
 * [**Project-Fluid**](https://github.com/Project-Fluid)
 * [**ProtonAOSP**](https://github.com/ProtonAOSP)
 * [**ProjectEverest**](https://github.com/ProjectEverest)
 * [**RisingTechOSS**](https://github.com/RisingTechOSS)
 * [**Syberia Project**](https://github.com/syberia-project)
 * [**Yet another AOSP project**](https://github.com/Yaap)
