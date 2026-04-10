
# Pokemon Card CSVs: Every set released in CSV format

Every card from every Pokemon TCG set organized as clean CSV files with card name, serial number, and rarity.

**Browse the full [Pokemon card database](https://pokemon.tradingcarddex.com/database) with images, filters and search completely free.**

Maintained by [TradingCardDex](https://tradingcarddex.com), a multi-game trading card database covering Pokemon, Magic: The Gathering, Yu-Gi-Oh, and more.

---

## What's Inside

This repository contains CSV files for every Pokemon TCG set ever released. Each file includes:

| Field | Description |
|-------|-------------|
| `Name` | Card name (e.g., Charizard ex, Pikachu VMAX) |
| `Number` | Card number within the set (e.g., 6/165) |
| `Rarity` | Official rarity (Common, Uncommon, Rare, Ultra Rare, Secret Rare, etc.) |

Sets are organized by series. Each directory is a series, individual files are the sets.

---

## Quick Start

### Download a Single Set

```
curl -O "https://raw.githubusercontent.com/tradingcarddex/Pokemon-Card-CSV/main/Scarlet%20%26%20Violet/Pokemon-151.csv"
```

### Use in Google Sheets (No Coding Required)

Paste this formula into any cell to import a set directly into your spreadsheet:

```
=IMPORTDATA("https://raw.githubusercontent.com/tradingcarddex/Pokemon-Card-CSV/main/Scarlet%20%26%20Violet/Pokemon-151.csv")
```

### Use in Python

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/tradingcarddex/Pokemon-Card-CSV/main/Scarlet%20%26%20Violet/Pokemon-151.csv")
print(df.head())
```

### Use in JavaScript

```javascript
const response = await fetch("https://raw.githubusercontent.com/tradingcarddex/Pokemon-Card-CSV/main/Scarlet%20%26%20Violet/Pokemon-151.csv");
const csv = await response.text();
```

---

## Available Sets

This Pokemon card database includes every English-language Pokemon TCG set. A few highlights:

| Era | Example Sets | Status |
|-----|-------------|--------|
| Base Era (1999–2003) | Base Set, Jungle, Fossil, Team Rocket, Gym Heroes, Neo Genesis | ✅ Complete |
| EX Era (2003–2007) | Ruby & Sapphire, FireRed & LeafGreen, Delta Species, Dragon Frontiers | ✅ Complete |
| Diamond & Pearl (2007–2010) | Diamond & Pearl, Mysterious Treasures, Legends Awakened, Platinum | ✅ Complete |
| Black & White (2011–2013) | Black & White, Noble Victories, Boundaries Crossed, Plasma Storm | ✅ Complete |
| XY Era (2014–2017) | XY, Flashfire, Phantom Forces, Roaring Skies, Evolutions | ✅ Complete |
| Sun & Moon (2017–2020) | Sun & Moon, Guardians Rising, Burning Shadows, Cosmic Eclipse | ✅ Complete |
| Sword & Shield (2020–2023) | Sword & Shield, Evolving Skies, Brilliant Stars, Crown Zenith | ✅ Complete |
| Scarlet & Violet (2023–present) | Scarlet & Violet, Paldea Evolved, 151, Temporal Forces, Shrouded Fable | ✅ Complete |
| Promos & Special | SWSH Promos, SVP Promos, McDonald's Promos, Celebrations | ✅ Complete |



## Who Uses This

- **Collectors** building personal checklists and tracking their collections
- **Content creators** referencing card data for articles, videos, and guides
- **Data enthusiasts** analyzing rarity distributions and set compositions

If you use this data in a project, attribution to [TradingCardDex.com](https://tradingcarddex.com) is appreciated.

---

## About TradingCardDex

[TradingCardDex](https://tradingcarddex.com) is a free, multi-game trading card database. The [Pokemon card database](https://pokemon.tradingcarddex.com/database) covers every Pokemon TCG set with card images, rarity, pricing, and full-text search.

### Connect

- 🌐 [TradingCardDex.com](https://tradingcarddex.com)
- 🔴 [Pokemon Card Database](https://pokemon.tradingcarddex.com/database)
- 📌 [Pinterest](https://www.pinterest.com/tradingcarddex/)
- 𝕏 [Twitter / X](https://x.com/tradingcard_dex)
- 🔵 [Reddit](https://www.reddit.com/r/TradingCardDex/)
- 📘 [Facebook](https://www.facebook.com/tradingcarddex)
- ⚙️ [GitHub](https://github.com/tradingcarddex/Pokemon-Card-CSV)
- ▶️ [YouTube](https://www.youtube.com/@tradingcarddex)
- 🔍 [Google](https://share.google/29KhJqD7Ubp6fCCMZ)
- 📄 [Scribd](https://www.scribd.com/user/949762294/Trading-Card-Dex)
- 🔖 [Substack](https://tradingcarddex.substack.com/) 

---

# Pokemon Card CSV Index

## Series Overview

| Series | Sets |
|---|---|
| Base | 6 |
| Gym | 2 |
| Neo | 4 |
| Other | 15 |
| E-Card | 3 |
| EX | 20 |
| NP | 1 |
| POP | 9 |
| Diamond & Pearl | 8 |
| Platinum | 4 |
| HeartGold & SoulSilver | 6 |
| Black & White | 13 |
| XY | 16 |
| Sun & Moon | 18 |
| Sword & Shield | 25 |
| Scarlet & Violet | 18 |
| Mega Evolution | 3 |

**Total: 171 sets across 17 series**

---

## Sets by Series

### Base (6 sets)

| Set Name | File |
|---|---|
| Base | `Base/Pokemon-Base.csv` |
| Jungle | `Base/Pokemon-Jungle.csv` |
| Wizards Black Star Promos | `Base/Pokemon-Wizards-Black-Star-Promos.csv` |
| Fossil | `Base/Pokemon-Fossil.csv` |
| Base Set 2 | `Base/Pokemon-Base-Set-2.csv` |
| Team Rocket | `Base/Pokemon-Team-Rocket.csv` |

### Gym (2 sets)

| Set Name | File |
|---|---|
| Gym Heroes | `Gym/Pokemon-Gym-Heroes.csv` |
| Gym Challenge | `Gym/Pokemon-Gym-Challenge.csv` |

### Neo (4 sets)

| Set Name | File |
|---|---|
| Neo Genesis | `Neo/Pokemon-Neo-Genesis.csv` |
| Neo Discovery | `Neo/Pokemon-Neo-Discovery.csv` |
| Neo Revelation | `Neo/Pokemon-Neo-Revelation.csv` |
| Neo Destiny | `Neo/Pokemon-Neo-Destiny.csv` |

### Other (15 sets)

| Set Name | File |
|---|---|
| Southern Islands | `Other/Pokemon-Southern-Islands.csv` |
| Legendary Collection | `Other/Pokemon-Legendary-Collection.csv` |
| Best of Game | `Other/Pokemon-Best-of-Game.csv` |
| Pokémon Rumble | `Other/Pokemon-Rumble.csv` |
| McDonald's Collection 2011 | `Other/Pokemon-McDonalds-Collection-2011.csv` |
| McDonald's Collection 2012 | `Other/Pokemon-McDonalds-Collection-2012.csv` |
| McDonald's Collection 2014 | `Other/Pokemon-McDonalds-Collection-2014.csv` |
| McDonald's Collection 2015 | `Other/Pokemon-McDonalds-Collection-2015.csv` |
| McDonald's Collection 2016 | `Other/Pokemon-McDonalds-Collection-2016.csv` |
| McDonald's Collection 2017 | `Other/Pokemon-McDonalds-Collection-2017.csv` |
| McDonald's Collection 2018 | `Other/Pokemon-McDonalds-Collection-2018.csv` |
| McDonald's Collection 2019 | `Other/Pokemon-McDonalds-Collection-2019.csv` |
| Pokémon Futsal Collection | `Other/Pokemon-Futsal-Collection.csv` |
| McDonald's Collection 2021 | `Other/Pokemon-McDonalds-Collection-2021.csv` |
| McDonald's Collection 2022 | `Other/Pokemon-McDonalds-Collection-2022.csv` |

### E-Card (3 sets)

| Set Name | File |
|---|---|
| Expedition Base Set | `E-Card/Pokemon-Expedition-Base-Set.csv` |
| Aquapolis | `E-Card/Pokemon-Aquapolis.csv` |
| Skyridge | `E-Card/Pokemon-Skyridge.csv` |

### EX (20 sets)

| Set Name | File |
|---|---|
| Ruby & Sapphire | `EX/Pokemon-Ruby-and-Sapphire.csv` |
| Sandstorm | `EX/Pokemon-Sandstorm.csv` |
| Dragon | `EX/Pokemon-Dragon.csv` |
| Team Magma vs Team Aqua | `EX/Pokemon-Team-Magma-vs-Team-Aqua.csv` |
| EX Trainer Kit Latias | `EX/Pokemon-EX-Trainer-Kit-Latias.csv` |
| EX Trainer Kit Latios | `EX/Pokemon-EX-Trainer-Kit-Latios.csv` |
| Hidden Legends | `EX/Pokemon-Hidden-Legends.csv` |
| FireRed & LeafGreen | `EX/Pokemon-FireRed-and-LeafGreen.csv` |
| Team Rocket Returns | `EX/Pokemon-Team-Rocket-Returns.csv` |
| Deoxys | `EX/Pokemon-Deoxys.csv` |
| Emerald | `EX/Pokemon-Emerald.csv` |
| Unseen Forces | `EX/Pokemon-Unseen-Forces.csv` |
| Delta Species | `EX/Pokemon-Delta-Species.csv` |
| Legend Maker | `EX/Pokemon-Legend-Maker.csv` |
| EX Trainer Kit 2 Plusle | `EX/Pokemon-EX-Trainer-Kit-2-Plusle.csv` |
| EX Trainer Kit 2 Minun | `EX/Pokemon-EX-Trainer-Kit-2-Minun.csv` |
| Holon Phantoms | `EX/Pokemon-Holon-Phantoms.csv` |
| Crystal Guardians | `EX/Pokemon-Crystal-Guardians.csv` |
| Dragon Frontiers | `EX/Pokemon-Dragon-Frontiers.csv` |
| Power Keepers | `EX/Pokemon-Power-Keepers.csv` |

### NP (1 set)

| Set Name | File |
|---|---|
| Nintendo Black Star Promos | `NP/Pokemon-Nintendo-Black-Star-Promos.csv` |

### POP (9 sets)

| Set Name | File |
|---|---|
| POP Series 1 | `POP/Pokemon-POP-Series-1.csv` |
| POP Series 2 | `POP/Pokemon-POP-Series-2.csv` |
| POP Series 3 | `POP/Pokemon-POP-Series-3.csv` |
| POP Series 4 | `POP/Pokemon-POP-Series-4.csv` |
| POP Series 5 | `POP/Pokemon-POP-Series-5.csv` |
| POP Series 6 | `POP/Pokemon-POP-Series-6.csv` |
| POP Series 7 | `POP/Pokemon-POP-Series-7.csv` |
| POP Series 8 | `POP/Pokemon-POP-Series-8.csv` |
| POP Series 9 | `POP/Pokemon-POP-Series-9.csv` |

### Diamond & Pearl (8 sets)

| Set Name | File |
|---|---|
| Diamond & Pearl | `Diamond & Pearl/Pokemon-Diamond-and-Pearl.csv` |
| DP Black Star Promos | `Diamond & Pearl/Pokemon-DP-Black-Star-Promos.csv` |
| Mysterious Treasures | `Diamond & Pearl/Pokemon-Mysterious-Treasures.csv` |
| Secret Wonders | `Diamond & Pearl/Pokemon-Secret-Wonders.csv` |
| Great Encounters | `Diamond & Pearl/Pokemon-Great-Encounters.csv` |
| Majestic Dawn | `Diamond & Pearl/Pokemon-Majestic-Dawn.csv` |
| Legends Awakened | `Diamond & Pearl/Pokemon-Legends-Awakened.csv` |
| Stormfront | `Diamond & Pearl/Pokemon-Stormfront.csv` |

### Platinum (4 sets)

| Set Name | File |
|---|---|
| Platinum | `Platinum/Pokemon-Platinum.csv` |
| Rising Rivals | `Platinum/Pokemon-Rising-Rivals.csv` |
| Supreme Victors | `Platinum/Pokemon-Supreme-Victors.csv` |
| Arceus | `Platinum/Pokemon-Arceus.csv` |

### HeartGold & SoulSilver (6 sets)

| Set Name | File |
|---|---|
| HeartGold & SoulSilver | `HeartGold & SoulSilver/Pokemon-HeartGold-and-SoulSilver.csv` |
| HGSS Black Star Promos | `HeartGold & SoulSilver/Pokemon-HGSS-Black-Star-Promos.csv` |
| HS—Unleashed | `HeartGold & SoulSilver/Pokemon-HSUnleashed.csv` |
| HS—Undaunted | `HeartGold & SoulSilver/Pokemon-HSUndaunted.csv` |
| HS—Triumphant | `HeartGold & SoulSilver/Pokemon-HSTriumphant.csv` |
| Call of Legends | `HeartGold & SoulSilver/Pokemon-Call-of-Legends.csv` |

### Black & White (13 sets)

| Set Name | File |
|---|---|
| BW Black Star Promos | `Black & White/Pokemon-BW-Black-Star-Promos.csv` |
| Black & White | `Black & White/Pokemon-Black-and-White.csv` |
| Emerging Powers | `Black & White/Pokemon-Emerging-Powers.csv` |
| Noble Victories | `Black & White/Pokemon-Noble-Victories.csv` |
| Next Destinies | `Black & White/Pokemon-Next-Destinies.csv` |
| Dark Explorers | `Black & White/Pokemon-Dark-Explorers.csv` |
| Dragons Exalted | `Black & White/Pokemon-Dragons-Exalted.csv` |
| Dragon Vault | `Black & White/Pokemon-Dragon-Vault.csv` |
| Boundaries Crossed | `Black & White/Pokemon-Boundaries-Crossed.csv` |
| Plasma Storm | `Black & White/Pokemon-Plasma-Storm.csv` |
| Plasma Freeze | `Black & White/Pokemon-Plasma-Freeze.csv` |
| Plasma Blast | `Black & White/Pokemon-Plasma-Blast.csv` |
| Legendary Treasures | `Black & White/Pokemon-Legendary-Treasures.csv` |

### XY (16 sets)

| Set Name | File |
|---|---|
| XY Black Star Promos | `XY/Pokemon-XY-Black-Star-Promos.csv` |
| Kalos Starter Set | `XY/Pokemon-Kalos-Starter-Set.csv` |
| XY | `XY/Pokemon-XY.csv` |
| Flashfire | `XY/Pokemon-Flashfire.csv` |
| Furious Fists | `XY/Pokemon-Furious-Fists.csv` |
| Phantom Forces | `XY/Pokemon-Phantom-Forces.csv` |
| Primal Clash | `XY/Pokemon-Primal-Clash.csv` |
| Double Crisis | `XY/Pokemon-Double-Crisis.csv` |
| Roaring Skies | `XY/Pokemon-Roaring-Skies.csv` |
| Ancient Origins | `XY/Pokemon-Ancient-Origins.csv` |
| BREAKthrough | `XY/Pokemon-BREAKthrough.csv` |
| BREAKpoint | `XY/Pokemon-BREAKpoint.csv` |
| Generations | `XY/Pokemon-Generations.csv` |
| Fates Collide | `XY/Pokemon-Fates-Collide.csv` |
| Steam Siege | `XY/Pokemon-Steam-Siege.csv` |
| Evolutions | `XY/Pokemon-Evolutions.csv` |

### Sun & Moon (18 sets)

| Set Name | File |
|---|---|
| Sun & Moon | `Sun & Moon/Pokemon-Sun-and-Moon.csv` |
| SM Black Star Promos | `Sun & Moon/Pokemon-SM-Black-Star-Promos.csv` |
| Guardians Rising | `Sun & Moon/Pokemon-Guardians-Rising.csv` |
| Burning Shadows | `Sun & Moon/Pokemon-Burning-Shadows.csv` |
| Shining Legends | `Sun & Moon/Pokemon-Shining-Legends.csv` |
| Crimson Invasion | `Sun & Moon/Pokemon-Crimson-Invasion.csv` |
| Ultra Prism | `Sun & Moon/Pokemon-Ultra-Prism.csv` |
| Forbidden Light | `Sun & Moon/Pokemon-Forbidden-Light.csv` |
| Celestial Storm | `Sun & Moon/Pokemon-Celestial-Storm.csv` |
| Dragon Majesty | `Sun & Moon/Pokemon-Dragon-Majesty.csv` |
| Lost Thunder | `Sun & Moon/Pokemon-Lost-Thunder.csv` |
| Team Up | `Sun & Moon/Pokemon-Team-Up.csv` |
| Detective Pikachu | `Sun & Moon/Pokemon-Detective-Pikachu.csv` |
| Unbroken Bonds | `Sun & Moon/Pokemon-Unbroken-Bonds.csv` |
| Unified Minds | `Sun & Moon/Pokemon-Unified-Minds.csv` |
| Hidden Fates | `Sun & Moon/Pokemon-Hidden-Fates.csv` |
| Hidden Fates Shiny Vault | `Sun & Moon/Pokemon-Hidden-Fates-Shiny-Vault.csv` |
| Cosmic Eclipse | `Sun & Moon/Pokemon-Cosmic-Eclipse.csv` |

### Sword & Shield (25 sets)

| Set Name | File |
|---|---|
| SWSH Black Star Promos | `Sword & Shield/Pokemon-SWSH-Black-Star-Promos.csv` |
| Sword & Shield | `Sword & Shield/Pokemon-Sword-and-Shield.csv` |
| Rebel Clash | `Sword & Shield/Pokemon-Rebel-Clash.csv` |
| Darkness Ablaze | `Sword & Shield/Pokemon-Darkness-Ablaze.csv` |
| Champion's Path | `Sword & Shield/Pokemon-Champions-Path.csv` |
| Vivid Voltage | `Sword & Shield/Pokemon-Vivid-Voltage.csv` |
| Shining Fates | `Sword & Shield/Pokemon-Shining-Fates.csv` |
| Shining Fates Shiny Vault | `Sword & Shield/Pokemon-Shining-Fates-Shiny-Vault.csv` |
| Battle Styles | `Sword & Shield/Pokemon-Battle-Styles.csv` |
| Chilling Reign | `Sword & Shield/Pokemon-Chilling-Reign.csv` |
| Evolving Skies | `Sword & Shield/Pokemon-Evolving-Skies.csv` |
| Celebrations | `Sword & Shield/Pokemon-Celebrations.csv` |
| Celebrations: Classic Collection | `Sword & Shield/Pokemon-Celebrations-Classic-Collection.csv` |
| Fusion Strike | `Sword & Shield/Pokemon-Fusion-Strike.csv` |
| Brilliant Stars | `Sword & Shield/Pokemon-Brilliant-Stars.csv` |
| Brilliant Stars Trainer Gallery | `Sword & Shield/Pokemon-Brilliant-Stars-Trainer-Gallery.csv` |
| Astral Radiance | `Sword & Shield/Pokemon-Astral-Radiance.csv` |
| Astral Radiance Trainer Gallery | `Sword & Shield/Pokemon-Astral-Radiance-Trainer-Gallery.csv` |
| Pokémon GO | `Sword & Shield/Pokemon-GO.csv` |
| Lost Origin | `Sword & Shield/Pokemon-Lost-Origin.csv` |
| Lost Origin Trainer Gallery | `Sword & Shield/Pokemon-Lost-Origin-Trainer-Gallery.csv` |
| Silver Tempest | `Sword & Shield/Pokemon-Silver-Tempest.csv` |
| Silver Tempest Trainer Gallery | `Sword & Shield/Pokemon-Silver-Tempest-Trainer-Gallery.csv` |
| Crown Zenith | `Sword & Shield/Pokemon-Crown-Zenith.csv` |
| Crown Zenith Galarian Gallery | `Sword & Shield/Pokemon-Crown-Zenith-Galarian-Gallery.csv` |

### Scarlet & Violet (18 sets)

| Set Name | File |
|---|---|
| Scarlet & Violet Black Star Promos | `Scarlet & Violet/Pokemon-Scarlet-and-Violet-Black-Star-Promos.csv` |
| Scarlet & Violet Energies | `Scarlet & Violet/Pokemon-Scarlet-and-Violet-Energies.csv` |
| Scarlet & Violet | `Scarlet & Violet/Pokemon-Scarlet-and-Violet.csv` |
| Paldea Evolved | `Scarlet & Violet/Pokemon-Paldea-Evolved.csv` |
| Obsidian Flames | `Scarlet & Violet/Pokemon-Obsidian-Flames.csv` |
| 151 | `Scarlet & Violet/Pokemon-151.csv` |
| Paradox Rift | `Scarlet & Violet/Pokemon-Paradox-Rift.csv` |
| Paldean Fates | `Scarlet & Violet/Pokemon-Paldean-Fates.csv` |
| Temporal Forces | `Scarlet & Violet/Pokemon-Temporal-Forces.csv` |
| Twilight Masquerade | `Scarlet & Violet/Pokemon-Twilight-Masquerade.csv` |
| Shrouded Fable | `Scarlet & Violet/Pokemon-Shrouded-Fable.csv` |
| Stellar Crown | `Scarlet & Violet/Pokemon-Stellar-Crown.csv` |
| Surging Sparks | `Scarlet & Violet/Pokemon-Surging-Sparks.csv` |
| Prismatic Evolutions | `Scarlet & Violet/Pokemon-Prismatic-Evolutions.csv` |
| Journey Together | `Scarlet & Violet/Pokemon-Journey-Together.csv` |
| Destined Rivals | `Scarlet & Violet/Pokemon-Destined-Rivals.csv` |
| Black Bolt | `Scarlet & Violet/Pokemon-Black-Bolt.csv` |
| White Flare | `Scarlet & Violet/Pokemon-White-Flare.csv` |

### Mega Evolution (3 sets)

| Set Name | File |
|---|---|
| Mega Evolution | `Mega Evolution/Pokemon-Mega-Evolution.csv` |
| Phantasmal Flames | `Mega Evolution/Pokemon-Phantasmal-Flames.csv` |
| Ascended Heroes | `Mega Evolution/Pokemon-Ascended-Heroes.csv` |

## License

MIT: use this data however you want. Attribution to [TradingCardDex.com](https://tradingcarddex.com) is appreciated but not required
