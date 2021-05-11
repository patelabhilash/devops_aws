
jenkin installation reference url : https://linuxize.com/post/how-to-install-jenkins-on-centos-7/
jenkin admin user name : patelabhilash
jenkin password: patelabhilash
jenkin url : http://18.222.129.24:8080/

************************************

deploy 2 serevers slave 1 and slave 2
connect the slaves using JNLP Connection

custom working dir : /home/ubuntu/jenkins

sudo mkdir ubuntu

sudo chown -R ec2-user:ec2-user  /home/ubuntu/jenkins
sudo chmod 777 -R /home/ubuntu/jenkins

root failure login:
ssh -i kp_first.pem root@[Public IPv4 DNS]
ssh -i kp_first.pem ec2-user@[Public IPv4 DNS]

