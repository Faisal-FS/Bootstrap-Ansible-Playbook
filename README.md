# Bootstrap-Ansible-Playbook
Setup each host in the hosts file to be used from ansible with password less access

### This playbook will do following tasks
1. Change the root user’s password
2. Create the user remote
3. Set the remote user’s password
4. Upload your workstation’s SSH public key to the remote user
5. Add the remote user to the sudoers file
6. Disallow root SSH access
7. Disallow SSH password authentication
8. Disallow SSH GSS API authentication

### How to use the playbook
+ Edit hosts file
+ Open Terminal and change directory to this playbook directory
+ Run following command
`ansible-playbook bootstrap.yml`

### Pre-requisites

+ Latest Ansible installed 
