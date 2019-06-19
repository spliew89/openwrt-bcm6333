# openwrt-bcm6333

Rename '.config<xxxxxxxxxx>' file to '.config' for the makefile to load the correct custom configs.
* 20190619 Note: I have forgotten to re-include iptables tool inside menuconfig. Routing function still works correctly without it, strangely. Well, please re-include it just to make sure the kernel's netfilter firewall works correctly. I'll fix it in the next OpenWrt release.
