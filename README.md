## Installing docker on Almalinux9

This ansible repository is for installing docker and fixing an [issue](https://www.lorenzobettini.it/2022/10/fixing-docker-problems-in-fedora/) that slows docker container start up.

### Requirements
```
pip install ansible==2.10.7
```

```bash
ansible-playbook -K docker-almalinux.yml
```