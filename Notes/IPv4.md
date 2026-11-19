![](../Attachments/Pasted%20image%2020261119135216.png)


![](../Attachments/Pasted%20image%2020261119135247.png)
IPv4 Header
- Length : 4 bits
-  IPv4, IPv6


![](../Attachments/Pasted%20image%2020261119135239.png)
Internet Head Length
- Header의 총 길이 유추가 가능하게 지시해주는 역할
- Length : 4 bits
- 최소 4*5 = 20 byte - 최대 4 * 15= 60 byte

![](../Attachments/Pasted%20image%2020261119135231.png)
DSCP
- Differentiatied Services Code Point
- Length : 6 bits
- QoS
	- 패킷 지연율이나 전송률 담당



ECN Field
- Stands for explicit confgestion notification
- Priveides end-to-end of network congestion without droppping packet.


Total length field
 : Indicates the total length of packet(L3 header segment) unlike IHL Header.


Identification field
- compose of the same value in the field that fragmmented due to being too large.


Flags field
- Control/ identify fragments
- 3 bits
- DF(Don't Fragment) - 단편화 멈춤
- MF(More Fragment) - 뒤에 이어지는 조각이 있음을 뜻함







