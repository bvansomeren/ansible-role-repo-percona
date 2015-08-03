Role Name
=========

Just installs the Percona Repo for CentOS / RHEL. Strongly inspired by a similar role (geerlingguy.repo-remi

Requirements
------------

none

Role Variables
--------------

From the defaults:

percona_repo_url: http://www.percona.com/downloads/percona-release/redhat/0.1-3/percona-release-0.1-3.noarch.rpm

percona_repo_gpg_key_url: https://www.percona.com/downloads/RPM-GPG-KEY-percona

Dependencies
------------

none

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: bvansomeren.repo-percona }

License
-------

MIT / BSD

Author Information
------------------

