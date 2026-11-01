# SOC-project-module-wireshark-Extra-
This is my wireshark module project having finding an attacker, following TCP streams among others
open web browser chrome and searched for wireshark, selected the operating system of my pc and downloaded it
I went on with installation process for the wireshark until the last command of finish
<img width="1059" height="727" alt="Screenshot 2026-10-31 210832" src="https://github.com/user-attachments/assets/e718c6f7-95de-41c2-a9b3-4653cffa2cf0" />
I had to clear the dns (clearing the cache) by opening the cmd and typed in these commands ipconfig /flushdns and ipconfig /all

<img width="895" height="666" alt="Screenshot 2026-10-31 210412" src="https://github.com/user-attachments/assets/df829352-0c3e-42ad-91b0-5ce228232261" />
identifying the attacker ip address
open wireshark, select wifi and start capturing packets. open chrome and login as a guest on the website networkwalks.com, filter packets by dns.qry.name == networkwalks.com command and look for source and destination 

<img width="1132" height="723" alt="Screenshot 2026-11-01 222908" src="https://github.com/user-attachments/assets/1ed2ac88-a099-4919-aa76-83693beffecf" />

follow tcp stream part 1
open wireshark, select wifi and start capturing packets. open chrome and login as a guest on the website networkwalks.com, filter packets by dns.qry.name == networkwalks.com
right click on the website ip address, go to follow and click on tcp stream

<img width="1242" height="725" alt="Screenshot 2026-11-01 224052" src="https://github.com/user-attachments/assets/d4564544-13b6-4b6d-9e63-9919c6a84db1" />

follow tcp stream part 2
open wireshark, select wifi and start capturing packets. open chrome and login as a guest on the website networkwalks.com, filter packets by dns.qry.name == networkwalks.com
right click on the website ip address, go to follow and click on tcp stream

<img width="1199" height="727" alt="Screenshot 2026-11-01 224211" src="https://github.com/user-attachments/assets/0d1092ae-7cb9-4cfc-a93c-ced6189daabb" />

http plain text
open wireshark, select wifi and start capturing packets. open chrome and login as a guest on the website networkwalks.com, filter packets by dns.qry.name == networkwalks.com
right click on the website ip address, go to follow and click on http stream
just type http in the wireshark filter

<img width="1121" height="730" alt="Screenshot 2026-11-01 224859" src="https://github.com/user-attachments/assets/93835a96-c756-49bc-bb5b-e93cce1c5803" />

cath the bruteforce attacker
open wireshark, select wifi and start capturing packets. open chrome and login as a guest on the website networkwalks.com, filter packets by dns.qry.name == networkwalks.com


<img width="1106" height="725" alt="Screenshot 2026-11-01 233456" src="https://github.com/user-attachments/assets/10c0f526-742c-43bc-9923-329951e3fa02" />


catch the call scammer 
open wireshark, select wifi and start capturing packets. open chrome and login as a guest on the website networkwalks.com, filter packets by dns.qry.name == networkwalks.com
start call and keep capturing as you continue recording and monitoring the sound

<img width="1192" height="724" alt="Screenshot 2026-11-01 235146" src="https://github.com/user-attachments/assets/5d97e799-1e10-4412-8257-869fd28835e6" />








