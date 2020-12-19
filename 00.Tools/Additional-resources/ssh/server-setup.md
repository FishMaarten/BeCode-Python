# How to setup a local SSH/Apache Server for the exercise...


1. install openssh  + apache2 + git   
 `apt-get install openssh apache2 git`
1. edit ssh config to set port to 1992:
	1. `vi /etc/ssh/sshd_config`
	2. change "Port 22" to "Port 1992"
1. `sudo adduser junior`  password: `yolo`
1. `sudo usermod -aG www-data junior`
1. create a symbolic link from `/home/junior/www` to `/var/www/html` : 
`ln -s /var/www/html /home/junior/www`
1. to find the server's current IP address: 
 `hostname -I`


You are now ready to launch your juniors [in the exercise](./readme.md)...
