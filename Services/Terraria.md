# Terraria Server

## Purpose

Run a small terraria server for friends to be opened 24/7

## Location

VM:
Refer to [Docker](Docker.md)

## Notes
This has been moved to Docker VM
Under docker container called 'terraria'
Edit with docker-compose.yml file
docker compose up -d - Rebuilds the container updating it according to the compose file
docker logs -f terria - Provides live logs of the server
Refer to https://github.com/PassiveLemon/terraria-docker for anything to do with this container

Tailscale still used to connect but friends are connected to my tailscale network
This required ACL rules to be setup, restricting them from accessing things they shouldn't.


## Problems encountered

After switching to docker container, presented with selecting an option but struggling to select any.
    Solved, forgot to add the .wld at the end of the world name in the docker compose file


Modded terraria must have all server-side mods installed
Installed mods must have the same mods as the mods listed in the enabled file.
Moving files from main computer to VM was a hastle, learnt about SCP command, scp LOCATION username@vm-name:/where I want it to go
Enabled.json had to be exactly correct and correspondant with the mods installed.
