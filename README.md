# Lightweight Communications and Marshalling (LCM)

LCM is a set of libraries and tools for message passing and data marshalling,aimed towards real-time applications that require high bandwidth and low latency. It has a publish/subscribe message forwarding model, as well as automatic marshalling/unmarshalling code creation and bindings for a variety of programming languages.

# LINKS
* [LCM Github](https://github.com/lcm-proj/lcm/releases)
* [Website and documentation](https://lcm-proj.github.io)
* [LCM Python Initialization](https://lcm-proj.github.io/tut_python.html)


## Installation

# LINUX
# DEBIAN(UBUNTU)
1-Installing git
```
apt-get install git
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
 sudo apt-get install python-dev
sudo apt-get install python3-dev
```
8- Installing LCM
```
cd ..
cd lcm-python
sudo python3 setup.py install
```
