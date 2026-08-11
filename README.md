**Backblaze64 Monitor:** an Unraid dashboard tile for the upload monitor built
into the Backblaze64 container (<a href="https://github.com/iamfoz/backblaze-64-personal-wine-container/tree/main">iamfoz/backblaze-64-personal-wine-container</a>).

Adds a native Unraid Dashboard tile displaying upload speed, backup progress,
memory usage, active threads, and connection latency without needing to open 
a separate browser tab.

Auto-refreshing, collapsible to a one-line summary, with color-coded
progress bars. A dedicated settings page lets you choose which fields
appear and how they're arranged across the tile's two columns.

This plugin does not gather any data itself; it polls the container's own
/monitor/api/status endpoint, which nginx proxies on the same port as the
container's Web UI, and shows a chosen subset of fields as a native Unraid
dashboard tile.

Requires a Backblaze64 container reachable from this Unraid server.
Configure the address, port, and security settings.
Settings -> Utilities -> Backblaze64 Monitor after installing.


Downloads:  
![GitHub all releases](https://img.shields.io/github/downloads/rogleete/backblaze64-unraid-dash-monitor/total)
