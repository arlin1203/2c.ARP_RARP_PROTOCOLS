# 2c.SIMULATING ARP /RARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.
## ALGORITHM:
## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.
P
## PROGRAM - ARP
client:
<img width="552" height="200" alt="Screenshot 2026-05-12 120615" src="https://github.com/user-attachments/assets/b3bd1082-0bd0-421b-9e50-29b8d510ca74" />

server:
<img width="818" height="317" alt="Screenshot 2026-05-12 120528" src="https://github.com/user-attachments/assets/da4b9fad-7067-456d-92ee-b7f74df54382" />

## OUPUT - ARP
client:                        server:
<img width="1787" height="509" alt="Screenshot 2026-05-12 120741" src="https://github.com/user-attachments/assets/b0b4ba2d-4b1a-42b1-bd57-39b11fb98715" />

## PROGRAM - RARP
client:
<img width="747" height="340" alt="image" src="https://github.com/user-attachments/assets/49fb37a6-cb6a-4469-9fd0-525b3f145378" />

server:
<img width="622" height="166" alt="image" src="https://github.com/user-attachments/assets/3531442b-c48c-4e94-a6ef-9b0413e8c786" />

## OUPUT -RARP
client:                  server:
<img width="1817" height="528" alt="image" src="https://github.com/user-attachments/assets/1e4f1250-e757-4cd7-9543-b0279e13c4dc" />

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
