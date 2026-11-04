# Mazda RX-7 '92 Veilside — Fast & Furious Edition (Forza Horizon 2 PC)

![RX-7 Fast & Furious Edition](images/screenshot.png)

Han's orange-and-black **RX-7 Veilside Fortune** from *Tokyo Drift*, added to **Forza Horizon 2** on PC as a brand new car (it does not replace the stock RX-7). You can paint it however you like in the game's paint shop: the body and the mirrors can each have their own colour.

This is a port of the Forza Horizon 6 mod **[Mazda RX-7 Veilside (FH6, Nexus Mods #299)](https://www.nexusmods.com/forzahorizon6/mods/299)** — all credit for the original Veilside model goes to its author.

> **Note:** this is mostly a **visual mod (a "skin")**. Under the Veilside body, the car keeps the physics and handling of Forza Horizon 2's stock Mazda RX-7 (the game's MAZ_RX7_97 model): same engine, weight, upgrades and driving feel.

> [!WARNING]
> **Car ID changed in v1.1.** v1.0 uses car Id **2600**, v1.1 and v1.2 use car Id **19920**.
> v1.1 was made for players whose v1.0 conflicts with another car pack that also uses Id 2600. v1.2 keeps Id 19920 and adds the underglow colour setting.
> **If you already bought the RX-7 with v1.0 and update to v1.1, the car disappears from your garage and you will have to buy it again** at the Autoshow.
> To update, delete the old `MAZ_RX7_92 Veilside` and `MAZ_RX7_92 Veilside Neons` folders from `mods\` first.

## Features

- **New car "RX-7 Fast & Furious Edition"** (car Id 19920 in v1.1, 2600 in v1.0), sold at the Autoshow under Mazda, with its own name and dealer pictures.
- **Full Veilside body kit**: bumpers, wide fenders, side skirts, wing, exhaust, Veilside headlights and taillights.
- **Veilside mirrors** that reflect the road in cockpit view and take the in-game mirror paint colour.
- **Working lights**: projector headlights, red taillights at night and when braking, front and rear **turn signals**.
- **Veilside badge** on the rear panel.
- **Optional add-on — underglow**: neon tubes, ground light and cabin light, on with the headlights. Orange by default, **any colour you want** since v1.2 (see below).
- **Wider track** for the Veilside stance through fh2wheels.

## Requirements

- Forza Horizon 2 running on PC with **[Azimuth](https://almost-there-games.itch.io/azimuth)** 1.0.4.
- **[Extra Options](https://github.com/RokkuDayo/ForzaHorizon2_ExtraOptions)** 0.4.4 or newer (it loads the `mods` folder).
- **[fh2wheels](https://github.com/conner-mcvay/fh2-mods)** — included here as an Extra Options plugin, already set up for this car.

## Installation

1. Download `rx7_Veilside_EN_v1.2.zip` from the [Releases](../../releases) page (older versions are still there: `rx7_Veilside_EN.zip` = v1.0 with Id 2600).
2. Extract it into your Azimuth folder (the one containing `azimuth.exe`).
3. You now have three folders in `mods\`:
   - `MAZ_RX7_92 Veilside` — the car.
   - `MAZ_RX7_92 Veilside Neons` — the underglow add-on (optional; delete it if you don't want neons).
   - `fh2wheels plugin` — the wider track (`fh2wheels.ini`: `19920=40,158` in v1.1, `2600=40,158` in v1.0).
4. Launch the game and find the car at the Autoshow (Mazda).

Extra Options adds new folders to `mods\loadorder.txt` automatically. Keep **Neons after the car**.

## Changing the underglow colour (v1.2)

1. **Close the game.**
2. Open `mods\MAZ_RX7_92 Veilside Neons\color.txt`, write the colour you want on the **first line** and save. For example:
   ```
   purple
   ```
   - Colour names: `red`, `orange`, `yellow`, `green`, `cyan`, `blue`, `purple`, `pink`, `white`
   - Or R,G,B from 0 to 255: `255,0,0`
   - Or hex: `#FF0000`
   - Optional: add a line `interior = blue` for a different cabin light colour (by default the cabin takes the underglow colour).
3. Double-click **`Apply color.bat`** in the same folder. The window says `Done` when the colour is applied.
4. Start the game and turn the headlights on.

The colour changes the neon tubes, the ground light and the cabin light. The tubes show day and night; the ground light and the cabin light only show at night. Write `orange` and apply again to go back to the original colour.

Tested on a clean (vanilla) Forza Horizon 2 + Azimuth 1.0.4 + Extra Options 0.4.4.

## Known issues

- **⚠️ You must turn damage OFF (Options → Difficulty → Damage: Cosmetic/Off) before driving this car.** With damage on, any crash causes visual glitches on the Veilside kit (black patches and stretched body parts). With damage off, everything stays clean.
- **Don't lower the ride height too much** in the tuning menu: with a very low setting the Veilside kit can clip into the wheels or the ground and glitch.
- **You can see through the body a little in some places** (small gaps between kit panels, mostly at night when the cabin light is on). It is only visible up close and does not affect gameplay.
- **Cockpit view and photo mode differ around the A-pillars.** In cockpit view the game does not draw the main Veilside body, so the inner edge of the windscreen pillar shows dark instead of in the car colour (photo mode shows it correctly).
- fh2wheels can occasionally crash the game at startup on Azimuth 1.0.4; launching again works.

| Cockpit view | Photo mode | Small gaps at night |
|---|---|---|
| ![Cockpit](images/issue_cockpit.png) | ![Photo mode](images/issue_photomode.png) | ![Gaps](images/issue_gaps.png) |

## Credits

- Original Veilside RX-7 model: [FH6 mod on Nexus Mods (#299)](https://www.nexusmods.com/forzahorizon6/mods/299) and its author.
- [Azimuth](https://almost-there-games.itch.io/azimuth) by Almost There Games.
- [Extra Options](https://github.com/RokkuDayo/ForzaHorizon2_ExtraOptions) by RokkuDayo.
- [fh2wheels / fh2-mods](https://github.com/conner-mcvay/fh2-mods) by conner-mcvay.
- Port to Forza Horizon 2: crasyimperior and Claude (Anthropic).

*Forza Horizon is a trademark of Microsoft. This is a fan-made mod, not affiliated with Microsoft, Playground Games or Turn 10.*
