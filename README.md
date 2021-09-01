# CMPE 272 Assignment 1 Ansible

### How to use with Ansible
1. ansible-playbook -k -K apacheInstall.yml
2. ansible-playbook -k -K apacheUndeploy.yml
3. ansible-playbook -k -K apacheChangeIndex.yml
4. ansible-playbook -k -K apacheAddPorts.yml
5. anisble-playbook -k -K apacheDeploy.yml

### How to use Apache Global playbook
1. ansible-playbook -k -K apacheGlobal.yml --tags "install"
2. ansible-playbook -k -K apacheGlobal.yml --tags "startApache"
3. ansible-playbook -k -K apacheGlobal.yml --tags "stopApache"
4. ansible-playbook -k -K apacheGlobal.yml --tags "deleteIndex"
5. ansible-playbook -k -K apacheGlobal.yml --tags "replaceIndex"
6. ansible-playbook -k -K apacheGlobal.yml --tags "addPort"
