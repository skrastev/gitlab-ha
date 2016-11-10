# Ansible AWS Gitlab HA

## The task

I will describe how to provision height available github infrastructure (Gitlab HA). 
The entry point of the Gitlab HA cluster will be a host and port 443

## The solution

HA Deployment of Gitlab

 - Provision 2 x EC2 instances with Gitlab and GlusterFS roles
 - Provision 1 x RDS instance postgresql role
 - Provision 1 x Elastic Load Balancing (ELB) load balancer
 - 


## Requirements:

 - Ansible 2.1.0
 - Python
 - boto
 - AWS

## Quickstart

 ```shell
git clone https://github.com/skrastev/gitlab-ha.git
cd gitlab-ha/
ansible-playbook -i hosts.yml site.yml
```

## References: 

1. [Ansible AWS VPC Highly-Available Wordpress]
2. [ansible-role-glusterfs]




[Ansible AWS VPC Highly-Available Wordpress]:https://rbgeek.wordpress.com/2015/08/03/highly-available-wordpress-installation-inside-aws-vpc-using-ansible/
[ansible-role-glusterfs]:https://github.com/skrastev/ansible-role-glusterfs

