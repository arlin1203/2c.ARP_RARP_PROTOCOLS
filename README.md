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
<img width="508" height="267" alt="image" src="https://github.com/user-attachments/assets/12317f92-410b-4102-82e2-f47f57821930" />

server:
<img width="547" height="193" alt="image" src="https://github.com/user-attachments/assets/296eac9a-125a-4346-9b2a-5c8a86bdd7b5" />


## OUPUT - ARP
client:                        server:
<img width="873" height="235" alt="image" src="https://github.com/user-attachments/assets/3f398c9d-9805-4fbb-b34b-9af81a7bd534" />

## PROGRAM - RARP
client:
<img width="647" height="262" alt="image" src="https://github.com/user-attachments/assets/a62cddbb-e97f-47da-a3d3-26dbc52fb25e" />

server:
<img width="747" height="175" alt="image" src="https://github.com/user-attachments/assets/1b1297c1-f97c-4351-b66e-1efa773b65ca" />

## OUPUT -RARP
client:                  server:
<img width="862" height="223" alt="image" src="https://github.com/user-attachments/assets/b4f8c3b5-2002-42b5-b1e5-284650ee9bb3" />

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
