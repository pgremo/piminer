Initial Setup
=============
1. arp -a
2. ssh-copy-id root@<ip address\>
3. ssh <ip address\>
4. hostnamectl set-hostname <hostname\>
5. pacman -Suy --noconfirm
6. pacman -S python2 --noconfirm
7. exit
8. configure inventory file (e.g. hosts)
9. ansible-playbook -u root -i <inventory\> piminer.yaml