# Networking

# IP Addresses

- `ifconfig` on kali to see IP address, gives:
  `inet 172.18.0.1 netmask 255.255.0.0 broadcast 172.18.255.255`
  - `inet`: 4 \* 8 bits = 32 bits = 4 bytes, IPv4 address
  - `netmask`: if 255 => byte can't change, if 0 => byte can change
  - `broadcast`:

# Media Access Control (MAC) address

- layer 2
- `ether 02:42:68:8e:0a:5d txqueuelen 0 (Ethernet)`
  first 3 pairs => identifiers

# Transmission Control Protocol (TCP) vs User Datagram Protocol (UDP)
