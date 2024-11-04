
# KEYWORDS:
## Computation:

Computation is driven by the CPU (Central Processing Unit), GPU (Graphics Processing Unit), and ASICs (Application-Specific Integrated Circuits). These components form the backbone of data processing and number crunching in both personal and enterprise computing environments.

## Hardware

Hardware includes the physical components that make up a computer system. From the memory (RAM) and storage devices to semiconductors that drive the computational logic, hardware plays a vital role in computing.

## Storage

In computer science, storage is the process of capturing and preserving digital information on storage media. Storage can be used in many places, including offices, data centers, remote locations, and mobile devices.

## Fullstack Development

A Fullstack developer is proficient in both frontend and backend technologies. This combined skill set allows developers to create fully integrated web applications.

## Networking:

#3.1 Local area network (LAN): A LAN covers a small geographic area suvh as a home, office or campus.

#3.2 Wide Area Network (WAN) :

A WAN spans a large geographic like multipke cities or countries.

#3.3 NIC (Network Interface Card)

A network interface card (NIC) is a hardware component, typically a circuit board or chip, installed on a computer so it can connect to a network. Modern NICs provide functionality to computers, such as support for input/output interrupt, direct-memory access interfaces, data transmission, network traffic engineering and partitioning.

## Operating Systems

An operating system (OS) is system software that manages computer hardware and software resources, and provides common services for computer programs. Kernel: The core part of the OS that manages system resources. OS Layer: Abstracts hardware resources for higher-level software. Applications: Programs that run on top of the OS. CISC & RISC: Two primary CPU instruction set architectures. Virtual Machine: An emulation of a computer system.

## Bare Metal

Bare metal refers to a physical computer server that's dedicated to a single user, or tenant. It can also refer to a computer's hard disk, or a virtualization environment that runs without a host operating system.

## Ethernet

Ethernet is a wired computer networking technology that allows devices to communicate with each other over a local area network (LAN), metropolitan area network (MAN), or wide area network (WAN).

## Virtual Machine
 
A virtual machine (VM) is a software-based computer that functions like a physical computer, but exists within another computer's operating system. In cloud computing, VMs are used to virtualize the resources of cloud service providers' servers. This allows multiple customers to share resources, which is known as multi-tenant cloud architecture.

## Virtualization and Cloud

Virtualization allows multiple operating systems to run on the same physical hardware, facilitated by a hypervisor. The cloud enables on-demand availability of computing resources.

## Blockchain abd Cryptocurrencies

Blockchain technology records and confirms cryptocurrency trades, like a digital ledger. It collects and stores information about buying, selling, or exchanging digital assets. This information exists without a central authority (such as a bank) overseeing or controlling the cryptocurrency market.

## Programming and Development

Compiler: Converts high-level code into machine code. Interpreter: Executes code line by line. Algorithms: Step-by-step procedures for solving problems. Data Structures: Ways to organize and store data efficiently. DSA (Data Structures & Algorithms): Crucial for performance optimization in software development.

## Open Source

Open source refers to software whose source code is made available to the public for anyone to view, use, modify, and distribute. This model promotes collaboration and transparency, allowing a community of developers and users to contribute to the software’s development and improvement.

## Closed Source

Closed source software, also known as proprietary software, is software whose source code is not made available to the public. Instead, the source code is kept secret by the software's developers or the company that owns it. Users are granted access to the software through licenses but do not have the ability to view, modify, or distribute the source code.

## VPN

Virtual Private Network, is a technology that creates a secure and encrypted connection over a less secure network, such as the internet. It allows users to send and receive data as if their devices were directly connected to a private network, enhancing security and privacy.

## DNS

Domain Name System, is a fundamental component of the internet that translates human-readable domain names into IP addresses that computers use to identify each other on the network. Without DNS, users would have to remember and enter numerical IP addresses to visit websites, rather than simple and memorable domain names like www.example.com.

## IP

An IP address (Internet Protocol address) is a unique numerical label assigned to each device connected to a network that uses the Internet Protocol for communication. IP addresses serve two main functions:

Identification: They uniquely identify a device on a network, ensuring that data is sent to the correct destination. Location Addressing: They provide the location of a device in the network, which helps in routing data packets across the internet.

## RISC-V

RISC-V is an open-source instruction set architecture (ISA) based on the principles of Reduced Instruction Set Computing (RISC). It was designed to be a simple, modular, and extensible ISA, making it a versatile and adaptable choice for a wide range of computing applications.

## CISC

CISC is a type of microprocessor architecture that aims to reduce the number of instructions needed to perform a task by providing a large set of complex instructions. CISC architectures are designed to execute multi-step operations with a single instruction, which can help simplify programming and reduce the number of instructions per program.

## DSA

DSA stands for Data Structures and Algorithms, which are fundamental concepts in computer science and software engineering. Understanding and applying DSA effectively is crucial for designing efficient and scalable software. Here’s a breakdown of these concepts:

Data Structures- Data structures are specialized formats for organizing, managing, and storing data in a computer so that it can be accessed and modified efficiently.

## DBMS

DBMS stands for Database Management System, which is a software system that provides an interface for interacting with databases. A DBMS manages and organizes data, supports data manipulation and retrieval, and ensures data integrity and security. It serves as a bridge between users and the database, handling data storage, queries, updates, and administration.

## Linker/Loader

Linker is a software tool that combines multiple object files generated by a compiler into a single executable file. It resolves references between object files and ensures that all code and data are properly connected. Here’s how it works:

## Semiconductors (ICs)

Semiconductor chips (also known as integrated circuits or ICs) are crucial components in modern electronics. They consist of multiple semiconductor devices (such as transistors, diodes, and resistors) integrated onto a single piece of semiconductor material, typically silicon. These chips are used in a wide variety of applications, from simple gadgets to complex computing systems.

# CLOUD SERVICES:
### 1.IAAS: Infrastructure as a Service
### 2.PAAS: Platform as a Service
### 3.SAAS: Software as a Service

# INTRODUCTION OF AWS:

### 1.AWS SERVICES:<br/>
### 2.EC2-Elastic Cloud Computing<br/>
### 3.EBS-Elastic Block Store<br/>
### 4.Auto scaling
### 5.S3-Simple Storage Services<br/>
### 6.ELB-Elastic Load Balancer<br/>
### 7.IAM-Identity and Access Management <br/>
### 8.VPC – Virtual Private Cloud<br/>
### 9.DNS Route 53 - DNS <br/>
### 10.RDS – Relational Database Service<br/>

# Creating VM and adding web server on AWS
#### 1. CREATE AN AWS ACCOUNT
#### 2. THEN GO TO CONSOLE WHERE YOU FIND EC2.
#### 3. THEN CLICK ON LAUCH INSTANCE, WHERE YOU HAVE TO ENTER THE NAME ATG{XYZ}.
#### 4. AFTER THAT SELECT THE OPERATING SYSTEM , THEN CLICK ON FREE TIRE ELIGBLE.
#### 5. NOW YOU HAVE TO CREATE NEW KEY PAIR , WHERE AS KEY PAIR ARE PUBLIC OR PRIVATE. ALSO SELECT THE .PPK THEN PRESS ENTER TO CREATE.DOWNLOAD THE KEY PAIR AND SAVE IT IN DESKTOP ALSO.
#### 6. NOW YOU WILL SEE THE RAM AND CPU WHICH IS GIVEN BY AWS.
#### 7. NOW ALLOW SSH AND HTTP.
#### 8. AFTER ALL THIS STEPS THEN CLICK ON THE LAUNCH INSTANC AND CLICK ON ALL INSTANCE.
#### 9. NOW YOU CAN SEE YOUR CREATED YOUR INSTANCE AND IP ADDRESS.
#### 10. COPY YOUR IP ADDRESS AND PASTE IT IN NEW TAB , YOU WILL FIND NOTHING BECAUSE THEIR IS NO SERVER PRESENT.
#### 11. TO CREATE SERVER INSTALL PUUTY.
#### 12. OPEN PUTTY WHERE FIRST GO TO SESSION AND ENTER YOUR IP ADDRESS.
#### 13. THEN GO SSH THEN AUTH THEN CREDITALS .
#### 14. WHERE YOU HAVE TO CLICK ON BROWSE WEHRE SELECT THE KEY PAIR FILE WHICH IS PRESENT IN DESKTOP.
#### 15. NOW GO TO SESSION AND CLICK ON OPEN
#### 16. YOUR VM IS CREATED.<br/>
#### TO OPEN A WEB SERVER---<br/>
#### 1.TYPE ON GOOGLE HOW TO INSTALL WEB SERVER IN YOUR OS WHICH YOU HAVE SELECTED.<br/>
#### 2.NOW DOWNLOAD ANY WEB SERVER LIKE APACHE2ETC.<br/>
#### 3.FROM THAT INSTALL APACHE2 IN YOUR VM<br/>
## TYPE :
```
sudo apt update
```
```
sudo apt install apache2
```

## ---PRESS ENTER AND WEB SERVER WILL START INSTALLING----<br/>

#### 4.TO SEE THE WEB SERVER GO TO GOOGLE OPEN NEW TAB AND ENTER YOU IP ADDRESS . YOU WILL SEE THE APACHE2 WEB SERVER.<br/>
#### -----------TO SEE HI ON SERVER ---------------<br/>


#### 1.ENTER THE FOLLOWING COMMAND<br/>
```
cd{ENTER SPACE}/var/www/html/
```
```
ls
```

#### YOU WILL SEE<br/>
  
```
index.html
```
#####  ------TO REMOVE SUDO----------- <br/>
  
```
sudo su
```
#####  --------NOW SUDO IS REMOVED--------<br/>

##### -------REMOVE THE APACHE2 SERVER -----------<br/>
```
rm index.html
```
#####  ------THEN ENTER--------<br/>
```
vi index.html
```
```
i
```
##### ----------ENTER----------<br/>
```
<html>  hi   </html>
```
## ------NOW PRESS THESE KEY-------<br/>

### ctrl+c<br/>

### shift+";"<br/>

###  wq<br/>

##### -------PRESS ENTER -------<br/>

###  NOW GO TO GOOGLE AND ENTER THE IP ADDRESS YOU WILL SEE HII<br/>

---------------------------------------------------------------------------------------------------------------------<br/>
<br/>
<br/>
<br/>
<br/>

#  USING DOCKER   CONTAINER's IN VM ,TO ADD NGINX SEVER IN IT AND TYPING HI IN WEB SERVER <br/>

 #### 1. First I login in my AWS account . Thne I created an instance .<br/>
 #### 2. In instance  I make some changes , where I edit in network setting , where I added SSH , HTTPS , HTTP, ALL TRAFFIC , ALL TCP , ALL UDP AND CREATED AN INSTANCE.<br/>
 #### 3. Then I open puuty add the IP address from instance and add key pair file which I have downloaded when I creating instance.<br/>
 #### 4. After that I click  on open , then my ubuntu terminal was opended , where I logined by writting ubuntu.<br/>
 #### 5. After that I have to install docker in my OS .<br/>
 #### 6. Then , I enter few command to  install the docker<br/>
 #### 7. COMMANDS ARE:<br/>
```
curl -sL https://github.com/ShubhamTatvamasi/docker-install/raw/master/docker-install.sh | bash
```
```
newgrp docker
```
### this command will help us to use docker<br/>
```
docker ps
```
### provides a list of the Docker containers on your machine<br/>
```
docker --version
```
### to check the version of docker which is installed<br/>
```
docker pull nginx
```
### TO use nginx server in container<br/>
```
docker run --name docker-nginx -p 80:80 nginx
```
### In a web browser, enter your server’s IP address to reveal Nginx’s default landing page<br/>
## ctrl + c  #to stop the container from running<br/>
```
docker ps -a
```
### The output reveals that the Docker container has exited<br/>
## DETACHED MODE<br/>
```
docker run --name docker-nginx -p 80:80 -d nginx
```
### output is the container’s ID <br/>
```
docker ps
```
### provoide new information about container<br/>
```
docker stop docker-nginx
```
### to stop the container<br/>
```
docker rm docker-nginx
```
## Building a Web Page to Serve on Nginx<br/>
```
mkdir -p ~/docker-nginx/html
```
### Create a new directory for the website content within the home directory<br/>
```
cd ~/docker-nginx/html
```
### Create an HTML file to serve on the server<br/>
```
ls
```
```
cd html/
```
```
ls
```
### will show index.html file<br/>
```
sudo vi index.html
```
```
i
```
### help to insert in the web server<br/>
```
<html> hi </html>
```
### write whatever you want to write I write only hi<br/>
#### ctrl + c<br/>
#### shift + ;<br/>
#### wq   
press {ENTER}<br/>
```
docker run --name docker-nginx -p 80:80 -d -v ~/docker-nginx/html:/usr/share/nginx/html nginx
```
### Linking the container to the VM<br/>
## After running that command, enter the server’s IP address into the browser to view the  new landing page<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

# INSTALLING MINIKUBE IN VM <br/>

### 1. CREATE AN INSTANCE IN AWS AS , WITH OS OF UBUNTU OR WHAT YOU WANT THEN CHANGE SOME SETTINGS TO WORK LIKE TAKING<br/>

###   Amozon Machine Image (AMI)<br/>

###   Instance type<br/>

###   t3.xlarge<br/>
  
###   AND <br/>

###   STORAGE<br/>

###   30GB<br/>

###   NETWORK SETTING YOU CAN INCLUDE<br/>

###   1. SSH<br/>

###   2. HTTP<br/>

###   3. HTTPS<br/>

###   4. ALL TRAFFIC<br/>


### 2. AFTER THESE CHANGES YOU CAN LAUNCH THE INSTNACE<br/>

### 3. AFTER  THAT COPYING THE IP ADDRESS , ADD IT IN PUTTY AND ALSO SELECT THE KEY WHICH HAS BEEN CREATED IN PERIVOUS STEPS , THEN CLICK OPEN , AND YOUR VM IS AGAIN READY<br/>

### 4. NOW WE HAVE TO INSTALL DOCKER<br/>

```
curl -sL https://github.com/ShubhamTatvamasi/docker-install/raw/master/docker-install.sh | bash
```
### THIS COMMAND WILL HELP TO INSTALL DOCKER<br/>

```
sudo usermod -aG docker $USER
```
### THIS COMMAND WILL HEPL TO USE DOCKER FUNCTIONS<br/>

```
newgrp docker
```
### THIS WILL CREATE A NEW GROUP IN OS<br/>


```
sudo snap install kubectl --classic
```
### TO INSTALL kubectl IN DOCKER<br/>

```
kubectl version --client
```
### TO SEE THE VERISON OF kubectl<br/>

```
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
```
### TO INSTALL MINIKUBE <br/>


```
sudo install minikube-linux-amd64 /usr/local/bin/minikube
```
### TO INSTALL MINIKUBE IN LINUX DIRECTORY<br/>


```
minikube version
```
### TO CHECK THE VERISON<br/>

```
minikube start --driver=docker
```
### TO START THE MINIKUBE ON VM<br/>


```
minikube start --driver=docker --force
```
### IF YOU GET SOME ERROR TRY THIS COMMAND TO SOLVE IT<br/>


```
minikube status
```
### TO CHECK THE STATUS OF MINIKUBE THAT IT IS RUNNING OR NOT<br/>

```
kubectl cluster-info
```
### TO SEE THE CLUSTER INFORMATION <br/>

```
kubectl config view
```
### CONFIGURING THE KUBECTL <br/>

```
kubectl get nodes
```
### TO SEE HOW MANY NODES ARE PRESENT IN KUBECTL<br/>

```
kubectl get pods
```
### TO SEE HOW MANY PODS ARE PRESENT IN KUBECTL
<br/>

## To deploy a sample nginx deployment, run following set of commands.<br/>

```
kubectl create deployment nginx-web --image=nginx
```
```
 kubectl expose deployment nginx-web --type NodePort --port=80
```
```
kubectl get deployment,pod,svc
```
### Managing Minikube Addons<br/>

```
minikube addons list
```
### TO SEE THE LIST OF ADDONS WHICH WE CAN ENABLE<br/>

```
 minikube addons enable dashboard
```
### ENABLING DASHBORAD <br/>

```
minikube addons enable ingress
```
### ENABLING INGRESS<br/>

```
minikube dashboard --url
```
### It will get the url and run the dashboard of MiniKube<br/>

```
kubectl proxy --address='0.0.0.0' --disable-filter=true &
```
### It will convert the address for 8001 which we can access on our browser<br/>

```
http://server_ip:8001/api/v1/namespaces/kubernetes-dashboard/services/http:kubernetes-dashboard:/proxy/#/workloads?namespace=default
```
## Run the above command on you browser and in server_ip add you ip address provided by AWS <br/>

![kube7](https://github.com/user-attachments/assets/94c2791e-d7d0-4487-96ad-28257c44ea11)


# Installing openstack on VM and creating a VM on it<br/>


### 1. CREATE AN INSTANCE IN AWS AS , WITH OS OF UBUNTU OR WHAT YOU WANT THEN CHANGE SOME SETTINGS TO WORK LIKE TAKING<br/>

###   Amozon Machine Image (AMI)<br/>

###   Instance type<br/>

###   t3.xlarge<br/>

###   AND <br/>

###   STORAGE<br/>

###   50GB<br/>

###   NETWORK SETTING YOU CAN INCLUDE<br/>

###   1. SSH<br/>

###   2. HTTP<br/>

###   3. HTTPS<br/>

###   4. ALL TRAFFIC<br/>


### 2. AFTER THESE CHANGES YOU CAN LAUNCH THE INSTNACE<br/>

### 3. AFTER  THAT COPYING THE IP ADDRESS , ADD IT IN PUTTY AND ALSO SELECT THE KEY WHICH HAS BEEN CREATED IN PERIVOUS STEPS , THEN CLICK OPEN , AND YOUR VM IS AGAIN READY<br/>


### Install the openstack snap<br/>

```
sudo snap install openstack --channel 2024.1/beta
```
### Prepare the machine<br/>


### Sunbeam can generate a script to ensure that the machine has all of the required dependencies installed and is configured correctly for use in OpenStack - you can review this script using:<br/>

```
sunbeam prepare-node-script
```
```
sunbeam prepare-node-script | bash -x && newgrp snap_daemon
```
### It will directly execute it<br/>


### Deploy the OpenStack cloud using the cluster bootstrap command and accept software defaults:<br/>

```
sunbeam cluster bootstrap --accept-defaults
```
### This process will take around 30 min or more/less dependes upon internet speed<br/>


```
sunbeam configure --accept-defaults --openrc demo-openrc
```
### This command will configure the deployed cloud . It will also take around 5 min .<br/>


```
sunbeam launch ubuntu --name test
```
## This command will launch our vm which we have created on openstack<br/>
![openstak 2](https://github.com/user-attachments/assets/e6a40e0f-0cbd-43ab-b48f-84e837588d56)

## CREATING A VPC AND LOAD BALANCER TESTING 
* First we have to go on to aws , then we have to go on to VPC (Virtual Private Cloud).
* Thn we have to create a vpc with our choice name tags and thn create.
* Next step , is to make subnet , here we are making 4 subnet were 2 subnets are private with two different zones , and other two subnets are ublic subnets which are also , with two other different zones , we have to check also that one private and one public subnets has same zones .
* ![subnetscreation](https://github.com/user-attachments/assets/8bfe36be-3f1e-4ba8-8537-3d05cc1b7821)

* After createing the subnets , we have to create IGW (Internet Gatways), after creation we have to attach that to our VPC that we have created
* ![creating igw ](https://github.com/user-attachments/assets/b823b827-522e-4e56-9c43-fb84948f51e7)
* ![attach to vpc igw](https://github.com/user-attachments/assets/ccf19fa4-c5e8-4eaa-8c82-15fae8fb9b78)

* Then we have to create the VGW(Virtual Gateway), it has also be connect to our VPC .
* ![attaching vgw wit the vpc](https://github.com/user-attachments/assets/233c2504-27c2-4070-bb53-dbcf46486686)
* ![creating vgw ](https://github.com/user-attachments/assets/60cd06bd-428b-4397-af81-73e986881323)

* After that we have to create the 2 Route table where one is for IGW and other is for VGW also we have to associte the public subnets with the IGW route table and private once with VGW route table .
* In the below images I have change some settings of rooute tables where I have connect them to my IGW & VGW , with some other port number .
* ![creating route tables](https://github.com/user-attachments/assets/cf513e63-9693-45ba-bba0-248524a7b673)
* ![associating subnets to the route tables](https://github.com/user-attachments/assets/28e4200e-9457-46a7-8343-0a960d0645ed)
* ![editing route table r1 ](https://github.com/user-attachments/assets/23ef3efa-099e-4d0d-9f98-52815bad9197)
* ![in r1 ip](https://github.com/user-attachments/assets/d2be1bef-adec-498c-9958-518d571eea32)
* ![for r2 ](https://github.com/user-attachments/assets/02110d42-4dda-409f-917b-90502fa4e7e3)















