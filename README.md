# ansible-laravel
Provisioning and Configuring your Laravel App using Ansible

1) Install pip and Ansible
Verify if you have pip installed:
$ sudo easy_install pip

Install Ansible using pip:
$ sudo pip install ansible

2) Configure your AWS credentials 

Install AWS Cli using pip:
$ sudo pip install awscli --upgrade

Install boto library 
$ sudo pip install boto --upgrade

Configure your AWS profile:
$ aws configure
AWS Access Key ID [None]: AKIAIOSFODNN7EXAMPLE
AWS Secret Access Key [None]: wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY
Default region name [None]: us-east-1
Default output format [None]: json

Warning: Create a credential with EC2 and VPC FullAccess.

3) Configure and run AWS iinit playbook. 

4) Provision and configure your environment:

# local
# staging
# production