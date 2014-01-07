Introduction
============

This buildout provides the necessary proxy setup for a basic webserver,
inlcuding:

* Nginx
* Varnish
* runscript
* logrotation
* supervisord


TODO:
-----

* add appropriate backend/context switches to varnish, if we do virtual hosting
in front of the caching proxy

* make the Nginx configuration actually include additional vhosts dynamically

* provide a solution for fallback/error pages
