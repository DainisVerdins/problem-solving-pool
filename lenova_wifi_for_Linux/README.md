# Linux and Lenova and WI FI driver  
How to make aviable to add wifi option to Lenova notebooks(Ideapads, e,t,c) if you are using Linux
on Lenova laptops.  
Worked  for Ubuntu LTS 20.01 and Linux Mint 20.1 

Type the following commands into a terminal window
```shell
$ sudo add-apt-repository ppa:canonical-hwe-team/pc-oem-dkms
$ sudo apt update
$ sudo apt install backport-iwlwifi-dkms
$ sudo modprobe iwlwifi
$ sudo reboot
```  
Complete eatch step , if error just ignore.




[SEE MORE HERE| installing|configuration and more options how to install wi-fi driver](https://download.lenovo.com/pccbbs/mobiles_pdf/LenovoThinkpad_P53_P73_Ubuntu_18.04_LTS_Installation_v1.0.pdf)