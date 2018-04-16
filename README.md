ansible_role-jenkins_docker_base
=========

[![Build Status](https://travis-ci.org/JRemitz/ansible_role-jenkins_docker_base.svg?branch=master)](https://travis-ci.org/JRemitz/ansible_role-jenkins_docker_base)

This role will install the minimal dependencies for customer containers used with the [kubernetes plugin](https://github.com/jenkinsci/kubernetes-plugin) for jenkins slaves.

Requirements
------------

None.

Role Variables
--------------

See [/default/main.yml](/defaults/main.yml) for variables.

Jenkins user
```yml
    jenkins_user: jenkins
```

Jenkins user id
```yml
    jenkins_uid: 10000
```

Home directory of jenkins user
```yml
    jenkins_home: /home/jenkins
```

Shell of jenkins user
```yml
    jenkins_user_shell: /usr/bin/bash
```

Default group of jenkins user
```yml
    jenkins_group: jenkins
```

Jenkins group id
```yml
    jenkins_gid: 10000
```


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

