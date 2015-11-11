# 
How to use this vagrant box
This vagrantfile downloads the Centos 6.3 preconfigured with the following softwares
- Jenkins
- Ant
- Maven
- Java 
- Artifactory
- git


Copy this vagrantFile to your local machine
- Run the command => - Vagrant up  (This will download the centos box from Atlas Hashicorp)


Content of this box

Centos 6.3
Jenkins
Java 1.7,1.8
Ant
Maven
Artifactory 4.2.2
Installed Location : /opt/software/

Services :

Service to start jennkins : sudo service jenkins start | stop | restart
Service to start artifactory : sudo service artifactory start | stop | restart
Url's :

Jenkins -> http://localhost:8080/jenkins
Artifactory -> http://localhost:8081/artifactory
Credentials : vagrant / vagrant root : root / vagrant devops : devops / devops

Jenkins Login credentials devops / devops
