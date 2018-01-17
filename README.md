# ofbassignment
Deployment - Go WebApp with Mysql Database and cadvisor monitoring    

Requirement:       
Ansible   
AWS account (if want to make deployment public)          

Approach:       
Ansible scripts will do the docker installation and docker containers will be run and exposed and linked for goapp, mysql and cadvisor    
Go app and Monitoring console can be viewed at publicIP:80 and publicIP:8080 respectively, same is printed in playbook run too.         



To Start:    
Update your mysql root password, go app repository and AWS details in "go-mysql-cAdvisor/playbooks/group_vars/all.yml"
cd playbooks           
run "ansible-playbook playbook.yml"     
