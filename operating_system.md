Operating System
================

Tier 1
------
 * webserver
  * make tests on wsgi/fastcgi setups
  * memory footprint is essential
  * https://github.com/jonashaag/bjoern
  * uwsgi
  * modwsgi
  * apache as a webserver?
 * separate users for services
 * python stack
 * strongswan
 * tor hidden services configuration
 * build script

Tier 2
------
 * automatic daily updates from raspbian, own repo
 * SELinux
 * the kitchensync software packed into .deb with proper dependency tree
 * post-install could set up the basics
 * a separate package should do the fine-tuning, so that installation on
   existing servers would be trivial

