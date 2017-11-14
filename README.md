Provisioning and configuring your Laravel App using Ansible

#Install pip and Ansible

Verify if you have pip installed:
`$ sudo easy_install pip`

Install Ansible using pip:
`$ sudo pip install ansible`

#Configure your AWS credentials 

Install AWS Cli using pip:
`$ sudo pip install awscli --upgrade`

Install boto library 
`$ sudo pip install boto --upgrade`

Configure your AWS profile:
```
$ aws configure
AWS Access Key ID [None]: AKIAIOSFODNN7EXAMPLE
AWS Secret Access Key [None]: wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY
Default region name [None]: us-east-1
Default output format [None]: json
```

Warning: Create a credential with EC2 and VPC FullAccess.

#Configure and run AWS iinit playbook. 

#Provision and configure your environment:
