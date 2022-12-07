# About
This repo contains Ansible roles to deploy [Steam](https://steampowered.com) (`steamcmd`) and specific Steam Dedicated Servers on Ubuntu.  Additionally, each server installs SourceMod and MetaMod to assist with administration.

The playbooks are written to consume [Morpheus](https://morpheusdata.com) CMP for orchestration, but should only require minor tweaks to run independently.  Morpheus has a free community license for those looking to run these as is.

The following Steam Dedicated Servers are supported:

* Core Keeper
* Left 4 Dead 2 (L4D2)
* Valheim

Additional Steam Dedicated Servers can easily be added with minor variable changes.

# Planned
* Dynamic NFS mounts for backup/restore of game files.
* Dynamic add/remove from backup scheduling.
* Morpheus integration for backup scheduling.
* Dynamic query for latest SourceMod packages.
* Dynamic query for latest MetaMod packages.