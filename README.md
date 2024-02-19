# build-linux
This is the project for remake kali linux as before. This is a ansible script which will do lots of work which i need to do after installing the fresh kali linux one by one. By executing this script i will get back all my privious settings custom commands everything. It will update my machine fully also update the searchsploit database.

## Installation 
```
git clone https://github.com/Raju-Talukder/build-linux.git
cd build-linux
ansible-playbook main.yml -K
```
N.B: it will ask for the super user (root) password.

## It will install this tools 
```
- sublime-text
- gobuster
- seclists
- ltrace
- html2text
- jq
- gh
- rsh-client
- flameshot
- xclip
```
## Others 
```
- Full update & upgrade the system including kernel
- Configure the bashrc with custom alias
- Configure tmux used to configurations
- Setup the custom handy commands
- Unzip rockyou.txt if its ziped.
```

