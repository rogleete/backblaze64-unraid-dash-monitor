<h1><b>Backblaze64 Monitor:</h1></b> 
An Unraid dashboard tile for the upload monitor built
into the Backblaze64 container (<a href="https://github.com/iamfoz/backblaze-64-personal-wine-container/tree/main">iamfoz/backblaze-64-personal-wine-container</a>).

Adds a native Unraid Dashboard tile displaying upload speed, backup progress,
memory usage, active threads, and connection latency without needing to open 
a separate browser tab.

Auto-refreshing, collapsible to a one-line summary, with color-coded
progress bars. A dedicated settings page lets you choose which fields
appear and how they're arranged across the tile's two columns.

<img width="450" height="73" alt="dashcollapsed" src="https://github.com/user-attachments/assets/fc8a4f67-6929-4de6-83b9-13fa0a107099" />

<img width="374" height="148" alt="dash" src="https://github.com/user-attachments/assets/5dea4255-6951-4da2-a283-a51fe0dff743" />


This plugin does not gather any data itself; it polls the container's own
/monitor/api/status endpoint, which nginx proxies on the same port as the
container's Web UI, and shows a chosen subset of fields as a native Unraid
dashboard tile.

Requires a <a href="https://github.com/iamfoz/backblaze-64-personal-wine-container/tree/main">Backblaze64</a> container reachable from the Unraid server.
Configure the address, port, and security settings.

Settings -> Utilities -> Backblaze64 Monitor after installing.

<img width="826" height="459" alt="settings1" src="https://github.com/user-attachments/assets/cb7add5c-ae18-4d59-aa45-aba16f0c0b7a" />
<img width="826" height="601" alt="settings2" src="https://github.com/user-attachments/assets/4f991b6f-8211-44ca-8eb4-cded850c088a" />
<img width="823" height="508" alt="settings3" src="https://github.com/user-attachments/assets/77cb8930-2862-44b4-a03c-9839c6f51e84" />



Hopefully satisfied users:  ![GitHub all releases](https://img.shields.io/github/downloads/rogleete/backblaze64-unraid-dash-monitor/total)
