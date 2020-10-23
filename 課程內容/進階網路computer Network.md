#
```
1.網路基本觀念	
題型1:網路連接設備(connecting devices):
      Gateway, Router, Switch，bridge，Hub,repeater

題型2:網路拓樸(Network Topology):
   網狀拓樸(Mesh topology)	星狀拓樸(Star topology) 巴士形拓樸(Bus topology) 環狀拓樸(Ring topology)

題型3:網路架構:Peer-to-Peer(P2P) vs. Client/Server
         Client/Server: 2-tier vs 3(N)-tier

題型4:常見的server:Web server, Proxy server

題型5:網路類型:WAN, MAN, LAN

題型6:網路標準: 
de facto(業界標準)TCP/IP
de jure(法定標準)OSI layered model
IEEE 802 Project
```
```
2.Physical Layer(實體層)	

題型7:資料傳輸的理論基礎:
有限頻寬訊號、頻通的最大資料傳送率

題型8:傳輸媒體(Media): 
雙絞線 (Twisted Pair)
基頻/寬頻同軸電纜 (Base band/broadband Coaxial Cable)
光纖 (Fiber Optics)..
無線傳輸、電話系統、窄頻 ISDN、寬頻 ISDN與非同步傳輸模式、蜂巢式電話、通訊衛星

題型9:實體層使用的技術:多工(multiplexing)/傳輸模式/交換方式(switching)
```
```
3.Data Link Layer資料鏈結層(1)	
題型10:資料鏈結層的服務及設計:
	(1)框架化(Framing)
(2)流量控制(Flow Control):
Stop-and-Wait流量控制
活動視窗協定(SLIDING WINDOW PROTOCOLS)
回溯(go-back-n) vs.選擇性回絕(selective rejection)
     (3)錯誤控制(Error Control)

題型11:錯誤控制:(1)錯誤偵測碼與錯誤修正碼
[1]Type of ERROR[錯誤的形式]
[2]Error Detection之冗位觀念Redundancy
[3]錯誤偵測碼:VRC,LRC,CRC, checksum

題型12:錯誤控制(Error Control):(2)錯誤修正碼
錯誤校正(Error Correction)和漢明碼(Hamming Code)


題型13:資料鏈結協定(Data Link Protocols)
非同步協定Asynchronous protocols 與同步協定Synchronous protocols
資料鏈結協定實例:[1]HDLC   [2]ATM    [3]Internet		

4.MAC(Medium Access Control，媒介存取控制)
題型14:3種常見的媒介存取方法：
        競爭(Contention)/符記傳遞(Token passing)/輪詢(Polling)

題型15:多重存取協定(Multiple Access Protocols)
[1]Pure  ALOHA/Slotted ALOHA   [2] CSMA與以太網路協定CSMA/CD
[3]Token-control
[4]Collision-Free Protocols: 
基本位元對應法(Basic bitmap method)
二元倒數法(Binary countdown method)

[5]無線網路問題與標準
問題:hidden station problem /exposed station problem
標準:CSMA/CA(1990)  802.11無線網路標準

[6]光纖網路使用的Wavelength Division Multiple Access Protocols
   FDMA、TDMA、WDMA、CDMA
```
```
5.LAN(區域網路)MAN WAN  WPAN/WLAN/WWAN 
題型16: LAN(區域網路)
Ethernet [IEEE 802.3]
Token Bus [IEEE 802.4]
Token Ring [IEEE 802.5]

題型17:WAN(廣域網路)基本觀念與類型
[1]廣域網路的資料鏈結層封裝：
   功能/兩大類WAN封裝技術:PPP(SLIP, PPP) vs. NBMA
[3]類型:X.25,Frame Relay，整體服務數位網路（Integrated Services Digital Network，ISDN） 
      非同步傳輸模式（Asynchronous Transfer Mode，ATM）
      類比電話線路,
      非對稱數位用戶迴路(ADSL) ,
      纜線數據機(CABLE MODEM)
題型18: WAN(廣域網路):ADSL與CABLE MODEM的比較分析 
題型19: 無線網路:WPAN/WLAN/WWAN
```
```
6.網路層(Network Layer)
題型20:IPV4 Protocol/Addressing(定址法)/IPv4 Header
題型21:子網路切割(Subnet)與子網路合併(Supernet)
題型22:IP路由(IP routing)與路由協定
題型23:IP 不足的幾種解決方案:
  DHCP/NAT/CIDR(Classless Inter-Domain Routing)/IPV6
題型24: Network Layer其他協定:ICMP/IGMP/ARP/RARP
```
```
7.傳輸層Transport Layer	
題型25:TCP與 UDP的比較
題型26:TCP協定
題型27:UDP協定
```
```
8.應用層Application Layer	
題型28:WEB:HTTP, HTTPS通訊協定
題型29:EMAIL:SMTP,POP3,IMAP4通訊協定
題型30:FTP通訊協定
題型31:DNS網域名稱服務通訊協定
題型32:LDAP
題型33:SNMP通訊協定與網路管理(Network Management)

9.網路安全與資訊安全管理	
題型34:網路安全基本觀念:CIA
題型35:密碼學(Cryptology):
題型36:各類型的Network Attacks
題型37:各類型的Security tools: Firewall, IDS,IDP, VPN
```
