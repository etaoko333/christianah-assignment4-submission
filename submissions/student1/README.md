please find submission of my assignmet4. christianah alonge
## Key learnings, experience and your main selling points.

This section will be used to write your profile for your CV. So record your key learnings and experience on a weekly basis so we can track your progress and learning.

| Number      |           Subject              | What you have learnt this week and how might you describe this at an interview?   |
| :---        |            :----:              | :---  |
| 1  | Collaboration                           | working together with one or more people to complete a project or task or develop ideas or processes. In a workplace setting, the people who are collaborating must communicate clearly and share knowledge effectively   |
| 2  | Communication                           | As a DevOps engineer, communication means effectively communicating with various teams involved in the software development process. This includes developers, testers, project managers, and other stakeholders   |
| 3  | Automation/CICD                         | CI/CD is a method to frequently deliver apps to customers by introducing automation into the stages of app development. The main concepts attributed to CI/CD are continuous integration, continuous delivery, and continuous deployment   |
| 4  | AWS                                     | Cloud services provider and designed to allow application providers, ISVs, and vendors to quickly and securely host your applications.    |
| 5  | Kubernetes                              | is an open-source system for automating deployment, scaling, and management of containerized applications.   |
| 6  | Terraform                               | Terraform allows you to automate and manage infrastructure as code. is a tool for building, changing and versioning infrastructure safely and efficiently. Terraform can manage existing and popular cloud service providers as well as custom in-house solutions. Configuration files describe to Terraform the components needed to run a single application or your entire datacenter   |
| 7  | Linux                                   | An operating system   |
| 8  | System and Application Design           | System design is the process of designing the elements of a system such as the architecture, modules and components, the different interfaces of those components and the data that goes through that system   |
| 9  | Productivity                            | Enable the team to be faster and more agile   |
| 10 | Yourself and your abilities             | I an upcoming devops engineer, and I am confident that I can bring a lot of value to any organization. I am passionate about technology, and I am always looking for ways to improve the performance of applications. I am also a team player and I enjoy working with others to achieve a common goal.  I have ability to automating the entire DevOps pipeline, including CI/CD cycles, app performance monitoring, infrastructure and configuration I have ability to configure and deploy, and provisioning code from my local machine into my local machine and use GitHub actions to deploy create server into aws cloudYYYY   |


## Kubernetes, Docker, Containerisation and Virtualisation

1.1.	Pod are the smallest deployable units of computing that you can create and manage in Kubernetes

2.	Container   image is a ready-to-run software package containing everything needed to run an application

3.	Node Pods are simply the smallest unit of execution in Kubernetes, consisting of one or more containers, each with one or more application and its binaries. Nodes are the physical servers or VMs that comprise a Kubernetes Cluste

4.	Control plane is handling routing while the data plane is responsible for switching. The router carries out different actions for these two planes

5.	Data plane the data plane consists of worker nodes with their pods and containers communicating via kubelet agents, which share the state and conditions with the container engine and database that maintains state information



## Linux administration and shell scripting

1.	What Linux command would your use to find out what commands you have run in the past? Ans: history

2.	Chmod to change mode.

3.	Scp used to copy  
	


4. ssh: is a key name ec2-user-pass in key connected to the machine in the cloud. there.

5.




## CICD, Infrastructure as as Code (IaC), Terraform, Packer and Ansible


1.	When you run the terraform init command in the directory containing terraform files, what changes does it make to directory in which you run the command? initializes a working directory containing Terraform configuration files

2. 	What is the purpose of a Terraform provider? A provider in Terraform is a plugin that enables interaction with an API

3. 	What is the purpose of Terraform state? is to store bindings between objects in a remote system and resource instances declared in your configuration.

4. 	How would you ensure that the Terraform state is secure and can be used in a collaborative environment with the rest of your team without it being corrupted? Ans: by store in s3 bucket that serves as backup folder in the cloud

5.	You have created a resource using Terraform. A colleague of your accidentally changed the resource on the AWS console. What would happen if you run the Terraform apply command again

6. 	What is a Terraform backend and how might you configure one?  defines where Terraform stores its state data files. Configure AWS S3 bucket as Terraform backend.

7. 	Describe the various method by which Terraform might obtain credentials it needs for authenticating to an endpoint? Ans: by using the AWS_ACCESS_KEY_ID , AWS_SECRET_ACCESS_KEY 

8. 	You have provisioned some infrastructure in the AWS cloud using Terraform. How could you check by querying the state what resources you have created using Terraform? By running this command terraform list state.

9.	What is the recommended approach for editing the Terraform state? By using vim command to edit tf.state

10.	What does is mean to lock and Terraform state file and why is it important to implement a locking mechanism for the state file? Ans:  supported by your backend, Terraform will lock your state for all operations that could write state. This prevents others from acquiring the lock and potentially corrupting your state. State locking happens automatically on all operations that could write state

11. Describe in details what each of the following Terraform command does; terraform init  ans : initializes a working directory containing Terraform configuration files 
b terraform apply --auto-approve instruct Terraform to apply the plan without asking for confirmation.
c  terraform fmt    used to rewrite Terraform configuration files to a canonical format and style. 
d terraform validate to the configuration files in a directory
e terraform destroy to destroy the resources/infrastructure

12.	How would you name a file so that it is recognised by Terraform when you run terraform plan or apply? tf
13.	What is the purpose of the Terraform plan command and why is it important to carefully read the output of the plan? Create an execution or what to create.
14.	What Terraform concept would you use to ensure your code is re-useable? Terraform modules.

15. 	What Terraform concept would you use to ensure your code is re-useable? Terraform modules.

16.	What do you understand by Terraform partial backend configuration? A backend defines where Terraform stores its state data files. Terraform uses persisted state data to keep track of the resources it manages.
17.	What do you understand by the Chicken-and-Egg problem with respect to Terraform backend configuration and how is it generally solved. By setting appropriate permissions.



## System Architecture and Application Design, Cloud Computing (AWS)

1.	What is a bastion server and why is it required in some network architectures? Ans: is a computer designed to withstand attacks. It hosts a single application, such as a proxy server, which serves as a gateway between the internal network and the Internet. A bastion host can repel attacks because it only runs the application while all other services are removed or reduced. ii why is required it is the recommended solution to manage secure remote access to cloud infrastructures

2.	In terms of accessibility, what is the difference between a Public IP and a Private IP. Ans: A public IP address identifies you to the wider internet so that all the information you're searching for you can find while private IP address is used within a private network to connect securely to other devices within that same network.
3.	Describe at a high level how the ssh system works. Ans: SSH is a secure protocol used as the primary means of connecting to Linux servers remotely. It provides a text-based interface by spawning a remote shell. After connecting, all commands you type in your local terminal are sent to the remote server and executed there and SSH encrypts and authenticates all connections. SSH provides IT and information security (infosec) professionals with a secure mechanism to manage SSH clients remotely. Rather than requiring password authentication to initialize a connection between an SSH client and server, SSH authenticates the devices themselves.
4.	When you create a key pair on AWS, describe where the keys are stored. Ans: Amazon EC2 stores the public key on your instance, and you store the private key


## Site Reliability Engineering (SRE), Troubleshooting, Observability

1. logs

2. metrics 

3. traces

4.

5.


## DevOps and Agile Transformation principles and methodology

1. 1.	Collaboration
2.	Automation
3.	Continue improvement
4.	Customer centric action
5.	Create with the end in mind

## New commands logs - Enter up to ten new commands you have learnt this week

| Number      | Commands | What does it do and how might you check its effect     |
| :---        |    :----:   | :---  |
| chmod        |  Change mode       | 
ls -lf         |  Find out          | 
Check -b       |   To move inside branch| 
wq             |   quit
i              |  insert mode on vim editor| 
Cd ~           |  home directory | 
Vim -r         |   to recover file name| 
      | YYYYYYYY   |
| 9  | XXXXXXXX       | YYYYYYYY   |
| 10 | XXXXXXXX       | YYYYYYYY   |

## Glossary of the week - Enter new technical words you have learnt this week and their meanings.

| Number   | Word | Meaning     |
| :---     | :----:   |  :---  |
      | YYYYYYYY   |
| 2  | AuthorisationXX       | Raw access to the key   |
| 3  | Authentication       | Permission to perform task on the system   |
| 4  | ELB	       | Elastic load balance  |
| 5  | XXXXXXXX       | YYYYYYYY   |
| 6  | XXXXXXXX       | YYYYYYYY   |
| 7  | XXXXXXXX       | YYYYYYYY   |
| 8  | XXXXXXXX       | YYYYYYYY   |
| 9  | XXXXXXXX       | YYYYYYYY   |
| 10 | XXXXXXXX       | YYYYYYYY   |

