logstash-grok
=============

Some logstash grok patterns

Mikrotik:
---------

Some settings for logging from Mikrotik (Currently tested with 6.0rc7, 6.6):

* DHCP - "dhcp, !debug"
* DNS - "dns, !packet"
* Web-Proxy - "web-proxy, !debug" | prefix - "web-proxy"
* Firewall - "firewall"
* Login/Out/Failures - "system"
