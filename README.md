
Role Name
=========

*ansible_nagios_graylog2_nsca*  
Graylog2 script and nagios automatic configuration to have nsca scripts for your streams. (Send notifications to nagio

Starting this work based on: 
https://bashinglinux.wordpress.com/2013/05/26/graylog2-and-nagios-integration-2/

I have seen this also: 
https://github.com/frederikhappel/graylog2-plugin-alarmcallback-nsca
But as this 4y old and I don't support java I will not use it. 


Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
