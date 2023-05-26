# EX-7 IMPLEMENTATION OF TRACEROUTE COMMAND

# DATE : 
20-04-2023

# AIM :
To write the python program for simulating Traceroute command

# ALGORITHM :
1. Start the program.
2. Get the frame size from the user.
3. To create the frame based on the user request.
4. To send frames to server from the client side.
5. If your frames reach the server, it will send ACK signal to client otherwise it will sendNACK signal to client.
Stop the program

# PROGRAM :
```
# Developed By : Manoj MV
# Register Number : 212222220023
from scapy.all import*
target = ["www.google.com"]
result, unans = traceroute(target,maxttl=32)
print(result,unans)
```
# OUTPUT :
![image](https://github.com/Kishore2o/EX-7/assets/118679883/8794e24e-c5f7-405f-8e05-602937950a74)


# RESULT :

Thus, the python program for simulating Traceroute command was successfully executed.
