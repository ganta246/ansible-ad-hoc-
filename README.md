# ansible-ad-hoc-
this is a ansible
i = inventory
b = become sudo user
m = module
a =arguments
sudo -i
sudo apt install ansible -y
ansible --version
adduser ansible
password:
root user ga marachali
visudo
ansible ALL=(ALL) NO PASSWD : ALL
cd /etc/ssh
vi sshd_config
passwd authecation : yes



ansible node instance create

sudo -i
apt update
adduser ansible
password
visudo
ansible ALL=(ALL) NO PASSWD : ALL
cd /etc/ssh
vi sshd_config
passwd authecation : yes
service ssh restart
cd
su ansible
ssh-keygen
ls -a
ssh-copy-id public ip copy
mkdir madhu 
cd madhu
vi hosts
private ip copy
save
cd ..
ls
rm -rf madhu
exit
mkdir madhu
cd madhu
vi madhu
private ip paste
ansible all  -i  hosts -m  ping
adhoc commands
mkdir m1
cd m1
touch f1 f2 f3
mkdir m2
cd m2
touch g1 g2 g3 mkdir m3
touch h1 h2 h3
cd ../.. / .. 
ls
tree m1
master ki veli 
mkdir  m1
cd m1
touch f1 f2 f3
mkdir m2
cd m2
touch g1 g2 g3
cd
tree m1
ls
ansible all  -i  hosts -b  -m apt -a  "name=tree"









