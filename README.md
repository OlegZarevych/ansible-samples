# ansible-samples

How-to:

- Create VM's
    - Go to machine with ansible
    - install dependency
        - pip install ansible[azure]
        - ansible-galaxy collection install azure.azcollection
        - python3 -m pip install --user -r ~/.ansible/collections/ansible_collections/azure/azcollection/requirements-azure.txt
    - Clone this repo git clone https://github.com/OlegZarevych/ansible-samples.git
    - Login to Azure using az login
    - Run command ansible-playbook azure-vms-create.yaml
