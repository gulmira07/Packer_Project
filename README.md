# Packer_Project

Jenkins with packer

To run Jenkins:
 packer build -var-file vars/jenkins_vars.json  tools/jenkins.json

To run r1soft:
cd to tools then packer build r1soft.json

To run Wordpress:
packer build -var-file vars/wordpress_vars.json tools/wordpress.json 
