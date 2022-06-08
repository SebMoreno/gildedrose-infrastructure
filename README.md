# Gildedrose Infrastructure

This applications is intended to be deployed to an aws account via terraform IaC, so the first step is to install the [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html) and the [Terraform CLI](https://www.terraform.io/downloads) configure your aws credentials.
```
aws configure
```

To deploy the aws infrastructure you must run this commands. Before applying the terminal will ask you for the rds username and password interactively, but if you want to pass it

```
cd terraform/deploy/
terraform init
terraform apply
```

enter to the public_ip_jenkins at the 8080 port and create an admin user.

# Docker hub Credentials
credentialsId: 'docker-hub'

# Plugins

Docker Pipeline
HTML Publisher plugin
NodeJS Plugin
Locale plugin

# Enviroment Variables

API_URL
http://3.232.104.87:9090/api

BD_IP
group2-rds.cqqmj66dxtlw.us-east-1.rds.amazonaws.com

FRONTEND_URL
http://3.232.104.87

# Global Tool Config

NodeJS
name: node
version: 16.15.0

System.setProperty("hudson.model.DirectoryBrowserSupport.CSP", "")
