ECGALAXY gopass role
====================

Installs gopass - https://www.gopass.pw/

Also installs it as a Summon provider.

Requirements
------------

* gpg
* tar
* wget

Role Variables
--------------

None.

Dependencies
------------

* ecgalaxy.common_packages
* optional: ecgalaxy.summon

Example Playbook
----------------

    - hosts: all
      roles:
        - ecgalaxy.gopass

License
-------

Copyright the European Union 2022.

Licensed under the EUPL-1.2 or later.

Author Information
------------------

ECGALAXY team.
