# Docker

## This will list all my services ran on docker, any problems and solutions I have encountered.

## Location

VM:
Docker (101)
Name: host

## Services ports

Portainer: 9443
UptimeKuma: 3001
Terraria: 7777


## Problems encountered
UptimeKuma installation ran into problems when normally running docker containers for the first time
    Created a docker-compose.yml file within a new directory for uptime-kuma to set the configuration.

Found out watchtower was unmaintained but there was another actively maintained fork of it.
    Switched to this and set up a discord webhook to notify me.

UptimeKuma can't connect to discord to notify
    Solved by restarting it
        Change the config to autorestart every day NOT DONE