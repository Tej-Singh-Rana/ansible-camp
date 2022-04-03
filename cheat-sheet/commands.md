## Overview of the ansible commands

1.) Ansible Version
```
[root@ansible-tester ~]# ansible --version
ansible 2.9.27
```

2.) All available commands
```
[root@ansible-tester ~]# ansible
ansible             ansible-connection  ansible-doc         ansible-inventory   ansible-pull
ansible-config      ansible-console     ansible-galaxy      ansible-playbook    ansible-vault
```

3.) Running a playbook with a dry run (`--check` && `-C` flags) so it will not create any objects. 
```
[root@ansible-tester ansible]# ansible-playbook -i inventory playbook.yml --check
```

