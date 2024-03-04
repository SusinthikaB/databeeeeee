# Cloud computing overview - 22 jan
It is providing computing services like servers,storage,databases,networking,software,analytics,intellegence over the internet.
# AWS(Amazon web services)
They are one of the top service providers,services they provide are:
- computing services
- storage services
- network services,etc
# Their famous services are like
- EC2(Elastic Computing Cloud) - we can deploy our application in the EC2, it provides a compute instances to the application in the cloud
- S3(simple storage service) - used to store any amount of data and retrive it any any part of web. data are stored as object in the buckets
- RDS(Relational database service) - used to set up operate and scale a relational database. We can choose our own database engines like postgresql,mysql etc.
- Cloudtrail - is used to continously monitor the activity of our AWS account, it is tool for security for making aws account an secured one
- Cloud Watch - it is a monitoring and managing services that helps us to gain visibility to our AWS account and troubleshoot issues
- Lambda - serverless network runs for only 15 minutes,once time completed the particular instance will be terminated
# GIT overview -20 jan
- Git stands for Global information tracking
- GIT is a website/cloud based services that is used by developers to manage and store their works and resources.
- It is called version because it helps to keep track and control the previous works
- whenever changes need to be done clone your file/code from main to your own branch and then complete it
- Once the changes are completed and checked then push it to the main/master
# Terminologies of GIT 18 jan
# Repository
- It acts like a project folder
- Contains all project related codes and files
- It also has the history of changes made by all
- Every project has distinct repositories , we can create when we need a new project.
# Main branch
- It is one of the branch in the repository but all works will be available there
- once the changes are made those details will be pushed to the main branch from other branch
# Branch
- It is used to clone the works from main branch and to make some changes over there
- we can create our own branch and make our own changes over there,once changes are done tey can be pushed to the main branch
# Pull request
- once we do some changes in the code cloned from main we should raise pull request for that 
- once all accept and approve our changes we should push that to the main branch
# Push
- It is used to push the commits from the local to remote repository
# Commit changes
- Is adding our changes to the file or keeping track of it
- Those are the changes we make to our codes or source files
- "commit changes" refers to the process of saving your changes to a Git repository.
- Git is a version control system that allows multiple contributors to work on a project simultaneously. 
- When you make changes to your project, you need to commit those changes to the Git repository
to track the modifications and make them part of the project's history.
# local repository
- It is the place where we do our individual development changes we need to make and everthing
# Remote repository
- It is the place where all works on collaboration and a shared space of work
- once we do changes in local repository we can commit those changes and push it it remote repository
 # VPC overview - 29 jan 
 - VPC stands for virtual private cloud
 - Create a name for VPC and create subnets
 - subnets are the ip we are creating for our instances in vpc
 - two subnets will be created
        - public subnet
        - private subnet
 - security groups will be created like for both public and private
 - NACL -> network accesss control list which controls the inbound and outbound traffic for accessing subnets
 - internet gateway -> is the way to connect to the instances inside VPC
 - NAT gateway -> allows private subnets to access internet when they are private
 - Overall it is used to deploy our resources and manages it effectively and securely
# Overview of AWS services in console - jan 30
# Terraform basic
- It is an "infrastructure as a code" (IAC) tool
- It is used to deploy create and manage our AWS resources through an automation approach using certain syntax
- User can give the state of their requirements for the infrastructure through code rather than specifying through steps
- Then terraform will automatically create an infrasturcture with all the specifications.
# Infrastructure Overview - feb 5
- servers -> It is a place to store our data and retrive whenever needed
- S3 -> These are the storage service that has the storage buckets where data can be stored
- Lambda overview -> These are the serverless one in which AWS takes care of its infrasturucture
- No need to provision or manage servers,they autoamtically update and runs once the code is uploaded.
# Terraform overview - Feb 8
- Traditional approach in infrastructure
- advantage of IAC method and how
- Terraform is a tool for infrasturcture as a code(IAC)
- Developed by Harshicrop
- They provide their own syntax in which we could code with our specifications
- It is supported in all cloud providers
- just to specify which provider we use is enough to modify the code accordingly
# Environments and its types - Feb 9
- Devlopment -> where the developer develops the code
- Quality analysis -> where the testing of the developed modules are done by QA teams
- end user testing -> The product owner test the application and checks if it satisfies the needs
- production -> Once after approved by all it comes to the production environment to the user or the client
# CI/CD Overview
- Continous integration and continous development
- CI -> the developers simultaneously works on the code or source
- update or modify something on the code
- CD -> Continous development pushing the changes into production environment simultaneously
- both integration and development occurs simultaneuosly
# KT from Data Fabric team
# Python
- List
- tuple
- dictionary
- map
- lambda basics
- set
- list comprehension
- Exception handling
- OOPS concept,super class , init class , object ,attributes
# Benthos
- It is a tool used for transfering data in pipeline
- It uses a language called Golang
- it has its own syntax
- from obtaining data processing it transfering and pushing it into an right place it takes care of it
# Docker
- Docker is an open source tool used for container creation
- Containers -> It is nothing but entire application is bulit into an single pack ie), every package and libraries and functions needed by the application to run is there
- they share the same OS in the server
- they are faster and obtain less memory space than the Virtual Machines
- Using Docker we can create our containers
  

