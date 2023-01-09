# ansible-linux-users

This is a simple ansible configuration that creates two linux users (alice and bob) and remove one user (charlie). It also add Alice's and Bob's public key for private key authentication.

The virtual machines were create with Vagrant and Virtualbox.

Prerequisites
-----------------------
Vagrant and virtualbox are both essential and can be easily installed on ubuntu/debian like distro:

	sudo apt-get install virtualbox && sudo apt-get install vagrant


Installation && Running
-----------------------

Do a git clone of the project:

	git clone https://github.com/dcc6fvo/ansible-linux-users

Access the newly created folder with the git clone command and type the following command:

	vagrant up

To forcible destroy all the configurations:

	vagrant detroy -f
