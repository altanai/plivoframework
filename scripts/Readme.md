Run the ./plivo_install.sh script till you get 

**************************************************************
Congratulations, Plivo Framework is now installed in /var/opt/plivo
**************************************************************

* Configure plivo :
    The default config is /var/opt/plivo/etc/plivo/default.conf
    Here you can add/remove/modify config files to run mutiple plivo instances

* To Start Plivo :
    /etc/init.d/plivo start

* Configure plivo cache:
    The config is /var/opt/plivo/etc/plivo/cache/cache.conf
    IMPORTANT: you need to install a redis server for plivo cache server!
               Check with your sysadmin !

* To Start Plivo cache server:
    /etc/init.d/plivocache start

**************************************************************
