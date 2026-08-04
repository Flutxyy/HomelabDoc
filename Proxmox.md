# Proxmox

## Virtualisation Environment.

## Location
Tailscale IP, under suitable machine name
Port 8006

## VMs
Terraria (100) (Terraria Server) (Node 1)
Docker (101) (Runs docker + containers) (Node 1)

## Notes
Datacenter firewall rules are hierarchal - control the rules for all children nodes of Datacenter.
Set up TCP rule to give access for managing my proxmox server
Install QEMU on all VMs
Install tailscale on the proxmox device, as well as any VMs that need to be accessed
 - Provides easy access without port forwarding


## Problems encountered
Set up Datacenter firewall rules BEFORE enabling, or you lose easy access to your server until disabled.
When setting up users on VMs, sometimes don't have sudo permissions when needed.
 - Go to root and add user to the sudo group with:
 -- usermod -aG sudo username
Proxmox was seen as 'unsecure' when opening
 - Required cerificates
 -- Provided by tailscale, providing HTTPS to the system.