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
Router int.1 (Office side)|192.168.10.1|255.255.255.0|–|-|<img width="1701" height="232" alt="Screenshot 2026-10-09 151707" src="https://github.com/user-attachments/assets/37a5bd6e-9694-4b44-b5da-82daae82ffc5" />|
Router int.2 (External side)|203.0.113.1|255.255.255.0|–|–|<img width="1707" height="241" alt="Screenshot 2026-10-09 151659" src="https://github.com/user-attachments/assets/0025403b-1e96-484e-9e41-3f59420b64fe" />| 
DNS Server|192.168.10.2|255.255.255.0|192.168.10.1|192.168.10.2|<img width="1714" height="242" alt="DNS Server" src="https://github.com/user-attachments/assets/c27a9395-a9d4-4e8d-97b6-6c449335a2df" />|
Office Server|192.168.10.10|255.255.255.0|192.168.10.1|192.168.10.2|<img width="1708" height="241" alt="Office Server" src="https://github.com/user-attachments/assets/f23b9b82-ea63-4808-a5b0-a1cbe33f2909" />| 
Admin PC|192.168.10.101|255.255.255.0|192.168.10.1|192.168.10.2| <img width="1716" height="241" alt="Admin PC" src="https://github.com/user-attachments/assets/b3d71da6-6e97-4549-865b-2abd0aa99425" /><img width="1713" height="240" alt="Project PC" src="https://github.com/user-attachments/assets/913b30cf-24c8-4fbb-b18b-e1933e77f497" />|
Project PC|192.168.10.111|255.255.255.0|192.168.10.1|192.168.10.2|<img width="1713" height="240" alt="Project PC" src="https://github.com/user-attachments/assets/3c55574f-f2b5-46ff-8545-5e4688e8fd20" />|
CAD PC|192.168.10.121|255.255.255.0|192.168.10.1|192.168.10.2|   <img width="1717" height="246" alt="Cad Pc" src="https://github.com/user-attachments/assets/53c1c432-641a-4c38-aeff-dff207f6981d" />|
Visual PC|192.168.10.131|255.255.255.0|192.168.10.1|192.168.10.2|<img width="1715" height="237" alt="Visual PC" src="https://github.com/user-attachments/assets/00981271-0e77-4c62-b1d4-543b2819e427" />|
ISP / Cloud Server|203.0.113.10|255.255.255.0|203.0.113.1|192.168.10.2|<img width="1714" height="243" alt="ISP_CLOUD server" src="https://github.com/user-attachments/assets/faaab48a-dc6d-471b-9c89-9935ba492ac9" />|
