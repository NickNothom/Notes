# AutoSSH

# Client:

Install: autossh, screen

Startup line in /etc/rc.local:

su nick -c '/home/nick/autossh'

Startup Script:

screen -dm -S 'autossh' bash -c 'sleep 60 && autossh -M 65500 -o ServerAliveInterval=20 -R 2222:localhost:22 nick@nicknothom.com'


# Server:

ssh -p 2222 username@127.0.0.1
