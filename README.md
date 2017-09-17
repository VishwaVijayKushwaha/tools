#CROSS-COMPILING for Raspberry pi
Reference https://www.raspberrypi.org/documentation/linux/kernel/building.md

```
git clone https://github.com/raspberrypi/tools ~/

#for 32 bit host system
echo PATH=\$PATH:~/tools/arm-bcm2708/gcc-linaro-arm-linux-gnueabihf-raspbian/bin >> ~/.bashrc
#for 64 bit host system
echo PATH=\$PATH:~/tools/arm-bcm2708/gcc-linaro-arm-linux-gnueabihf-raspbian-x64/bin >> ~/.bashrc

source ~/.bashrc

```
