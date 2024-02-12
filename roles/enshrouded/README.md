# About
Palworld[a] is an action-adventure, survival, and monster-taming game created and published by Japanese developer Pocket Pair. The game is set in an open world populated with animal-like creatures called "Pals", which players can battle and capture to use for base building, traversal, and combat. Palworld can be played either solo or online with up to 32 players on one server. It was announced in 2021 and launched through early access for Windows, Xbox One, and Xbox Series X/S in January 2024.

![Palworld](https://cdn.wccftech.com/wp-content/uploads/2023/06/palworld_ConceptArt_01-728x410.jpg)

# Role Variables
| Ansible Variable | Morpheus Variable | Description | Default |
| --- | --- | --- | --- |
|`METAVER`||MetaMod Version to Install.| `1.11` |
|`METASOURCE`||MetaMod Installer Package.| `mmsource-1.11.0-git1148-linux.tar.gz` |
|`SOURCEMODVER`||SourceMod Version to Install.| `1.11`|
|`SOURCEMODSOURCE`||SourceMod Installer Package.|`sourcemod-1.11.0-git6923-linux.tar.gz`|
|`SERVERID`||Steam Dedicated Server ID.|`2394010`|
|`STEAMPORT`|customOptions.steamPort|The listening port for the Steam Dedicated Server.||
|`INSTANCEID`|instance.id|Instance ID from the provisioning Server. Used for server naming.||