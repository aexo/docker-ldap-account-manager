## Ldap Account Admin (lam)

A basic configuration of the Ldap Account Admin.

This image will initialize a basic configuration of LAM.

For example, to start a container running LAM, use the command:

    docker run  -v /data/lam:/var/lib/ldap-account-manager/config \	
	       -d aexoti/lam

Persistent data configuration for LAM is stored in /var/lib/ldap-account-manager/config


