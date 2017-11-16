# Provisioning and configuring your Laravel App using Ansible

<h3>Install pip and Ansible</h3>

Verify if you have pip installed:

`$ sudo easy_install pip`

Install Ansible using pip:

`$ sudo pip install ansible`

<h3>Configure your AWS credentials</h3>

Install AWS Cli using pip:

`$ sudo pip install awscli --upgrade`

Install boto library:

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

<h3>Configure and run AWS iinit playbook</h3>

<h3>Provision and configure your environment</h3>
