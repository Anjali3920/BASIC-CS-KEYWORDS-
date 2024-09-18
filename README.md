using EC2 in aws
First open aws search EC2 then Launch Instance and there select keypair in putty then download it

after that Launch it and run putty and paste public id on HOST NAME and open that downloaded key pair for putty in SSH then Auth then Credentials and open there

after that run it and write username as ubuntu as selected os and then type following commands

sudo apt update
sudo apt install apache2
to install a web server on ip then

sudo su
How to make a vm( virtual machine)= 1.make an account on aws,    2.select ec2 service,    3.inside ec2 make an instance,   4. For an instance  select an os( operating system),    5.make an key pair ( the key pair will automatically be downloaded).  ,6 while making key pair select ppk type ,     7.an public ip will be generated,   8.launch the instance 9. Install an putty ( search on google how to download putty for (the operating system you have chosen) and download it, 10. After that open the putty and on ssh option paste the public ip from the instance,  11.in the aut option select credentials and browse the key pair you have created in instance,   12. Now to download a web server open putty and type :-sudo apt update, after that type :-sudo apt Install apache2,   13:- to remove the dollar sign type:- sudo su,   14:- after that the next step is to type :-/var/www/html/ ,15.enter the above and on the next line type index.html, 16.after that type :-rm index.html, 17.enter the above and type :-vi index.html ( by writing this  a new page will appear in which you have to either type html code aur copy paste it from GitHub),  18.to run the code type :- control+c ,shift+ ,wq and enterHow to make a vm( virtual machine)= 1.make an account on aws,    2.select ec2 service,    3.inside ec2 make an instance,   4. For an instance  select an os( operating system),    5.make an key pair ( the key pair will automatically be downloaded).  ,6 while making key pair select ppk type ,     7.an public ip will be generated,   8.launch the instance 9. Install an putty ( search on google how to download putty for (the operating system you have chosen) and download it, 10. After that open the putty and on ssh option paste the public ip from the instance,  11.in the aut option select credentials and browse the key pair you have created in instance,   12. Now to download a web server open putty and type :-sudo apt update, after that type :-sudo apt Install apache2,   13:- to remove the dollar sign type:- sudo su,   14:- after that the next step is to type :-/var/www/html/ ,15.enter the above and on the next line type index.html, 16.after that type :-rm index.html, 17.enter the above and type :-vi index.html ( by writing this  a new page will appear in which you have to either type html code aur copy paste it from GitHub),  18.to run the code type :- control+c ,shift+ ,wq 
For basic cs knowledge 






what is docker :-docker is a containerization platform that enables developers to package, ship, and run applications in containers, which are lightweight and portable encapsulations of software and its dependencies.


*Key Features:*

1. Containerization: Run multiple isolated applications on a single host.
2. Lightweight: Containers share the host's kernel, reducing overhead.
3. Portable: Containers run consistently across
[18/09, 9:32 am] Meta AI: Docker is a containerization platform that enables developers to package, ship, and run applications in containers, which are lightweight and portable encapsulations of software and its dependencies.


*Key Features:*

1. Containerization: Run multiple isolated applications on a single host.
2. Lightweight: Containers share the host's kernel, reducing overhead.
3. Portable: Containers run consistently across environments.
4. Isolation: Containers provide secure, isolated environments.
5. Scalability: Easily scale containers up or down.


*Benefits in Cloud Computing:*

1. Efficient Resource Utilization
2. Faster Deployment
3. Improved Security
4. Simplified Management
5. Enhanced Scalability
6. Better Compatibility

platform supporting docker

1. Amazon Web Services (AWS)
2. Microsoft Azure
3. Google Cloud Platform (GCP)
4. IBM Cloud
5. Oracle Cloud
6. DigitalOcean


*Docker Components:*

1. Docker Engine: Runtime environment.
2. Docker Hub: Registry for container images.
3. Docker Compose: Tool for defining multi-container apps.
4. Docker Swarm: Tool for container orchestration.


*Use Cases:*

1. Web Applications
2. Microservices Architecture
3. DevOps
4. Continuous Integration/Continuous Deployment (CI/CD)
5. Big Data Analytics


*Advantages over Virtual Machines (VMs):*

1. Lightweight
2. Faster Boot Times
3. Better Resource Utilization
4. Easier Management


*Common Docker Commands:*

1. docker run
2. docker build
3. docker push
4. docker pull
5. docker stop
6. docker start


https://images.app.goo.gl/1hUHPqTDDLV88h3w6
