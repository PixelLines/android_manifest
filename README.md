# PixelLines AOSP

<img width="1080" height="540" alt="PixelLines" src="https://github.com/user-attachments/assets/f078887e-1bd2-4f67-8afe-91f837da2ab0" />

## Getting Started

To get started with the PixelOS source code, you'll need to be
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

To initialize your local repository, run:

```bash
repo init -u https://github.com/PixelLines/android_manifest.git -b seventeen --git-lfs
```

Then, sync the repository:

```bash
repo sync
```

## Building the System

Initialize the ROM build environment by sourcing the envsetup.sh script:

```bash
source build/envsetup.sh
```

After cloning the device-specific sources, use breakfast to configure the build for your device:

```bash
breakfast devicecodename
```

Start the compilation:

```bash
m pixellines
```
