The system admins team of xFusionCorp Industries has noticed intermittent issues with DNS resolution in several apps . App Server 1 in Stratos Datacenter is having some DNS resolution issues, so we want to add some additional DNS nameservers on this server.


As a temporary fix we have decided to go with Google public DNS. Please make appropriate changes on this server.

ssh tony@stapp01 
cat /etc/resolv.conf
ping google.com 
vi /etc/resolv.conf
cat /etc/resolv.conf
