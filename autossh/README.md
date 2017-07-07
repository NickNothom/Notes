# AutoSSH

Client:

screen autossh -M 65500 -o ServerAliveInterval=20 -R 2222:localhost:22 username@remote


Server:

ssh -p 2222 username@127.0.0.1
