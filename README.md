htop with CPU Freq and CPU Temp
-------------------------------

**htop** Ubuntu deb packages modified to display CPU Frequency and CPU Temperature.

* Ubuntu 16.04
* Ubuntu 18.04


# arm64

* Ubuntu 18.04

Installing **htop**:

	sudo dpkg -i ./htop_2.1.0-3_arm64.deb 


[![htop](https://github.com/avafinger/htop/raw/master/img/arm64-htop-2.1.0-2.png)]

[![htop](https://github.com/avafinger/htop/raw/master/img/arm-64-htop-2.1.0.png)]

[![htop](https://github.com/avafinger/htop/raw/master/img/arm64-htop-f3.png)]

M64 under high workoad and kernel 4.4.89+
[![htop](https://github.com/avafinger/htop/raw/master/img/m64_build.png)]


* Ubuntu 16.04

Installing **htop**:

	sudo dpkg -i ./htop_2.0.1-1ubuntu1_amd64.deb 


# armhf



# amd64

* Ubuntu 16.04

Installing **htop**:

	sudo dpkg -i ./htop_2.0.1-1ubuntu1_amd64.deb 


[![htop](https://github.com/avafinger/htop/raw/master/img/amd64-htop-2.0.1.png)]


# Uninstalling

If you want to restore the stock package for any reason, type in shell:

	sudo apt-get remove --purge htop

and then:

	sudo apt-get install htop

# Configuring

After install, please type F2 and add **CpuTemp** and/or **CpuFreq**


Issues
------
htop 2.1.0 display info (ubuntu 18.04 - arm64) via ssh is broken.