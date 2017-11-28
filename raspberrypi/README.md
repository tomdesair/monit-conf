# Installation
Checkout this repository on your raspberry pi as root under `/root/monit-conf` and create a symbolic link as follows:

    $ rm -r /etc/monit/conf.d
    $ ln -s /root/monit-conf/raspberrypi /etc/monit/conf.d
    $ systemctl restart monit


