# Ansible with Vagrant

## Vagrant ssh info

Fetch info:
```bash
~/path/to/project$ vagrant ssh-config
```

Test ssh connection:
```bash
~/path/to/project$ ssh -i /path/to/project/.vagrant/machines/default/virtualbox/private_key
vagrant@192.168.33.10
```
## Ansible

Have [ansible](https://docs.ansible.com/ansible/2.4/intro_installation.html#latest-releases-via-apt-ubuntu) installed.

Run!
```bash
~/path/to/project$ ansible-playbook -v ansible-playbook.yml -i hosts
```

## Meta

Alex Rocha - [about.me](http://about.me/alex.rochas)
