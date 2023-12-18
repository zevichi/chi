## aaPanel installation script

## For Centos

```yum install -y wget && wget -O install.sh http://www.aapanel.com/script/install_6.0_en.sh && bash install.sh aapanel```

## FOR UBUNTU

```wget -O install.sh http://www.aapanel.com/script/install-ubuntu_6.0_en.sh && sudo bash install.sh aapanel```

## FOR DEBIAN

```wget -O install.sh http://www.aapanel.com/script/install-ubuntu_6.0_en.sh && bash install.sh aapanel```

## Notice:
Ensure that it is a clean operating system, there is no other environment with Apache/Nginx/php/MySQL installed (the existing environment can not be installed)

It is recommended to use Chrome, Firefox, and edge browsers to access the panel login address

## aaPanel Management script

## Stop
```service bt stop```
## Start
```service bt start```
## Restart
```service bt restart```
## Uninstall
```service bt stop && chkconfig --del bt && rm -f /etc/init.d/bt && rm -rf /www/server/panel```

## THANK YOU 
