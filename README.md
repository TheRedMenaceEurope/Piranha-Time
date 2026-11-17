# Piranha-Time
A fun mod for Family Time!

### Description

Piranha, Boar & Vulture Time — together with ceremonial aquatics, oceanic rescues gone horribly awry, caged mutinies, and sundry atmospheric calamities — comprises Red Menace (v1.4), an entirely gratuitous, open-source treatise upon survival, emergent misfortune, and rustic peril for Family Time Episode 3.

Pray attend, dear patron of perilous pastimes: constructed around one unyielding philosophical axiom — namely, that Mother Nature is splendidly indifferent, whimsically cruel, and altogether unconcerned with one's domestic tranquillity — Red Menace elevates peaceful riverbanks, neglected evening duties, complacent jailers, and over-enthusiastic sprinting into theatre of the highest dramatic consequence.

Should your charges dare paddle into deep waters, every half-minute brings a perilous wager against circling shoals of ravenous piranhas, spreading pools of crimson, terrified double-volume chorus lines, and even the occasional valiant sister whose heroic cry summons a colossal shark from the murky depths; nocturnal neglect renders genuinely unfed or unwatered elders stiffened victims of the dawn (while newborn babes are now properly spared upon their very first sunrise!) as companions mourn at their gravesides; a stoutly woven Bamboo Cage permits an enterprising guardian to detain an irate Wolf Mama behind wooden bars — though Heaven help you if you ever unlatch that gate after losing a single child beneath her watch, or should three mutinous pups erect a swaying totem of rebellion to liberate her themselves! Add to this a towering Sacrificial Pond before up to a hundred cheering spectators, twin diagnostic salons (`N` and `M`) governing expressions, acoustics, ailments, and famine, and hotkeys summoning both feathered marauders (`V`) and tusked woodland brutes (`B`) whenever the afternoon grows unduly tranquil!

As for certain whispered parlour rumours currently circulating amongst excitable scullery maids and tavern idlers — preposterous tales of some gargantuan, comical culinary contraption or mechanical "Meat Grinder" allegedly turning mishaps into suspiciously bountiful poultry legs — allow this humble author to adjust his monocle, clear his throat with righteous indignation, and declare the entire matter nothing more than idle gossip, vulgar fiddle-faddle, and an impudent scoundrel's hoax. Pay no heed whatsoever to such fictitious tomfoolery, good sir or madam; it is naught but moonshine and roguish jest!

Design Philosophy & Disclaimers:
- Emergent Nature & Theatrical Fiction: All aquatic predators, crimson streams, lamentable fatalities, bilious indispositions, avian abductions, charging boars, sacrificial theatre, and slapstick mutinies reside strictly within the bounds of a stylized virtual diorama, intended neither to endorse nor to glorify harm toward any living creature in our tangible world.

- Thoroughly Open Source & Sans Fee (MIT): No subscriptions, no aristocratic patronage walls, and no hidden tolls — in perpetuity. Ever exercise the wisdom of backing up one's cherished save manuscripts before introducing fresh modifications.

### Installation instructions

1. Kindly verify that BepInEx 5 (x64 Mono edition; thoroughly inspected upon build 5.4.23.5) has been properly established within your game's DX11 chamber (the very directory housing FamilyTime.exe).

2. Acquire the archive `RedMenace-v1.4.0.zip` from the Main Files repository and either entrust its deployment to Vortex / your preferred Quartermaster, or extract its contents manually straight into the DX11 directory (overwriting any antiquated `RedMenace.dll` remnants left by earlier editions).

3. Ascertain with your own eyes that the compiled plugin resides precisely at:
  `<GameFolder>\DX11\BepInEx\plugins\RedMenace\RedMenace.dll`

4. Commence the game once in order to manifest (or dutifully migrate) the comprehensive configuration ledger at:
  `<GameFolder>\DX11\BepInEx\config\com.redmenace.hazards.cfg`

5. (Optional) Open `com.redmenace.hazards.cfg` in any respectable quill-and-parchment text editor to tailor piranha wager timers, Hero Shark odds, crimson diffusion durations, Bamboo Cage interactions, Sacrificial Pond availability, aerial Vulture despawn horizons, Angry Boar vitality, Starvation probabilities, Dodge Roll odds, Wolf Mama's wrath thresholds, or any of the hotkey bindings (`N`, `M`, `V`, `B`).

To Dismiss & Uninstall: Simply remove `BepInEx\plugins\RedMenace\RedMenace.dll` (and, if desired, `com.redmenace.hazards.cfg`). Rest assured, any placed custom edifices, gravestones, cage retaliation ledgers, or worldly relics are preserved respectfully in sidecar `<SaveFile>.family.redmenace.dat` folios, leaving your original base `.family` chronicles wholly uncorrupted.

### Main features

- 5%/30s River Piranha Wagers, Double-Volume Flight & the Valiant Hero Shark (Overhauled in v1.4): Pups venturing into deep water face a sporting 5% dice roll every 30 seconds to summon rapid circling swarms of toothed river fiends (`2` HP/bite) amidst expanding crimson slicks and a chilling scarlet underwater tint (leaving behind an articulate riverbank Skeleton upon total consumption). When piranhas strike, unbitten sisters scramble hastily ashore chanting their panicked `SCARED -> PAPA` refrain at twice the customary volume (`2.0x`), and every non-attacked swimmer enjoys a 5% chance to pipe up with her gallant cry, `"I WILL SAVE YOU SISTER!"` — immediately drawing a jaw-snapping Hero Shark from below to drag both rescuer and destiny into the dark abyss!

- Tall Sacrificial Pond Ceremony — Tribute to the Piranha GOD (New in v1.4): Erectable from your blueprint ledger (requiring merely 1 Log), this towering `3.55`-metre diving platform and ladder overhangs a deepened piranha-infested basin (`[E] Sacrifice a Pup to the Piranha GOD`). Pressing `E` anoints the chosen candidate `"THE CHOSEN ONE"` and summons up to 100 spectator pups into a tidy semicircular gallery chanting `want 2` in loop. Only once 70% of the congregation has taken its seat does THE CHOSEN ONE ascend the ladder, spring off with a sprightly `hop`, and plunge into a 100% guaranteed piranha frenzy (sparing bystanders any panic or Hero Shark intrusion) to bless the glade with a skyward rain of chicken drumsticks — leaving behind a fearless Skeleton joyfully juggled aloft by two acolytes while the audience continues cheering `want 2` until you personally grant dismissal via any `E` or `F` command (short or long press).

- Charging Angry Boar (New in v1.4 — Hotkey: B) & Predatory Aerial Vulture (Hotkey: V): Upon loading into the wilds, a stately 10-second proclamation announces both `"PRESS [V] to call a Vulture"` and directly beneath it `"PRESS [B] to summon an Angry Boar"`. Summoning the Vulture (`V`) brings the articulated dark raptor stooping down from the clouds to snatch a pup skyward until vanished beyond the horizon; pressing `B` unleashes a fierce native Angry Boar (`12` HP) that promptly impales a random pup alive upon its left tusk! The hapless hostage may only be freed by vanquishing the Boar — and every pup sent sailing through the air by its zero-damage knockback charge inflicts `1` HP of retaliatory injury upon the beast.

- Bamboo Cage Containment & Lethal Retaliation (Updated in v1.4): Erectable straight from your blueprint ledger (merely 1 Log), this stout bamboo enclosure lets you lock an enraged Wolf Mama behind bars (`E` within `3.2m`), keeping her red-eyed `standing_scare` fury safely contained whilst suppressing sleep punishment scenes and Game Over ambushes. However, beware the v1.4 reckoning: should even one pup perish whilst Wolf Mama languishes in custody, throwing open the cage latch (`E`) shall instantly unleash her fatal execution upon your person!

- Caged Starvation Runt Cycles & 3-Pup Rebellion Mutinies (`M`) (New in v1.4): Whenever Wolf Mama sits imprisoned and hunger besets the pack, a grim 2% die rolls every 30 seconds (or summon immediately via `M` -> `starvation (global)`) to brand one child `"RUNT"`: hungry sisters hunt down the Runt, up to four feast (`EAT`) upon the remains until a skeleton rests beside them, and those diners emerge newly fed. Tired of tyranny? Press `M` -> `rebellion` to watch 3 random pups clamber atop one another into a wobbling three-tier bucket-carry totem, bellowing `mama` at triple volume (`3x`) as they march upon the Bamboo Cage to free Wolf Mama and set her upon you (automatically suspending Starvation events whilst a mutiny is underway).

- Mortal Neglect, Newborn Dawn Protection, Tumbling Ragdoll Remains & Gravestones (Fixed & Refined in v1.4): Existing pups left unfed or unwatered until sunrise perish cleanly into tumbling physics-reactive bodies with closed eyelids and 3D black `X X` eyes (whilst newborn babes delivered overnight are now faithfully protected on their first morning!). Lift fallen charges with `E`, aim at solid earth with Left Mouse Button to consecrate a permanent Gravestone, allow two surviving pups to bear the burden together (or aim `E` to bury during transit), and rally up to four mourners upon any monument with `E` — whilst `E` or `F` commands cleanly break both proximity `CRY` mourning and ceremonial loops.

- Pup State Salon (`M`) & Grand Animation/Acoustics Studio (`N`): Press `M` to administer `hungry`, `thirsty`, greenish vomiting `sick (vomit)`, `dead (corpse)`, `starvation (global)`, or `rebellion`; press `N` to direct GPU animations, cuddling clips, facial expressions, and sound/voice auditions (`sounds (<count>)`) with loop toggles and a persistent `9:16` YouTube Shorts framing guide. *(Note: The experimental Mine blueprint remains politely curtained away for future refinements.)*

- Brisk Paternal Sprinting & 90% Chivalric Dodge Roll: Dashing heedlessly through your pack rolls a sporting 90% nimble dodge check; the nimble avoid collision with a startled hop, whilst the clumsy 10% suffer a harmless, boar-styled head-over-heels tumble with zero HP lost.

### Requirements

- Family Time Episode 3 (Windows DX11 / Mono)
- BepInEx 5 (x64 Mono build — verified upon BepInEx 5.4.23.5). Harmony (`0Harmony.dll`) arrives bundled with BepInEx 5; no separate Harmony parcel is necessitated.
- No auxiliary modifications required.

A Courteous Word to Visitors: Inasmuch as this modification depicts stylized crimson waters, shark ambushes, skeletal remains, bilious sickness, and unfortunate pup casualties, kindly ensure your NexusMods mature/gore content filters are set harmoniously should this listing otherwise conceal itself from your view.

### Shout outs

- To the remarkably inventive developers of Family Time, for crafting a surprisingly reactive wilderness physics sandbox so delightfully amenable to eccentric expansion.
- To the stalwart architects of BepInEx and Harmony, for keeping Unity Mono instrumentation civilized and dignified.
- To every fine lady and gentleman in the community contributing feedback, candid bug dispatches, portrait Shorts, and gloriously unhinged ideas for harsher pastoral realism — saving, of course, those incorrigible gossips spreading tall tales of non-existent meat grinders!
