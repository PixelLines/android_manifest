<img width="800" height="400" alt="PixelLines_logo" src="https://github.com/user-attachments/assets/c30c8314-b17a-4573-ace8-d8f6c1ef2b9a" />

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
