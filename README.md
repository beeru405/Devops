# Devops
jenkins instalation error in ubuntu 22.04
path : /etc/apt/sources.list.d/jenkins.list

deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] https://pkg.jenkins.io/debian binary/

Update it as
```
deb [trusted=yes] https://pkg.jenkins.io/debian binary/
```
then run these commands
```
sudo apt-get update
sudo apt-get install fontconfig openjdk-11-jre
sudo apt-get install jenkins
```
