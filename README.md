<div align="center">

<a href="#support-the-project"><img src="https://img.shields.io/badge/USDT-Donate-1A7A5D?style=for-the-badge&logo=tether&logoColor=white&labelColor=26A17B" alt="Donate USDT" width="198"></a>
<a href="#solana"><img src="https://img.shields.io/badge/SOL-Donate-14F195?style=for-the-badge&logo=solana&logoColor=white&labelColor=9945FF" alt="Donate SOL" width="185"></a>
<a href="#evm-networks"><img src="https://img.shields.io/badge/ETH-Donate-627EEA?style=for-the-badge&logo=ethereum&logoColor=white&labelColor=3C3C3D" alt="Donate ETH" width="183"></a>
<a href="#bitcoin"><img src="https://img.shields.io/badge/BTC-Donate-B8650A?style=for-the-badge&logo=bitcoin&logoColor=white&labelColor=F7931A" alt="Donate BTC" width="185"></a>
<br>
<a href="#evm-networks"><img src="https://img.shields.io/badge/BNB%20Chain-Donate-B8860B?style=for-the-badge&logo=bnbchain&logoColor=black&labelColor=F0B90B" alt="Donate on BNB Chain" width="206"></a>
<a href="#evm-networks"><img src="https://img.shields.io/badge/Base-Donate-0033A0?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiAwYTEyIDEyIDAgMSAxLTExLjk1IDEzLjFoMTUuOHYtMi4ySC4wNUExMiAxMiAwIDAgMSAxMiAweiIvPjwvc3ZnPg==&logoColor=white&labelColor=0052FF" alt="Donate on Base" width="165"></a>
<a href="#evm-networks"><img src="https://img.shields.io/badge/Polygon-Donate-5A2EB0?style=for-the-badge&logo=polygon&logoColor=white&labelColor=8247E5" alt="Donate on Polygon" width="193"></a>
<br>
<a href="#evm-networks"><img src="https://img.shields.io/badge/Robinhood-Donate-6B8500?style=for-the-badge&logo=robinhood&logoColor=black&labelColor=CCFF00" alt="Donate on Robinhood" width="213"></a>
<a href="#evm-networks"><img src="https://img.shields.io/badge/ARC-Donate-283593?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTMgMTlhOSA5IDAgMCAxIDE4IDAiIGZpbGw9Im5vbmUiIHN0cm9rZT0id2hpdGUiIHN0cm9rZS13aWR0aD0iMy4yIiBzdHJva2UtbGluZWNhcD0icm91bmQiLz48L3N2Zz4=&logoColor=white&labelColor=3D5AFE" alt="Donate on ARC" width="156"></a>
<a href="#evm-networks"><img src="https://img.shields.io/badge/HyperEVM-Donate-2B7A68?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iYmxhY2siIGQ9Ik0yIDRoNHY2aDEyVjRoNHYxNmgtNHYtNkg2djZIMnoiLz48L3N2Zz4=&logoColor=black&labelColor=97FCE4" alt="Donate on HyperEVM" width="201"></a>

<br><br>

<img src="Godot/AsdaClient/Branding/game.png" alt="Asda Story logo" width="200">

# Asda Story Revival

<a href="https://discord.gg/anQRWEKVqG"><img src="https://img.shields.io/badge/Discord-Join%20the%20community-5865F2?style=for-the-badge&logo=discord&logoColor=white&labelColor=404EED" alt="Join the Discord server" width="330"></a>

</div>

Asda Story Revival is a community project to rebuild the original Asda Story MMORPG with a Godot client and a compatible game server, both written in C#. The original game guides the reconstruction of its maps, interface, and gameplay. Arabic is the client’s initial language, with support for additional translations.

The goal is to release the project as open source so anyone can download it, run a playable version, and adapt it to their own ideas. Shared tools and documentation will help contributors restore classic content, edit maps and interfaces, add new systems, and share their improvements.

The project is in active development. The first stable, playable release will be published here with the source code and setup instructions.

## Progress

✅ Done &nbsp;&nbsp; ⬜ Not done yet

### Server (C#)

The server speaks the original game's network protocol and stores its data in PostgreSQL. A new unified server replaces the original's separate server programs, one part at a time. Each part must give the same results as the original server for the same requests.

✅ The original server programs reproduced in C#, used as the reference server\
✅ The original database and its stored procedures moved to PostgreSQL\
✅ Login, server and channel lists, character list and selection\
✅ Entering the world, loading character data and saving on logout\
✅ Movement and seeing other players\
✅ Items: moving, equipping, potions, drops and pickup\
✅ Monsters: spawns, idle and walking behavior, patrols and walking NPCs\
✅ Combat with monsters: normal attacks, monsters fighting back, death, revive and respawn\
✅ Experience and level-up\
✅ Skills: learning, casting, cooldowns, buffs and other states\
✅ Soul guard and its skills\
✅ Player versus player combat and duels\
✅ Area chat, emotions and fame\
⬜ Party, whisper, friends and guilds\
⬜ Trading between players\
⬜ Portals between maps\
⬜ The unified server running the whole game on its own

### Client (Godot, C#)

✅ Original startup screen and game icon\
✅ Login screen rebuilt from the original artwork, layout and texts\
✅ Server, channel and character selection\
✅ Arabic interface by default, with selectable translations\
✅ The starting map, Alpen, with its original terrain and scenery\
✅ Click-to-move, running, jumping and camera control\
✅ Original HUD: HP, MP and EXP bars, target panel, buffs and cooldowns\
✅ Inventory, equipment, item tooltips and cosmetic avatar slots\
✅ Worn armor and weapons shown on characters, with upgrade glows and auras\
✅ Character window\
✅ Skill window, skill bar and casting with the original animations, effects and sounds\
✅ Monsters with their original models and animations\
✅ Combat with damage numbers, death and respawn\
✅ Item drops on the ground and pickup\
✅ Other players, duels, area chat and emotions\
✅ Soul guard\
✅ Usable items and the premium package\
⬜ Party, guild, trade and friends windows\
⬜ Travel to the other maps\
⬜ First playable public release

## Community

Join the project's Discord server, in Arabic with an English chat channel, to follow development, share ideas and old memories of the game, and help with testing or translation: https://discord.gg/anQRWEKVqG

## Support the project

If you would like to support development, donations are welcome. Please check the network before you send. USDT can be sent on Solana to the Solana address, or on Ethereum, BNB Chain or Polygon to the EVM address.

### Solana

SOL and USDT on Solana

```text
2d6zxzE9D27yX3hXJeriyBVGw3w3Q1FhEEhQhzhZ73FJ
```

### EVM networks

ETH and USDT on Ethereum, BNB Chain, Base, Polygon, Robinhood, ARC and HyperEVM

```text
0xBBc28fA66AA2AA189b7cD6DD1Ca89e79A5596d9C
```

### Bitcoin

Bitcoin (Taproot)

```text
bc1pmulqwc05rugm5q0x03m3nwv6sa7a9um3gcjh3nksyyrxpvp5rpzscywt0x
```

<div align="center">

<a href="#support-the-project"><img src="https://img.shields.io/badge/USDT-Donate-1A7A5D?style=for-the-badge&logo=tether&logoColor=white&labelColor=26A17B" alt="Donate USDT" width="198"></a>
<a href="#solana"><img src="https://img.shields.io/badge/SOL-Donate-14F195?style=for-the-badge&logo=solana&logoColor=white&labelColor=9945FF" alt="Donate SOL" width="185"></a>
<a href="#evm-networks"><img src="https://img.shields.io/badge/ETH-Donate-627EEA?style=for-the-badge&logo=ethereum&logoColor=white&labelColor=3C3C3D" alt="Donate ETH" width="183"></a>
<a href="#bitcoin"><img src="https://img.shields.io/badge/BTC-Donate-B8650A?style=for-the-badge&logo=bitcoin&logoColor=white&labelColor=F7931A" alt="Donate BTC" width="185"></a>
<br>
<a href="#evm-networks"><img src="https://img.shields.io/badge/BNB%20Chain-Donate-B8860B?style=for-the-badge&logo=bnbchain&logoColor=black&labelColor=F0B90B" alt="Donate on BNB Chain" width="206"></a>
<a href="#evm-networks"><img src="https://img.shields.io/badge/Base-Donate-0033A0?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiAwYTEyIDEyIDAgMSAxLTExLjk1IDEzLjFoMTUuOHYtMi4ySC4wNUExMiAxMiAwIDAgMSAxMiAweiIvPjwvc3ZnPg==&logoColor=white&labelColor=0052FF" alt="Donate on Base" width="165"></a>
<a href="#evm-networks"><img src="https://img.shields.io/badge/Polygon-Donate-5A2EB0?style=for-the-badge&logo=polygon&logoColor=white&labelColor=8247E5" alt="Donate on Polygon" width="193"></a>
<br>
<a href="#evm-networks"><img src="https://img.shields.io/badge/Robinhood-Donate-6B8500?style=for-the-badge&logo=robinhood&logoColor=black&labelColor=CCFF00" alt="Donate on Robinhood" width="213"></a>
<a href="#evm-networks"><img src="https://img.shields.io/badge/ARC-Donate-283593?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTMgMTlhOSA5IDAgMCAxIDE4IDAiIGZpbGw9Im5vbmUiIHN0cm9rZT0id2hpdGUiIHN0cm9rZS13aWR0aD0iMy4yIiBzdHJva2UtbGluZWNhcD0icm91bmQiLz48L3N2Zz4=&logoColor=white&labelColor=3D5AFE" alt="Donate on ARC" width="156"></a>
<a href="#evm-networks"><img src="https://img.shields.io/badge/HyperEVM-Donate-2B7A68?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iYmxhY2siIGQ9Ik0yIDRoNHY2aDEyVjRoNHYxNmgtNHYtNkg2djZIMnoiLz48L3N2Zz4=&logoColor=black&labelColor=97FCE4" alt="Donate on HyperEVM" width="201"></a>

</div>
