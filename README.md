## $5 Tech Unlocked 2021!
[Buy and download this Book for only $5 on PacktPub.com](https://www.packtpub.com/product/openstack-networking-essentials/9781785283277)
-----
*If you have read this book, please leave a review on [Amazon.com](https://www.amazon.com/gp/product/1785283278).     Potential readers can then use your unbiased opinion to help them make purchase decisions. Thank you. The $5 campaign         runs from __December 15th 2020__ to __January 13th 2021.__*

#OpenStack Networking Essentials

This is the code repository for [OpenStack Networking Essentials](https://www.packtpub.com/virtualization-and-cloud/openstack-networking-essentials?utm_source=github&utm_medium=repository&utm_campaign=9781785283277), published by Packt. It contains all the supporting project files necessary to work through the book from start to finish.

##Instructions and Navigation

The code included with this book is meant for use as an aid in performing the exercises and should not be used as a replacement for the book itself.
Used out of context, the code may result in an unusable configuration and no warranty is given.

The commands and instructions will look like the following:
```
==== Interface configurations ====

# ifcfg-enp0s3

TYPE=Ethernet
BOOTPROTO=none
DEFROUTE=no
IPV4_FAILURE_FATAL=no
IPV6INIT=no
NAME=enp0s3
DEVICE=enp0s3
ONBOOT=yes
IPADDR=10.254.254.100
PREFIX=24

# ifcfg-enp0s9

TYPE=Ethernet
BOOTPROTO=dhcp
DEFROUTE=yes
IPV4_FAILURE_FATAL=no
IPV6INIT=no
NAME=enp0s9
DEVICE=enp0s9
ONBOOT=yes 

# Enabling interfaces

sudo ifdown enp0s3; sudo ifdown enp0s9; 
sudo ifup enp0s3; sudo ifup enp0s9;
```


##Related OpenStack Products:
* [OpenStack Cloud Computing Cookbook](https://www.packtpub.com/virtualization-and-cloud/openstack-cloud-computing-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781849517324)
* [OpenStack Cloud Computing Cookbook - Second Edition](https://www.packtpub.com/virtualization-and-cloud/openstack-cloud-computing-cookbook-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781782167587)
* [OpenStack Cloud Computing Cookbook - Third Edition](https://www.packtpub.com/virtualization-and-cloud/openstack-cloud-computing-cookbook-third-edition?utm_source=github&utm_medium=repository&utm_campaign=9781782174783)
* [Learning OpenStack Networking (Neutron)](https://www.packtpub.com/virtualization-and-cloud/learning-openstack-networking-neutron?utm_source=github&utm_medium=repository&utm_campaign=9781783983308)
* [OpenStack Essentials](https://www.packtpub.com/virtualization-and-cloud/openstack-essentials?utm_source=github&utm_medium=repository&utm_campaign=9781783987085)
* [Learning OpenStack Networking (Neutron) - Second Edition](https://www.packtpub.com/virtualization-and-cloud/learning-openstack-networking-neutron-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781785287725)
* [OpenStack Networking Cookbook](https://www.packtpub.com/virtualization-and-cloud/openstack-networking-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781785286100) 
* [Learning OpenStack High Availability](https://www.packtpub.com/virtualization-and-cloud/learning-openstack-high-availability?utm_source=github&utm_medium=repository&utm_campaign=9781784395704)
