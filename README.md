For Kernel 4.15.x ~ 5.9.x (Linux Mint, Ubuntu or Debian Derivatives)

------------------

## How to install

`sudo apt-get install build-essential git dkms linux-headers-$(uname -r)`

`git clone https://github.com/kelebek333/rtl8192fu-dkms`

`sudo dkms add ./rtl8192fu-dkms`

`sudo dkms build rtl8192fu-dkms/5.8.6.2`

`sudo dkms install rtl8192fu-dkms/5.8.6.2`


------------------

## How to uninstall

`sudo dkms remove rtl8192fu-dkms/5.8.6.2 --all`


------------------

## How to install from PPA repository

You can install rtl8192fu driver with following commands from PPA.

for xUbuntu 16.04-18.04-20.04-21.10 / Linux Mint 18.x-19.x-20.x

`sudo add-apt-repository ppa:kelebek333/kablosuz`

`sudo apt-get update`

`sudo apt install rtl8192fu-dkms


You can purge packages with following commands

`sudo apt purge rtl8192fu-dkms`