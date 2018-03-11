This playbook launches Amazon EC2 instances + Apache

Requirements
------------
- python >= 2.6
- boto (It will be installed automatically)

Variables
--------------
- Hard coded the variables in order to create ec2_instance

Play
--------------
- Launch AWS instance (t2.micro) with given variables
- Install Apache
- Install GIT
- Deploy sample htm page from my GITHUB into apache home directory

Dependencies
------------
Key pait has to be copied in the same path (where the yml file is located)

Example Playbook
----------------
anisible-playbook aws_apache.yml

Troubleshoot
----------------
- If the script didn't work or throwing any erros, please go through "Dynamic Inventory" pages in Ansible
- If any SSH related errors like Permission Denied or Publick Key related issue, import the AWS Keypair into SSH-Bash profil

Syntax:
$ ssh-agent bash 
$ ssh-add ~/.ssh/keypair.pem

Author Information
------------------
https://github.com/veerssamples

