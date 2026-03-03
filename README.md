# 🛡️ CreeperAuth
**Advanced Hybrid Authentication System for Minecraft (1.21+)**
*The only authentication plugin that offers secure auto-login for both Premium and Cracked players via unique IP-Binding Identity Locking.*

![Minecraft Version](https://img.shields.io/badge/Minecraft-1.21+-green.svg)
![Platform](https://img.shields.io/badge/Platform-Spigot%20%7C%20Paper-orange.svg)
![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Developer](https://img.shields.io/badge/Developer-Eianzio-blueviolet.svg)

---

## 🚀 Why CreeperAuth?
Most authentication plugins only offer automatic login for Premium accounts, leaving Cracked players to type their passwords every time. **CreeperAuth** bridges this gap. 

By using **Hybrid IP-Binding Technology**, CreeperAuth allows Cracked players to enjoy the same seamless auto-login experience as Premium users, while keeping their accounts 100% secure from name-spoofing (TLauncher exploits).

## ✨ Key Features
* **Hybrid Auto-Login:** Seamless entry for both Mojang-verified and Cracked players.
* **Identity Locking:** Premium players can verify and lock their identity using the Mojang API.
* **Anti-Spoof IP Binding:** Automatically binds login sessions to player IPs. If the IP changes or doesn't match the identity, password login is enforced.
* **Hardcore Restrictions:** Full movement, chat, block-breaking, and damage protection until authenticated.
* **Dynamic BossBar:** High-visibility countdown timer to remind players to log in or register.
* **Custom AuthSpawn:** Send all unauthenticated players to a specific "Lobby" spot.
* **Database Flexibility:** Native support for high-speed **SQLite** or network-ready **MySQL**.

---

## 🛠️ Commands & Permissions

| Command | Alias | Description | Permission |
| :--- | :--- | :--- | :--- |
| `/register <pass> <confirm>` | `/reg` | For registering a new account. | *None* |
| `/login <password>` | `/l` | For logging into an existing account. | *None* |
| `/changepassword <old> <new>` | `/cp` | For changing your current password. | *None* |
| `/ca premium [on/off]` | - | For locking or unlocking premium identity. | `creeperauth.use` |
| `/ca set authspawn` | - | For setting the authentication spawn point. | `creeperauth.admin` |
| `/ca reload` | - | For reloading the plugin configuration. | `creeperauth.admin` |
| `/ca reset <player> <pass>` | - | For resetting another player's password. | `creeperauth.admin` |
| `/ca unregister <player>` | - | For deleting a player from the database. | `creeperauth.admin` |

---

## ⚙️ Quick Installation
1.  Download the latest `CreeperAuth.jar`.
2.  Place it into your server's `plugins` folder.
3.  Restart your server.
4.  Stand where you want players to wait and type `/ca set authspawn`.
5.  Enjoy a faster, more secure server!

## 📂 Configuration
The plugin generates a detailed `config.yml` where you can customize:
* **IP-Account Limits:** Control how many accounts can be made per IP.
* **Timers:** Adjust the auto-kick time limit.
* **Messaging:** Full color-code support for all titles, subtitles, and chat messages.

---

## 🤝 Support & Credits
Developed with ❤️ by **Eianzio** at **Borno Studio**.
For custom inquiries or server hosting, visit **BornoCloud**.

---
*© 2026 Borno Studio. Licensed under the MIT License.*
