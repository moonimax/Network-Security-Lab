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


![](../Attachments/Pasted%20image%2020261119142519.png)
ECN Field
- Stands for explicit confgestion notification
- Priveides end-to-end of network congestion without droppping packet.

![](../Attachments/Pasted%20image%2020261119142527.png)
Total length field
 : Indicates the total length of packet(L3 header segment) unlike IHL Header.

![](../Attachments/Pasted%20image%2020261119142535.png)
Identification field
- compose of the same value in the field that fragmmented due to being too large.

![](../Attachments/Pasted%20image%2020261119142542.png)
Flags field
- Control/ identify fragments
- 3 bits
- DF(Don't Fragment) - 단편화 멈춤
- MF(More Fragment) - 뒤에 이어지는 조각이 있음을 뜻함



Fragment Offset field
- 단편화되거나 단편화되지 않은 Fragment를 찾아내서 IP 패킷을 찾는 위치이다.



TTL
- Time to Live
- 패킷이 사라지지 않고 계속 유지되어 무한으로 네트워크에 잔류하는 것을 막는 기능










