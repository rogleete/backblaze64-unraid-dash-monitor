**Backblaze64 Monitor:** an Unraid dashboard tile for the upload monitor built
into the Backblaze64 container (iamfoz/backblaze-64-personal-wine-container).

This plugin does not gather any data itself; it polls the container's own
/monitor/api/status endpoint, which nginx proxies on the same port as the
container's Web UI, and shows a chosen subset of fields as a native Unraid
dashboard tile.

Requires a Backblaze64 container reachable from this Unraid server.
Configure the address, port, and security settings.
Settings -> Utilities -> Backblaze64 Monitor after installing.


Downloads:  
![GitHub all releases](https://img.shields.io/github/downloads/rogleete/backblaze64-unraid-dash-monitor/total)
