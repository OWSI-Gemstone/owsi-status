# OWSI Notebook status

The public status page at https://status.owsiusa.com: is OWSI Notebook working right now, and its uptime by day.

- One static page (`index.html`), hosted by GitHub Pages, so it stays up when the notebook or Vercel is down.
- It reads UptimeRobot's public status data for page `tDR10pRG9z` (monitor `804811799`, checking `https://notebook.owsiusa.com/api/health` every 5 minutes). No keys or client data live here.
- DNS: a GoDaddy CNAME `status` → `owsi-gemstone.github.io`.
- Alerts and the monitor itself are managed in UptimeRobot (Skyler-Berry account).
