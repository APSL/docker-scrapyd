========================
Docker scrapyd image
========================

Docker image for scrapyd project.
Multi-process container, managed by circusd. 
scrapyd managed with env vars.

Other configuration managed with envtpl (circusd).

Description
===========

Docker image for scrapyd daemon

* See parent image https://registry.hub.docker.com/u/apsl/circusbase
* circus to control processes. http://circus.readthedocs.org/
* envtpl to setup config files on start time, based on environ vars. https://github.com/andreasjansson/envtpl

Ports
=====

* 6800: scrapyd daemon port

Env vars:
=========

