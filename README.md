yasarlaro.k8s_prereq
=========

It installs the below prerequisites on CentOS 7 / Ubuntu 18.04 / Ubuntu 20.04 control or worker nodes for K8s cluster installation
- Swap
- SELinux
- Firewall

Requirements
------------

CentOS servers are assumed to have `firewalld` installed and, Ubuntu servers are assumed to `ufw` installed.

Role Variables
--------------

The role expects below variables:
```
swapfile_path: "/swapfile"
selinux_policy: "targeted"
selinux_state: "permissive"
```


Dependencies
------------

N/A

License
-------

MIT
