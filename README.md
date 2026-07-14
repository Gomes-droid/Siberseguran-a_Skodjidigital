# Siberseguran-a_Skodjidigital


<img width="1598" height="1002" alt="Tarefas" src="https://github.com/user-attachments/assets/944ecbeb-7393-42f9-bbca-a1536d5711a8" />


<img width="1853" height="978" alt="Captura de ecrã 2026-07-14 212924" src="https://github.com/user-attachments/assets/dbf705cc-2b8f-42ae-8ec7-00b7fdfd815c" />


<img width="1862" height="911" alt="nmap instal" src="https://github.com/user-attachments/assets/48b8a5cc-74b4-4993-92f6-359bdf5c3f5f" />


SS -TULN
root@ip-10-129-185-75:~# ss -tuln
Netid State  Recv-Q Send-Q      Local Address:Port    Peer Address:Port Process 
udp   UNCONN 0      0                 0.0.0.0:53           0.0.0.0:*            
udp   UNCONN 0      0      10.129.185.75%ens5:68           0.0.0.0:*            
udp   UNCONN 0      0               127.0.0.1:111          0.0.0.0:*            
udp   UNCONN 0      0          172.17.255.255:137          0.0.0.0:*            
udp   UNCONN 0      0              172.17.0.1:137          0.0.0.0:*            
udp   UNCONN 0      0          10.129.191.255:137          0.0.0.0:*            
udp   UNCONN 0      0           10.129.185.75:137          0.0.0.0:*            
udp   UNCONN 0      0                 0.0.0.0:137          0.0.0.0:*            
udp   UNCONN 0      0          172.17.255.255:138          0.0.0.0:*            
udp   UNCONN 0      0              172.17.0.1:138          0.0.0.0:*            
udp   UNCONN 0      0          10.129.191.255:138          0.0.0.0:*            
udp   UNCONN 0      0           10.129.185.75:138          0.0.0.0:*            
udp   UNCONN 0      0                 0.0.0.0:138          0.0.0.0:*            
udp   UNCONN 0      0                 0.0.0.0:8443         0.0.0.0:*            
udp   UNCONN 0      0               127.0.0.1:323          0.0.0.0:*            
udp   UNCONN 0      0                    [::]:53              [::]:*            
udp   UNCONN 0      0                   [::1]:111             [::]:*            
udp   UNCONN 0      0                    [::]:8443            [::]:*            
udp   UNCONN 0      0                   [::1]:323             [::]:*            
tcp   LISTEN 0      200             127.0.0.1:5433         0.0.0.0:*            
tcp   LISTEN 0      4096              0.0.0.0:7778         0.0.0.0:*            
tcp   LISTEN 0      4096              0.0.0.0:7777         0.0.0.0:*            
tcp   LISTEN 0      4096            127.0.0.1:111          0.0.0.0:*            
tcp   LISTEN 0      50                0.0.0.0:445          0.0.0.0:*            
tcp   LISTEN 0      4096              0.0.0.0:22           0.0.0.0:*            
tcp   LISTEN 0      32                0.0.0.0:53           0.0.0.0:*            
tcp   LISTEN 0      50                0.0.0.0:139          0.0.0.0:*            
tcp   LISTEN 0      10                0.0.0.0:8443         0.0.0.0:*            
tcp   LISTEN 0      1024            127.0.0.1:21047        0.0.0.0:*            
tcp   LISTEN 0      4096                 [::]:7778            [::]:*            
tcp   LISTEN 0      4096                 [::]:7777            [::]:*            
tcp   LISTEN 0      50                   [::]:445             [::]:*            
tcp   LISTEN 0      4096                 [::]:22              [::]:*            
tcp   LISTEN 0      32                   [::]:53              [::]:*            
tcp   LISTEN 0      4096                [::1]:111             [::]:*            
tcp   LISTEN 0      50                   [::]:139             [::]:*            
tcp   LISTEN 0      10                   [::]:8443            [::]:*            
root@ip-10-129-185-75:~# 
