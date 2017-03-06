Drush
=====

Install a more modern version of Drush than is normally available in stock yum/apt repositories.

Requirements
------------

Ansible 2.0

Role Variables
--------------

None

Dependencies
------------

None


Installation
------------
Add the following to your `requirements.yml` file:
```
- name: acromedia.drush
  src: https://github.com/AcroMedia/ansible-role-drush
```
Then run: 
`ansible-galaxy install -r requirements.yml`


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: acromedia.drush }

License
-------

BSD

Author Information
------------------

Dale Anderson, Acro Media Inc.
https://www.acromediainc.com/
