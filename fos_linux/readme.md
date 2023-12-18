sudo apt-get install -y make
sudo apt-get install -y qemu-system

remove cross folder in opt and replace it with cross folder in this repo
and remove .vscode and remplace it with .vscode in this repo
export PATH for opt/cross/bin

if you encouter error like i386-elf missing
make sure it's added to path /*using export*/
try 
##These libraries are often needed to run 32-bit binaries on a 64-bit system.
sudo dpkg --add-architecture i386
sudo apt-get update
sudo apt-get install libc6:i386 libncurses5:i386 libstdc++6:i386
