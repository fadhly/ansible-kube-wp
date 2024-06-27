# ansible-kube-wp
Ansible Script for Running Wordpress on Kubernetes Automatically

Method:

    Installing Password Generator on Ansible Host
    Create Random Password on Ansible Host
    Installing Docker on Remote Host (Server)
    Pull Docker Image on Remote Host (Server)
    Create Wordpress and Mysql Container
    Running the container and publish ports
    Access Remote Host with Browsers and Setup WP

Usage:
ansible-playboook -i inventory ansible-docker-wp.yml

Note:
Modify your /etc/hosts and add your server+ip
Modify your 'ansible_user' on ansible-docker-wp.yml
