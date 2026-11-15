# Broccoli Launcher

A launcher for Minecraft: Java Edition, built with Electron. It installs Fabric and the Broccoli Client mod.

## What it does
- Downloads Minecraft 1.21.11 from Mojang's official servers and installs Fabric.
- Signs you in with your own Microsoft account using the device code flow. Your login tokens are stored encrypted, only on your own computer.
- Checks that your Minecraft account has a Broccoli license, then downloads and starts "Broccoli Client".

## Privacy
- To check your license, the launcher and the client send your Minecraft account name and account ID to the Broccoli license server. The server also asks Mojang to confirm that the login is really yours.
- Your Microsoft password and login tokens are never sent to the Broccoli license server.
- The launcher and client also read a small public settings file from GitHub, which tells them the oldest allowed version.
- Nothing else is collected.

## Getting a license
Broccoli Client is a paid product. If the launcher says your account has no license, contact the developer on Discord: https://discord.gg/XWgyJsQyw

## Disclaimer
This is NOT an official Minecraft product. It is not approved by or associated with Mojang or Microsoft.
