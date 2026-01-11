# 👤 About me 
- 🇨🇿 Nationality: Czech Republic

## 🔬 Technologies:
  - C#, C++, C
  - Unity
  - Blender, Onshape (CAD)
  - 3D Printing
  - Linux
  - Networking
  - Docker

## 🗄️My Linux server
### 🐋 Fully dockerized
**All services** except the VPN are _running in Docker_
- [Docker](https://www.docker.com/)
- [Arcane](https://getarcane.app/)
    
### 💾 Automatic incremental backups
Hourly backups to local storage and Google Drive   
- [Rstic](https://github.com/restic/restic) & crontab
- [Rclone](https://rclone.org/)
- [Backrest](https://garethgeorge.github.io/backrest/)

### 🔒 Server accessible only trough VPN
Server has 3 services accesible from the web without _**public IP**_ using the Tailscale **Funnel** feature.
Rest of the server can be accesed only trough the VPN (or LAN)
- [Tailscale](https://tailscale.com/)
    
### Hosted Services: 
#### Public:
- 🔐 Password manager: [Vaultwarden](https://github.com/dani-garcia/vaultwarden)
- 💵 Finance manager: [Firefly III](https://www.firefly-iii.org/)
#### Internal (VPN only):
- 📊 Dashboard: _TBD_
- 🐋 Docker manager: [Arcane](https://getarcane.app/)
- 💾 Backup manager: [Backrest](https://garethgeorge.github.io/backrest/)
- 🕹️ Game server: [Pterodactyl](https://pterodactyl.io/)
- 📁 File browser: _TBD_
- 📘 Obsidian Sync: [CouchDB](https://couchdb.apache.org/)


## Contact
- 💬 [LinkedIn](https://www.linkedin.com/in/filip-gajdusek/)
- ✉️ [Email](mailto:filipgajdusek1@gmail.com)
