import socket
target = "google.com"

ports = [22,80,443]

for port in ports :
s= socket.socket()

try: 
s.connect((target ,port))
print(f"port {port} is open")
except:
print(f"port {port} is closed")


s.close()
