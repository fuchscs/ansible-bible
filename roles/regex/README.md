# ansible-bible
Ansible példák A nagy Ansible Biblia - Publikációhoz  
Publikáció: https://https://fuchs.technology/public.php?contents=documentation/public/ANSIBLE.md 
## Roles-ok leírása
system_check_sample_roles - https://fuchs.technology/public.php?contents=documentation/public/ANSIBLE.md#regex_findall
Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
---
- hosts: localhost
  become: true
  gather_facts: yes

  roles:
  - role: regex
```
Run playbook
```
ansible-playbook regex.yml -i hosts.ini
```
