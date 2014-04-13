unicorn init script for Debian
==============================

Yep, here comes another init script for rails-based web servers.

It allows you to:
* start, stop, restart, and reload unicorn for multiple sites running on the same server;
* use a separate RVM environment for each specific site;
* use unicorn, puma, or any other application server;
* control each site without requiring root permissions (makes it easy to use init script in capistrano deploy process).

Usage:
* copy `railsweb` to `/etc/init.d/`
* create configuration files in `/etc/railsweb/` directory

Licensed under MIT license.

