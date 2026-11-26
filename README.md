PIRANHA TIME 2: THE REVENGE (v1.2 — THE GRAND VICTORIAN EDITION)
A BepInEx 5 Treatise on Wilderness Peril & Chaos for Family Time Episode 4

Dear Reader,

Nature is splendidly indifferent, whimsically cruel, and altogether
unconcerned with one's afternoon tea. Piranha Time 2: The Revenge
(RedMenaceRevenge.dll) bestows upon Family Time Episode 4 the complete
wilderness calamity suite — and pushes the delightful madness further still.
Pray read on with a stout heart and a steady teacup.

--------------------------------------------------------------------------------
I. THE WATERS, THE PIRANHAS & THE HERO SHARK
--------------------------------------------------------------------------------
* Deep-Water Follow Pathfinding: Commanding Follow [F] whilst standing or
  swimming in deep water guides your pups cleanly off riverbanks and shorelines
  so they swim straight out to attend you.
* River Piranha Swarms (5%): Pups wading (>= 0.08m) or swimming in natural
  waters roll a 5% chance upon entry (and every 30s thereafter) to summon up to
  8 circling, biting piranhas per pup (2 HP every 0.70s).
* Pack Flight & Hero Shark (5%): During an attack, unbitten sisters flee ashore
  crying SCARED -> PAPA at double volume, whilst each bystander pup has a 5%
  chance to bellow "I WILL SAVE YOU SISTER!" before a Hero Shark drags her down
  into the abyss.
* Blood Water & Toggle: Injuries tint the waters crimson (toggleable at will
  from the [M] Pup Control Panel via the Blood ON/OFF switch).

--------------------------------------------------------------------------------
II. CAMPFIRE IGNITION, DYING CRAWL & WATER SALVATION
--------------------------------------------------------------------------------
* Igniting by Campfire: Leaving a pup atop a campfire sets her ablaze once the
  vanilla bounce concludes. She dashes frantically within 15m of Father,
  alternating every 10s between panicked screams (STARTLE) and zoomies
  (RUN_FRENZY with long wee3 / long wee7).
* Contagion & Collapse: Bumping a sister carries a 50% chance of spreading the
  flame (after 45s without contact, burning pups actively seek the nearest
  sister). After 60s ablaze, she collapses into a non-lethal Dying ("morente")
  crawl — lying belly-down, smoking, and creeping toward the nearest river or
  pond without arousing Wolf Mama's wrath.
* Water Cure: Reaching natural water or a Sacrificial Pond extinguishes the
  flames and restores the pup to full vigour.

--------------------------------------------------------------------------------
III. WOLF MAMA'S SPIRAL-EYED CAULDRON RITUAL
--------------------------------------------------------------------------------
* Whenever a pup corpse rests within 10m of Wolf Mama, she approaches at a
  measured gait, adopts dizzying spiral eyes with a solitary bewildered "woah",
  performs pup_carry_auto_grab, and marches straight to the nearest lit,
  watered, meatless cauldron — depositing the remains for the equivalent of
  100 chicken drumsticks (matching player-tossed cauldron corpses).

--------------------------------------------------------------------------------
IV. COMPACT IRON PUP CONTAINMENT ("PUP CAGE", 1 LOG)
--------------------------------------------------------------------------------
* Cramped Waterless Iron Cell: Unlocked from day one for 1 Log (0.56m x 0.56m
  x 0.78m, forged cleanly without unsightly water bottles).
* Bar-Rattling Custody & Visible Nameplate [E]: Aim within 4.0m and press [E],
  or toss/drop a carried pup past the gate, to shut the brass-padlocked door.
  Inside, the pup retains her live overhead nameplate, gazes straight forth with
  wide mournful eyes and chattering teeth, shivers continuously at 14-18 Hz, and
  clasps both front bars in periodic cage-rattling panic bursts until freed [E].

--------------------------------------------------------------------------------
V. THE BAMBOO CAGE, RETALIATION & SAVE PERSISTENCE
--------------------------------------------------------------------------------
* Bamboo Cage (1 Log): Unlocked from the outset. Lead Wolf Mama within 3.2m and
  press [E] to imprison her behind bars with glowing red eyes, halting rage
  points, angry sleep sequences, and Game Over triggers.
* Retaliation: Should any pup perish while Wolf Mama languishes in captivity,
  re-opening the cage with [E] immediately unleashes her fury upon the player.
* Save Sidecar: Custom blueprints, Bamboo & Pup Cages, retaliation flags,
  gravestones, and corpses persist across normal saves and Quicksaves in an
  adjacent <SaveFile>.family.redmenace.dat file.

--------------------------------------------------------------------------------
VI. CONSTRUCTIONS: THE SACRIFICIAL POND & THE MINING SITE
--------------------------------------------------------------------------------
* SACRIFICIAL POND (1 Log): Erects a clear basin beneath a 3.55m diving ladder
  and springboard. Aim and press [E] to anoint THE CHOSEN ONE, gathering up to
  100 chanting spectators before she plunges into a 100% piranha frenzy,
  triggering a skyward rain of Chicken Drumsticks and leaving a pup-haired
  skeleton tossed by two acolytes until dismissed via [E] or [F].
* MINING (1 Boulder): Assign up to 4 pups via [E] to don glowing miner helmets
  and pickaxes, striking the ore boulder amidst metallic clangs and sparks.
* Hairbrush & Coiffure: The Hairbrush blueprint requires but 1 Fresh Grass
  bundle, and every hairstyle is unlocked from the very first moment.

--------------------------------------------------------------------------------
VII. SKY, BEAST & DIVINE INTERVENTIONS ([V], [B], [Z], [T])
--------------------------------------------------------------------------------
* [V] Vulture or Stork (selectable in [M]):
  - Vulture Mode: A circling raptor swoops from the heavens to abduct a pup.
  - Stork Mode: A noble black-and-white Stork glides in carrying a pup inside a
    knotted cloth bundle ("fagottino"), releasing it gently from the skies
    where your gaze is aimed to deliver a brand-new pup!
* [B] Angry Boar: Summons a ferocious wild Boar (12 HP) that impales a pup
  alive upon its left tusk; defeat it by launching pups airborne at the beast.
* [Z] Zeus Intervention (3 modes in [M]): Strike a random pup without provoking
  Wolf Mama's wrath using:
  - Lightning Bolt (jagged bolt + thunder)
  - Heavenly Wrath (sacred golden pillar + celestial choir)
  - Falling Boulder (hurls a real boulder from the heavens, crushing pups into
    3 chicken drumsticks cleanly without blood, skulls, or gore)
* Boulder Traps: Hanging & falling boulder traps likewise crush pups into 3
  clean chicken drumsticks (no whole corpse, blood, skulls, or gore).
* [T] 3-Pup Totem Stacks: Assembles unoccupied pups into wobbly 3-tier totems
  obeying [F] commands via the base pup; press [T] again to dismount.

--------------------------------------------------------------------------------
VIII. PUP CONTROL PANEL [M], ANIMATION STUDIO [N] & SPAWN MENU [O]
--------------------------------------------------------------------------------
* [M] Pup Control Panel (this pup or all pups):
  - Needs & Ailments: hungry, thirsty, sick (vomit), dead (corpse, non-wrath),
    morente (dying crawl), starvation (global Runt event + Evening trigger),
    rebellion, and cure & feed.
  - Zoomies Suite:
    * Zoomies Light: Keeps native AI & [E]/[F] obedience intact; RUN_FRENZY +
      LongWee when moving, stationary idles when still; NO collisions.
    * Zoomies Plus: Preserves full [E]/[F] obedience whilst adding local 6m
      roaming & cover-hiding around stationary Father with pup collisions that
      never exit Zoomies Plus.
    * ZOOMIES (global): Unleashes standard vanilla zoomies across all pups.
  - Boar Rider: Mounts selected pup(s) atop real in-game Boars using original
    Boar animations (80% saddle / 20% comical head-peek), yelling wahoo/yahoo/
    wee and obeying ONLY [F] commands.
  - Toggles: [Z] Lightning / Wrath / Boulder, [V] Vulture / Stork, Blood ON/OFF.
* [N] Pup & Wolf Mama Studio: Full Episode 4 pup animation/face/soundboard
  (including 9:16 Shorts framing lines) plus a dedicated Wolf Mama tab.
* [O] Spawn Menu:
  - Actors: Spawn the bound, struggling Angry Old Man (4 pups haul him via [E]
    like boulders & logs, or load custom .glb/.obj models from
    BepInEx\plugins\RedMenaceRevenge\Assets\).
  - Books: Browse and spawn every single readable Lore book in the game!
  - Tools: Spawn the Cracked Pup Skull for Skull Soccer — 2 random pups chase
    and pass continuously, yielding immediately to [E]/[F]!

--------------------------------------------------------------------------------
IX. BOWL ATHLETICS [G], LA CHANCLA, SPRINT KNOCKBACK & PREPOSTEROUS RUMOURS
--------------------------------------------------------------------------------
* Dawn Neglect & Gravestones: Genuinely neglected pups perish at dawn into
  X X-eyed ragdoll corpses; bury them with [LMB] / [E] beneath wooden headstones.
* Chatty Pups, Gremlins HUD & 0% Sprint Knockback: Pups eagerly name animals
  held nearby, the left-hand HUD counter hails your little brood as "Gremlins",
  and holding Left Shift to sprint lowers pup dodge chance from 90% to 0%!
* [G] Soup-Bowl Mischief:
  - Press [G] whilst carrying a brimming soup bowl to execute a fluent upside-
    down pour animation splashing broth upon the ground; pups within 2m dismay
    (DISAPPROVE_2_STANDING). Press [G] with an empty bowl to hurl it straight.
  - Hitting a pup with a thrown bowl triggers a sharp Zoomies-style burst
    without KO, snapping her upright (STARTLE) with a frightened visage.
* La Chancla (Tool Wheel — Before Mallet):
  - Held cleanly from the heel base matching its diagonal sprite; left-click
    throws the spinning slipper, triggering original Zoomies collision bursts
    and delighted expressions on upright pups — while chivalrously passing
    harmlessly through pups already knocked down or lying on the ground!
* Concerning Preposterous Rumours: Pay no mind to idle whispers in the village
  concerning an alleged "Meat Grinder" apparatus: I assure you upon the honour
  of a Victorian gentleman that such lurid gossip is sheer moonshine and
  tomfoolery.

--------------------------------------------------------------------------------
INSTALLATION (BepInEx 5 — Windows Mono)
--------------------------------------------------------------------------------
1. Ensure BepInEx 5 (e.g., 5.4.23.5) is installed in your Family Time Episode 4
   root directory (where FamilyTime.exe resides).
2. Extract PiranhaTime2TheRevenge-v1.2.0.zip into the game's root folder so
   that the plugin lands at:
   <GameDir>\BepInEx\plugins\RedMenaceRevenge\RedMenaceRevenge.dll
3. Launch the game once to generate:
   <GameDir>\BepInEx\config\com.redmenacerevenge.hazards.cfg

================================================================================
