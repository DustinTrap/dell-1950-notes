# dell-1950-notes

CentOS 7 and earlier work fine on this hardware. CentOS 8 drops support for the PERC 5i and 6i raid controller and requires loading of the kmods manually. I chickened out and didn't do it.

# Install directions
* With the 5i, I had best results booting off a CentOS 7.0 Live CD, fdisk and deleting all partitions and then installing the OS using normal methods.
* Use the rear USB ports, front ports are not bootable. 
* On Windows using rufus, choose the 'iso' format option when creating the USB bootable device.
* If the system will not post, disconnect USB devices and try again.

# Maintenance notes
* I refreshed the thermal paste on both CPUs
* Both RTC clock batteries were replaced on 5/1/2019
