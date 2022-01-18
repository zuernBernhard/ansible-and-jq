## Sample Playbook - Local Homebrew

Sample Playbook to install a package locally on macos and write its installed local version into a Variable.

### Installation 

Assuming that Ansible (and PIP to install Ansible with PIP) are installed.

```
#!/bin/bash -xe
ansible-galaxy install -r requirements.yml
ansible-playbook site.yml -i inventory -K
```

