# Aion 2 Meter

Live DPS meter for AION 2.

## How it works

There's no official api for AION 2, and you don't need one. During a fight the game server keeps sending your pc packets about what's going on: who hit who, how much, crits, boss hp, buffs, deaths. The meter just reads that traffic as it arrives and adds it all up. That's why it needs Npcap, it's the thing that lets it see the traffic.

What it does NOT do:

* touch the game files or the game client
* read the game's memory or inject anything
* send anything to the game server

It only watches what's already coming into your pc. Pretty much every meter works like this, Shinra in TERA included.

## Install

1. Grab **Npcap** from https://npcap.com (free). When the installer asks, tick **WinPcap API compatible Mode**.
2. Download `Aion2Meter-win-Setup.exe` from the [latest release](../../releases/latest) and run it. No admin needed.
3. Open the meter before you pick your character so it catches everyone from the start.

## Updates

You don't have to do anything. New versions download in the background and get installed when you close the meter. Want it right now? Right click the tray icon and hit **Restart to update**.

## Heads up

Windows SmartScreen might yell at you the first time since the installer isn't signed yet. Click **More info** and then **Run anyway**.

Found a bug or got an idea? Hit us up on Discord.
