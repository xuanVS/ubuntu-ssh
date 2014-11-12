ubuntu-ssh
==========


Build the image using:

$ sudo docker build -t kent/test_ssh ./


example：
$ docker run -d -p 22222:22 kent/test_ssh



$ ssh root@ipaddress -p 22222
