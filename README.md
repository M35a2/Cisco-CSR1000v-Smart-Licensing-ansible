# Cisco-CSR1000v-Smart-Licensing-ansible

Ansible 2.9 playbook 

built for on-prem smart license servers. 

Tested on CSR1000v running 16.12.4a

required changes:

Hosts file edit: 

 - hosts ip/name 

 - username

 - password

DLC playbook is for Device led conversions
https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/smart-licensing/qsg/b_Smart_Licensing_QuickStart/b_Smart_Licensing_QuickStart_chapter_011.html

edit vars:

 - dns name
 
 - interface
 
 - token

 - dns server

 - domain name

on-prem smart license playbook is for standard smart license led.

edit vars:

 - dns name
 
 - interface
 
 - token

 - dns server

 - domain name
