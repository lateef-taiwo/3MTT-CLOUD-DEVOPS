# 3MTT-CLOUD-DEVOPS

This repository containe Dockerfiles and notes I used to train students/fellows of the 3MTT Cloud & DevOps program
The repository explains a step by step process on how to write Dockerfiles and also build and push docker images

We will be writing a lot of Dockerfiles for various applications like python, javascript and node applications

### Apache Dockerfile

        # FROM httpd:2.4.54-alpine
        # COPY . /usr/local/apache2/htdocs/\

        FROM httpd:2.4-alpine3.19
        COPY . /usr/local/apache2/htdocs


#### Ordered list
1. Apache webserver
2. nginx webserver
3. IIS
4. Node
5. Mojo

#### Unordered list
* Java

    * Simple java program
    * Hello World Java Program 
* Python
* Go
* Node

### Java Dockerfile

    FROM openjdk:17
    COPY . /usr/src/app/
    WORKDIR /usr/src/app/
    RUN javac Hello.java
    CMD ["java", "Hello"]


You can open a dockerhub account on DockerHub [here](https://hub.docker.com/)

![Github actions](./images/github-actions.png)

![](./images/circleci.png)

Other Programming Languages
`Rust programming` 
