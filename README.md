# Lightweight Communications and Marshalling (LCM)

LCM is a set of libraries and tools for message passing and data marshalling,aimed towards real-time applications that require high bandwidth and low latency. It has a publish/subscribe message forwarding model, as well as automatic marshalling/unmarshalling code creation and bindings for a variety of programming languages.

# LINKS
* [LCM Github](https://github.com/lcm-proj/lcm/releases)
* [Website and documentation](https://lcm-proj.github.io)
* [LCM Python Initialization](https://lcm-proj.github.io/tut_python.html)


# INSTALLATION

## LINUX
## DEBIAN(UBUNTU)
1-Installing git
```
sudo apt-get install git
```
2-Downloading Glib and Cmake
```
sudo apt update && sudo apt install build-essential g++ libglib2.0-dev cmake
```
3-Cloning the main [LCM]((https://github.com/lcm-proj/lcm/releases)) Repo
```
git clone https://github.com/lcm-proj/lcm.git
```
4- Creating directory build
```
cd lcm
mkdir build
cd build
```
5- Cmake
```
cmake ..
```
6 - Installing make
```
make
sudo make install
```
7 - Installing python dev
```
 sudo apt-get install python-dev && sudo apt-get install python3-dev
```
8- Installing LCM
```
cd ..
cd lcm-python
sudo python3 setup.py install
```

## ARCH LINUX
## BUILDING PACKAGE MANUALLY FROM AUR

1-Installing git and base-devel package
```
sudo pacman -Sy git base-devel
```
2- Cloning repo from AUR
```
git clone https://aur.archlinux.org/lcm-git.git
```
3- Changing directory to lcm
```
cd lcm
```
4- Building package (will install required dependencies automatically)
```
makepkg -si
```
5- Installing the built package using pacman
```
sudo pacman -U lcm-git.xxxx.pkg.tar.zx
```
## USING AUR HELPER
Refer to https://wiki.archlinux.org/title/AUR_helpers for installing aur helpers

1 - Installing lcm using yay or any other aur helper

```
yay -S lcm
```
or
```
peru -S lcm
```


LCM IS INSTALLED! HAPPY CODING :)
