# Python_Reverse_Shell
what is a reverse shell?
According to google "A reverse shell is a shell initiated from the target host back to the attack box which is in a listening state to pick up the shell."

In other words, Reverse shell is getting the connection from the victim or target to your computer(that assumes to be attacker here). You can think of, your computer (attacker) acts like a server and listens on port specified, Now here victim connects to you and in the end connection appears as if victim himself intending to connect us. When target machines have strong firewalls then reverse shells come in handy.[ here's a video on youtube that explains reverese shells, watch for better understanding ](https://www.youtube.com/watch?v=ps00wDz6d-U)

---

![a](https://www.timip.net/content/images/2020/08/ICMP-ReverseShell11042014.gif)

---


# How to use these codes:
1. simply clone the repository : **git clone https://github.com/ramixix/Python_Reverse_Shell.git**

2. move to Python_Reverse_Shell directory : **cd Python_Reverse_Shell**

3. copy server.py on attacker machine and chnage "Bind_ip" and "Bind_port" variables to ip and port that you want your server to listen on and then run the server.py script : **pyhton3 server.py**

4. download the client.py on attacher machine, open the script and change "IP" and "PORT" variables to ip and ports that your server is listening on and then run the script : **python3 client.py**
