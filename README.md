# avahi.services

[![Join the chat at https://gitter.im/dacbarbos/avahi](https://badges.gitter.im/dacbarbos/avahi.svg)](https://gitter.im/dacbarbos/avahi?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[![No Maintenance Intended](http://unmaintained.tech/badge.svg)](http://unmaintained.tech/)

RTFM @ [avahi.service(5)](https://linux.die.net/man/5/avahi.service)

Hints:  
$ service avahi-daemon status  
$ systemctl status avahi-daemon.service  
$ avahi-browse -a  
$ sudo ufw allow mdns  
$ firewall-cmd --zone=public --permanent --add-service=mdns  
