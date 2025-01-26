# Keepalived
In this project we configure Keepalived, for 2 server.
Keepalived is a software where goal is to add high availabilty.
Indeed, Keepalived can create VRRP ( Virtual Rendundacy Router Protocol ) on 2 host.
In this case, every server have same virtual IP ( VIP ): one server is the Master and the other one is Backup.
In case MASTER goes down, BACKUP will reamin alive and responde to the same VIP.
This guarantees high availability and rendundacy.

In red hat based OS, configuration file is located in: 
/etc/keepalived
