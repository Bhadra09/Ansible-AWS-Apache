This playbook launches Amazon EC2 instances + Apache

Requirements
------------

- python >= 2.6
- boto

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

None

Example Playbook
----------------

anisible-playbook aws_apache.yml

Author Information
------------------

https://github.com/veerssamples

