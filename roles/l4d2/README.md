# About
Left 4 Dead 2 is a 2009 multiplayer survival horror game developed and published by Valve. The sequel to Turtle Rock Studios's Left 4 Dead, it was released for Windows and Xbox 360 in November 2009, Mac OS X in October 2010, and Linux in July 2013.

![L4D2](https://static.wikia.nocookie.net/left4dead/images/6/6c/Dark_Carnival02.png)

# Role Variables
| Ansible Variable | Morpheus Variable | Description | Default |
| --- | --- | --- | --- |
|`METAVER`||MetaMod Version to Install.| `1.11` |
|`METASOURCE`||MetaMod Installer Package.| `mmsource-1.11.0-git1148-linux.tar.gz` |
|`SOURCEMODVER`||SourceMod Version to Install.| `1.11`|
|`SOURCEMODSOURCE`||SourceMod Installer Package.|`sourcemod-1.11.0-git6923-linux.tar.gz`|
|`SERVERID`||Steam Dedicated Server ID.|`222860`|
|`STEAMPORT`|customOptions.steamPort|The listening port for the Steam Dedicated Server.||
|`INSTANCEID`|instance.id|Instance ID from the provisioning Server. Used for server naming.||