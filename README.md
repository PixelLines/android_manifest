# PixelLines

## Getting Started

To initialize your local repository, run:

```bash
repo init -u https://github.com/PixelLines/android_manifest.git -b sixteen --git-lfs
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
