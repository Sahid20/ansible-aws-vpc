# VPC Setup for Vprofile Project on AWS Cloud using Ansible for Cloud Automation.

## Scenario - Current Situation:

1.	AWS Cloud Management Team

2.	Deploy / Setup Infrastructure on Cloud

3.	Usage of Secure and HA (Highly Available) VPC for New Projects

4.	Regular Requests

## Problem - Issues with Current Situation:

1.	VPC Consists of Many Moving Parts

2.	Subnets, NAT Gateways, Internet Gateways, Route Tables, NACLs, Security Groups

3.	Bastion Hosts

4.	Human Error can lead to Non-Functional or Exposed VPC

5.	Managing Manually is a Time-Consuming Task

## Solution - Fix:

1.	Configuration Management of VPC

2.	Automatic Setup (No Human Errors)

3.	Centralize Change Management

4.	Version Control (IaC)

## Tools used in the Project:

1.	Ansible - Configuration Management of VPC
2.	AWS Cloud Platform - VPC Setup with Bastion Hosts
3.	IDE (IntelliJ, VSCode, etc)
4.	GitHub account, git

## Diagram
![Project-9](https://user-images.githubusercontent.com/73986565/235444535-47d627b3-d22f-4b36-a3be-361c143def00.png)

## Usage (Flow of Execution):


1.	Login to AWS 

2.	Create EC2 Instance to Run Ansible Playbooks

3.	Install Ansible

4.	Install Boto

5.	Setup EC2 Role for Ansible

6.	Create a Project Directory

7.	Create Variables File for VPC and Bastion Host

8.	Create VPC Setup Playbook

9.	Create Bastion Setup Playbook

10.	Site.yml playbook to call Playbook at once.
