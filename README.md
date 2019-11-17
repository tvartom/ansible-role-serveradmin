tvartom.git
===========



Install role
------------

Create `requirements.yml` in your ansible playbook-folder.

    ---
    # Documentation:
    # https://docs.ansible.com/ansible/latest/reference_appendices/galaxy.html#installing-multiple-roles-from-a-file
    
    - name: tvartom.serveradmin
      src: https://github.com/tvartom/ansible-role-serveradmin
      scm: git
      # version: "v1.0" # Omit for latest version.

Run:

    $ ansible-galaxy install -r requirements.yml -p roles/


Requirements
------------

CentOS 8

Dependencies
------------



Example Playbook
----------------

License
-------

CC-BY-4.0

Author Information
------------------

tvartom
