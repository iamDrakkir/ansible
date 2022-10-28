run: 

ansible-playbook local.yml --ask-become-pass --ask-vault-pass

also convert this checkout to ssh when done: 

git remote set-url origin git@github.com:iamDrakkir/ansible.git
