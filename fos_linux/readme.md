

```
# Setup FOS Project Environment

## Install Required Packages

sudo apt-get install -y make
sudo apt-get install -y qemu-system
```

## Download Archives from GitHub

Click on the "Download" button to get the required archives.

## Remove Unnecessary Folders

```bash
# Remove the "cross" folder in /opt and the ".vscode" folder in fos_cygwin.
# Extract cross.rar and .vscode.rar, then move the "cross" folder to fos_cygwin/opt 
# and the ".vscode" folder to fos_cygwin.
```

## Add Toolchain to PATH

```bash
# Example of adding the toolchain to the PATH
export PATH="/home/ahmed/fos_cygwin/opt/cross/bin:$PATH"
```

## Resolve Missing "i386-elf" Error

```bash
# If you encounter an error like "i386-elf" is missing,
# ensure it's added to the PATH using export.
# Additionally, install the required 32-bit libraries for a 64-bit system.
sudo dpkg --add-architecture i386
sudo apt-get update
sudo apt-get install libc6:i386 libncurses5:i386 libstdc++6:i386
```

## Resolve Permission Error for "i386-elf"

```bash
# If you encounter a permission error for "i386-elf",
# navigate to the fos_cygwin directory and update permissions.
cd fos_cygwin
sudo chmod -R +x opt/cross
```

