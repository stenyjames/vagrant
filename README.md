# 
How to use this vagrant box
- This vagrantfile downloads the Centos 6.3 preconfigured with the following softwares
- Jenkins 1.636
- Ant 1.9.6
- Maven 3.3.3
- Java 1.7, 1.8
- Artifactory 4.2.2
- git 


Copy this vagrantFile to your local machine
- Run the command => - Vagrant up  (This will download the centos box from Atlas Hashicorp)


- Installed Location : /opt/software/

-Services :

- Service to start jenkins : sudo service jenkins start | stop | restart
- Service to start artifactory : sudo service artifactory start | stop | restart

-  Url's :

- Jenkins -> http://localhost:8080/jenkins
- Artifactory -> http://localhost:8081/artifactory


- Credentials : 
- User / pass : vagrant / vagrant
- User / pass : root : root / vagrant 
- User / pass : devops : devops / devops

- Jenkins Login credentials devops / devops
