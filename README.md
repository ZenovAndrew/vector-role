Vector 
=========

Install Vector

Requirements
------------

Tested on Centos 8 

Role Variables
--------------
vector_version: "0.22.1"
vector_home: "/tmp/vector"
vector_url: "https://packages.timber.io/vector/{{ vector_version }}/vector-{{ vector_version }}-1.x86_64.rpm"
vector_user: "vector"
vector_group: "vector"
vector_environment_file: "/etc/default/vector"

Dependencies
------------
none

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - vector

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
