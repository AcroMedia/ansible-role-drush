Drush (for Drupal 6/7)
======================

![.github/workflows/molecule.yml](https://github.com/AcroMedia/ansible-role-drush/workflows/.github/workflows/molecule.yml/badge.svg)

Install a more modern version of Drush than is normally available in stock yum/apt repositories.

If you're using Drupal 8 or newer, you don't want this. You want Drush installed from composer instead.

Requirements
------------

- Ansible 2.0
- Drupal 7 or older

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
