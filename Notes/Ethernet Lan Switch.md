
Ethernet Frame

![](Attachments/Pasted%20image%2020261118193242.png)


Ethernet Header
![](Attachments/Pasted%20image%2020261118193655.png)

FCS
- Length : 4 bytes
- CRC 알고리즘을 통해 위변조된 데이터를 검출
- CRC : Cyclic Redundancy Check

---

MAC Address
- 6-byte physical address assigned to the device
- the first 3 bytes are the OUI(Organizationally Unique Identifier). which is assigned to the company.


![](../Attachments/Pasted%20image%2020261118195334.png)

Unknown Unicast frame = Flood

자신과 관계없는 Dest로 전송된 목적지의 패킷은 무시된다. 여기서 추가 설명이 되면 좋을거 같은데 ....
Dynamic MAC addresses are removed from the MAC addreess table after 5 minutes of inactivity. ..

---



