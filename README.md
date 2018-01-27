# mspj-team-04

## Installation

```
virtualenv --no-site-packages .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Run ansible

### decrypt enctypted file

```
ansible-vault encrypt roles/samba/vars/main.yml
```

```
ansible-playbook site.yml -i production
```
