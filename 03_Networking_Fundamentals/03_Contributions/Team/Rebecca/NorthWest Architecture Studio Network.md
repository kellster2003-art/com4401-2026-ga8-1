Required Tests
<br>
<br>
|**Test**|**Command Actions**|**What it Proves**|**Screenshot**|
|:-|:-|:-|:-|
|LAN PC-to-PC|ping 192.168.10.101|What it proves?|!<img width="1711" height="1374" alt="1)_LAN_PC_to_PC" src="https://github.com/user-attachments/assets/3e63efb8-1c0e-49c7-baeb-f13f12be68a1" />
|PC to Office Server| ping 192.168.10.10|What it proves|!<img width="1711" height="1734" alt="2)_PC_to_Office_Server" src="https://github.com/user-attachments/assets/cabe2d86-0de2-4fa5-af88-8598d00bacc4" />
|PC to DNS Server|ping 192.168.10.2|What it proves?|!<img width="1716" height="1378" alt="3)_PC_to_DNS_Server" src="https://github.com/user-attachments/assets/faf28fff-8e5a-49f1-850a-feb44d47427d" />
|Internal web by IP|http://192.168.10.10|What it proves?|!<img width="1715" height="1385" alt="4)_Internal_web_by_IP" src="https://github.com/user-attachments/assets/0fbdf931-54bf-4aec-b157-4cefeb135a58" />
|Internal web by name|http://intranet.archstudio.local|What it proves?|!<img width="1706" height="1379" alt="5)_Internal_web_by_name" src="https://github.com/user-attachments/assets/44448f10-d72a-404e-8fd4-99a6ce5e2e37" />
|External server ping|ping 203.0.113.10|What it proves?|!<img width="1706" height="1376" alt="6)_External_server_ping" src="https://github.com/user-attachments/assets/23dce690-0c91-49de-b577-45ab9830049a" />
|External web by IP|http://203.0.113.10|What it proves?|!<img width="1704" height="1374" alt="7)_External_web_by_IP" src="https://github.com/user-attachments/assets/0ee6aec6-aab8-457f-b3ba-d008ea5e5cdb" />
|External web by name|http://cloud.archstudio.example|What it proves?|!<img width="1704" height="1367" alt="8)_External_web_by_name" src="https://github.com/user-attachments/assets/d3e84785-11f5-4439-bfd6-11689abaa56e" />
<br>
<br>
<br>
<br>
EXPLINATION PROTOCALS AND CONCEPTS
<br>

|**CONCEPTS**|**WHERE IT APPEARS**|**EXPLINATION**|
|:-|:-|:-|
TCP/IP|All device communication||
IP addressing|Every device has a unique IP|| 
Subnet mask|255.255.255.0 on both networks|| 
Gateway|Client PCs use 192.168.10.1|| 
DNS|intranet.archstudio.local etc.||
HTTP|Opening pages in the browser|| 
ICMP / ping|Ping tests||
Client-server|CAD PC → Office/Cloud Server||
Switch vs router| Office/External switch; Office Router||
<br>
<br>
<br>
<br>
Evidence to submit, team roles & contribution

|**Required Evidence**|**Screenshot**|
|:-|:-|
Topology screenshot (office LAN, router, external switch, ISP/cloud server)|!<img width="1500" height="1300" alt="0) _Topology" src="https://github.com/user-attachments/assets/368eee43-a075-406e-97ee-45618438ade5" />|
Completed IP addressing table|!<img width="1101" height="902" alt="image" src="https://github.com/user-attachments/assets/c89fbf00-7124-4437-848f-191390e27f1e" />|
Router-interface screenshot|!<img width="2556" height="571" alt="image" src="https://github.com/user-attachments/assets/56b09ce0-0820-41bb-9bc9-b46e433ce096" /> <img width="2558" height="547" alt="image" src="https://github.com/user-attachments/assets/067d40ec-19bf-4f06-8673-58b0bae76999" />|
DNS-records screenshot|
Internal and external web pages opening from the CAD PC|
At least three successful ping tests|
a protocol table explaining 5+ concepts|
a short explanation of the LAN vs external network and of the client-server model|
<br>
<br>

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

