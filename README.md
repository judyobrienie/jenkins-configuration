Jenkins-Configuration
===




Requirements
------------

This role must be used in conjuction with two files
plugins.txt
security.groovy
Example in repo https://github.com/judyobrienie/ansible-jenkins



Example Playbook
----------------

Running openshift-templates is easy! Here's a sample playbook:

    - hosts: localhost 
      gather_facts: no
      connection: local
      roles:
         - { role: jenkins-configuration }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).