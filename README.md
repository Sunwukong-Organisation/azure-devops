What is Azure Devops and its related services
Azure Devops is a cloud service for collaborating on code development. It provides an integrated set of features that you access through your browser or IDE client

Services provided by Azure Devops are as follows -

Dashboard

Source Control

GIT or TFVC

Boards

Agile Board or Kanban Board to track work

Pipelines

Continuous Integration and Deployment Pipelines

Manual and exploratory testing

Team Collaboration

Hosted Services and integration with Azure Cloud

Install Ansible on Ubuntu Machine
   sudo apt-get update

   sudo apt-get install software-properties-common

   sudo apt-add-repository --yes --update ppa:ansible/ansible

   sudo apt-get install ansible

ansible-playbook -i /opt/ansible/inventory/ --private-key=/root/gcpsshkey/mykey azure-agent-play.yaml -vvvv
