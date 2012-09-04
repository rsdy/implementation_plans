Admin interface
===============

Tier 1
------
 * network setup
  * static
  * dhcp
  * hostname
 * show local ip address
 * show tor hidden service domain
 * show certificate fingerprint
 * show qr code with the configuration of
  * tor hidden service
  * cert fingerprint
  * username
 * qr code shown on button push
 * one admin user
 * strongswan configuration upload

Tier 2
------
 * central, multiple device management
 * user-friendly strongswan configuration
 * x509 authentication
  * client banning
 * proper ssh support
 * deploy static webpages under different hidden services
 * opt: show external ip address
 * torrent client?
 * something like cryptocat?
 * telehash?

opt: can be disabled

Technology
----------
 * if going with owncloud, then integrate stuff into it
 * flask
 * sqlalchemy
 * jinja templates for config generation
 * sqlite db backend
 * only a rest api
 * basic authentication
 * qr code generation on server side (shareable)
  * https://github.com/lincolnloop/python-qrcode
 * frontend in javascript
  * backbone.js
  * underscore.js
