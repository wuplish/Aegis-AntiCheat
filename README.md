<br />
<div align="center">
  <img src="https://wuplish.com.tr/x.png" alt="Aegis Logo" width="120" height="120">

  <h1 style="font-size: 3rem; font-weight: bold; margin-top: 10px;">AEGIS ANTI-CHEAT</h1>

  <p>
    <strong>The Next-Gen Open-Source Protection for Minecraft 1.21+</strong>
  </p>

  <p>
    <a href="#"><img src="https://img.shields.io/badge/Platform-PaperMC-blue?style=for-the-badge&logo=paper" alt="PaperMC"></a>
    <a href="#"><img src="https://img.shields.io/badge/Java-21-orange?style=for-the-badge&logo=java" alt="Java 21"></a>
    <a href="#"><img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License"></a>
    <a href="#"><img src="https://img.shields.io/badge/Status-BETA-red?style=for-the-badge" alt="Status"></a>
    <a href="#"><img src="https://img.shields.io/badge/Release-FEB%201st-critical?style=for-the-badge" alt="Launch Date"></a>
  </p>

  <h3>🚀 REVOLUTIONIZING SERVER SECURITY 🚀</h3>
  <p>Free. Open Source. Uncompromising Performance.</p>
</div>

<br />

## ⚡ What is Aegis?

**Aegis** is not just another check-based plugin. It is a comprehensive **security ecosystem** designed for modern Minecraft (1.21+). While other anti-cheats struggle with new mechanics like Wind Charges, Tridents, and Maces, Aegis embraces them.

We combine **Packet-Level Analysis**, **Server-Side Physics Simulation**, and **Statistical Heuristics** to distinguish between a skilled player and a client-assisted cheater.

---

## 🔥 Feature Showcase

### ⚔️ Combat Intelligence (The Punisher Engine)
*Detects combat hacks with surgical precision, ensuring legitimate PvP flows smoothly.*

* **Advanced KillAura:** Uses Ray-Tracing and angle heuristics to detect impossible rotations, wall-hits, and multi-entity targeting.
* **Dynamic Reach:** Calculates player velocity, ping, and hitboxes to enforce strict reach limits (3.01 blocks) with backtrack support.
* **Aim Consistency:** Analyzes mouse movement patterns to detect "Aim Assist," "Smooth Aim," and robotic locking behaviors.
* **AutoClicker / Macro:** Bayesian statistical analysis of click patterns (Kurtosis/Skewness) to flag non-human consistency (even randomized macros).
* **Velocity / Anti-Knockback:** Checks if a player responds correctly to server-side velocity packets (Horizontal & Vertical checks).
* **Criticals:** Prevents "packet criticals" (mini-jumps) that don't match ground status.
* **Hitbox Expansion:** Prevents clients from inflating entity hitboxes to make aiming easier.

### 🏃 Newtonian Movement Physics
*A complete simulation of Minecraft's movement code to prevent illegal travel.*

* **Prediction Flight:** Simulates where a player *should* be based on gravity, friction, and potion effects. Perfect for Elytra & Trident.
* **Speed / Omni-Sprint:** Prevents exceeding vanilla speed limits in any direction (including strafing).
* **Liquid Walk (Jesus):** Smart detection for walking on water/lava, including "Dolphin" mode bypasses.
* **NoFall / Spoof:** Detects packet spoofing to avoid fall damage (Ground spoofing).
* **Step & Spider:** Prevents moving up blocks instantly or climbing walls without ladders.
* **Phase / Blink:** Prevents moving through blocks or choking packets to teleport (Lag switching).
* **Elytra Speed:** Enforces strict speed limits and pitch checking for 1.21 Elytra mechanics.

### 🌍 World & Player Interactions
*Protecting the integrity of your map and economy.*

* **Scaffold / Tower:** Analyzes block placement rotations and timing to stop auto-bridging.
* **FastPlace:** Enforces vanilla block placement intervals.
* **Nuker / FastBreak:** Prevents breaking blocks faster than mathematically possible (mining fatigue/haste aware).
* **Ghost Hand:** Prevents interacting with blocks or entities through walls.
* **Fast Eat / Consumables:** Stops instant consumption of food or potions.
* **Inventory Move:** Detects movement while clicking inside GUIs (Survival mode).

### 🛡️ Network & System Internals
* **Packet Limiter:** Prevents "Crasher" exploits and packet spam that lags the server.
* **Ping Spoof Detection:** Identifies players faking high latency to bypass checks.
* **Payload Filter:** Blocks malicious book edits and custom payload exploits.

- And many more modules to be added alongside these.

---

## 🔮 The Future (Roadmap)

We are constantly pushing the boundaries. Here is what's coming next:

- [ ] **Ghost Replay System:** Record and playback a suspect's movement/combat for manual review.
- [ ] **Machine Learning Model:** Training a model to auto-ban based on probability scores.
- [ ] **Cross-Server Sync:** Sync bans and violations across your BungeeCord/Velocity network.

---

## 🛠️ Installation & Config

1.  **Download** the latest release (Available Mar 1st).
2.  **Drop** into `/plugins`.
3.  **Restart** your server.
