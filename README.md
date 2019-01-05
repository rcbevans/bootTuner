bootTuner
=========

simple systemd script and service which will tune your power settings at boot up as per reccomendations from intel in powerTop

The changes made by this script are taken from powerTop and do as follows:

1. Enable runtime PM on PCI devices
2. Enable autosusped on 1s on USB devices
3. VM writeback timeout  
4. Enable Audio codec power management   
5. Enable SATA link power management for /dev/sda
6. Wireless Power Saving for interface wlan0     
7. Enable SATA link power management for /dev/sda
8. NMI watchdog should be turned off     
9. VM writeback timeout  
10. Wake-on-lan status for device eth0    
11. Enable Audio codec power management

I made this script for my own convenience, feel free to make use of it. If you make any improvements please push the changes back to me!


Test change