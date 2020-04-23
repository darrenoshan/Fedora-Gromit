# Fedora-Gromit
Script to install Gromit-MPX on fedora linux

this is a personal simple script to install Gromit-MPX on fedora linux 


```
sudo su
dnf install gtk3 gtk3-devel libappindicator-gtk3-devel cmake -y
git clone https://github.com/bk138/gromit-mpx.git
cd gromit-mpx && mkdir build
cd build
cmake ..
make
make install
```
