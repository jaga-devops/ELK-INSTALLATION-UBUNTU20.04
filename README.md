# ELK-INSTALLATION-UBUNTU20.04
$ cd ELK-INSTALLATION-UBUNTU20.04/
$ ls
ansible.cfg  elk.yml  hosts  roles
$ sudo cp elk.yml /etc/ansible/
$ sudo cp -r roles /etc/ansible/
$ sudo ls -l /etc/ansible/
total 32
-rw-r--r-- 1 root root 19985 Mar  5  2020 ansible.cfg
-rw-r--r-- 1 root root   146 Aug 21 06:40 elk.yml
-rw-r--r-- 1 root root   982 Dec 18  2018 hosts
drwxr-xr-x 5 root root  4096 Aug 21 06:40 roles
$ cd /etc/ansible/

Add the elasticsearch server IP in the variable of roles/elasticsearch/defaults/main.yml, roles/filebeat/defaults/main.yml, roles/kibana/defaults/main.yml
