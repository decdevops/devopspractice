1) I have launched two EC2 instances as requested.(MSR-test-Instance-1,MSR-test-Instance-2)
2) In MSR-test-Instance-1 instance ,I have created playbook  for installing GIT,DOCKER,DOCKER COMPOSE,NODE,NVM.
3) by using ansible-playbook command i ran the playbooks for installing the tools.
 ex: ansible-playbook git.yml
3) Created a Docker Container in MSR-test-Instance-1 using Docker Compose file.
    By using docker-compose file i have launched docker container.
	ex:   docker-compose.yml -- this is the file which contains the instructions to run conatiner
command:	docker-compose build && dokcer-compose up

4) By Ansible playbook I have insatlled apache  webserver. i have created github repository and created one smaple html files also.
5) CouchDB also installed and connected funton also as reuested.
  

