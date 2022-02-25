架構
===
![image](https://github.com/Henryliu880922/Cisco/blob/main/%E6%9E%B6%E6%A7%8B.jpg)  

模擬架構
===
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/simulation.jpg)  

* 點選Edit Filters  
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/Edit%20Filters.jpg)  

* 會跳出  
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/ARPandICMP.jpg)  

* 僅勾選ARP以及ICMP即可  
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/ARPandICMP.jpg)  

* 並確定ARP表格為  
PC0  
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/PC0%20ARP%20Table.jpg)  

PC3  
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/PC3%20ARP%20Table.jpg)  

* 點選ARP簡單封包(左邊)  
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/ARP%E5%B0%81%E5%8C%85.jpg)  

* 點選旁邊ARP形式的封包  
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/simulation%20panel%20ARP-0.jpg)  

* 看目的地的MAC(Dest Addr)、來源MAC(SRC Addr)、目的IP(Target IP)  
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/PC0%20PDU%20Formats%20Outbound.jpg)  

* 按下發送封包按鈕  
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/%E6%92%AD%E6%94%BE%E5%B0%81%E5%8C%85%E6%A8%A1%E6%93%AC.jpg)  

* 查看PC3的ARP Table會發現多一個PC0的IP  
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/PC3%20ARP%20Table%20%E5%A4%9A%E4%B8%80%E5%80%8BPC0%20IP.jpg)  

* 查看PC0的ARP Table會發現多一個PC3的IP  
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/PC0%20ARP%20Table%20%E5%A4%9A%E4%B8%80%E5%80%8BPC3%20IP.jpg)  

* 查看Hub會發現已經知道了PC3的MAC了(Dest Addr)  
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/PC0%20PDU%20Formats%20Outbound%20ICMP.jpg)  

封包碰撞
===
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/PC0%20PDU%20Formats%20Outbound%20%E7%A2%B0%E6%92%9E%E5%B0%81%E5%8C%85.jpg)  

![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/simulation%20panel%20PC0%E3%80%81PC1%20ARP.jpg)  

* 查看Hub 碰撞  
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/Hub%20%E7%A2%B0%E6%92%9E.jpg)  

* 碰撞結束之後會是空的  
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/PC0%20PDU%20Formats%20Outbound%20%E7%A2%B0%E6%92%9E%E6%9C%83%E6%98%AF%E7%A9%BA%E7%9A%84.jpg)  
