# WEEK3
#
    Refreshed Introduction to Course for new-arrived students
    Hands-on  experience in UNIX SHELL 
    Possible hardware-related routing issues in IPv4 communications  
    An intuitive approach to solving problems
    Secure Terminal Connection to a remote machine (ssh).
#also practised below commands in a similar way at that time.
$ 127.0.0.1 netmask 0xff000000 

inet6 ::1 prefixlen 128 

inet6 fe80::1%lo0 prefixlen 64 scopeid 0x1 

nd6 options=201<PERFORMNUD,DAD>

gif0: flags=8010<POINTOPOINT,MULTICAST> mtu 1280

stf0: flags=0<> mtu 1280

en0: flags=8863<UP,BROADCAST,SMART,RUNNING,SIMPLEX,MULTICAST> mtu 1500

ether f4:5c:89:9f:f5:39 

inet6 fe80::77:9824:468a:1999%en0 prefixlen 64 secured scopeid 0x4 

inet 10.0.1.3 netmask 0xffffff00 broadcast 10.0.1.255

nd6 options=201<PERFORMNUD,DAD>

media: autoselect

status: active

en1: flags=963<UP,BROADCAST,SMART,RUNNING,PROMISC,SIMPLEX> mtu 1500

options=60<TSO4,TSO6>

ether 4a:00:05:07:72:00 

media: autoselect <full-duplex>

status: inactive

en2: flags=963<UP,BROADCAST,SMART,RUNNING,PROMISC,SIMPLEX> mtu 1500

options=60<TSO4,TSO6>

ether 4a:00:05:07:72:01 

media: autoselect <full-duplex>

status: inactive

p2p0: flags=8843<UP,BROADCAST,RUNNING,SIMPLEX,MULTICAST> mtu 2304

ether 06:5c:89:9f:f5:39 

media: autoselect

status: inactive

awdl0: flags=8943<UP,BROADCAST,RUNNING,PROMISC,SIMPLEX,MULTICAST> mtu 1484

ether d2:af:39:13:58:bd 

inet6 fe80::d0af:39ff:fe13:58bd%awdl0 prefixlen 64 scopeid 0x8 

nd6 options=201<PERFORMNUD,DAD>

media: autoselect

status: active

bridge0: flags=8863<UP,BROADCAST,SMART,RUNNING,SIMPLEX,MULTICAST> mtu 1500

options=63<RXCSUM,TXCSUM,TSO4,TSO6>

ether 4a:00:05:07:72:00 

Configuration:

id 0:0:0:0:0:0 priority 0 hellotime 0 fwddelay 0

maxage 0 holdcnt 0 proto stp maxaddr 100 timeout 1200

root id 0:0:0:0:0:0 priority 0 ifcost 0 port 0

ipfilter disabled flags 0x2

member: en1 flags=3<LEARNING,DISCOVER>

        ifmaxaddr 0 port 5 priority 0 path cost 0

member: en2 flags=3<LEARNING,DISCOVER>

        ifmaxaddr 0 port 6 priority 0 path cost 0

nd6 options=201<PERFORMNUD,DAD>

media: <unknown type>

status: inactive

utun0: flags=8051<UP,POINTOPOINT,RUNNING,MULTICAST> mtu 2000

inet6 fe80::e7c9:a5f5:4460:ee2a%utun0 prefixlen 64 scopeid 0xa 

nd6 options=201<PERFORMNUD,DAD>

utun1: flags=8051<UP,POINTOPOINT,RUNNING,MULTICAST> mtu 1380

inet6 fe80::7db1:ece6:9bf0:169e%utun1 prefixlen 64 scopeid 0xb 

nd6 options=201<PERFORMNUD,DAD>

$ route -n

usage: route [-dnqtv] command [[modifiers] args]

$ route 

usage: route [-dnqtv] command [[modifiers] args]

$ route 

usage: route [-dnqtv] command [[modifiers] args]

 

$ man route

$ nmap 192.168.1.0/24

 

Starting Nmap 7.01 ( https://nmap.org ) at 2019-02-12 11:48 EET

 

$ ping 192.168.1.110

PING 192.168.1.110 (192.168.1.110): 56 data bytes

36 bytes from 10.0.1.1: Destination Net Unreachable

Vr HL TOS  Len   ID Flg  off TTL Pro  cks      Src      Dst

 4  5  00 5400 935d   0 0000  40  01 1a33 10.0.1.3  192.168.1.110 

 

ping: sendto: No route to host

Request timeout for icmp_seq 0

ping: sendto: No route to host

Request timeout for icmp_seq 1

ping: sendto: No route to host

Request timeout for icmp_seq 2

ping: sendto: No route to host

Request timeout for icmp_seq 3

ping: sendto: No route to host

Request timeout for icmp_seq 4

ping: sendto: No route to host

Request timeout for icmp_seq 5

ping: sendto: No route to host

Request timeout for icmp_seq 6

ping: sendto: No route to host

Request timeout for icmp_seq 7

ping: sendto: No route to host

Request timeout for icmp_seq 8

ping: sendto: No route to host

Request timeout for icmp_seq 9

ping: sendto: No route to host

Request timeout for icmp_seq 10

ping: sendto: No route to host

Request time
^C

--- 192.168.1.110 ping statistics ---

90 packets transmitted, 0 packets received, 100.0% packet loss

$ 

$ 

$ ping goole.lv

ping: cannot resolve goole.lv: Unknown host

$ ping google.lv

ping: cannot resolve google.lv: Unknown host

$ ping goole.lv

ping: cannot resolve goole.lv: Unknown host

$ ping google.lv

ping: cannot resolve google.lv: Unknown host
