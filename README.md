<div align="center">

<a href="#support-the-project"><img src="https://img.shields.io/badge/Donate-USDT-26A17B?style=for-the-badge&logo=tether&logoColor=white" alt="Donate USDT"></a>
<a href="#support-the-project"><img src="https://img.shields.io/badge/Donate-SOL-9945FF?style=for-the-badge&logo=solana&logoColor=white" alt="Donate SOL"></a>

<br><br>

<img src="Godot/AsdaClient/Branding/game.png" alt="Asda Story logo" width="200">

# Asda Story Revival

</div>

Asda Story Revival is a community project to rebuild the original Asda Story MMORPG with a Godot client and a compatible game server, both written in C#. The original game guides the reconstruction of its maps, interface, and gameplay. Arabic is the client’s initial language, with support for additional translations.

The goal is to release the project as open source so anyone can download it, run a playable version, and adapt it to their own ideas. Shared tools and documentation will help contributors restore classic content, edit maps and interfaces, add new systems, and share their improvements.

The project is in active development. The first stable, playable release will be published here with the source code and setup instructions.

## Progress

### Server (C#)

The server speaks the original game's network protocol and stores its data in PostgreSQL. A new unified server replaces the original's separate server programs, one part at a time. Each part must give the same results as the original server for the same requests.

- [x] The original server programs reproduced in C#, used as the reference server
- [x] The original database and its stored procedures moved to PostgreSQL
- [x] Login, server and channel lists, character list and selection
- [x] Entering the world, loading character data and saving on logout
- [x] Movement and seeing other players
- [x] Items: moving, equipping, potions, drops and pickup
- [x] Monsters: spawns, idle and walking behavior, patrols and walking NPCs
- [x] Combat with monsters: normal attacks, monsters fighting back, death, revive and respawn
- [x] Experience and level-up
- [x] Skills: learning, casting, cooldowns, buffs and other states
- [x] Soul guard and its skills
- [x] Player versus player combat and duels
- [x] Area chat, emotions and fame
- [ ] Party, whisper, friends and guilds
- [ ] Trading between players
- [ ] Portals between maps
- [ ] The unified server running the whole game on its own

### Client (Godot, C#)

- [x] Original startup screen and game icon
- [x] Login screen rebuilt from the original artwork, layout and texts
- [x] Server, channel and character selection
- [x] Arabic interface by default, with selectable translations
- [x] The starting map, Alpen, with its original terrain and scenery
- [x] Click-to-move, running, jumping and camera control
- [x] Original HUD: HP, MP and EXP bars, target panel, buffs and cooldowns
- [x] Inventory, equipment, item tooltips and cosmetic avatar slots
- [x] Worn armor and weapons shown on characters, with upgrade glows and auras
- [x] Character window
- [x] Skill window, skill bar and casting with the original animations, effects and sounds
- [x] Monsters with their original models and animations
- [x] Combat with damage numbers, death and respawn
- [x] Item drops on the ground and pickup
- [x] Other players, duels, area chat and emotions
- [x] Soul guard
- [x] Usable items and the premium package
- [ ] Party, guild, trade and friends windows
- [ ] Travel to the other maps
- [ ] First playable public release

## Support the project

If you would like to support development, donations are welcome. Please check the network before you send.

**Solana**: SOL and USDT on Solana

```text
2d6zxzE9D27yX3hXJeriyBVGw3w3Q1FhEEhQhzhZ73FJ
```

**Ethereum and EVM networks**: ETH and USDT, also BNB Chain, Base, Polygon, Robinhood, ARC and HyperEVM

```text
0xBBc28fA66AA2AA189b7cD6DD1Ca89e79A5596d9C
```

**Bitcoin** (Taproot)

```text
bc1pmulqwc05rugm5q0x03m3nwv6sa7a9um3gcjh3nksyyrxpvp5rpzscywt0x
```

<div align="center">

<a href="#support-the-project"><img src="https://img.shields.io/badge/Donate-USDT-26A17B?style=for-the-badge&logo=tether&logoColor=white" alt="Donate USDT"></a>
<a href="#support-the-project"><img src="https://img.shields.io/badge/Donate-SOL-9945FF?style=for-the-badge&logo=solana&logoColor=white" alt="Donate SOL"></a>

</div>
