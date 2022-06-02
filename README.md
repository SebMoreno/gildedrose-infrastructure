# Gildedrose Infrastructure

This applications is intended to be deployed to an aws account via terraform.
```
aws configure
```

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
