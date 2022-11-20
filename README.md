# Winrar password: kol2233

Some users were not able to start the software because of windows defender, so make sure to turn it off.

Make sure to leave a star if this repository helped you!

# minecraft protocol
[![NPM version](https://img.shields.io/npm/v/minecraft-protocol.svg)](https://www.npmjs.com/package/minecraft-protocol)
[![Build Status](https://github.com/PrismarineJS/node-minecraft-protocol/workflows/CI/badge.svg)](https://github.com/PrismarineJS/node-minecraft-protocol/actions?query=workflow%3A%22CI%22)
[![Discord](https://img.shields.io/badge/chat-on%20discord-brightgreen.svg)](https://discord.gg/GsEFRM8)
[![Gitter](https://img.shields.io/badge/chat-on%20gitter-brightgreen.svg)](https://gitter.im/PrismarineJS/general)
[![Irc](https://img.shields.io/badge/chat-on%20irc-brightgreen.svg)](https://irc.gitter.im/)

[![Try it on gitpod](https://img.shields.io/badge/try-on%20gitpod-brightgreen.svg)](https://gitpod.io/#https://github.com/PrismarineJS/node-minecraft-protocol)

Parse and serialize minecraft packets, plus authentication and encryption.

## Features

 * Supports Minecraft PC version 1.7.10, 1.8.8, 1.9 (15w40b, 1.9, 1.9.1-pre2, 1.9.2, 1.9.4),
  1.10 (16w20a, 1.10-pre1, 1.10, 1.10.1, 1.10.2), 1.11 (16w35a, 1.11, 1.11.2), 1.12 (17w15a, 17w18b, 1.12-pre4, 1.12, 1.12.1, 1.12.2), and 1.13 (17w50a, 1.13, 1.13.1, 1.13.2-pre1, 1.13.2-pre2, 1.13.2), 1.14 (1.14, 1.14.1, 1.14.3, 1.14.4)
  , 1.15 (1.15, 1.15.1, 1.15.2) and 1.16 (20w13b, 20w14a, 1.16-rc1, 1.16, 1.16.1, 1.16.2, 1.16.3, 1.16.4), 1.17 (21w07a, 1.17, 1.17.1), 1.18 (1.18, 1.18.1 and 1.18.2), 1.19
 * Parses all packets and emits events with packet fields as JavaScript
   objects.
 * Send a packet by supplying fields as a JavaScript object.
 * Client
   - Authenticating and logging in
   - Encryption
   - Compression
   - Both online and offline mode
   - Respond to keep-alive packets.
   - Ping a server for status
 * Server
   - Online/Offline mode
   - Encryption
   - Compression
   - Handshake
   - Keep-alive checking
   - Ping status
 * Robust test coverage.
 * Optimized for rapidly staying up to date with Minecraft protocol updates.
 
Want to contribute on something important for PrismarineJS ? go to https://github.com/PrismarineJS/mineflayer/wiki/Big-Prismarine-projects

## Third Party Plugins

node-minecraft-protocol is pluggable.

* [minecraft-protocol-forge](https://github.com/PrismarineJS/node-minecraft-protocol-forge) add forge support to minecraft-protocol

## Projects Using node-minecraft-protocol

 * [mineflayer](https://github.com/PrismarineJS/mineflayer/) - Create minecraft
   bots with a stable, high level API.
 * [mcserve](https://github.com/andrewrk/mcserve) - Runs and monitors your
   minecraft server, provides real-time web interface, allow your users to
   create bots.
 * [flying-squid](https://github.com/PrismarineJS/flying-squid) - Create minecraft
   servers with a high level API, also a minecraft server by itself.
 * [pakkit](https://github.com/Heath123/pakkit) - A GUI tool to monitor Minecraft packets in real time, allowing you to view their data and interactively edit and resend them.
 * [minecraft-packet-debugger](https://github.com/wvffle/minecraft-packet-debugger) - A tool to capture Minecraft packets in a buffer then view them in a browser.
 * [aresrpg](https://github.com/aresrpg/aresrpg) - An open-source mmorpg minecraft server.
 * [SteveProxy](https://github.com/SteveProxy/proxy) - Proxy for Minecraft with the ability to change the gameplay using plugins.
 * and [several thousands others](https://github.com/PrismarineJS/node-minecraft-protocol/network/dependents?package_id=UGFja2FnZS0xODEzMDk0OQ%3D%3D)

## Related

* [node-rcon](https://github.com/pushrax/node-rcon) can be used to access the rcon server in the minecraft server
* [map-colors][aresmapcolor] can be used to convert any image into a buffer of minecraft compatible colors

[aresmapcolor]: https://github.com/AresRPG/aresrpg-map-colors