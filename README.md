# Create an AMI using packer and ansible.

This will be run from codebuild, but can be easily ported to jenkins.

To create a new app, files are needed in;
```bash
bake-packer/${APPLICATION}/${APPLICATION}.yml
ansible/inventories/group_vars/${APPLICATION}.yml
playbooks/${APPLICATION}/${APPLICATION}.yml
```

## Required Environment Variables 
ENV
APPLICATION
