# IPv6 Generator For /etc/rc.conf (FreeBSD) v1.0

 This script generates a list of IPv6 addresses to be added
 into your FreeBSD 12 (or higher) /etc/rc.conf file. I wrote this
 simple shell script to help populate new servers assigned with
 large blocks of IPv6 IP addresses that must be self-setup.

 You can adjust the number value ('a' and 'b') and IPv6 base
 according to your own network / server settings. This script
 works great in setting up servers and VPS quickly for use
 with IPv6 services and reverse DNS.

 Simply paste the output of this script into your /etc/rc.conf
 and reboot your FreeBSD for the changes to kick in. You can
 refresh without rebooting, but hardware is so fast now, why not?

 In this example, my IPv6 address and alias number do not match.
 Since I have additional IPv4 taking up that space, you'll want
 to change these values to match yours.

# vtnet alias start: 4 (end 260)
# ipv6 ip start: 8001 (end 8257)
# ipv6 address space: 2001:19f0:9002:bc8:5400:02ff:feff:
# adding 256 additional IPs
