Remote_Server

Spin up EC2 instance (AWS)

Create SSH key, copy to .ssh 

# change permissions for owner to read and write

# login to instance by passing in ssh -i "key" <instance>

# Create another ssh key and generate the public key -- ssh-keygen -y -f "privatekey.pem"

# Add that key to the authorized hosts within .ssh

# Configure the config file to accept the both private keys

https://roadmap.sh/projects/ssh-remote-server-setup



