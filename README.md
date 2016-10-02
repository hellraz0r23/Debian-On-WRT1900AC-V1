#McDebian - for Linksys WRT1900AC V1
Linux Kernel version is "4.7.6".

Debian root files system is "Jessie" stable.


#####The wireless driver is updated to the lastest version.
#####NAND timeout patch.
#####fancontrol implementation.



## McDebian Deployment Instructions
https://github.com/Chadster766/McDebian/wiki

-
##Warning!

Flashing the McDebian firmware must only be done using a USB to Serial cable. 
-


  +------+              +------+
  |      |              |      |
  |      +--------------+      |
  |      |              |      |
  +------+              +------+
  firewall              wrt1900ac
192.168.10.1           192.168.10.10

DHCP failover between wrt1900ac and firewall => 
While wrt1900ac is in middle of my local network, 
it'll drop all broadcast 67/68 udp port in forward.
