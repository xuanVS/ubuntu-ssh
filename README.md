ubuntu-ssh
==========
ubuntu:14.04


Build the image using:
======
$ sudo docker build -t kent/test_ssh ./


Example：
======
$ docker run -d -p 22222:22 kent/test_ssh


Use ssh connect to container
======
$ ssh root@ipaddress -p 22222
