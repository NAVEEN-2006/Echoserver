## NAME  : NAVEEN KUMAR S
## REG NO: 212223040129
# Echoserver
Echo server and client using python socket

# AIM:

To develop a simple webserver to serve html programming pages.

## DESIGN STEPS:

### Step 1:

Design of echo server and client using python socket

### Step 2:

Implementation using Python code

### Step 3:

Testing the server and client 

## PROGRAM:

```python
Client.py
import socket
HOST = "127.0.0.1" 
PORT = 65432  
with socket.socket(socket.AF_INET, socket.SOCK_STREAM) as s:
    s.connect((HOST, PORT))
    s.sendall(b"NAME : NAVEEN KUMAR S REG NO:212223040129")
    data = s.recv(1024)
print(f"Received {data!r}")
```

```python
Server.py
import socket
HOST = "127.0.0.1" 
PORT = 65432  
with socket.socket(socket.AF_INET, socket.SOCK_STREAM) as s:
    s.connect((HOST, PORT))
    s.sendall(b"NAME : NAVEEN KUMAR S REG NO:212223040129")
    data = s.recv(1024)
print(f"Received {data!r}")
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/1cc0da5e-0e0c-45ac-b661-c775cf5d12b6)

![image](https://github.com/user-attachments/assets/6cb26a0e-c1a2-47b3-9987-5462b9f6c504)


## RESULT:
The program is executed successfully
