# Requires-container-selinux-2.9
-----------------------------------
Requires: container-selinux >= 2.9, You could try using --skip-broken to work around the problem You could try running: rpm -Va --nofiles --nodigest


This could help you :

[root@worker-node1 run]# subscription-manager repos --enable=rhel-7-server-extras-rpms
