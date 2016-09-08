Apigee OPDK Setup Validate Cleanup
=========

This role performs the installation cleanup of the Apigee OPDK validation.

Requirements
------------

The installation of Apigee OPDK requires root access. Credentials must also be supplied to override the empty placeholders
provided here. It is recommended that credentials be consolidated into a single credentials.yml file that can be stored 
separately. It is assumed that files containing credentials are stored in the ~/.apigee folder. 

Role Variables
--------------

Default values for variables are provided by the role opdk-setup-default-settings.

Dependencies
------------

This role depends on the following roles:

* opdk-setup-default-settings

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: opdk-setup-validate-cleanup }

License
-------

Apache License Version 2.0, January 2004

Author Information
------------------

Carlos Frias
