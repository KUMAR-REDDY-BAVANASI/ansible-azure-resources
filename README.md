# Azure_Ansible_Poc_Neatly


Azure CLI:
=========
curl -sL https://aka.ms/InstallAzureCLIDeb | sudo bash


Ansible(Python) Installation Steps:
===================================

sudo apt update -y && apt upgrade -y

sudo apt install python3-pip

pip3 install ansible==2.10.7

pip3 install --upgrade pip

sudo apt install ansible

ansible-galaxy collection install azure.azcollection

wget https://raw.githubusercontent.com/ansible-collections/azure/dev/requirements-azure.txt

sudo pip3 install -r requirements-azure.txt


mkdir ~/.azure

vi ~/.azure/credentials


[default]

subscription_id = XXXXXXXXXXXXXXXXXXXXXXXXXXXXXX

client_id = XXXXXXXXXXXXXXXXXXXXXXXXXXXXXX

secret = XXXXXXXXXXXXXXXXXXXXXXXXXXXXXX

tenant = XXXXXXXXXXXXXXXXXXXXXXXXXXXXXX


(OR)


Ansible Env
============

export AZURE_TENANT=XXXXXXXXXXXXXXXXXXXXXXXXXXXXXX

export AZURE_CLIENT_ID=XXXXXXXXXXXXXXXXXXXXXXXXXXXXXX

export AZURE_SECRET=XXXXXXXXXXXXXXXXXXXXXXXXXXXXXX

export AZURE_SUBSCRIPTION_ID=XXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
