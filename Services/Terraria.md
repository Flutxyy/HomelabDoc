# Terraria Server

## Purpose

Run a small terraria server for friends to be opened 24/7

## Location

VM:
Terraria (100)
Name: vm1

## Notes
Running Debian Trixie
Installed tailscale on VM
Shared tailscale device with friends to connect to it
Located on port 7777
Accessed with the tailscale IP
Start server file located in /terraria/tModLoader/.start..server.sh

## Problems encountered

Modded terraria must have all server-side mods installed
Installed mods must have the same mods as the mods listed in the enabled file.
Moving files from main computer to VM was a hastle, learnt about SCP command, scp LOCATION username@vm-name:/where I want it to go
Enabled.json had to be exactly correct and correspondant with the mods installed.
