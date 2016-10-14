CoreOS Kubernetes Masters
=========================

current version: 0.3.0
A role to manage Kubernetes masters in a CoreOS cluster

Role Variables
--------------

Example Playbook
----------------

    - name: kubernetes masters
      hosts: kubernetes-masters
      roles:
        - role: "sigma.coreos-kubernetes-master"
          etcd_group: "kubernetes"

License
-------

MIT
