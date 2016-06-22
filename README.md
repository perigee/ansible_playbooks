# ansible playbooks


The ansible playbooks for installation development machines, the `remote_user` in playbook defines the user account on remote machine.



## Ubuntu server version installation

1. Disable the UEFI in machine for installation
2. set the `TimeoutSartSec=5sec` in file `/etc/systemd/system/network-online.targets.wants/networking.service` for shortening the booting network searching time (when disconnected to network [ref](http://ubuntuforums.org/showthread.php?t=2323253)).
