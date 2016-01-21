#!/usr/bin/env python
#Copy right (c) Alan

import socket

#ip , TCP
clientSocket = socket.socket(socket.AF_INET, socket.SOCK_STREAM)

clientSocket.connect(("www.google.ca", 80))

#clientSocket.connect(("127.0.0.1", 8080))
request = "HEAD / HTTP/1.0\n\n"

clientSocket.sendall(request)

response = bytearray()

done  = False

while True:
	part = clientSocket.recv(1024)
	if (part): 
		response.extend(part)
	else:
		break
print response
