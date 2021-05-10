# DevOps-Wordpress-test
# Instruction

Stack:
- Docker Compose
- Ansible 
- Ngnix
- Docker 
- AWS

To start enter you need Ansible, AWS.
After enterr command:
> sudo ansible-playbook --private-key=~/.ssh/ssh.pem -u=ubuntu ansible.yml

ssh.pem - AWS public Key
ubuntu - default user in AWS, but in Server we will use sudo

In Ansible file we updete and install mysql, docker, docker-compose, copy docker-compose file and up it.

To improve this build we can use Travice CI, Terraform and Kubernetes.
