# Terraform

## Types of IAC - 
1. Configuration Management (Ansible, Puppet)
2. Server Templating (Docker, Vegrant)
3. Provisioning tool (Terroform, CloudFormation)

## Why We do not use Ansible at place of terrform- 

becasue Ansible is a configuration management tools that is used to install and configre resource on already build infrastructure. & In terraform it provision the infrasture & has a state file
that keeps the track of insfrastructure and do not repeat the tasks. 

## HCL Basics - 

HCL files consist of blocks and argument

Blocks contains the argument. 

```
local.tf (filename)


resource "local_file" "pet" { 
filename = "/root/pets.txt"
content = "we love pets!"
}

```
Where all outside curly braces are the block and inside are the arguments. 

Block consist of three things.  Block name (resource) resource type (local_file) & resource Name(pet)

![image](https://github.com/user-attachments/assets/49c8bd10-212b-4827-aeef-d6974ca016d4)

Below is the example of tf file to create ec2 instance of AWS 

![image](https://github.com/user-attachments/assets/a66a5892-e685-4833-8572-30f20f210e05)



