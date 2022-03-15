架構
===
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/%E6%9E%B6%E6%A7%8B.jpg)  

* 更改Router0 G0/0的介面IP  
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/%E6%9B%B4%E6%94%B9Router%20g0-0%E7%9A%84IP.jpg)  

* 更改DNS Serve 的介面IP  
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/DNS%E6%94%B9IP.jpg)  

* 更改PCA 的IP  
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/PCA%E6%94%B9IP.jpg)  

* 設定DNS Serve 的DNS  
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/DNS%E8%A8%AD%E5%AE%9A.jpg)  

* 封包傳送的設定值(已經勾好了)  
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/%E5%B0%81%E5%8C%85%E5%82%B3%E9%80%81%E9%81%B8%E9%A0%85-1.jpg)  

![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/%E5%B0%81%E5%8C%85%E5%82%B3%E9%80%81%E9%81%B8%E9%A0%85-2.jpg)  

* 封包傳送的路徑  
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/%E5%B0%81%E5%8C%85%E5%82%B3%E9%80%81%E8%B7%AF%E5%BE%91.jpg)  

* PCA 封包傳送的資訊(DNS傳輸層數值：1025、DNS接收值：53)  
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/PCA%20PDU%20Outbound.jpg)  

* DNS應用層傳輸的資料  
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/DNS%E6%87%89%E7%94%A8%E5%B1%A4%E5%82%B3%E8%BC%B8%E7%9A%84%E8%B3%87%E6%96%99-1.jpg)  

![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/DNS%E6%87%89%E7%94%A8%E5%B1%A4%E5%82%B3%E8%BC%B8%E7%9A%84%E8%B3%87%E6%96%99-2.jpg)  

* DNS找IP資料、並將域名資料轉換成IP位置  
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/DNS%E6%89%BEIP.jpg)  

![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/DNS%E5%B0%87%E5%9F%9F%E5%90%8D%E8%BD%89%E6%8F%9B%E6%88%90IP%E4%BD%8D%E7%BD%AE.jpg)  

* PCA也可以自訂DNS Server  
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/PCA%E8%87%AA%E8%A8%82DNS%20Server.jpg)  

* PCA瀏覽器下了http://www.ntub.edu.tw、並檢驗DNS封包內容  
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/PCA%20PDU%20Outbound%20DSTIP.jpg)  

* PCA將封包傳送至Switch及DNS Server  
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/PCA%E5%B0%81%E5%8C%85%E5%82%B3%E9%80%81%E8%87%B3Switch.jpg)  

![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/Switch%E5%B0%87%E5%B0%81%E5%8C%85%E5%82%B3%E9%80%81%E8%87%B3DNS%20Server.jpg)  

* DNS成功接收到DNS封包的資料  
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/DNS%20Server%20%E5%9B%9E%E6%87%89%E6%88%90%E5%8A%9F.jpg)  

* PCA成功取得http://www.ntub.edu.tw的IP  
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/PCA%E6%88%90%E5%8A%9F%E6%8E%A5%E6%94%B6%E5%88%B0%E5%9B%9E%E5%82%B3%E7%9A%84%E8%B3%87%E6%96%99.jpg)  

* PCA換作HTTP封包  
![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/PCA%E6%8F%9B%E5%81%9AHTTP%E5%B0%81%E5%8C%85.jpg)  

![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/PCA%20HTTP%20PDU-1.jpg)  

![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/PCA%20HTTP%20PDU-2.jpg)  

![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/Router%20ARP%20Table.jpg)  

![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/PCA%20ARP%20Table.jpg)  

![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/Router%20Routing%20Table.jpg)  

![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/PCA%20HTTP%20PDU%20IP%20Inform-1.jpg)  

![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/PCA%20HTTP%20PDU%20IP%20Inform-1.jpg)  

![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/HTTP%20Router%20%E5%82%B3%E8%BC%B8.jpg)  

![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/Router%20Routing%20Table%20%E9%80%81%E4%BB%8B%E9%9D%A2g0-0.jpg)  

![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/Router%20PDU%20Outbound%20DSTIP.jpg)  

![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/Web%20ServerPDU%20Outbound-1.jpg)  

![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/Web%20ServerPDU%20Outbound-2.jpg)  

![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/Router%E5%B0%81%E5%8C%85%E5%82%B3%E8%BC%B8%E4%B8%AD.jpg)  

![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/Router%20PDU%20Iutbound.jpg)  

![image](https://github.com/Henryliu880922/Cisco/blob/main/pic/OSI%E5%AF%A6%E9%A9%97/HTTP%20Router%20Routing%20Table.jpg)  

