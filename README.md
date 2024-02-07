# How to Install
Configure the `requirements.yml` file.
```
- name: k8s
  src: https://github.com/nilsonvieira/ansible-role-k8s
  version: main
```
In the Roles include:
```
  roles:
    - k8s
```
Execute the command to install role.

```bash
ansible-galaxy role install -r requirements.yml