Thoth: Metrics Exporter
==================================

This role will deploy the Thoth Metrics Exporter to a given OpenShift Project.

Role Variables
--------------

This role requires a namespace in which the metrics exporter should be created.


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters):

    - hosts: localhost
      connection: local
      gather_facts: False

      roles:
        - role: thoth-station.metrics_exporter
          namespace: thoth-test-core

License
-------

GPLv3

Author Information
------------------

The Thoth Station Team.