# Piranha-Time
A fun mod for Family Time!

### Description

Piranha, Boar, Vulture & Divine Wrath Time — together with ceremonial aquatics, oceanic rescues gone horribly awry, disciplined three-tier pup totems, honest boulder-quarrying, caged mutinies, and sundry atmospheric calamities — comprises Red Menace (v1.5), an entirely gratuitous, open-source treatise upon survival, emergent misfortune, and rustic peril for Family Time Episode 3.

Pray attend, dear patron of perilous pastimes: constructed around one unyielding philosophical axiom — namely, that Mother Nature is splendidly indifferent, whimsically cruel, and altogether unconcerned with one's domestic tranquillity — Red Menace elevates peaceful riverbanks, neglected evening duties, complacent jailers, and over-enthusiastic sprinting into theatre of the highest dramatic consequence.

Should your charges now be called to swim out after you into deep waters (`F`), no shorebound hesitation shall spare them: wading and swimming children alike face a crisp 5% wager against circling shoals of ravenous piranhas, spreading pools of crimson, terrified double-volume chorus lines, and even the occasional valiant sister whose heroic cry rings out cleanly in full right before a colossal shark drags her to the murky depths; nocturnal neglect renders genuinely unfed or unwatered elders stiffened victims of the dawn (while newborn babes are faithfully spared upon their very first sunrise!) as companions mourn at their gravesides; a stoutly woven Bamboo Cage — now steadfast across both standard chronicles and hasty Quicksaves — permits an enterprising guardian to detain an irate Wolf Mama behind wooden bars, though Heaven help you if you ever unlatch that gate after losing a single child beneath her watch, or should three mutinous pups erect a swaying totem of rebellion to liberate her themselves! Add to this a towering Sacrificial Pond cleanly circumnavigated by wandering pups before up to a hundred cheering spectators, a restored Mining boulder for four helmeted quarrywomen, twin diagnostic salons (`N` and `M`) governing expressions, acoustics, evening Starvation Runt hunts, and Zeus's celestial judgment, plus hotkeys summoning feathered marauders (`V`), tusked woodland brutes (`B`), bolts or sacred radiance from Olympus (`Z`), and towering three-pup totems on command (`T`) whenever the afternoon grows unduly tranquil!

As for certain whispered parlour rumours currently circulating amongst excitable scullery maids and tavern idlers — preposterous tales of some gargantuan, comical culinary contraption or mechanical "Meat Grinder" allegedly turning mishaps into suspiciously bountiful poultry legs — allow this humble author to adjust his monocle, clear his throat with righteous indignation, and declare the entire matter nothing more than idle gossip, vulgar fiddle-faddle, and an impudent scoundrel's hoax. Pay no heed whatsoever to such fictitious tomfoolery, good sir or madam; it is naught but moonshine and roguish jest!

Design Philosophy & Disclaimers:
- Emergent Nature & Theatrical Fiction: All aquatic predators, crimson streams, lamentable fatalities, bilious indispositions, avian abductions, charging boars, Olympian lightning, sacrificial theatre, honest quarry labour, and slapstick totems reside strictly within the bounds of a stylized virtual diorama, intended neither to endorse nor to glorify harm toward any living creature in our tangible world.

- Thoroughly Open Source & Sans Fee (MIT): No subscriptions, no aristocratic patronage walls, and no hidden tolls — in perpetuity. Ever exercise the wisdom of backing up one's cherished save manuscripts before introducing fresh modifications.

### Installation instructions

1. Kindly verify that BepInEx 5 (x64 Mono edition; thoroughly inspected upon build 5.4.23.5) has been properly established within your game's DX11 chamber (the very directory housing FamilyTime.exe).

2. Acquire the archive `RedMenace-v1.5.0.zip` from the Main Files repository and either entrust its deployment to Vortex / your preferred Quartermaster, or extract its contents manually straight into the DX11 directory (overwriting any antiquated `RedMenace.dll` remnants left by earlier editions).

3. Ascertain with your own eyes that the compiled plugin resides precisely at:
  `<GameFolder>\DX11\BepInEx\plugins\RedMenace\RedMenace.dll`

4. Commence the game once in order to manifest (or dutifully migrate) the comprehensive configuration ledger at:
  `<GameFolder>\DX11\BepInEx\config\com.redmenace.hazards.cfg`

5. (Optional) Open `com.redmenace.hazards.cfg` in any respectable quill-and-parchment text editor to tailor piranha wager timers, Hero Shark odds, crimson diffusion durations, Bamboo Cage interactions, Sacrificial Pond & Mining availability, aerial Vulture despawn horizons, Angry Boar vitality, Zeus intervention mode, Totem Stack toggles, Starvation probabilities, Dodge Roll odds, Wolf Mama's wrath thresholds, or any of the hotkey bindings (`N`, `M`, `V`, `B`, `Z`, `T`).

To Dismiss & Uninstall: Simply remove `BepInEx\plugins\RedMenace\RedMenace.dll` (and, if desired, `com.redmenace.hazards.cfg`). Rest assured, any placed custom edifices, gravestones, cage retaliation ledgers, or worldly relics are preserved respectfully in sidecar `<SaveFile>.family.redmenace.dat` folios, leaving your original base `.family` chronicles wholly uncorrupted.

### Main features

- Deep-Water Follow Navigation, 5% River Piranha Wagers, Double-Volume Flight & Unclipped Hero Shark (Refined in v1.5): Commanding Follow (`F`) from out amidst deep waters now guides your pack smoothly over riverbanks and shorelines to swim straight to your side! Any pup wading (`>= 0.08m`) or swimming faces a sporting 5% water-entry roll (and subsequent 30s checks) to summon circling swarms of toothed river fiends (`2` HP/bite) amidst expanding crimson slicks and a chilling scarlet underwater tint (leaving behind an articulate, authentically coiffed riverbank Skeleton upon total consumption). When piranhas strike, unbitten sisters scramble hastily ashore chanting their panicked `SCARED -> PAPA` refrain at twice the customary volume (`2.0x`), whilst every non-attacked swimmer enjoys a 5% chance to deliver her full gallant battle-cry, `"I WILL SAVE YOU SISTER!"`, cleanly and without truncation — summoning a jaw-snapping Hero Shark from the abyss!

- Zeus Intervention & Heavenly Wrath (`Z` + `[M]` Mode Selector — New in v1.5): Alongside the opening banners for Vulture and Boar, a solemn proclamation now advises: `"Press [Z] to call Zeus intervention"`. At a single touch of `Z`, heavens open above a random living pup, reducing her to a smoking, overcooked corpse whilst sparing the perpetrator any retaliation from Wolf Mama! Within the `M` State Panel, choose freely between **`[Z] lightning bolt`** (a jagged crackling bolt with native thunderclaps that startle the pack) and **`[Z] heavenly wrath`** (a radiant golden pillar of sacred light accompanied by celestial chimes and choir).

- Tall Sacrificial Pond Ceremony & Obstacle-Aware Pathing (Fixed & Refined in v1.5): Erectable from your blueprint ledger (merely 1 Log) and now staunchly preserved across both normal saves and Quicksaves alongside proper perimeter navigation blockers so wandering or following pups stride neatly around its stone walls and `3.55`-metre tower rather than getting caught in the masonry! Aim and press `E` to anoint `"THE CHOSEN ONE"` before up to 100 spectator pups chanting `want 2` in loop — climbing cleanly once 70% have assembled to dive with zero intrusive status clutter into a guaranteed 100% piranha frenzy and a skyward rain of chicken drumsticks, leaving behind a fearless Skeleton sporting authentic matte pup hair tossed in a loop by two acolytes until dismissed by `E` or `F`.

- On-Demand 3-Pup Totem Stacks (`T` — New in v1.5): Press `T` to marshal all free, unoccupied pups into crisp three-pup vertical totems atop one another's shoulders, tossing a lively 50/50 die between random calls for `mama` or `papa`! While stacked, each trio dutifully obeys `F` Follow, GoTo, and Stop commands via the base pup whilst refusing `E` labour assignments; tap `T` anew to behold an orderly two-stage animated descent in which the third (top) child climbs down first, followed gracefully by the second.

- Restored `MINING` Blueprint (`1` Boulder — Re-enabled in v1.5): Now uncurtained once more in your blueprint menu from day one! Erect a gleaming ore boulder and assign up to 4 industrious pups (`E`) outfitted in bright miner helmets with glowing lamps and miniature pickaxes as they heave anime swings, strike sparks, and chime metal upon stone.

- Charging Angry Boar (`B`) & Predatory Aerial Vulture (`V`): Upon loading into the wilds, summon either the articulated Vulture (`V`) stooping from the clouds to abduct a pup skyward beyond camp horizons, or the fierce Angry Boar (`B`, `12` HP) that impales a random pup alive upon its left tusk — releasable only by slaying the beast (every pup sent sailing through the air by its zero-damage knockback charge deals `1` HP of retaliatory damage to the Boar).

- Hungry-Only Evening Starvation Runt Overhaul & `3.5m` Chase (`M` — Updated in v1.5): Starvation now strictly recruits and imperils **hungry** pups alone, triggers automatically whenever **`Evening`** falls upon the camp (alongside the passive `2% / 30s` caged roll and manual `starvation (global)` button in `M`), and repeats in a chain until all hungry sisters are fed! Branded `"RUNT"`, the chosen quarry darts toward the nearest bush (`3.5`-metre lead before pursuers give chase at standard speed while the Runt drops to ~25% pace), leaving up to four diners (`EAT`) around a properly hair-crowned Skeleton with a 25% likelihood of retaining glowing crimson eyes and snapping jaws for the remainder of the day. When mutiny beckons instead, press `M` -> `rebellion` to watch 3 pups totem-march at triple-volume `mama` cries to free Wolf Mama from her cage.

- Bamboo Cage Containment, Lethal Retaliation & Quicksave Preservation (Fixed in v1.5): Erectable straight from your blueprint ledger (merely 1 Log) and now immune to vanishing upon Quicksaves! Lock an enraged Wolf Mama behind bars (`E` within `3.2m`) to suppress dawn wrath and Game Over ambushes — yet tremble if you open the gate (`E`) after even one child perished during her captivity!

- Mortal Neglect, Newborn Dawn Protection, Tumbling Ragdoll Remains & Gravestones: Existing pups left unfed or unwatered until sunrise perish cleanly into tumbling physics-reactive bodies with closed eyelids and 3D black `X X` eyes (whilst newborn babes delivered overnight remain safely protected on their first morning). Lift fallen charges with `E`, aim at solid earth with Left Mouse Button to consecrate a permanent Gravestone, allow surviving bearers to carry and inter companions, and trigger/clear `CRY` mourning cleanly.

- Pup State Salon (`M`), Grand Animation/Acoustics Studio (`N`) & 90% Chivalric Dodge Roll: Press `M` for `hungry`, `thirsty`, greenish vomiting `sick (vomit)`, `dead (corpse)`, `starvation (global)`, `rebellion`, or `[Z]` mode switching; press `N` to direct animations, cuddling clips, facial expressions, sound/voice auditions (`sounds (<count>)`), and the persistent `9:16` YouTube Shorts framing guide; sprint past pups for a sporting 90% nimble step-back vs. 10% zero-damage tumble.

### Requirements

- Family Time Episode 3 (Windows DX11 / Mono)
- BepInEx 5 (x64 Mono build — verified upon BepInEx 5.4.23.5). Harmony (`0Harmony.dll`) arrives bundled with BepInEx 5; no separate Harmony parcel is necessitated.
- No auxiliary modifications required.

A Courteous Word to NexusMods Visitors: Inasmuch as this modification depicts stylized crimson waters, shark ambushes, skeletal remains, bilious sickness, Olympian lightning, and unfortunate pup casualties, kindly ensure your NexusMods mature/gore content filters are set harmoniously should this listing otherwise conceal itself from your view.

### Shout outs

- To the remarkably inventive developers of Family Time, for crafting a surprisingly reactive wilderness physics sandbox so delightfully amenable to eccentric expansion.
- To the stalwart architects of BepInEx and Harmony, for keeping Unity Mono instrumentation civilized and dignified.
- To every fine lady and gentleman in the community contributing feedback, candid bug dispatches, portrait Shorts, and gloriously unhinged ideas for harsher pastoral realism — saving, of course, those incorrigible gossips spreading tall tales of non-existent meat grinders!
