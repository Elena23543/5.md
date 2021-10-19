
answers to questions:
1)root@8935c4c3aac6:/# apt install less
2)root@8935c4c3aac6:/# pwd
/
3)root@8935c4c3aac6:/# cd /
4)root@8935c4c3aac6:/# ls
bin  boot  dev  docker-entrypoint-initdb.d  etc  home  lib  lib32  lib64  libx32  media  mnt  opt  proc  root  run  sbin  srv  sys  tmp  usr  var
5)root@8935c4c3aac6:/# ls -F --color
bin@  boot/  dev/  docker-entrypoint-initdb.d/  etc/  home/  lib@  lib32@  lib64@  libx32@  media/  mnt/  opt/  proc/  root/  run/  sbin@  srv/  sys/  tmp/  usr/  var/
6)root@8935c4c3aac6:/# ls -F --color ~ root@8935c4c3aac6
ls: cannot access 'root@8935c4c3aac6': No such file or directory
7)root@8935c4c3aac6:/# cd
root@8935c4c3aac6:~# 
8)root@8935c4c3aac6:~# pwd
/root
root@8935c4c3aac6:~# 
9)root@8935c4c3aac6:~# cd . .
bash: cd: too many arguments
10)ls -выводит список содержимого, ls -R более подробная информация 
11)root@8935c4c3aac6:/ls -a
.  ..  .dockerenv  bin  boot  dev  docker-entrypoint-initdb.d  etc  home  lib  lib32  lib64  libx32  media  mnt  opt  proc  root  run  sbin  srv  sys  tmp  usr  var
12)total 60
13)root@8935c4c3aac6:/# ls -F
bin@  boot/  dev/  docker-entrypoint-initdb.d/  etc/  home/  lib@  lib32@  lib64@  libx32@  media/  mnt/  opt/  proc/  root/  run/  sbin@  srv/  sys/  tmp/  usr/  var/
14)root@8935c4c3aac6:/# cd
root@8935c4c3aac6:~# 
15)root@8935c4c3aac6:~# cd /etc
root@8935c4c3aac6:/etc# cd X11
16)root@8935c4c3aac6:~# cd /etc
root@8935c4c3aac6:/etc# cd X11
root@8935c4c3aac6:/etc/X11# cd .
17)root@8935c4c3aac6:/etc/X11# home
18)root@8935c4c3aac6:/etc/X11# ls group
19)root@8935c4c3aac6:/etc/X11# ls -passwd
ls: invalid line width: 'd'
20)root@8935c4c3aac6:/etc/X11# ls -a
.  ..  Xsession.d
21)
