# spring-boot-microservices-new
This repository contains the latest source code of the spring-boot-microservices tutorial


K8s branches - K8 folder has the updated deployment files

It contains working deployment files

#Below command can be used to build the image and push it


mvn compile jib:build -D'jib.to.auth.username'=<username> -D'jib.to.auth.password'=<password>

username should be username not whole email, if it still gives error delete creds from config.json of .docker folder


Order to Inventory call is still not working
