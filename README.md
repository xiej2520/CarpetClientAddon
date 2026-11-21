# Carpet Client on Ornithe

Carpet Client support for [ornithe-carpet](https://github.com/CrazyHPi/ornithe-carpet) on Minecraft 1.12.2 (Ornithe gen2).

| Mod | Directory | Jar | Install on |
| --- | --- | --- | --- |
| Carpet Client Addon | `addon/` | `carpetclientaddon-<version>.jar` | with ornithe-carpet (server + singleplayer) |
| Carpet Client | `carpet-client/` | `carpetclient-<version>.jar` | clients only |

The addon is an ornithe-carpet extension. It should be installed on the server, and in singleplayer.
The client talks to the addon, or to traditional carpetmod112 servers.

Full credit to the Carpet dev team.
[Original mod](https://github.com/X-com/CarpetClient)

## Building

```
./gradlew build
```

The jars are written to `addon/build/libs/` and `carpet-client/build/libs/`.

