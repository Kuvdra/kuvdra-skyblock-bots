# Kuvdra's Skyblock Discord Bots

A set of Hypixel SkyBlock Discord bots developed, hosted and maintained by Kuvdra for the Kuvdra's Cove Discord community.

## Developer

| | |
|---|---|
| Developer | Kuvdra |
| Minecraft account | Kuvdra |
| Minecraft UUID | `e643bbeb-d397-4338-ab6f-c73c31b9dc17` |
| YouTube | [Kuvdra](https://www.youtube.com/@Kuvdra) |
| Discord server | https://discord.gg/kuvdra |

The bots are available exclusively within the Kuvdra's Cove Discord server.

## Features

The primary bot, Kuvdra Method Bot, provides the following:

- **Account linking:** links a player's Minecraft account and SkyBlock profile, so results reflect their own stats, collections and unlocked requirements.
- **Stat progress:** analyses a player's profile (wardrobe, equipment, accessories, pets and attributes) and lists the upgrades needed to maximise a chosen stat.
- **Accessory calculators:** identify the most cost-effective ways to increase Magical Power.
- **Hunting calculators:** estimate profit per hour from a player's stats, attribute levels and profile, and the cheapest ways to maximise Hunter Fortune.
- **Market tools:** bazaar, auction house, crafting and forge flip calculations, price history, and detection of likely price manipulation.

## Hypixel API usage

- All requests are made from a single privately hosted server. The API key is stored in a private environment file on that server and is never shared, published or distributed to any client.
- Player profile data is cached in an SQLite database to avoid repeated requests for the same data.
- Bazaar and auction house data are retrieved from the public SkyBlock endpoints and shared across all commands, rather than requested per user.
- The API is not proxied or made available to any third-party developers or applications.

## Access

Many commands are available free of charge to all members of the server. Some additional features are reserved for Patreon supporters (Premium tiers); this support covers the cost of hosting and continued development of the bots. All paid features consist of the bot's own calculations, not raw API data.

## Source code

The source code is not publicly available. This repository serves as the project's public information page.
