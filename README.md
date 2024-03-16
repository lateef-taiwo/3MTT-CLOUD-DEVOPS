# 3MTT-CLOUD-DEVOPS

The repository explains a step by step process on how to write Dockerfiles and also build and push docker images

We will be writing a lot of Dockerfiles for various applications like python, javascript and node apps

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
