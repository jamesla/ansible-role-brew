## ansible-role-brew

Installs brew and a list of user specified packages

### Usage

add the following variable:
```
brew_packages:
  - packer
  - hello

cask_packages:
  - virtualbox
```
playbook.yml:
```
- { role: ansible-role-brew }
```

requirements.yml:
```
- src: https://github.com/jamesla/ansible-role-brew.git
  version: master
  name: ansible-role-brew
```
