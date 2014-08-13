cadaver
=======

Cadaver unofficial repo - based on cadaver-0.23.3

cadaver is a WebDAV command line client.

Original can be found here: http://www.webdav.org/cadaver/

#### Changes

* make it compile with openssl v3 - Ubuntu does not support the openssl v2 calls. (./configure -with-ssl=openssl)
* Add an option to always trust untrusted certificates (so you can use it in scripts easier)

