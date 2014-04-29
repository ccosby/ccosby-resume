This document was created as a very quick response to a manager when asked "What things do you do that your incoming replacement will have to know?" It's meant as an example of some of the things I touch on a regular basis.


proxy-host

* squid3 - proxy server for lab networks
  (should be able to use the corporate global proxy, but it doesn't work with https)

infrastructure

* bind9 dns server
* isc dhcp server v3

coverity

* coverity - static / dynamic analysis for rmm code

vcenter

* vmware vcenter appliance

wiki

* artifactory - java jar repository for maven
* sonar - static and dynamic code analysis for java projects
* gerrit2 - git central & code review
* trac - wiki server
* subversion - source code control
* apache2 - web server
  * mod_wsgi for trac
  * ldap authentication to cec
  * yum repos for redhat rpms
  * mysql - backing store for nearly all applications
* tomcat6 - application server (artifactory,sonar,gerrit2)
* git - distributed source code control
* jenkins ci server

nis

* nis server for femto.eng
* /var/yp/ypsource/yp.generate - to sync ldap users with nis

important things to know

* maven2, maven3
* ant
* bash
* perl
* gnu make
* gcc
* groovy
* ruby
* python
* redhat
  * rpm
  * yum
  * createrepo
  * reposync
  * kickstart
* solaris
  * svr4 packaging
  * jumpstart
* nfs (v2-v4 and the differences)
* nis
* dns
* dhcp
* sonar
* gerrit
* trac
* subversion
* apache2
* tomcat6
* jenkins
* artifactory
* sonar
* mysql
* ldap
* samba
* ssh
* git
* subversion
* derby
* postgresql
* vmware
  * esxi 4/5
  * vsphere
  * vcenter
* cisco
  * Nexus 1000v
  * MDS
  * IOS
    * static routing
    * dynamic routing protocols (OSPF, EIGRP, BGP)
    * VLANs - to include access, dot1q trunks, etherchannel, spanning tree, et al
    * VRF
  * NxOS
  * UCS C Series
  * UCS Manager
