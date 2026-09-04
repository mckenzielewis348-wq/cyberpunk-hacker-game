# ⚡ Cyber City Manager - Hacker Engine

An isometric cyberpunk city management game built with **Phaser 3** and **JavaScript**. Command data centers, breach high-security telecom nodes using logic gates, manage threat levels, and take over PC and Mobile networks.

![Cyber City Manager Gameplay](https://img.shields.io/badge/Status-Playable-00f0ff?style=for-the-badge)

---

## 🚀 Live Demo & Deployment

Play the game directly in your browser:
👉 **[Launch Cyber City Manager](https://mckenzielewis348-wq.github.io/cyberpunk-hacker-game/)**

---

## 🎮 Game Overview

In **Cyber City Manager**, you act as a rogue system operator seeking complete control of city infrastructure:

* **Isometric Grid City Management:** Upgrade Data Centers, Telecom Arrays, Security Hubs, and Mainframe Vaults to generate income.
* **Logic Gate Hacking Minigame:** Solve Boolean logic circuit puzzles (OR, AND gates) to unlock high-tier security nodes.
* **ICE Antivirus Threat System:** Manage your digital footprint. Every hack spikes your threat level; hitting 100% triggers a **Lockdown** that halts all income until you purge your traces.
* **Local Storage Save System:** Your progress, building upgrades, money, and network control persist automatically in your browser.
* **Win/Loss Objectives:** Conquer 100% of both PC and Mobile networks to win, or run out of money during a network lockdown to face termination.

---

## 🛠️ Key Features

| Feature | Description |
| :--- | :--- |
| **Logic Gate Minigame** | Toggle input nodes ($L_1, L_2, L_3, R_1, R_2, R_3$) to send binary signals through circuit gates and breach locked nodes. |
| **ICE Threat Meter** | Real-time security tracker that increases passively over time and spikes by +20% with every security breach. |
| **Clear Traces Routine** | Clear accumulated threat level back to 0% for $100S to end system lockdowns. |
| **Audio Synthesizer** | Web Audio API synthesizer for retro click, breach, and alarm sounds without external audio assets. |
| **Game State Persistence** | Built-in `localStorage` handling save states and manual system resets. |

---

## 🕹️ How to Play

1. **Earn Credits:** Active Data Centers passively generate credits every tick (2 seconds).
2. **Unlock Nodes:** Click locked nodes to trigger the **Logic Gate Hacking Interface**.
3. **Solve Circuit Logic:** Toggle input nodes until the final system output reads `HACK: 1 (SUCCESS)` and click **EXECUTE BREACH**.
4. **Manage ICE Threat:** Keep an eye on your **THREAT** percentage in the top HUD. Use **CLEAR TRACES ($100S)** before reaching 100% to avoid income lockdowns.
5. **Achieve Dominance:** Upgrade all network infrastructure to reach **100% PC Control** and **100% Mobile Control**.

---

## 💻 Local Setup Instructions

No build process or installation is required!

1. Clone this repository:
   ```bash
   git clone [https://github.com/mckenzielewis348-wq/cyberpunk-hacker-game.git](https://github.com/mckenzielewis348-wq/cyberpunk-hacker-game.git)
