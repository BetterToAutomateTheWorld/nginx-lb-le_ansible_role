
# nginx-basic

This is simple ansible role used to create nginx static sites.
LetsEncrypt acme.sh binary can be used to require LE certificates.

Originally written by VerosK and modified by Darcidride.

## Changelog for the Darcidride tweaks

- Don't use "sudo" rights on all tasks but only on specific tasks
- Fix some rights issue because don't use anymore "sudo" on all tasks
- Fix some issues about acme certificates generation on Ubuntu 14.04
- Fix some issues about Nginx reload/restart on Ubuntu 14.04
- Fix compatibility issues between ansible 2.1.0 and 2.4.0 execution
- Some rights tweaks
- Typo fix on task comments

This script was originally made to be executed with Ansible 2.1.0, now it can be executed with Ansible 2.4.0
