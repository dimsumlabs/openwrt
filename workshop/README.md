# OpenWRT workshops - suggested topics

## Session #1 - Getting started with OpenWRT

*Goal: Buying a not-so-randomly chosen cheap router and making it work with OpenWRT*

- upgrading the firmware from the proprietary vendor firmware
- making the web interface work
- making WiFi work
- making routing/firewalling/NAT work
- use a 3G/LTE dongle instead of DSL or fiber for Internet connectivity
- adding packages of your choice to do stuff that the vendor firmware didn't support
* make traffic shaping work (so your flatmates don't kill your Internet connection with BitTorrent)
* share your USB Hard drive via FTP, NFS, iSCSI, UPnP/DLNA
* stream music/videos
* making DynDNS work
* making OpenVPN work so you can connect to your home network when travelling
* making IPv6 work (natively, or via a tunnel broker if your ISP doesn't support IPv6 yet)

## Session #2 - Unbrick your router

*Goal: Recover from bad flashes, lost passwords and other havoc*

- what can we do via the LAN to fix broken routers
- connecting to the RS232 (serial) port, and building your own voltage level converterhttp://wiki.openwrt.org/doc/hardware/port.serial 
- when things went really wrong: using JTAG to fix your router

## Session #3 - Pimp the router

*Goal: add nonstandard hardware mods*

- control the LEDs and buttons on your router at your convenience
- add more RAM so it can run a MySQL database server
- use I/O pins to add sensors/trigger relays/...
- use a USB to VGA adapter for video http://www.nslu2-linux.org/wiki/HowTo/AddVGAAdapter

## Session #4 - Doing mesh networking using OLSR

*Goal: Build a small mesh network using five OpenWRT routers*

- basics of mesh routing protocols
- planning a small mesh network
- configuring OpenWRT to do OLSR
- configuring your laptop to do OLSR

## Session #5 - Pimp the antenna

*Goal: Understand the basics of wave propagation and antennas, modify and build your own antenna, how to go shopping for antennas*

- legal Do's and Don'ts
- basics of wave propagation and antennas (Mathis): wavelength, gain, dipoles, directional antennas, ...
- finding the antenna port on your router
- connecting an external antenna using a pigtail
- quality of pigtails and antennas
- if you have enough dough: how to go shopping for pigtails, antennas and complete systems
- quick'n'dirty mods of builtin antennas
- build your own Cantenna
- build your own pigtail

## Session #6 - Going outdoor

*Goal: Set up a long distance WiFi link*

- legal Do's and Don'ts
- doing LOS (line of sight) surveying
- possible power sources if there is no wall socket around (PoE, Solar, ...)
- configure the equipment
- aligning antennas and measuring SNR and bandwidth
- mechanical considerations or how to prevent a T8 from kiling the next best pedestrian with your antennaSession #7 - Building a scalable hot spot network- using OpenWRT and OpenFlow to integrate OpenID and Facebook Connect authenticationhttps://docs.google.com/file/d/0B2yD56YxjZy6YzgwNmZiZDYtM2JlYi00NzgzLWJjYTEtMDU0ZTM5NjE0YjYz/edit?hl=en_US 

## Session #7 - Wireless Community Networks worldwide - soon in HK?

*Goal: Learn about WCNs in other countries, and start building a WCN in HK*

- for an overview, refer to http://en.wikipedia.org/wiki/Wireless_community_network
- for a list, refer to http://en.wikipedia.org/wiki/List_of_wireless_community_networks_by_region
- what's needed to bootstrap a WCN in Hong Kong


FIXME

Other unsorted topics

https://docs.google.com/file/d/0B2yD56YxjZy6YzgwNmZiZDYtM2JlYi00NzgzLWJjYTEtMDU0ZTM5NjE0YjYz/edit?hl=en_US%EF%BB%BF - Separating Authentication, Access and Accounting
