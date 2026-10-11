# Deluge (PIA VPN) for Umbrel

Deluge BitTorrent client configured with Private Internet Access (PIA) VPN integration for Umbrel, based on the binhex/arch-delugevpn container.

## How to Install & Setup

1. Add this repository URL to your Umbrel Community App Store.
2. Install the Deluge PIA app.

⚠️ Important: The app will fail to launch initially until you update your VPN login credentials.

3. Open the files app on your Umbrel server and navigate to:
/Apps/dxd7-deluge-pia/docker-compose.yml
4. Select "Edit anyway" when prompted.
5. Replace VPN_USER=CHANGE_ME and VPN_PASS=CHANGE_ME with your actual PIA credentials.
6. Save the changes and restart the app from your Umbrel dashboard.
