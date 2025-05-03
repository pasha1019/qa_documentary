Simple example run jenkins in docker 
--
docker run -p 8080:8080 -p 50000:50000 --restart=on-failure -v jenkins_home:/var/jenkins_home jenkins/jenkins:lts-jdk17

Example open page-jenkins in web
--
http://localhost:8080  
