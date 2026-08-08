# **Segment 8**

**Author:** Vincent Pierce  
**Project Start Date:** 7/16/2026  
**Latest Revision:** 8/4/2026  



<a name=top></a>
[Back to Overview](Overview.md)



As mentioned in the Overview, the router on a stick with a firewall and edge router is not currently setup due to issues with scope and complexity. Getting the router to trunk just the phone Vlan would of been a bit much. On top of this, I would have to setup a routing protocol and everything as well. So, it was just out of scope for this current project. However, as stated I do have a VoIP lab where dialing and calling is officially working, and a lab is currently in progress to setup routing protocols for various different networks.



## **Devices**

Switches - 1  
Routers - 2  
Firewalls - 1  



### Switch Details



**Gigabit Ethernet Port 1/0/3:**

* Switchport Mode: Trunk
* Allowed Trunks: 100, 200, 300
* Native Vlan: 99
* Connected Switch: [Segment 1](Section1.md)



**Gigabit Ethernet Port 1/0/13:**

* Switchport Mode: Trunk
* Allowed Trunks: 100, 150, 200, 300
* Native Vlan: 99
* Connected Switch: [Segment 2](Section2.md)



**Gigabit Ethernet Port 1/0/9:**

* Switchport Mode: Trunk
* Allowed Trunks: 100, 200, 300
* Native Vlan: 99
* Connected Switch: [Segment 3](Section3.md) and [Segment 4](Section4.md)



**Gigabit Ethernet Port 1/0/11:**

* Switchport Mode: Trunk
* Allowed Trunks: 200
* Native Vlan: 99
* Connected Switch: [Segment 5](Section5.md)



**Gigabit Ethernet Port 1/0/7:**

* Switchport Mode: Trunk
* Allowed Trunks: 200, 300
* Native Vlan: 99
* Connected Switch: [Segment 6](Section6.md)



**Gigabit Ethernet Port 1/0/5:**

* Switchport Mode: Trunk
* Allowed Trunks: 200, 300
* Native Vlan: 99
* Connected Switch: [Segment 7](Section7.md)



## **Proof of Concept**

Here is the [Startup Config](Images/S8POC/Startup.txt) for the Layer 3 Aggregation switch.



[Back to top](#top)  
[Return to Overview](Overview.md)  



\*  
\*  
\*  

