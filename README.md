# ansible-role-without-jinja
The role with deploy RGB game without jinja, Tasks and Vars

Playbook to be used
---
  - name: checing the roles
    hosts: web
    roles:
     - ansible-role-without-jinja
