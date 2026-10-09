|**TEST**|**SCREENSHOTS**|**COMMAND ACTIONS**|**RESULTS**|
|:-|:-|:-|:-|
|LAN PC TO PC|[<img width="1131" height="1122" alt="1 lan pc to pc" src="https://github.com/user-attachments/assets/396f2099-f6f7-4cab-85a2-ddcd8a2564ab" />)|PING.168.10.101|](https://www.amazon.co.uk/dp/B0DHWTLNPJ?tag=buildcoresx-21&linkCode=ogi&th=1&psc=1)|
|PC to Office Server |<img width="960" height="1125" alt="2 pc to office#" src="https://github.com/user-attachments/assets/9b80d951-2071-47fa-9df6-b204c9874a97" />|PING 192.168.10.10|](https://www.amazon.co.uk/dp/B0DHWTLNPJ?tag=buildcoresx-21&linkCode=ogi&th=1&psc=1)|
|PC TO DNS SERVER |<img width="958" height="1128" alt="3 pc to dns" src="https://github.com/user-attachments/assets/dfdd3130-941d-4336-a97b-29ed5ad64ece" />|ping 192.168.10.2|](https://www.amazon.co.uk/dp/B0DHWTLNPJ?tag=buildcoresx-21&linkCode=ogi&th=1&psc=1)|http://intranet.archstudio.local|]
|Internal web by IP|<img width="960" height="1128" alt="4 iternal web ip" src="https://github.com/user-attachments/assets/288af291-56f6-4020-84b2-8f29adf4b6a9" />|http://192.168.10.10|](https://www.amazon.co.uk/dp/B0DHWTLNPJ?tag=buildcoresx-21&linkCode=ogi&th=1&psc=1)|
|Internal web by name |<img width="955" height="1145" alt="5 internal web by name" src="https://github.com/user-attachments/assets/1200ba71-80e5-4eaa-a023-81a5e2ba0821" />|http://intranet.archstudio.local\]results
|External server ping |<img width="960" height="1117" alt="6 external server ping" src="https://github.com/user-attachments/assets/0de460fa-894f-45f7-8bd7-6a9a76725c63" />|ping 203.0.113.10|](https://www.amazon.co.uk/dp/B0DHWTLNPJ?tag=buildcoresx-21&linkCode=ogi&th=1&psc=1)|
|External WEB BY IP |<img width="948" height="1121" alt="7 exturnel web by ip" src="https://github.com/user-attachments/assets/36c9f621-21d2-4ced-bb2d-5726773c634a" />|http://203.0.113.10|](https://www.amazon.co.uk/dp/B0DHWTLNPJ?tag=buildcoresx-21&linkCode=ogi&th=1&psc=1)|
| External WEB BY NAME |<img width="960" height="1125" alt="2 pc to office#" src="https://github.com/user-attachments/assets/9b80d951-2071-47fa-9df6-b204c9874a97" />|http://cloud.archstudio.example|](https://www.amazon.co.uk/dp/B0DHWTLNPJ?tag=buildcoresx-21&linkCode=ogi&th=1&psc=1)|





Protocols and concepts to explain (at least five) 

**Concept**|**Where it appears**|**Explainations**
|:-|:-|:-|
TCP/IP|All device communication| 
IP addressing|Every device has a unique IP| 
Subnet mask|255.255.255.0 on both networks| 
Gateway|Client PCs use 192.168.10.1| 
DNS|intranet.archstudio.local etc.| 
HTTP|Opening pages in the browser| 
ICMP / ping|Ping tests| 
Client-server|CAD PC → Office/Cloud Server| 
Switch vs router|Office/External switch; Office Router| 





Evidence to submit  

|**Required Evidence**|**Screenshot**|
|:-|:-|
Topology screenshot (office LAN, router, external switch, ISP/cloud server)||
Completed IP addressing table|| 
Router-interface screenshot||
DNS-records screenshot||
Internal and external web pages opening from the CAD PC||
At least three successful ping tests||
a protocol table explaining 5+ concepts||
a short explanation of the LAN vs external network and of the client-server model|| 


**Device**|**IP address**|**Subnet mask**|**Gateway**|**DNS**|**Screenshots**|
|:-|:-|:-|:-|:-|:-|
Router int.1 (Office side)|192.168.10.1|255.255.255.0|–|-|<img width="1258" height="857" alt="1 router int 1" src="https://github.com/user-attachments/assets/8d2a0203-7b0c-475e-950f-b6c4892b0f88" />
Router int.2 (External side)|203.0.113.1|255.255.255.0|–|–|<img width="1248" height="848" alt="2 router in 2" src="https://github.com/user-attachments/assets/553caf80-1dfa-4819-aedc-10e280cc7504" />
DNS Server|192.168.10.2|255.255.255.0|192.168.10.1|192.168.10.2|<img width="1912" height="1131" alt="3 DNS SERVER" src="https://github.com/user-attachments/assets/b0b983a1-0283-455c-947b-219028b03fde" />
Office Server|192.168.10.10|255.255.255.0|192.168.10.1|192.168.10.2|<img width="1917" height="1127" alt="4 OFFICE SERVER" src="https://github.com/user-attachments/assets/f259a9fd-3c0a-4147-96dc-89ae2f24186e" />
Admin PC|192.168.10.101|255.255.255.0|192.168.10.1|192.168.10.2| <img width="1667" height="1197" alt="5 ADMIN PC" src="https://github.com/user-attachments/assets/50d3423b-a999-4659-af0d-bdcd9c64e4df" />
Project PC|192.168.10.111|255.255.255.0|192.168.10.1|192.168.10.2|<img width="1912" height="1132" alt="6 PROJECT PC" src="https://github.com/user-attachments/assets/124c4a84-9491-4a76-b0d3-e418c919e0a6" />
CAD PC|192.168.10.121|255.255.255.0|192.168.10.1|192.168.10.2|   <img width="1717" height="246" alt="Cad Pc" src="https://github.com/user-attachments/assets/53c1c432-641a-4c38-aeff-dff207f6981d" />|
Visual PC|192.168.10.131|255.255.255.0|192.168.10.1|192.168.10.2|<img width="1715" height="237" alt="Visual PC" src="https://github.com/user-attachments/assets/00981271-0e77-4c62-b1d4-543b2819e427" />|
ISP / Cloud Server|203.0.113.10|255.255.255.0|203.0.113.1|192.168.10.2|<img width="1714" height="243" alt="ISP_CLOUD server" src="https://github.com/user-attachments/assets/faaab48a-dc6d-471b-9c89-9935ba492ac9" />|
