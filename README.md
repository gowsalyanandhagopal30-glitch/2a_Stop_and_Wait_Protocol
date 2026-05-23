# 2a_Stop_and_Wait_Protocol
## AIM 
To write a python program to perform stop and wait protocol
## ALGORITHM
1. Start the program.
2. Get the frame size from the user
3. To create the frame based on the user request.
4. To send frames to server from the client side.
5. If your frames reach the server it will send ACK signal to client
6. Stop the Program
## PROGRAM
CLIENT:
/*
DEVELOPED BY:N.Gowsalya
REGISTER NO:212225230085

import socket
s=socket.socket()
s.bind(('localhost', 8001))
s.listen(5)
c,addr=s.accept()
while True:
    i=input("Enter a data: ")
    c.send(i.encode())
    ack=c.recv(1024).decode()
    if ack:
        print(ack)
        continue
    else:
        c.close()
        break
*/

SERVER:

DEVELOPED BY:N.Gowsalya
REGISTER NO:212225230085

/*
import socket
s=socket.socket()
s.connect(('localhost', 8001))
while True:
    print(s.recv(1024).decode())
    s.send("Acknowledgement Recived from the server".encode())


*/

## OUTPUT
<img width="587" height="235" alt="Screenshot 2026-05-23 084252" src="https://github.com/user-attachments/assets/95a0d5ba-4dac-42c7-acd2-f3bd9baa383f" />

<img width="526" height="139" alt="Screenshot 2026-05-23 084309" src="https://github.com/user-attachments/assets/cd142cec-85f4-435f-9af7-70dec85ed166" />


## RESULT
Thus, python program to perform stop and wait protocol was successfully executed.
