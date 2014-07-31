a2utils-mac
============

Apache Utilities ported to Mac OS from Ubuntu. Tools available:

* **a2ensite** - used to enable a site located in the sites-available folder
* **a2dissite** - used to disable a site located in the sites-enabled folder

These tools assume the following setup under `/etc/apache2/`

* The existence of 2 folders `sites-available/` and `sites-enabled/`
* The httpd.conf file includes everything from the sites-enabled director 
