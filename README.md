# netPractice_42

# model OSI

* Application Layer for get the Protocls (https , ftp , smtp);
* presention layer translation data top binary system then it compression data or
data compression.
* session layer (transmision)
  >> simplex mode |   full-duplex |   mode half-duplex mode
session managment (cach , authentication , Authorization);
* transport layer :
 1) splite data to segmentation  and order them;
 2) Flow control
 3) detrmine Protocl (tcp , udp )
 * network layer :
 1)  logical addresing (ipr,ips,data segment) PACKET(data unit)
 2)  Routing  take Best Routing information protocol.
>>  ospf : open shortest Path first
>> RIP : Routing Information potocol
* data link layer
Physical Addressing : Data link Layer >> Mac Address 
 >> Frame : Macr,Macs,Ipr,IPs, Data Segment, Trailer
checkSum =? 1.s complement
CSMA => chack channel if empty , wait for it , tack packet 
* physical layer
   data to signals / media
  

*tcp : three Way handshake
syn / syn Ack / Ack
unicast 
syn  {seq: 42 , Ack : 0 }
syn/Ack  {seq : 1337 , Ack : 43 }
Ack  {seq : 42 , Ack : 1338 }

