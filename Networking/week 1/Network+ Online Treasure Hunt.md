**Clue 1** -
The OSI layer that is in volved is Layer # 3 the Network Layer, One of the fuctions of this layer is to handle routing and path determination.

**Clue 2** -
The first useable host is 192.168.50.1, The last useable host is 192.168.50.62, and the broadcast address is 192.168.50.63.
The block size for the subnet is 64 because the subnet mask is 255.255.255.192. To find how many available host you do 256-192= 64 so there are 64 useable host. 
Your subnet rang will be 192.168.50.0- 192.168.50.63

**Clue 3** -
Two commands I would use to verify VLAN status and confirm trunk operation would be, "show vlan brief" This will show all the VLANS avalible and which port there assigned to. 
This would allow you to see if VLAN 20 was active or not.
To see the trunk operation I would use command " show interfaces trunk" This will allow me to see thr trunks and there allows VLANS to ensure VLAN 20 is one of the allowed trunks.

**Clue 4** -
On Router A you would enter the command "(config)# ip route 172.16.0.0 255.255.255.0 10.10.10.2" This would allow you to create a static route.

**Clue 5**
The ACL entry I would configure would be "access-list 100 deny icmp any any echo" as this will block ANY ICMP echo request from any source.

**Clue 6**
If the Wifi is dropping randomly you should first check to see if the issue is specific to just the one device or if it happens on multiple. If the issue is happening on multiple devices then you may want to check to see if there are any obstuctions like
concrete or thick walls between you and the router, or anything that could be causing EMF like microwaves, baby monitors ect. These things can cause your WIFI to randomly drop.

**Clue 7**
The correct color order from Pin 1 to Pin 8 for T568B connector is as fallows. White/orange, orange, white/green, blue, white/blue, green, white/brown, brown.

**Clue 8**
Im going to test the network layer, Pinging 8.8.8.8 is an adress outside the local network therefor the traffic must be routed by the gateway to the internet. 
This makes me think the issue is with the gateway not being able to forward the traffic which i beileve is handleing in the network layer. 

**Clue 9**
The tool i would use would probably be Zenmap and then protocol SNMP as it allows you to see a wide range of data from devices.


**Clue 10** 
<img width="1717" height="906" alt="Screenshot 2025-11-07 144336" src="https://github.com/user-attachments/assets/45b45d77-30a5-4030-9cf2-a1641df1ba12" />
