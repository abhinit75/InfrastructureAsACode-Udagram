# InfrastructureAsACode-Udagram

This CloudFormation Script Deploys a High Availability Application.

Problem:

Your company is creating an Instagram clone called Udagram. Developers pushed the latest version of their code in a zip file located in a public S3 Bucket.

You have been tasked with deploying the application, along with the necessary supporting software into its matching infrastructure.

This needs to be done in an automated fashion so that the infrastructure can be discarded as soon as the testing team finishes their tests and gathers their results.

Solution:

Summary: An apache Web Server was deployed, code was picked up from S3 storage and deployed in the web folder on the web server.

First, an infrastructure diagram was developed  using Lucid Chart which serves as visual aid to understand the CloudFormation script. Second, instruction and infrastructure diagram were interpreted and a matching CloudFormation Script was created.

Files Attached to project submission

//Udagram.yaml --> specifications for networking elements: VPC, Public/Private Subnets
//UdagramParams.json --> Specifies all parameters
//Servers.yaml --> Specifications for all sever requirements // vCpus, OS, Routing, Load balancer and Roles
//ServerParams.json --> Specifices server parameters
