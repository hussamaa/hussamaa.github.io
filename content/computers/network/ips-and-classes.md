---
title: "IPv4 - IP address and classes"
draft: true
---

IP (Internet Protocol) address is a logical identifier assigned to each device connected to a computer network. In the version 4, this identifier is composed by 32-bits (4-bytes), or 4 octets. Due to the shortage of IPv4 addreses availables on the internet, nowadays, this has been replaced by a new standard IPv6.

## Private Addresses

From the whole spectrum, some ranges are reserved for private network usage. These ranges are known as class A, B and C.

### Class A
* **10.0.0.0/8** (lock the first 8-bits, or 255.0.0.0), gives an IP range from 10.0.0.0 to 10.255.255.255, which means **16,777,216 (16 millions)** addresses available. This is usually used by large corporations.

### Class B
* **172.16.0.0/12** (lock the first 12-bits, or 250.240.0.0), gives an IP range from 172.16.0.0 to 172.31.255.255 which means **1,048,576 (1 million)** addresses available. This is usually used by medium-large corporations.

### Class C
* **192.168.0.0/16** (lock the first 16-bits, or 255.255.0.0) gives an IP range from 192.168.0.0 to 192.168.255.255, which means **65,536 (65 thousands)** addresses available. This are usually used in our local networks (i.e., home-wifi, etc).

### Other:

* Interactive IP range visualizer: https://cidr.xyz/

### References:

1. https://en.wikipedia.org/wiki/IP_address
2. http://penta2.ufrgs.br/trouble/ts_ip.htm