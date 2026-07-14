# void-hauler-test
VOID HAULER — Instruction Manual (v1.1)
A space mining, combat, and trading game. This manual covers every system in the current build.


1. The Basics
You captain a single mining hauler with a laser, a cargo hold, and not much else. Blast asteroids into fragments, collect the ore that spills out, and haul it back to a station to sell. Everything else — crew, ship upgrades, combat, factions, two additional star systems — grows out of that one loop.

Starting out: click Launch on the title screen. Progress autosaves continuously (see §21 for exactly how, especially if you're playing outside Claude's interface). A reset save data link is available on the title screen if you want to start fresh.


2. Controls
Key
Action
W / ↑
Thrust forward
S / ↓
Reverse thrust (half power)
A / D or ←/→
Turn
SPACE (hold)
Fire mining laser
SHIFT or CTRL (hold)
Activate Tractor Beam and/or Ram Scoop (once installed — same key does both)
Z
Fire a missile — auto-targets the nearest threat (once you have a launcher)
E
Dock at a station/outpost, or activate a Stargate when nearby
I
Open the Cargo Manifest (also where you smelt ore)
ESC
Close any open menu


Mouse is used for all menu interaction. Buttons for donations and ammo purchases support hold-to-repeat — press and hold instead of clicking dozens of times.

A speaker icon (🔊/🔇) in the top HUD toggles all sound.


3. Mining
Asteroid tiers
Every asteroid starts as a plain gray, unidentified rock. Composition is unknown until you grind it all the way down:

Large → breaks into 2–3 Medium fragments
Medium → breaks into 2–3 Small fragments
Small → breaks into 2–4 collectible ore chunks, and this is the moment the material is finally revealed (colored, with a scanner symbol if you have one)

Each fragment independently rolls its own material, so a single large rock can yield a genuine mix instead of being "a platinum asteroid" from the start. There's no cherry-picking by color; you have to commit to cracking a rock open to find out what's inside.
Materials
Material
Symbol
Base Price
Notes
Iron Ore
Fe
5 cr
Most common
Copper Ore
Cu
13 cr
Common
Silver Ore
Ag
32 cr
Uncommon
Gold Ore
Au
78 cr
Rare
Platinum Ore
Pt
155 cr
Very rare
Ruby
Ru
260 cr
Gem, very rare
Sapphire
Sa
260 cr
Gem, very rare
Diamond
Di
650 cr
Gem, extremely rare
Quantum Crystal
Qx
420 cr
Extremely rare
Dark Matter
Dm
20,000 cr
Special — see §9
Scrap Metal
Sc
90 cr
Corvette salvage only — see §17


Gems, Dark Matter, and gas clouds all glow or sparkle distinctly in space so a rare find catches your eye before you check what it is.
The Mining Laser
Hold SPACE to fire. Damage scales with proximity: point-blank shots deal up to 1.75× damage, while shots at the edge of your range fall to 0.65×. While locked onto something (laser or missile), a target-lock panel at the top of the screen shows its live HP/shield and your current proximity bonus.

The laser also damages pirates — see §7.
Tractor Beam
Once installed, hold SHIFT/CTRL to pull nearby loose ore toward your ship. Does not work on Dark Matter chunks — they're too dense. If you also own a Ram Scoop, the same key does both jobs at once, pulling in ore and extracting nearby gas simultaneously.
Cargo & the Manifest
Press I anytime to open your Cargo Manifest — a full breakdown of your Cargo Hold and, once you own a Ram Scoop, your separate Gas Tank (see §16). It pauses the game while open. This is also where you smelt ore once you have a Smelter installed (§10). If a pickup ever fails because your hold is full, you'll now get an explicit warning toast rather than the item silently vanishing with no explanation.


4. Energy
Your ship runs on a limited energy cell that powers the laser (13/s while firing), the Tractor Beam (9/s while active), and the Ram Scoop (7/s while active). Run it dry and those systems go dark until it recovers.

Idle regen is 2.4× faster than regen while actively running any of those systems.
Docking instantly refills your cell to full.
The energy bar glows and shows a ⚡ icon whenever it's actively recharging.


5. Ship Upgrades & Modules
Everything below is bought at Ceres Trade Anchorage under Ship Upgrades, unless noted otherwise.
Leveled upgrades (buy repeatedly, cost scales up)
Upgrade
Effect
Cap
Cargo Expansion
More cargo hold space
Unlimited
Mining Laser
More laser damage
Unlimited
Engine Core
Top speed, acceleration, turn rate
Unlimited
Hull Plating
Max hull integrity
Unlimited
Energy Cell
Energy capacity & regen rate
Unlimited
Tractor Beam
Pull range & strength
Level 4 (6 with a Faction perk)
Deflector Shield
Shield capacity & regen
Level 4 (6 with a Faction perk)
Mineral Scanner
Identifies revealed asteroid composition at range
Level 2 (full screen)
Gas Tank
Separate gas storage capacity
Unlimited (requires Ram Scoop first)
Mule Bay
Cargo hold for your Faction Escort
Unlimited (requires Escort Level 50)

One-time modules (milestone-gated, bought once)
Module
Unlock Condition
What it does
Missile Battery
Salvaged from a destroyed Frigate
Lets you fire missiles with Z (see §14)
Smelter
Captain Level 6
Refine raw ore into ingots (see §10)
Ram Scoop
15 Frigate kills (Frigate Bounty quest)
Collect gas from clouds in the Nebula (see §16)

Deflector Shield
Absorbs incoming damage — from asteroid collisions and enemy weapons fire — before it touches your hull. Regenerates a few seconds after you stop taking hits. Shows as its own bar in the HUD, plus a faint ring around your ship.
Mineral Scanner
Shows an element-symbol readout (Fe, Au, Pt...) on any asteroid once it's been revealed. Before revealing, scanned-but-unidentified rocks show a dim "?" so you know the module is working.


6. Captain & Crew
Captain Level
You gain XP from destroying asteroids and selling cargo. Leveling up heals you slightly and unlocks new station features at certain thresholds (Faction Relations at Level 3, the Smelter at Level 6).
Crew (up to 6)
Hire crew at the station's Crew Quarters. Each crew member has a role and levels up from your general XP gains (0.7× your rate). Hiring cost rises with each additional member.

Role
Bonus
Mining Officer
+laser damage
Navigator
+ship speed & turn rate
Quartermaster
+cargo capacity
Weapons Specialist
+missile damage & faster reload
Metallurgist
+ingot sale value
Gas Engineer
+Ram Scoop collection volume


Each role's bonus scales 6% per crew level, stacking with your ship upgrades.


7. Pirates
Pirates roam the field in three states: patrol, chase, and flee (after a successful hit-and-run). They show up as red radar blips, brightening once they've spotted you.

In range, they open fire on your hull (or shield, if you have one).
At close range, they attempt to steal cargo — grabbing a chunk of one random material from your hold, then fleeing. Destroy them before they escape and any stolen goods drop back as recoverable ore.
Fleeing pirates that get away vanish with a visible flash and a toast telling you whether they got away clean or empty-handed.
Asteroids block enemy fire. If a rock sits between you and an attacker, its shot hits the asteroid instead of you — a legitimate tactic against any enemy type in the game.
Asteroids also damage enemies on collision.
Destroying a pirate pays a credit bounty and XP.

HP (and shield, where applicable) is always visible above every hostile ship, and the target-lock panel confirms whatever you're actively engaging.
Tougher variants
Frigates (Deep Zone only) — 2× a pirate's HP, plus an 80-point shield, 1.6× the damage output, and 3× the bounty.
Corvettes (Nebula only) — see §17. The toughest standard enemy in the game.


8. The Faction Escort
Unlocked via the Escort Contract Faction perk (§11) — a permanent friendly gunship that trails your ship and grows alongside you.

Levels 1–50, gaining XP automatically at half your rate.
Level 25: starts mining nearby asteroids with its own laser when there's no pirate to fight.
Level 50: starts collecting loose ore chunks — needs a Mule Bay installed first.
Whenever it's near you with cargo aboard, it automatically hands its cargo over to you as space allows.
A level tag floats above it in-world — teal once mining-capable, amber once it can collect.
Combat: automatically engages the nearest hostile ship (of any type) within 550 units.


9. Dark Matter
The rarest, richest ore-type resource in the game. Only 2 deposits exist in the world at any time, spawned far from the station.

HP by tier: 10,000 (large) → 5,000 (medium) → 2,500 (small) — always splits cleanly into exactly 2 pieces at each stage.
Each small fragment yields exactly 2 collectible chunks.
Each chunk takes 100 cargo slots and sells for 20,000 credits.
Immune to the Tractor Beam. Fly right up and collect manually.
Unmistakable in the world: near-black with a pulsing indigo/violet glow — note this is a different hue from the Stargate (see §19).
The Deep Space Charts Faction perk reveals both deposits on your radar permanently.
Dark Matter Missiles (§14) are the dedicated tool for cracking these open faster.


10. Smelting (Metallurgist)
Once you install a Smelter (Level 6+, one-time purchase), refine raw metal ore into denser, more valuable ingots — from the Cargo Manifest (I), not the station.

Applies to the five metal ores only: Iron, Copper, Silver, Gold, Platinum. Gems, Crystal, Dark Matter, and gases can't be smelted.
10 raw ore → 1 ingot. The win is cargo space (10 slots → 1) plus a roughly 10% value premium per unit refined.
Batch buttons smelt 10, 20, 50, or 100 at once, right in the Manifest.
A Metallurgist crew member adds a further bonus to ingot sale value.


11. Faction Relations
Unlocks at Captain Level 3. A station tab where you trade goods or credits for Faction Points (FP) and build reputation — and where both major quests in the game are tracked.

Earning FP:

Gold Ore Tribute — donate your entire Gold Ore hold for 15 FP per unit
Credit Contribution — 500 credits for 12 FP (hold-to-repeat supported)

Rank (based on lifetime FP earned — spending doesn't lower it):

Unaffiliated → Associate → Trusted Contractor → Veteran Partner → Elite Operative → Legendary Benefactor

Perks:

Perk
Requires
Cost
Effect
Trade License
Associate
150 FP
10% off all ship upgrades
Tractor Overcharge Clearance
Trusted Contractor
300 FP
Raises Tractor Beam cap to 6
Shield Overcharge Clearance
Trusted Contractor
300 FP
Raises Shield cap to 6
Deep Space Charts
Veteran Partner
500 FP
Always shows Dark Matter on radar
Escort Contract
Elite Operative
900 FP
Unlocks the Faction Escort ally ship



12. Quest: The Frontier Trial → Stargate & Deep Zone
Tracked automatically in the Faction tab:

Destroy 5 pirates
Collect 1 Dark Matter chunk
Reach Veteran Partner Faction rank

Completing all three spawns the first Stargate (indigo/blue) at a fixed, distant point in the world. Fly up and press E to activate it, warping between the normal system and the Deep Zone.
The Deep Zone
No Ceres station. The only place to sell or resupply is the Black Market Relay (§13).
Frigates patrol here instead of ordinary pirates.
A second gate activation warps you home.


13. Black Market Relay
A fence-run outpost in the Deep Zone (amber/rust structure). Dock with E.

Sells cargo at 80% of market price.
Sells both missile ammo types (§14) at marked-up prices.
Refuels your energy on dock.
No ship upgrades, crew hiring, or Faction access here.


14. Missiles
Fired with Z — the launcher automatically figures out what to shoot.
Getting a launcher
Not for sale anywhere. It's a rare drop (25% chance) from a destroyed Frigate.
Two ammo types, one 30-slot bay
Type
Bay Cost
Damage
Notes
Ship Missile
1 slot
Scales with upgrades/crew
Homes in on any hostile ship
Dark Matter Missile (DMM)
10 slots
20% of target's max HP
Only targets Dark Matter, hard-capped at 3 carried


You can carry 3 DMM alone, or 2 DMM + 10 ship missiles, or any mix respecting both limits.

Auto-targeting: a Dark Matter deposit in range with DMM in stock takes priority; otherwise it fires a ship missile at the nearest hostile.
Getting ammo
Not sold at Ceres. Instead: any destroyed pirate/Frigate/Corvette has a chance to drop 1–3 ship missiles; Frigates and Corvettes specifically have a smaller chance to drop a DMM. Both types are also purchasable at the Black Market Relay.


15. Quest: Frigate Bounty → Ram Scoop & the Nebula Gate
A second standing contract, accepted separately from the Frontier Trial, also in the Faction tab.

Open the Faction tab and click Accept Contract on the Frigate Bounty card.
Destroy 15 Frigates in the Deep Zone. Kills you already had before accepting still count.
Once accepted, a live X/15 tracker appears in your main HUD (below your credit total) so you don't need to check the menu to see progress.

Hitting 15 unlocks two things at once:

The Ram Scoop becomes purchasable at Ceres.
A second Stargate (teal) spawns in the Deep Zone, leading to the Nebula.


16. The Nebula, Gas Clouds & Ram Scoop
The Nebula is reached via the teal Stargate found in the Deep Zone. No ore mining here — it's a dedicated gas-collection zone, patrolled by Corvettes (§17) instead of Frigates.
Ram Scoop
A ship module (one-time purchase) that adds visible twin pylons to your ship. Hold SHIFT/CTRL near a gas cloud to extract gas — same key as the Tractor Beam, and both can run at once if you own both modules.
Gas Clouds
Diffuse, colored regions with a depleting volume — unlike asteroids, their composition is visible immediately (no reveal mechanic). The cloud visibly shrinks as you drain it, and a live volume readout (320/750) floats above it at all times. While actively scooping, the on-screen target-lock panel shows exactly what you're extracting and how full your tank is getting.
Gas Tank — a separate pool from your Cargo Hold
Gas has its own dedicated capacity, entirely independent of your ore/gem cargo hold — filling one never eats into the other. Buying the Ram Scoop grants a starter tank for free; a separate Gas Tank upgrade at the station grows it further. Your HUD shows a second bar for it once you own the scoop, and the Manifest shows both totals side by side.
Gas types
Gas
Symbol
Price
Rarity
Hydrogen
H
4 cr
Very common
Helium
He
9 cr
Common
Nitrogen
N
22 cr
Uncommon
Methane
CH4
45 cr
Uncommon
Neon
Ne
180 cr
Rare
Xenon
Xe
500 cr
Very rare


A Gas Engineer crew member increases how fast you extract, on top of ship upgrades.

If your tank is full, the scoop stops draining the cloud entirely (so you're not wasting it) and warns you with a toast — the same protection now applies to a full Cargo Hold when picking up ore, gems, or Scrap Metal.


17. Corvettes & Scrap Metal
The Nebula's patrol force, and the toughest standard enemy in the game.

Roughly 2× a Frigate: ~152 HP, a 140-point shield, and higher damage output.
Rendered as a large hexagonal hull in cool gray-blue — visually distinct from the arrow-shaped pirates and Frigates.
Pays a 5× bounty — the highest of any standard kill.
On destruction, always drops 2–5 Scrap Metal chunks at the wreck site — a physical pickup (fly in or Tractor Beam it), landing in your regular Cargo Hold, not the Gas Tank.
Like Frigates, Corvettes have a chance to drop ship missile ammo, and a smaller chance to drop a Dark Matter Missile.

Scrap Metal is currently sellable like any other material; a dedicated use for it is planned but not yet implemented.


18. Combat Feedback
HP (and shield, where applicable) is always visible above every hostile ship.
The target-lock panel at the top of the screen shows live status for whatever you're engaging — laser, missile, or (in the Nebula) your Ram Scoop — including your proximity damage bonus while lasering, and combined Cargo Hold/Gas Tank totals whenever you're tractoring or scooping anything.
Damage sounds differ: a soft ping for a shield absorb, a harsher thud for actual hull damage.
Explosions, missile launches/impacts, and escapes all have distinct sound and visual cues.


19. Radar
Bottom-right of the HUD. Color key:

Cyan blip — Ceres station (normal zone only)
Amber blip — Black Market Relay (Deep Zone only)
Indigo/blue blip — the original Stargate (normal ↔ Deep Zone)
Teal blip — the Nebula Gate (Deep Zone ↔ Nebula)
Violet — Dark Matter deposits (with Deep Space Charts)
Red blips — hostile ships, brightening once locked onto you
Colored dots — nearby identified asteroids, or gas clouds while in the Nebula
Amber triangle at center — you, rotating with your facing direction

A distance readout at the bottom always points to your nearest relevant point of interest for your current zone.


20. Sound
Every sound is synthesized in real time — no audio files. Laser hum (a pulsing, detuned dual-tone beam), engine rumble while thrusting, asteroid cracks, ore/gas pickup chimes, missile launches and explosions, level-up fanfares, docking tones, sale chimes, purchase clicks, a smelting crunch, stargate warp sweeps, and damage/warning cues. Toggle everything with the speaker icon (🔊/🔇) in the top HUD.


21. Saving Your Progress
The game autosaves continuously and detects its environment automatically:

Playing inside Claude's interface: progress saves to Claude's built-in persistent storage, tied to your account.
Playing as a standalone file (downloaded and opened directly in a browser — the situation if someone sends you this .html file): the game automatically falls back to your browser's local storage instead. This works completely offline and needs no account — progress is saved on that specific computer, in that specific browser, as long as browser data isn't cleared.

Sharing this with someone else: yes, they can open the file as-is and it will save their progress locally on their machine — no setup required. A few practical notes:

Each browser/device keeps its own separate save — it doesn't sync between people or computers.
If they later clear that browser's site data/history, the save is lost, same as any browser-based game.
The reset save data link on the title screen only clears that one browser's save.


22. Quick Tips
Don't cherry-pick by color — nothing's identified until you crack a rock down to its smallest pieces.
Coast between bursts to let energy regen faster; docking is the only way to refill it instantly.
Hide behind asteroids against any enemy type — let their own weapon do your mining for you.
Gold is worth more to the Faction than to a buyer in the long run.
Smelt before you haul — 10 ore for 1 ingot frees up massive cargo space.
A Dark Matter deposit is a multi-trip commitment, especially early on.
Frigates and Corvettes hit hard — bring a shield, and save DMM specifically for Dark Matter rather than burning bay space you might need for ship missiles.
Gas and cargo are separate now — filling your Gas Tank won't block ore pickups, and vice versa, so manage them independently.
Accept the Frigate Bounty early if you're planning to fight Frigates anyway — the kills count retroactively, so there's no downside to accepting it the moment you unlock Faction Relations.

