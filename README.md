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

![Screenshot 2024-03-16 104829](https://github.com/Neethiventhan123/2c.ARP_RARP_PROTOCOLS/assets/148514848/412423ee-4017-4f86-aa07-e33da4e0227f)

server:

![Screenshot 2024-03-16 104848](https://github.com/Neethiventhan123/2c.ARP_RARP_PROTOCOLS/assets/148514848/524f605b-f760-4001-9daf-18c49365c071)

## OUPUT - ARP
client:

![Screenshot 2024-03-16 102907](https://github.com/Neethiventhan123/2c.ARP_RARP_PROTOCOLS/assets/148514848/6c38993f-3b23-4242-923c-86b400270771)

server:

![Screenshot 2024-03-16 102938](https://github.com/Neethiventhan123/2c.ARP_RARP_PROTOCOLS/assets/148514848/f86b424e-4113-4e14-8973-897662aa3d09)


## PROGRAM - RARP
client:

![Screenshot 2024-03-16 104904](https://github.com/Neethiventhan123/2c.ARP_RARP_PROTOCOLS/assets/148514848/8685ca82-9571-46a2-ad33-67c532b9e781)

server:

![Screenshot 2024-03-16 104920](https://github.com/Neethiventhan123/2c.ARP_RARP_PROTOCOLS/assets/148514848/97d17622-7a19-4295-a5ce-f4a0f4e6150b)


## OUPUT -RARP
client:

![Screenshot 2024-03-16 104402](https://github.com/Neethiventhan123/2c.ARP_RARP_PROTOCOLS/assets/148514848/91ae10f5-d867-400f-9118-d5e9aaf3607c)

server:

![Screenshot 2024-03-16 104415](https://github.com/Neethiventhan123/2c.ARP_RARP_PROTOCOLS/assets/148514848/a8c68abc-f42d-44be-a0bd-e7fca9f746dc)

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
