ansible_role-jenkins_docker_base
=========

This role will install the minimal dependencies for customer containers used with the [kubernetes plugin](https://github.com/jenkinsci/kubernetes-plugin) for jenkins slaves.

Requirements
------------

None.

Role Variables
--------------

See [/default/main.yml](/defaults/main.yml) for variables.

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible_role-jenkins_docker_base }

License
-------

MIT

