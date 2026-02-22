# 🛡️ Purple RP Management Bot
### *High-Performance Discord Roleplay Orchestration*

 ####### #    #  ######  ######  #        #    #
 #    #  #    #  #    #  #    #  #         #  # 
 ######  #    #  ######  ######  #          ##  
 #       #    #  #  #    #       #          ##  
 #       ######  #   #   #       ######   #    #

![Python](https://img.shields.io/badge/Language-Python%203.10+-blue)
![Library](https://img.shields.io/badge/Library-discord.py%202.0+-green)
![License](https://img.shields.io/badge/License-Single--Server-red)

---

## ✨ Core Features

* **🛂 Automated Entry System**: Seamlessly manage the transition from "Arrival" to "Citizen" with the `/einreise` command.
* **🏢 Faction Database**: Create, track, and manage factions with built-in warning systems for organization leaders.
* **🚫 Smart Security**: Automatically detects and blocks users with a history of 3+ warnings upon joining the server.
* **🛠️ Maintenance Mode**: Lock the server for updates with a single command, featuring a countdown and custom reason display.
* **📋 Logging System**: Every staff action is logged to a designated channel to ensure transparency and accountability.

---

## 🚀 Commands Overview

### **Staff & Moderation**
| Command | Description | Permission |
| :--- | :--- | :--- |
| `/einreise` | Officially enters a user into the RP. | Staff+ |
| `/warn` | Issues a permanent warning to a user (3 = Auto-Sperre). | Staff+ |
| `/sperre` | Manually locks a user out of the server roles. | Staff+ |
| `/staffstatus` | Checks your current permission level. | Everyone |

### **Faction Management**
| Command | Description | Permission |
| :--- | :--- | :--- |
| `/frakadd` | Registers a new faction and assigns a leader. | HighTeam |
| `/frakwarn` | Issues an official warning to a specific faction. | HighTeam |
| `/frakliste` | Displays all registered factions and their warning status. | Everyone |

---

## ⚙️ Setup & Installation

> **Note:** This bot is a premium, single-server licensed product. Initial setup requires a manual configuration of Server IDs to ensure maximum security.

1. **Prepare Files**: Ensure `UserData.JSON`, `Fraktionen.json`, and `maintenance.json` are in the bot's root directory.
2. **Configure IDs**: Open `RP Bot.py` and navigate to **Section 1 (EINRICHTUNG)**.
3. **Insert Keys**: Replace placeholders (e.g., `000000000...`) with your specific Channel, Role, and Guild IDs.
4. **Intents**: Enable **Server Members Intent** in the Discord Developer Portal.
5. **Run**: Execute the script using `python "RP Bot.py"`.

---

## 🔒 Security & Licensing
This software is protected and restricted to the authorized Guild ID provided during setup. This "Guild-Lock" ensures that the bot remains secure and exclusive to your community. Unauthorized distribution or modification of the core logic is strictly prohibited.

---
*Developed by **@purplxwastaken***.  
*For support or license verification, contact the developer via DM.*

