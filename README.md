ubuntu-ssh
==========
ubuntu:14.04


Build the image using:
======
$ sudo docker build -t kent/ubuntu-ssh ./


Example：
======
$ docker run -d -p 22222:22 kent/ubuntu


Use ssh connect to container
======
$ ssh root@ipaddress -p 22222
