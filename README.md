# ansible-kube-wp
Ansible Script for Running Wordpress on Kubernetes Automatically

Method:

1. Installing K3S (Lightweight Kubernetes)
2. Create MySQL Database Deployment
3. Create MySQL Services
4. Create Wordpress Deployment
5. Create Wordpress Services Loadbalancer Port 80
6. Access Remote Host with Browsers and Setup WP

Usage:
ansible-playboook -i inventory ansible-kube-wp.yml

Note:
Modify your /etc/hosts and add your server+ip
Modify your 'password' on ansible-docker-wp.yml
Justify your Inventory Settings
