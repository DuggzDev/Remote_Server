# Remote_Server

Spin up EC2 instance (AWS)

Create SSH key, copy to private key to .ssh 

Change permissions for owner to read and write (chmod 600)

Login to instance by passing in ssh -i "privatekey"@instance

Create another ssh key and generate the public key -- ssh-keygen -y -f "privatekey.pem"

Add that key to the authorized hosts within .ssh

Configure the config file to accept the both private keys

https://roadmap.sh/projects/ssh-remote-server-setup



