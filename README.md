# Ansible Playbooks

## Create User role

In the create user role, there are two variables which needs to be set, in `roles/create-user/vars/main.yml`: "user_to_create" and "password". The password must be a password hash. The best way to create a hash is by using this command:

```
mkpasswd --method=sha-512 password_to_use
```