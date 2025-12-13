# Purple Hack

> _The following are "house rules" and clarifications, a mish-mash of D&D Basic/Expert a la OSE, and a fantastic ruleset called [Simulacrum](https://osrsimulacrum.blogspot.com/2021/06/simulacrum-beta-release.html). Rampant stealing has occurred below, and is intended only for use in my own home games._

# Table of Contents

Some highlights:

- [Character Creation](#character-creation)
  - [Warrior](#warrior)
  - [Mage](#mage)
  - [Feats](#choose-feats)
- [Armour, Weapons, and Equipment](#armour-weapons-and-equipment)
  - [Starting Gear](#starting-gear)
  - [Armour](#armour)
  - [Weapons](#weapons)
  - [Costed Items](#costed-items)
  - [Quick Packs](#quick-packs)
  - [Animals & Mounts](#animals--mounts)
- [Checks & Saves](#checks--saves)
- [Combat](#combat)
  - [Surprise](#surprise)
  - [Reactions](#reactions)
  - [Attacking](#attacking)
  - [Combat Phases](#combat-phases)
  - [Escaping an Encounter](#escaping-an-encounter)
  - [Death](#death)
- [General Adventuring](#general-adventuring)
  - [Doors](#doors)
  - [Dungeon Random Encounters](#dungeon-random-encounters)
  - [Equipment Wear & Tear](#equipment-wear--tear)
  - [Experience & Leveling](#experience--leveling)
  - [Fatigue](#fatigue)
  - [Item Saving Throws](#item-saving-throws)
  - [Light & Vision](#light--vision)
  - [Lockpicking](#lockpicking)
  - [Magic & Spells](#magic--spells)
  - [Perception Checks](#perception-checks)
  - [Retainers](#retainers)
  - [Sailing](#sailing)
  - [Trap Detection](#trap-detection)
- [Upgrading Armour and Weapons](#upgrading-armour-and-weapons)
- [Wilderness Exploration](#wilderness-exploration)
  - [Entering a Hex](#entering-a-hex)
  - [Camping in the Wilds](#camping-in-the-wilds)
  - [Hunting](#hunting)
  - [Weather](#weather)
  - [Wilderness Random Encounters](#wilderness-random-encounters)
- [Hirelings](#hirelings)

# Character Creation

Conversion guide is found [here](conversion.md).

## Roll Your Stats

Roll 3d6 down the line for each of the skills below. You can swap one set of stats.

- **Strength** measures physical might. It affects your lifting, carrying, and grappling. Any Str modifier is applied to your melee and thrown weapon attack damage.
- **Dexterity** measures agility, reflexes, and hand-eye coordination. Any Dex mod is applied to your Armour Class, as long as you can move freely.
- **Constitution** measures endurance and vitality. Any Con mod is applied to your Hit Point total at the start of the game and each time you go up a level.
- **Perception** measures your observational acuity. Any Per mod affects your ability to see through illusions, and to spot traps, secret doors, and ambushes.
- **Willpower** measures discipline and mental endurance. Any Will mod affects your ability to resist enchantment, fear, mind control, possession, and other mental attacks.
- **Arcana** measures your connection to magical forces. Any Arc mod is applied to chances to learn spells and to saving throws to resist spell damage.

## Choose a Character Race & Make Any Adjustments

- **Humans**: The most flexible & common. +1 to one stat of your choice.
- **Dwarf**: +1 Con, -1 Dex. Add Con mod to saves vs poison. Cannot wield large weapons.
- **Elf**: +1 Per, -1 Str. 90% resistance to sleep and charm spells. Immune to ghoul paralysis.
- **Half-Elf**: 30% resistance to sleep and charm spells.
- **Halfling**: -1 Str, +1 Dex. +1 bonus to missile weapon attacks. +2 AC vs large enemies. Cannot wield large weapons.

## Note Ability Score Modifiers

| Ability Score | Modifier |
| :-----------: | :------: |
|      2-3      |    -3    |
|      4-5      |    -2    |
|      6-8      |    -1    |
|     9-12      |    0     |
|     13-15     |    +1    |
|     16-17     |    +2    |
|     18-19     |    +3    |

## Determine Initial Background

Using the [character background generator](background.md), determine your character's height, weight, family upbringing, and progenitor.

## Choose Your Class & Note Hit Die

### Warrior

1d8 Hit Die (8hp+Con mod at 1st level). Receive attack bonus of +1 every level, starting at level 1, stopping at +15 at level 15. Can use any weapon or armour, so long as they meet its strength minimum, if any (see [equipment](#armour-weapons-and-equipment)). Every name level, warriors add an extra weapon die of damage to their armed combat attacks and an additional feat. At 1st level, warriors select one style, reflecting their preferred manner of fighting:

- **Arcanist**: You can read Mithric and gain access to two schools of magic of your choice. You can cast spells in armour as well as when being jostled. You cannot create or cast from scrolls, though you can copy spells from them. You have half the spell slots of a mage of your same level (rounded down, to a minimum of 1 slot). You start with a spellbook and spells the same way a mage does, but no schools or spells are automatically acquired through gaining levels. The source of your power must be defined.
- **Hordeslayer**: If you kill an opponent with an attack, you can immediately make a bonus attack of the same kind (melee or ranged). You can make a maximum number of melee bonus attacks per round equal to your level, and a maximum number of missile bonus attacks equal to your number of name levels plus 1.
- **Smiter**: Once per combat encounter, you can declare a smite after you score a hit, melee or ranged, which doubles the number of damage dice rolled. If a smite was announced on a critical hit, the extra weapon dice do not automatically deal maximum damage.

### Mage

1d6 Hit Die (6hp+Con mod at 1st level). Can cast one spell per round. Can use any weapon or armour, so long as they meet its strength minimum, if any, but they can't normally cast spells in armour. Receive attack bonus of +1 every two levels, starting at level 2. All spells are divided into eight schools (see [Magic & Spells](#magic--spells)). By default, mages have access to four schools (one chosen, and three rolled randomly). After rolling, a mage can trade away access to one school (up to two maximum) in exchange for one of the following special abilities (each can be chosen only once, and only at character creation):

- **Battlemage**: You can cast spells while wearing light armour, and your class attack bonus improves to +1 every level, starting at level 1, stopping at +15.
- **Focused**: Select one additional mage feat.
- **Innate**: While you can still use them, you need not own a spellbook or consult one to prepare your spells.
- **Specialist**: Choose one school you can already access. You have one additional spell slot at each spell level, to fill with a spell from this school. When you gain a level, you learn one extra random new spell from this school. Spells from this school are easier to bind.

**Starting Spells**: Mages start with one random 1st-level spell from each school to which they have access. Specialists then select one extra 1st-level spell of their choice from their specialty school. Mages can prepare a limited number of spells each day, and gain further spell slots as they gain levels (see [Magic & Spells](#magic--spells)).

**New Spells**: Mages learn one random new spell each time they gain a level. You also gain access to a new school of your choice at each name level. When this happens, you learn random spells of that school, one at each spell level you can cast.

## Determine Formative Institution

Using the [character background generator](/background.md#institution), determine formative institution.

## Note Your Saving Throw & Check Bonuses

**Check Bonuses**: Starts at 0. Characters gain +1 to regular checks at each name level.

**Save Bonuses:** Starts at 0. Characters gain a +1 save bonus for every 2 full Hit Dice they have.

## Choose Languages

You start play knowing your native language(s). Additionally, roll 1d6. On a 5, you gain one more language. On a 6, you gain two more languages. Mages also know Mithric (the language of magic), plus one additional language of their choice.

## Choose Feat(s)

All characters receive one feat at 1st level, and another feat at each name level. A feat can only be taken once, unless noted otherwise. No ability score can be raised above 19 through feats.

### Warrior feats

- **Brawler**: If your melee opponent is no more than one size level larger than you, and your attack roll against them is a natural 18 or 19, then in addition to your regular damage you can either:
  1. Disarm them
  2. Trip them (they become prone; two-legged creatures only)
  3. Drive them directly back 5 feet, if the space is available to do so. You may follow up immediately with a free 5-foot move of your own, even if you have already made your full move this turn or are otherwise locked in combat.  
     If none of those are possible or desired, then instead you bash them for an additional 1d4 damage (+2 per name level).
- **Captain**: Some are born to command. Your party gains a +1 initiative bonus. Add a +1 attack bonus to all other party members and associated NPCs, raised to +2 at level 10 or higher (this does not benefit yourself). Apply +2 to friendly Morale checks. These bonuses apply only as long as your orders can be understood and the individuals benefiting are willing to be led by you. Multiple captains in a group do not stack these benefits.
- **Defender**: If you decide that none will pass, then _none will pass_. You ignore all magical commands to move aside, flee, surrender and the like, and are immune to all fear-based effects, magical or not. You gain a 4-point modifier in your favor when resisting any other effect that would result in you being involuntarily moved. Also, in combat, you can always choose to receive the effects of the Guard combat stance, even if using another stance. If you actually choose the Guard stance, you can intercept up to four enemies instead of two.
- **Great-Weapon Fighter**: When attacking with a two-handed melee weapon, your critical hit range improves by 1, plus 1 per name level (e.g. you score critical hits on a natural to-hit roll of 19-20 at level 1, 18-20 at level 5, etc.).
- **Marksman**: If firing into melee, you can pick your target instead of rolling randomly. Your ranged to-hit penalties are reduced by 2 points, plus 2 per name level. Your rate of fire with small thrown weapons increases from 1 to 2.
- **Read Scrolls**: You can read Mithric, as well as cast from scrolls containing spells from four schools of your choice; if an Arcanist, two of these schools must be the two schools you already know. This does not grant the ability to create scrolls.
- **True Grit**: You may reroll failed death saves.
- **Whirlwind**: +2 AC (and a further +1 AC per name level). If not casting a spell that round, you receive the effects of the Dash combat stance (this does not count as your stance pick for the round). You are not locked in melee combat unless in melee with at least three opponents. To gain these benefits, you must be able to move freely, not wearing medium or heavy armour, and cannot be encumbered.

### Mage Feats

A mage can combine multiple feats on a spell. The spell adjustments from these stack (e.g. a _Silent Magic Missile_ spell with extended range would in all ways be treated as a 3rd level spell). A feat cannot take a spell over 6th level. Note that a spell cannot be both Silent and Stilled.

- **Concentration**: You can cast spells while being jostled (e.g. on a ship or a horse).
- **Dextrous**: You can cast 1st-level spells using only one hand. For each name level you have, the level of spells that can be cast in this way increase by one.
- **Familiar**: You acquire a Tiny or Small mundane creature appropriate to the area that obeys your commands. You can see through its eyes, and gain a small power appropriate to the creature while doing so (e.g. +2 visual Perception for a bird). Regardless of its normal statblock, the creature has 2 Hit Dice. Its death applies one level of fatigue to you for the next week, after which you may take a new familiar.
- **Metamagic**: You can double the duration of your spells (not concentration, permanent, or instant spells), or you can double the base range of spells with Short, Medium or Long range (range increases due to gaining levels are unaffected). Preparing a Metaspell uses up a spell slot one level higher than the spell's normal level for each alteration you make (e.g. duration is +1 spell level; duration & range is +2).
- **Quickcast**: Casting times of your spells are reduced by 1 (see [magic phase](#combat-phases)). This can take them to 0 or below. This feat may be taken up to twice.
- **Spell Silence**: You can craft your spells to require no vocal component. Preparing a Silent spell uses up a spell slot one level higher than the spell's normal level. This feat may be taken twice. The second time removes the vocal component from your spells permanently, with no level adjustment to them required.
- **Stillcasting**: You can craft your spells to require no somatic components. Preparing a Stilled spell uses up a spell slot one level higher than the spell's normal level. This feat may be taken twice. The second time removes the somatic component from your spells permanently, with no level adjustment to them required.
- **Undeniable**: Once an Undeniable spell is declared, loss of concentration does not disrupt it (unless you are killed or otherwise rendered incapable of casting). All other restrictions apply. Preparing an Undeniable spell uses up a spell slot one level higher than the spell's normal level.

### Unrestricted Feats

- **Anointed**: You are zealous for your god or extra-planar benefactor. Spells or effects that would target supernatural creatures aligned with your patron also affect you.
  - Your weapon attacks against undead or supernatural beings opposed to your patron add +1 weapon die of damage (add/gain another if level 10 or higher). This always counts as a magical attack.
  - When resisting spells and effects that would place you in direct conflict with your patron's known tenets and goals, the saving throw difficulty is one level lower.
  - Gain a small power appropriate to your patron (e.g. healing touch once per day that heals hp equal to your level for a god of life or healing).
- **Conditioning**: Gain +2 to a chosen ability score. This feat can be taken only once for a given ability score.
- **Fieldcraft**: Gain +1 Constitution. Pick two broad terrain types (forest, desert, swamps, jungle, tundra, mountains, etc.). In these terrain types, your difficulties for tasks such as stealth, tracking, and concealing tracks are lowered, and you:
  - Heal +2 HP per day, and still heal even if marching in terrain that normally prevents such.
  - Succeed more often when hunting.
  - Are less likely to get lost, have random encounters, or be surprised.
- **Lockpicking**: Gain +1 Dexterity. You have the tools and expertise to pick locks. Your search for traps on a lock are one difficulty level lower.
- **Tough**: Your hit die is one die higher (i.e. a warrior will use a d10, and a mage will use a d8).

## Determine Starting Age & Choose Skills

Using the [character background generator](background.md#starting-age), determine your character's starting age. Then, select appropriate skills.

Skills represent specialized knowledge of or training in a particular field. All characters select one to three skills at 1st level, and another at each name level.

It's assumed that characters possess all the skills and knowledge appropriate to their background, along with a host of everyman abilities that nearly all posses, such as climbing, hiding, or moving silently. Skills for adventurers' purposes are almost always specialized (like reading lips) or non-intuitive (like lockpicking), and reflect special training, deep knowledge, or intense & focused practice in that particular narrow area. Broad interaction (e.g. Conversation), social skills that achieve a result otherwise possible only through roleplay (e.g. Deception or Intimidation), skills that boil down a non-linear non-standard task down to a simple roll (e.g. Dungeoneering or Investigation) or skills that allow for ready identification of magical items cannot be taken. **Skills are largely meant to measure a proficiency over and above what one could reasonably be expected to have, NOT to define what is possible!**

Concretely, skills might, depending on the circumstances, allow you to:

- Avoid what might otherwise involve a roll.
- Lower the difficulty of a check or negate penalties.
- Lessen the consequences of failure.
- Gain information not obvious to the average observer.

Sample skills include: Acrobatics, Blindfighting, Climbing, Disguise, Etiquette, Gambling, Herbalism, Jumping, Language (_choose one_), Lockpicking (_a character cannot have both the skill and the feat_), Lore (_specific subject_), Performing, Pick Pockets, Read Lips, Riding, Running, Seafaring, Shadowing, Stealth, Swimming, Tracking, Wrestling.

## Buy Equipment

Roll 6d6 and multiply the number by 10. That’s your starting silver pieces (d.). See the [equipment](#armour-weapons-and-equipment) list for things to buy (don't forget armour!) or choose a [quick pack](#quick-packs).

If you plan to cast Turn Undead, be sure to buy a holy symbol! If you’re a thief, you’ll want lockpicks. A magic-user needs a book to use as a spellbook.

## Note a Motivation or Motto

_Why is your character risking their life for adventure? This can be one word, or a short sentence. Examples:_

- Rejected from his clan, Gorend is on a mission to prove himself.
- Percival always has to be the hero.
- Cedric can't resist a good story.
- Spread the faith
- Earn glory
- Amass wealth
- Take revenge
- Master a skill
- Obey duty
- Discover truth
- Do good
- Help others
- Instill chaos

---

# Armour, Weapons, and Equipment

## Item Slots

We’re using container-based “item slot” encumbrance, measuring both weight and awkwardness.

You can carry 10 + Str mod slots of equipped items (anything you're wearing, holding, actively using, ready to use at short notice). You can carry 16 + Str mod slots of stowed items. Your encumbrance is based on how many slots you have occupied:

| Equipped Slots |  Stowed Slots   | Combat Speed | Exploration Speed | Normal Travel | Forced March |
| :------------: | :-------------: | :----------: | :---------------: | :-----------: | :----------: |
|      0-3       |      0-10       |     40'      |       120'        |     8 pts     |    12 pts    |
|      4-5       |      11-12      |     30'      |        90'        |     6 pts     |    9 pts     |
|      6-7       |      13-14      |     20'      |        60'        |     4 pts     |    6 pts     |
| 8-10 + Str mod | 15-16 + Str mod |     10'      |        30'        |     2 pts     |    3 pts     |

A backpack can only carry 12 stowed slots of items; more than that, and you must use a sack. 13-14 slots of items means you're carrying the sack with one hand, and 15 or more slots requires two hands to carry.

- **Small** items (like chalk or potions) fit four to a slot.
- **Medium** items (most things) are 1 slot.
- **Large** items like 2h weapons and medium armour are 2 slots. Heavy armour takes 3 slots (as do all items listed as L+) and adds a level of encumbrance.

Coins & gems stack 500 to a slot. A typical body (willing or unconscious) fills 9 slots, before gear, and adds a level of encumbrance.

## Starting Gear

The following base gear is automatically added to your character for free:

- One weapon of your choice (+ 20 arrows/bolts if missile weapon) with a scabbard/sheathe/quiver if needed, (number of slots depends on size)
- Backpack (10 + Str mod slots) & pouches (worn clothing & in-use backpags & pouches do not count toward your slots), waterskin (M), tinderbox (S) (for lighting torches or small fires)
- Misc tiny items (within reason); worn items/clothing

After this, you can have whatever basic gear you wish (within reason, as determined by the referee). Some common basic adventuring items include but are not limited to (size listed after each):

- **Bedroll (M)**: A blanket that can double as a sleeping bag. Helps protect against the cold when [sleeping in the wilds](#sleeping-in-the-wilds).
- **Caltrops, bag (M)**: Small metal spikes sufficient to cover a 5' × 5' area. Creatures moving through have a 2-in-6 chance of treading on a spike for a 50% penalty to movement rate for 24 hours (or until magically healed). Intelligent creatures can move cautiously through areas with known caltrops, which requires their entire Movement Phase to travel 5', but eliminates any risk of impalement.
- **Candle (S)**: Dimly illuminates a 5' radius, and burns for 4 hours.
- **Chalk (S)**: Useful for marking trails in dungeons.
- **Crowbar (M)**: Makes it easier to force open doors, and doubles as an improvised medium weapon.
- **Food, fresh, poor** (M): Poor-quality fresh food, 1 day's worth. Won't win awards, but it'll keep you fed.
- **Food, trail** (M): Preserved and packaged food, 1 day's worth. Won't go bad.
- **Grappling Hook (S)**: Steel, 1'x8", four prongs
- **Hammer (S)**: Doubles as an improvised small weapon.
- **Sack, canvas (M)**: Holds 10 + str mod slots of items.
- **Spike, iron x4 (S)**: One of these can be hammered in to block one typical door.
- **Lantern (M)**: A lantern can be closed to hide its light, burns one flask of lamp oil every 4 hours, and illuminates a 20' radius.
- **Oil flask (M)**: Fuels lantern 4 hours. Poured on ground and lit burns for 1 turn. Thrown on monster (roll to hit) & set on fire does 1d6 damage each round for two rounds.
- **Pick, mining (M)**: This excavating tool doubles as an improvised medium weapon.
- **Pole, 10' (L)**: Often used to prod potential dangers at a safe distance. When wielded during cautious exploration, has a 2-in-6 chance of setting off most traps.
- **Rope, hemp, 3/8" (L)**: Holds 250lbs, 50' length.
- **Scroll case, leather (M)**: Each holds up to 10 spell levels in spell scrolls.
- **Shovel (L)**: Excavating tool doubles as an improvised medium weapon.
- **Sledgehammer (L)**: Excavating tool doubles as an improvised medium weapon.
- **Torch (S)**: Burns for 1 hour, illuminating a 40' radius. Will remain lit if dropped to the ground or thrown. Can be used as a small weapon without dousing it; some targets take further damage due to the fire. Also useful to burn away rot grubs, green slime, and webs.
- **Twine, hemp, 1/8" (S)**: Ball, holds 10lbs, 100' length.
- **Vial, glass (S)**: 4oz, 1.4" dia, 5" high, cork stopper.

Finally, you can add "costed" items, which do cost money at character creation.

**Note**: After character creation, all items you buy in the world are "costed items," even if they appear on the free list above; their prices may differ from the prices below.

### Costed Items

> [!NOTE]
> 40 copper farthings (f.) = 10 silver pence (d.) = 1 gold noble (g.)

| Item                                | Cost |
| ----------------------------------- | ---- |
| Acid, vial (S)                      | 50d. |
| Arrow or light bolt, silver, single | 5d.  |
| Book, leatherbound, 24pgs (M)       | 30d. |
| Chain, iron, 1" links, 10' (L)      | 40d. |
| Holy symbol, iron                   | 5d.  |
| Holy symbol, silver                 | 50d. |
| Holy symbol, wooden                 | 1d.  |
| Holy water vial (S)                 | 25d. |
| Mapping kit (M)                     | 10d. |
| Mirror, small, bronze (S)           | 2d.  |
| Rope, silk, 3/8" (M)                | 75d. |
| Tent, single (L)                    | 20d. |
| Thieves' picks & tools (M)          | 12d. |
| Wolfsbane sprig (S)                 | 1d.  |

**Acid, vial**: Can splash contents on a target within 5' or hurl it as a small thrown weapon; it shatters on impact. A hit deals 1d6+1 acid damage. A vial can also be used to open most mundane locks in 1 turn.

**Holy symbols**: Wooden symbols incur -1 penalty to Turn Undead hit dice roll; silver symbols receive +1 bonus.

**Holy water**: Can splash contents onto an undead creature within 5' or hurl it as a small thrown weapon; it shatters on impact. Causes 2d4 damage when thrown on most undead.

**Mapping kit**: A cased roll of parchment plus quills and vials of ink, sufficient to map all but the largest areas.

**Rope, silk**: Lighter and stronger than hemp, can hold 500lbs. 50' length.

**Tent**: Protects against adverse weather when adventuring in the wilds. See [sleeping in the wilds](#sleeping-in-the-wilds).

**Wolfsbane**: If a lycanthrope is hit by wolfsbane, it must make a Very Hard (17+) save or run away in fear. The sprig must be swung or thrown as a weapon.

## Armour

An unarmoured character has a base Armour Class of 10.

| Armour                             | AC  | Cost  | Time to Don/Doff |
| ---------------------------------- | :-: | :---: | :--------------: |
| Small Shield (M)                   | +1  | 25d.  |     1 action     |
| Large Shield (L)                   | +2  | 60d.  |     1 action     |
| Leather or Furs (light armour) (M) | 12  | 80d.  |      1 min       |
| Ring (med. armour) (L)             | 13  | 130d. |      5 min       |
| Scale/Lamellar (med. armour) (L)   | 14  | 180d. |      5 min       |
| Chainmail (med. armour) (L)        | 15  | 280d. |      5 min       |
| Splint (heavy armour) (L+)         | 16  | 580d. |      10 min      |
| Plate (heavy armour) (L+)          | 17  | 850d. |      10 min      |

Heavy armour (L+ = 3 slot) and Large Shields require minimum 9 Str to equip. Heavy armour adds a level of encumbrance. A Shield also provides a save bonus vs non-gaseous breath weapons equal to its AC bonus.

## Weapons

### Melee Weapons

Weapons are divided into three basic damage categories: small, medium, and large.

- **Small** weapons deal 1d4 damage (plus the user's Str modifier), are one-handed, and include knives, daggers, and small handaxes. Can be dual-wielded for +1 to hit (doesn't grant additional attacks). Average cost: 12d.
- **Medium** weapons deal 1d6+1 damage (plus the user's Str modifier), are one-handed, and include most swords, spears, maces, flails, and battle axes. Can be wielded two-handed, which adds +1 damage. Average cost: 20d.
- **Large** weapons deal 1d8+3 damage (plus the user's Str modifier), are two-handed, and include polearms and pikes, as well as large swords, spears, axes, and maces. A minimum Str of 9 is required to wield large weapons. Average cost: 75d.

#### Weapons of Special Metals

Adventurers sometimes seek out weapons made of cold iron or silver, as these are harmful to fey or certain undead monsters. Cold iron and silver weapons must be crafted to special order, incurring a delay of 2d6 days.

**Cold Iron Weapons** are made of pure iron, forged in flames of ancient yew wood, and doused in water infused with mandrake root. They cost double the weapon's normal price. They gain a +1 damage bonus against fey and demi-fey, but suffer a -1 damage penalty against other creatures.

**Silver Weapons** are made of pure silver, and cost ten times the weapon's normal price. They inflict +1 damage against undead, and normal damage against other foes, and certain foes can _only_ be harmed by silver (or magic) weapons. They don't hold an edge well, and are prone to wear and tear, making all item degradation checks with disadvantage (rolling twice and taking the lower die).

### Missile Weapons

Missile weapons have a rate of fire of 1 shot per attack (except for small thrown weapons with the marksman feat). Loading does not require an action if ammunition is readily at hand (except for heavy crossbows, which require an action to load). All missile weapons have three range brackets (Short, Medium, Far). Attacks made against targets at a given range apply the attack penalty listed.

| Weapon                  | Size & Damage | Cost | Hands | S:0 | M:-4 | F:-8 |
| ----------------------- | :-----------: | :--: | :---: | :-: | :--: | :--: |
| Arrows/bolts x20        |       M       | 20d. |   -   |  -  |  -   |  -   |
| Bow, short\*            |       M       | 35d. |   2   | 45' | 90'  | 180' |
| Bow, long\* (req 9 Str) |       M       | 60d. |   2   | 90' | 180' | 360' |
| Crossbow, light         |       M       | 50d. |   2   | 45' | 90'  | 180' |
| Crossbow, heavy\*\*     |       L       | 75d. |   2   | 90' | 180' | 360' |
| Holy Water              |    \*\*\*     | 25d. |   1   | 10' | 20'  | 30'  |
| Javelin/Spear           |      M†       | 16d. |   1   | 20' | 40'  | 60'  |
| Sling                   |       S       | 1d.  |   1   | 45' | 90'  | 180' |
| Small thrown weapon     |      S†       | 12d. |   1   | 10' | 20'  | 30'  |

\*If fired indoors, halve all ranges.  
\*\*+2 attack bonus, reload requires action.  
\*\*\*See costed equipment list below for details.  
†Plus user's Str modifier.

## Quick Packs

- **The Gygax** (10 slots, 25d. cost): Hempen rope 50' (L), 10’ pole (L), Iron spikes x4 (S) x2, Hammer (S), Lantern (M), Oil flask (M) x2, Holy water vial (S, 25sp), Trail food (M) x2.
- **The Generalist** (6 slots, 10d. cost): Candle (S), Chalk (S), Hammer (S), Iron spike x4 (S), Crowbar (M), Trail food (M), Oil flask (M), Lantern (M), Mapping kit (M, 10d.).
- **The Cautious** (7 slots): Candle, pillar (S) x4, Chalk (S), Hammer (S), Iron spikes x4 (S), Wolfsbane (S), Caltrops (M), Trail food (M) x2, 10' pole (L).
- **The Delver** (6 slots): Candle, pillar (S) x3, Hammer (S), Beef jerky (S) x2, Cheese (S), Dried fruit (S), Pickaxe (L) or Shovel (L) or Sledgehammer (L), Hempen rope (L).
- **The Scholar** (6 slots, 10d. cost): Chalk (S), Vial (S) x3, Trail food (M), Oil flask (M), Lantern (M), Mapping kit (M, 10d.), Scrollcase (M).
- **The Torchbearer** (6 slots): Trail food (M) x2, Oil flask (M) x2, Torches (S) x8.

## Animals & Mounts

| Animal        | Cost  | Size | Combat Speed | Item Slot Limit |
| ------------- | :---: | :--: | :----------: | :-------------: |
| Donkey/Pony   | 70d.  |  L   |      50      |       20        |
| Dog, hunting  | 35d.  |  M   |      50      |        -        |
| Dog, war      | 65d.  |  M   |      50      |        -        |
| Hawk          | 40d.  |  S   |      80      |        -        |
| Horse, draft  | 150d. |  L   |      50      |       30        |
| Horse, riding | 100d. |  L   |      80      |       20        |
| Horse, war    | 300d. |  L   |      65      |       25        |
| Mule          | 90d.  |  L   |      65      |       25        |
| Ox            | 120d. |  L   |      50      |       35        |

| Item          | Cost  |
| ------------- | :---: |
| Cart          | 60d.  |
| Feed, per day |  1d.  |
| Wagon         | 800d. |

**Cart**: Open, road-bound, two-wheeled vehicle. Pulled by 1-2 beasts of burden. Capacity: 2x of the animals drawing it.

**Encumbrance**: A rider counts against a mount's item slot limit at a rate of 3 slots per the rider's size level, starting at Tiny (so 9 slots for a Medium rider), plus the rider's own carried slots, if any. A mount can carry no more than two typical riders. An animal, cart, or wagon 1 point over its item limit gains one encumbrance level. Every 3 slots past that adds another (or every 8 points past for a cart or wagon).

**Wagon**: Open, four-wheeled, road-bound vehicle for heavy loads. Pulled by 4-6 beasts of burden. Capacity: 2x of the animals drawing it.

**War**: An animal not trained for combat may panic in battle. If it's wounded, its owner must make a Hard (14+) check to keep it from fleeing or tossing its rider.

_For water vehicles, see [ships](#ships)._

---

# Checks & Saves

**Checks** are a single roll against a target number, used to resolve situations with interesting stakes that would either be too tedious or difficult to describe, or involve a strong element of chance. Even if it comes down to a die roll, players will be rewarded for thinking the action through, and sometimes penalized for not. For example, if a player thinks to first apply some lamp oil to the chain and gearing responsible for raising a stuck gate, this would reduce the difficulty.

First, the referee decides how difficult a check is:

| Difficulty Level | Result Needed |
| :--------------: | :-----------: |
|     Moderate     |      8+       |
|     Daunting     |      11+      |
|       Hard       |      14+      |
|    Very Hard     |      17+      |
|      Heroic      |      20+      |

The player rolls 1d20 (unless success or failure would not be obvious, in which case the referee rolls instead, in secret). If an ability score modifier is relevant, the check will note this (e.g. "Hard (Con x2)" means apply double the character's Con mod). If the modified total equals or exceeds the result needed, the check succeeds. Rolling under indicates failure. A natural 20 is not an automatic success for a check.

**Saving throws** or **saves** represent an attempt to resist a notable threat, such as magic, poison, or disease. A creature can always choose to fail a saving throw. A save is a check with any relevant ability score listed as normal (e.g. "Save: Hard (Con)"). The default save is Hard (14+). The exception is saves for instant-death effects (known as "death saves"); their default save is Daunting (11+). Unlike a regular check, a natural 20 always saves, and a natural 1 always fails. See also [item saving throws](#item-saving-throws).

**Check Bonuses**: Characters gain +1 to regular checks at each name level.

**Save Bonuses**: Characters gain a +1 save bonus for every 2 full Hit Dice they have.

---

# Combat

## Surprise

Surprise is a circumstance that might occur between parties at the moment of contacting one another, indicating the possibility that one or both might be taken aback by the occurrence.

Once it has been determined that surprise might occur, each party potentially affected rolls a d12. The default chance of surprise is 4 in 12 (i.e., on a die roll of 4 or lower). Each roll applies to all the individuals on each side of a conflict; individuals may, however, adjust the die roll in their favor.

A character with a Perception modifier subtracts that modifier from the surprise threshold (i.e., a character with a +1 Per mod is surprised on a 3 or lower; a character with a -1 Per mod is surprised on a 5 or lower, etc.). A character with the Fieldcraft feat has a default chance of being surprised of 2 in 12. The minimum chance of being surprised is 1 in 12.

For example, the player party's die roll is a "3," indicating the party is surprised. However, the surprise occurs in a forest, a terrain for which one character has a Fieldcraft feat. That character is not surprised; while the rest of the party would be unable to act in the first round of combat, that character can act normally.

### Effects of Surprise

Surprise lasts one round. In that round, those that are surprised cannot move, act, or apply Dex-based AC modifiers, and attacks on them gain a +4 bonus. Attacks against surprised targets from behind also ignore any shield modifiers, and raise the range for a critical hit by 4. Killing surprised foes might force a Morale check.

## Reactions

Some encounters are essentially pre-determined due to the nature of the creatures or the encounter itself, and will end up in combat no matter what (e.g., intelligent undead and sentinels like golems will almost always attack).

However, when any creatures are encountered, if their nature or the circumstances don't automatically dictate their behavior, the referee _always_ rolls to see how they react to the players _before_ actions are taken.

If the players do not immediately attack, the referee rolls on the Reaction Table, applying -2 to the roll if the creatures encountered are Evil, and rerolling Hostile results if the creatures are Good:

| 2d6  |                    Behavior                     |
| :--: | :---------------------------------------------: |
|  2   |                     Hostile                     |
| 3-6  |       Unfriendly (unintelligent: Hostile)       |
| 7-8  |                Neutral/uncertain                |
| 9-11 |                  Unthreatening                  |
|  12  | Actively helpful (unintelligent: Unthreatening) |

## Attacking

To attack, the attacker rolls 1d20 and adds their attack bonus and all applicable modifiers. If the result equals or exceeds the target's Armour Class (AC), the attack hits. The most common attack modifiers are:

- Attacker is striking from the rear: +2
- Target is surprised or attacker is invisible: +4 (replaces above)
- Attacker declared an offensive stance: +2
- Attacker cannot see target: -4
- Attacker is fatigued: -2 (light) or -4 (heavy)
- Attacker is on a mount, target is upright: +2
- Attacker is using improvised weapon: -2
- Target is prone, attacker is in melee: +4

For PCs, a natural 20 is always a hit. The attack is also a critical hit, unless the attacker could only hit by rolling a natural 20. Melee and short-range missile attacks against sleeping, paralyzed, willing, and similar targets always hit and deal maximum damage. Such targets include PCs at 0hp.

#### Dealing Damage

An attacker's Strength modifier is applied to melee and thrown weapon attack damage. Modifiers cannot drop a successful attack below 1 point of damage. Ar successful charge or set vs. charge adds two weapon dice to the attack. Attacks against helpless targets automatically deal maximum damage.

An **unarmed strike** deals 1d2 damage (a critical hit does 4 damage), plus the attacker's Strength modifier. Weapon dice do not apply.

If a PC rolls a natural 20 on an attack, a **critical hit** is scored: the attack deals its maximum possible damage. However, you cannot score a critical hit if you can only hit by rolling a 20. The critical hit range is increased by 4 for all attacks from behind against a surprised target.

## Combat Phases

Each combat round is 10 seconds and has seven steps, taken in the following order:

- **Declarations**: All spellcasting and combat stances for the round must be declared _before_ anything else in the round happens.
- **Missile**: Combatants with equipped missile weapons can fire. Players who chose the Dash combat stance fire first, then all remaining missile attacks from all sides are resolved simultaneously.
- **Initiative**: 1d12 is rolled by each side involved, with the side that rolled the highest winning (re-roll ties). Only determines movement order, not action order.
- **Movement**: Everyone on the side that won initiative for the round can move, followed by any movement by the losing side.
- **Melee**: Combatants that did not fire a missile weapon can attack with melee weapons (or take a miscellaneous action). Players who chose the Dash combat stance act first, and then all remaining actions from all sides are resolved simultaneously.
- **Magic**: Spells are canceled if desired, and then all spells declared and not disrupted are cast.
- **Morale**: The referee may need to make morale checks for opponents, retainers, and other NPCs.

### Declaration Phase

Any character not surprised or casting a spell must pick a stance. A character casting a spell must pick the exact spell at this time, and cannot do anything else that round (i.e., no moves, attacks, actions, etc.).

#### **Combat Stances**

- **Offensive**: +2 attack bonus
- **Defensive**: +2 Armour Class
- **Dash**: Your action occurs before those of the enemy (exceptions: charging a set opponent; attacking a pike/spear wall; grapple attempts)
- **Guard**: Pick a 5' square. If you remain within 10' of it and can move freely, the first two enemies you are in the way of that try to move up to or make a ranged attack against anything in that square must engage you instead. Enemies already within 5' of the square or whom you are not in the way of are unaffected. Additionally, if an enemy can't be locked in melee, you cannot block its move.
  The effects of a stance last only for that round. Monsters and NPCs do not use stances.

### Missile Phase

Missile attacks can be made if you have a ranged weapon equipped at the start of the round, are not locked in melee, and the target is not blocked (by one or more creatures along direct line of sight, unless the target is one or more sizes larger than any blockers).

Missile attacks use all relevant modifiers above, except the bonus for being on a mount or the target being prone. Missile-specific modifiers include:

- Target is prone, attacker is at range: -2
- Firing from a moving or unsteady position: -4
- Low visibility (gloom, smoke, fog, etc.): -2
- Target has cover: -2 (half cover) or -4 (heavy cover)
- Target is at medium range: -4
- Target is at long range: -8

A miss is generally presumed to hit no other target. Other considerations:

- **Crossbows** can be fired while kneeling or prone.
- **Firing into Melee**: To pick a target that is in melee, the target must be one or more sizes larger than all those with which it is in melee (unless the attacker is a warrior with the marksman feat). Otherwise, the attacker randomly rolls to see who in that melee (friend or foe) they roll their attack against. A target's melee opponents do not provide it cover.
- **Holding Fire**: Instead of firing in the Missile Phase, an attacker can choose to wait until the end of any other Phase. This allows the use of thrown weapons "on the run" at the end of the Movement Phase at short range, just before being locked in melee.
- **Magic Devices**: Ranged effects and spells from magic items are treated as missile attacks, except for line of sight.
- **Poor Conditions**: If in very windy conditions, or if the target is above the attacker, long-range missile attacks cannot be made. If both, medium-range missile attacks also cannot be made.

### Movement Phase

In an encounter, a creature can move once per round up to its combat speed (for unencumbered PCs, this is 40'). One can move through creatures that allow it and aren't in a tight formation. Modifications include:

- **Backwards Movement** applies a x2 movement cost penalty (e.g. 5' of clear terrain costs 10' of movement).
- **Charging**: An attacker with a lance, pike, large spear, or similar large pole weapon and no more than lightly encumbered can charge. So too can creatures with large horns/tusks. A charge must be in a straight line from at least 30' away, in non-difficult terrain, and not uphill. The attacker's first strike on the round it makes the charge adds two weapon dice if it hits.
- **Difficult Terrain** applies a x2 movement cost penalty (or x3 if moving backward).
- **Encumbrance**: Being encumbered reduces your combat speed.
- **Holding Movement**: A combatant on the side that won initiative can choose to move after the enemy in the round.
- **Jumping** ends your move that round.
- **Prone**: To stand up, a prone creature must use all their movement for the round.
- **Set vs. Charge**: If armed with a pike, spiked polearm, or large spear, a combatant not prone or locked in melee can choose not to move that round and instead hold their weapon firm, braced against the ground. A set combatant attacks first against the first charge made against them (even if the attacker has the Dash stance), and adds two weapon dice if it hits.

#### Locked in Melee

A creature within 5 feet of one or more enemies (three or more if it has the Whirlwind feat) is **locked** in melee with those enemies. Locked combatants cannot use missile weapons or leave their location unless they make a fighting withdrawal or flee.

- **Blind** creatures can only lock opponents in melee if surrounding them.
- **Flight and Teleportation** allow one to leave melee without penalty, even if surrounded.
- **Invisible** creatures are not locked unless their melee opponents can see them or otherwise fully ignore invisibility, or are surrounding them.
- **Prone** creatures cannot lock opponents in melee.
- **Size**: A creature more than two sizes large than any of their melee opponents is not locked, even if surrounded.

#### Fighting Withdrawal

A creature locked in melee can move out of that melee if they didn't make a missile attack that round, but all their movement for the round must be backwards (applying the standard x2 movement cost penalty). They can take no actions that round.

#### Fleeing

A fleeing creature can move as normal, but must leave the melee they're in. However, any enemy with which they were in melee prior to fleeing may first choose to take its attack(s) for the round against the fleeing creature, instead of in the Melee Phase. Such attacks gain the +2 rear attack bonus, while the fleeing creature loses all shield and stance AC bonuses.

#### Running

If a combatant did not act in the Missile Phase and commits to taking no actions this round, they may **run**. This raises their movement this round by 50% (rounded down to the nearest 5'), or by 100% with the Running skill.

### Melee Phase

In the Melee Phase, a combatant can take one action: a single attack against an opponent with which they are in melee, or a single non-attack action. All actions in this phase are simultaneous, not affecting any other action that phase, unless specifically stated otherwise. Considerations include:

- **Dash**: Choosing this combat stance allows a PC to act first that round, instead of simultaneously.
- **Grappling:** The attackers (or attacker) make individual to-hit rolls. The grapple is resolved among those who hit: Each combatant rolls their total hit dice. If the sum of the attackers’ dice is higher than the defender’s total, the defender is grappled. If the sums are exactly equal, everyone is struggling, and none of them can attack with a weapon. If the defender wins, the attackers are beaten back and stunned for a number of rounds equal to the number of points by which the defender beat them. Breaking free of a grapple requires another HD contest; all currently grappling together are counted as automatically having hit.
- **Polearms** (spears, pikes, etc.) in the second rank of a battle formation can attack by reaching through the first rank.
- **Spacing & the Second Rank:** Only daggers, shortswords, spears, and polearms can be used three-abreast in a 10’ area. All other one-handed weapons require five feet of room (two-abreast in a 10’ area), and non-thrusting two-handed weapons require a full 10’ space to wield.
- **Two-weapon fighting**: A combatant can use two melee weapons at once, which grants a +1 attack bonus (but no additional attacks).

### Magic Phase

If a caster wants to cancel a spell they're casting that hasn't been disrupted by having been attacked or jostled, they must do so before any spells are resolved.

After spells are canceled, spells still being cast are revealed and cast in the order of their **casting time**, which is equal to their spell level, unless stated otherwise. Spells with the same casting time are cast simultaneously, unless stated otherwise. For each instance of the Quickcast feat that they have, a mage reduces their spells' casting times by 1. Other feats raise a spell's level, raising its casting time to match. Spells cast from scrolls add 2 to their casting time.

### Morale Phase

Monsters and NPCs (but not PCs) have a **Morale threshold** between 1 and 20, representing how likely they are to fight or flee; the lower the threshold, the better.

Creatures with a Morale of 20 only fight if cornered and always flee if able, while those with a Morale of 1 never retreat unwillingly, but can be convinced to (if intelligent), and are still susceptible to magical fear. A score of -- means the creature ignores the Morale rules altogether, just like PCs.

The referee makes a Morale check--rolling 1d20, applying any situational modifiers (light fatigue gives -2, heavy fatigue gives -4, etc.)--at the end of a round for each of the following that occurred that round:

- Half or more of the side present at the battle's start has been incapacitated or killed.
- The last of the side (or its only member) was reduced to 1/4 or less of its full Hit Point total.
- A group with a Morale of 12 or higher that has any of its members killed during the surprise round.
- Any other unusually trying circumstance, at the referee's discretion.
  If the roll is lower than the Morale threshold, the check fails: the creature or side attempts to flee.

## Escaping an Encounter

If a side has none of its members locked in melee after the movement of that side for the round has been resolved (whether or not the other side has moved yet), that side can choose to try to escape the encounter.

If the enemy follows, **pursuit checks** are made. The referee rolls 1d12 for each group of enemies with a different combat speed, while the players roll 1d12 for their entire party. Apply any relevant modifiers. If only some of the PCs have modifiers, only those PCs apply them, giving them a result different from their base party result.

|             Fleeing Side              |             Modifier             |
| :-----------------------------------: | :------------------------------: |
|               Is faster               | +1 per 5' of combat speed faster |
|             Is invisible              |           Auto escape            |
|     Drops caltrops or flaming oil     |                +4                |
| Drops desirable items (food/treasure) |             +2 or +4             |
|          Is lightly fatigued          |                -2                |

|    Pursuing Side    |             Modifier             |
| :-----------------: | :------------------------------: |
|      Is faster      | +1 per 5' of combat speed faster |
| Has senses hindered |                -4                |
| Is lightly fatigued |                -2                |

**Faster Side** assumes that side can use their full speed, which isn't a given.
**Hindered Senses** usually involves difficulties using one's primary tracking sense. Hunting dogs compensate for some of these instances.

Each individual in a pursuit has one **pursuit action** each pursuit round. However, neither mapping nor spellcasting can occur.

- **Dropping Items**: Any pursued as their action can drop items to apply a bonus to their side's pursuit check. Dropping desirable items like food or treasure can be effective, but this depends on how the pursuers view what is dropped, how much is dropped, and how many pursuers there are compared to what is dropped; the referee must arbitrate this. If enough food is dropped & desired, durable food (+2) is always less effective than fresh food (+4).
- **Missile Attacks**: After each pursuit check, if the pursuit is not over, then missile attacks can be made by those who have not used their action. Assume a range of 20'.

### Ending Pursuit

A side automatically wins if they are either six points of modifiers or more ahead of all their opponents, or score a higher result than the other side twice in a row.

If the pursuers catch the fleeing side, a new combat round begins in the Melee Phase, with the two sides locked in melee, positioning and so on to be determined by the referee.

## Death

When a player character’s hit points reach 0, the character is unconscious and must make a Daunting (11+) Con saving throw. On a failure, the character dies. On a success, the character will die in 1d4 rounds, rolled in secret by the referee, unless magically healed or aided by another player character. Each PC may attempt to aid once, requiring a successful Very Hard (17+) check; if the aiding PC uses proper bandages, the check's difficulty is lowered to Hard (14+). Other modifiers may apply.

Even after returning to 1 or more hp, the character will remain in a coma for 1d6 turns and must rest for a minimum of one week before resuming any sort of strenuous activity, mental or physical. Magical healing that returns characters to consciousness does not incur these penalties.

Characters who are slain may be raised from the dead if a Mage of sufficient level is available to perform the casting. Each time a character is brought back from the dead, their CON score is reduced by one point.

---

# General Adventuring

## Climbing

No roll is required for simple climbs, like a basic rope or tree. A more difficult climb might require a Moderate (Dex) check. A climber must make one check before every 40' section to be climbed or portion thereof. If the check fails, the character falls at the halfway point (see [falling](#falling)).

Base climbing speed is 5' per round. Add 5' if the climber has the Climbing skill or is using rope (not cumulative).

The following each raise the difficulty by one level: high winds, extreme cold, smooth surfaces, slippery surfaces, each encumbrance level. The aid of appropriate equipment--a rope and grapnel, or pitons and a hammer--will lower the difficulty.

## Doors

Along with puddles, the bane of adventurers' existence.

### Listening at Doors

While exceptions can occur, it's assumed that player characters cannot hear through the typical dungeon door. If the situation is such that noise would carry through the door, the referee will notify players that they hear something without the need of the players to ask.

### Spotting Secret Doors

Requires a Perception check, with the difficulty based on how well-concealed the door is. During cautious exploration, this is a group check made automatically by the referee in secret for each secret door within 10'.

A character can also actively search a 10' square area for secret doors. This takes one turn; more than one person cannot search the same area at the same time.

Spotting the average secret door is Very Hard (17+) during cautious exploration, and Daunting (11+) via an active search. Finding one does not necessarily reveal how it opens. Describing narratively how one is searching might bypass the Perception check if the searching technique would logically reveal the door.

### Stuck Doors

Upon discovering that a door is stuck, a character may attempt a Strength check to pull the door open as swiftly and quietly as possible. Only the strongest character in the party may attempt (representing the party's best efforts). On a failure, the party may decide to work with crowbars or other tools to wrench the door open anyway. This takes a turn and will trigger a wandering monster check.

Locked doors need keys, thieves' tools and someone trained in lockpicking, or a battering ram (or axes). Any failed attempt to open a stuck or locked door will alert any creature(s) on the other side of the door to the party's presence.

You should also know: Doors tend to close on their own. Iron spikes are invaluable for keeping doors open or closed (it takes a round and some noise to hammer a spike in).

## Dungeon Random Encounters

Random encounters occur in almost all dungeon areas. These are typically monsters inclined to hostility (you're in their home) and with no treasure (it's back in their bedroom). To make a check, the referee rolls 1d6 at the end of the appropriate turn: on a 1, an encounter occurs.

If an area doesn't have a preset encounter rate, how often the referee checks to see if a random encounter occurs varies, based on the nature of the area being explored:

- Organized defenders, alert sounded: every turn
- Organized defenders, no alert sounded: every 2 turns
- No organized defenders: every 3 turns

Even if players hide somewhere (e.g. a disused storeroom), the encounter roll is still made. Only if the hiding place is exceptional are encounter checks avoided.

**Noisy**: If the party makes an unusual amount of noise while exploring (yelling, spiking a door; combats do not count), their next encounter check is made at -4, and the party cannot surprise creatures so encountered except via unusual means.

## Equipment Wear & Tear

Equipment can be worn down! Every object has five levels of decay: new, used, worn, shabby, and ruined. (You can indicate this simply by adding a (n) next to new items when you first acquire them, erasing and replacing as things change.) Used, worn, and shabby items still function just as well as their new counterparts; they're just more prone to breaking at the most inopportune moments.

Objects are subject to a decay roll after:

- One month of normal use, in normal conditions
- Three days of wilderness use
- One day of dungeon use
- Armour: Receiving a natural-20 hit
- Weapons: Rolling a natural 1 to hit
- Food: Every day, fresh foods decay one level automatically, and then roll as usual.
- Spice: Each use, spices decay one level automatically, in addition to usual rolls.

Objects that are expressly protected (e.g., a scroll in a scrollcase, or a spellbook in a metal box, etc.) are exempt. Thoughtful storage can reduce wear & tear!

Objects degrade as follows:

- A new object becomes used if a 1 in 4 is rolled. Under stress, a new object breaks on a 1 in 100.
- A used object becomes worn on a 1 in 20. Under stress, it breaks on a 1 in 50.
- A worn object becomes shabby on a 1 in 12. Under stress, it breaks on a 1 in 20.
- A shabby object becomes ruined on a 1 in 8. Under stress, it braks on a 1 in 6.

Magical items and "sturdy" items roll two of the appropriate dice, only degrading if two 1s are rolled.

You can purchase objects that aren't necessarily new for less money. New items cost 100% of list price, used cost 80% of list price, worn cost 60%, and shabby cost 40%. Likewise, you can sell such objects to merchants for half that price: 50% new, 40% used, 30% worn, and 20% shabby.

### Repairing Items

Weapons and armour can be repaired by an appropriate craftsman, costing 10% of the item's original base price to bring it from worn to used, and 20% of its original base price to bring it from shabby to worn (i.e., 30% to go from shabby to used).

### Alternative System

Simply track when something breaks, without tracking the intermediate steps. At the above intervals, roll 2d6. If both two 1s are rolled, the item is ruined or broken, and must be replaced. Magic items and "sturdy" items roll 1d100 + 1d6, and break if 1s are showing on all dice. Using this alternative system is simpler, but tracking more minutely has the benefit of knowing when things are getting close to breaking, plus a slight mathematical edge (tracking intervals gives you on average 44 checks until breakage, vs 36 simplified, or 624 vs 600 checks on a magic or sturdy item).

## Experience & Leveling

You gain experience primarily through recovering treasure: 1f. recovered = 1XP (so 4XP per 1d. recovered) Also, each new dungeon room or hex **explored and mapped** grants 10 XP per character. Each hex or room past the fifth in a given delve or adventure begins to grant cumulative XP (i.e. room #6=20XP, room #7=30XP, etc.). The referee can optionally multiply this per-room number by the dungeon's level or hex's distance from civilization to account for the party's growth & added difficulty. Once the party returns to safety to heal and restock, the counter resets. A room or hex can only ever be “explored” for XP in this way once.

The table below indicates what a character's XP total needs to reach to advance to each level:

| Level | Total XP | Warrior Hit Dice | Mage Hit Dice |
| :---: | :------: | :--------------: | :-----------: |
|   1   |    0     |       1d8        |      1d6      |
|   2   |  2,000   |       2d8        |      2d6      |
|   3   |  4,000   |       3d8        |      3d6      |
|   4   |  8,000   |       4d8        |      4d6      |
|   5   |  16,000  |       5d8        |      5d6      |
|   6   |  32,000  |       6d8        |      6d6      |
|   7   |  64,000  |       7d8        |      7d6      |
|   8   | 120,000  |       8d8        |      8d6      |
|   9   | 240,000  |       9d8        |      9d6      |
|  10   | 360,000  |      9d8+2       |     9d6+2     |

Each level beyond 10 requires an additional 120,000XP and adds only a flat 2HP per level, with no Con modifier being applied.

## Falling

Damage from falling is determined as follows: Falls of less than 5 ft do no damage in game terms, falls of up to 10 ft cause 1d6 damage, falls of up to 20 ft cause 3d6 damage, falls of up to 30 ft cause 6d6, 40 ft is 10d6, 50 ft is 15d6, and falls of over 50 ft cause 20d6 points of damage.

## Fatigue

Fatigue represents a serious depletion of body, mind, or spirit.

| Fatigue Level |                   Effect                   |
| :-----------: | :----------------------------------------: |
|     Light     |  -2 to attacks, checks, and Morale checks  |
|     Heavy     | Raise above to -4, +1 level of encumbrance |
|  Exhaustion   |     Halve HP, +2 levels of encumbrance     |

Possession four or more levels of fatigue results in death. Fatigue levels from different sources stack.

A character exposed to any of the causes of fatigue below gains one fatigue level at the increments listed next to each cause (e.g. every full day without water applies one level).

| Cause of Fatigue  | Fatigue Level Increments |
| :---------------: | :----------------------: |
| Unable to breathe |  30 seconds (3 rounds)   |
|   Lack of water   |       Days 1/2/3/4       |
|   Lack of sleep   |     Days 2/4/8/--\*      |
|   Lack of food    |     Days 2/10/20/30      |

\*A lack of sleep can only apply up to three fatigue levels, i.e. it cannot kill you alone.

Per positive Con modifier point, a character can ignore 30 seconds without air, or one day of a lack of water, sleep, and/or food.

If total exposure to a cause of fatigue is avoided (e.g. a bit of water drank, a fitful nap here or there), the current fatigue level increment is doubled.

## Healing

A character will recover 1 HP by resting overnight in a safe and comfortable location, assuming a meal of poor quality has been eaten. A character who dines on common food will recover 2 HP overnight, and a character who dines on fancy food will recover 3 HP overnight. A character will heal HP equal to their level per day of uninterrupted rest. Even while adventuring, a character might get a comfortable night's rest (see [Wilderness Exploration > Rest Checks](#rest-checks)) and naturally heal HP. 30 days of rest will return any character to full HP.

## Item Saving Throws

Generally, only creatures make saving throws. However, some items are especially fragile, and some rare effects (like area-effect attacks or puddings/oozes) specifically target objects. A failed item save results in the item's destruction, while a successful save results in no damage or effect.

If a creature must make a saving throw and it passes, no item carried by that creature needs to make a save unless the effect specifies otherwise.

**Fragile items** can be almost anything (not including weapons, armour, or typical adventuring gear), but most notably include potions, scrolls, and wands that is equipped (kept close at hand, so that they're usable in combat without requiring an action to draw). The price of having such useful items at hand for immediate use is that they're vulnerable to destruction. For example, a potion in a backpack is not available for drinking in combat, but at the same time, if its owner is hit by a fireball, the potion is safe. Fragile items are the exception rather than the rule, and tend to be consumable, creating a risk to their use.

- **Area-effect Attacks**: Affect any item that's both fragile and equipped. Daunting (11+) save.
- **Bashing Containers**: Potions in a container require a Hard (14+) save, while scrolls, wands, and gemstones require a Moderate (8+) save.
- **Disintegration**: Affects all equipped items, fragile or not. Very Hard (17+) save, Hard (14+) if the item is magical.
- **Falls**: Affects carried potions (equipped or not), requires a fall of at least 20' onto a hard surface. Hard (14+) save, -1 penalty for each additional full 10' fallen over 20'.
- **Magic Items**: Any that provide magic attack, save, or AC bonuses apply this modifier to any save such items are forced to make.
- **Shields**: If used to provide a save bonus against a breath weapon attack, and the shield's wielder fails their save, the shield must save as well. The save is Moderate (8+).
- **Water**: Affects paper and parchment, Heroic (20+) save. Standard spellbooks (with vellum pages and magical inks) and scrolls in scroll cases always pass their save.
- **Other Cases**: Cases not covered above are a Hard (14+) save.

## Jumping

**Long jumps**: Characters can jump across a stream, chasm, or pit of up to 5' wide with a 10' run-up--no roll is required. For longer jumps of up to 10', a Daunting (11+) Strength check is required. In combat, a jump ends your move.

**High jumps**: Characters can jump over obstackles of up to 3' high with a 10' run-up--no roll is required. For higher jumps of up to 5', a Daunting (11+) Strength check is required.

**Modifiers**: The difficulty level is lowered one tier if the character has the Jumping skill, raised one tier (usually to Hard (14+)) if the character is wearing Medium armour, and two tiers (usually to Very Hard (17+)) if wearing Heavy armour.

## Lifting

The encumbrance rules are the standard way to measure how much a PC can carry around (see p. 30). However, to quickly calculate the maximum a character can lift or push, use their Strength × 15 in pounds.

## Light & Vision

Wise characters carry illumination--magical or mundane--when exploring at night or underground. Typical light sources enable normal vision within a particular radius. A party needs one light source for approximately every three members of the party.

Note that light sources can be seen from much further away than the illumination they shed for those holding them. Approaching light will warn intelligent creatures of the approach of surface-dwellers, perhaps giving them a chance to prepare; creatures around a corner can see a light source whose radius projects around that corner, while two corners between prevent its detection.

**Low light**: In low light conditions (e.g. at night without a light source, or if a party has insufficient light sources), characters suffer a -2 penalty to attack rolls and move at half speed.

**Pitch darkness or blindness**: Characters in pitch darkness or blindness suffer a -4 penalty to attack rolls, armor class, and saving throws, and have Speed 10. A character with the Blindfighting skill would not suffer the penalties while in combat.

## Lockpicking

Characters with the proper tools and either the Lockpicking feat or skill can attempt to pick locks. This is a Dex check, the difficulty scaling with the locks' complexity. If a character's lockpicking ability is from a feat rather than a skill, the difficulty should be a level lower.

A lockpicking attempt requires 1 turn. If a character fails, they can try again, but after two failed attempts, the character cannot try that lock again until they gain a level.

### Trapped Locks

Noticing a trap on a lock requires a successful Perception check (having the Lockpicking feat reduces the difficulty to notice such traps by one level). Only an active search for traps can reveal such traps without triggering them. In the case of multiple traps on a single lock, the referee will roll a separate Per check for each trap.

A successful lockpicking attempt disarms all detected traps in addition to opening the lock, but undetected traps will be set off automatically before any lockpicking roll is made, unless specified otherwise.

## Magic & Spells

### Creating Potions

Potions can be crafted by any mage of 5th level or above, with the aid of an alchemist (or with the Skill), and only one potion may be made at any one time.

Potion brewing requires a stocked laboratory of at least 500d. in value. A mage can only brew potions they have drank or own the recipe for, and costs silver per dose to brew; the referee will have these costs.

### Gaining New Spells

Mages learn one random spell each time they gain a level from a random school they can access (plus another spell if a specialist). If the caster has just gained access to a new spell level, the spell(s) are from that level. They can also gain access to new spells via the following methods:

- **Binding**: Anyone that can read Mithric can read a spellbook or scroll to see what it is, but you cannot prepare and thus cast a spell until you have bound it to you. Only spells from schools the caster can access can be bound. Binding a spell takes 1 week + 100d. per level of the spell, and a successful Moderate (Arc x2) check, rolled at the end of the binding period; apply +2 if a specialist is binding a spell from their specialist school. Failure means the spell is permanently erased from the source scroll or spellbook. Success means that the spell has been copied to your own spellbook, and that a permanent bond between the caster and spell has been created: you can always write the spell into a spellbook or scroll, even if you don't have another written copy on hand to reference or have the spell prepared for casting.
- **Research**: Casters can research new spells. These can be variants of spells the caster already knows--a Hard (Arc) check--spells the caster has witnessed being cast--a Very Hard (Arc) check--or spells the caster has only heard of--a Heroic (Arc) check. Only spells from schools the caster can access can be researched, and any given spell can only be attempted once per level. Researching a new spell requires, on average and per level of the spell, 1d4+1x50d. in materials and 1 week.

### Spell Slot Progression Table

This shows the number of spells of a given spell level that a caster can prepare per day (also known as their spell slots). Mages are the first number, Arcanist Warriors are the number in parentheses. If the mage is a specialist, they add one to each level's spell slot total, but the extra spell must be from the school specialized in. If a spell is level-adjusted through feats, that spell is treated in all ways as a spell of the level to which it has been modified.

| Mage Level |  1   |  2   |  3   |  4   |  5   |  6   |
| :--------: | :--: | :--: | :--: | :--: | :--: | :--: |
|     1      | 2(1) |      |      |      |      |      |
|     2      | 3(1) |      |      |      |      |      |
|     3      | 3(1) | 1(1) |      |      |      |      |
|     4      | 3(1) | 2(1) |      |      |      |      |
|     5      | 4(2) | 2(1) |      |      |      |      |
|     6      | 4(2) | 2(1) | 1(1) |      |      |      |
|     7      | 4(2) | 3(1) | 2(1) |      |      |      |
|     8      | 5(2) | 3(1) | 2(1) |      |      |      |
|     9      | 5(2) | 3(1) | 2(1) | 1(1) |      |      |
|     10     | 5(2) | 3(1) | 2(1) | 2(1) |      |      |
|     11     | 5(2) | 4(2) | 3(1) | 2(1) |      |      |
|     12     | 5(2) | 4(2) | 3(1) | 2(1) | 1(1) |      |
|     13     | 6(3) | 4(2) | 3(1) | 2(1) | 1(1) |      |
|     14     | 6(3) | 4(2) | 3(1) | 3(1) | 2(1) |      |
|     15     | 6(3) | 5(2) | 4(2) | 3(1) | 2(1) | 1(1) |
|     16     | 6(3) | 5(2) | 4(2) | 3(1) | 2(1) | 1(1) |
|     17     | 6(3) | 5(2) | 4(2) | 3(1) | 3(1) | 1(1) |
|     18     | 6(3) | 5(2) | 4(2) | 4(2) | 3(1) | 2(1) |
|     19     | 6(3) | 6(3) | 5(2) | 4(2) | 3(1) | 2(1) |
|     20     | 6(3) | 6(3) | 5(2) | 4(2) | 3(1) | 2(1) |

### Preparing & Casting

**Preparing Spells:** Once a spell is mentally in place, it remains until either intentionally dismantled or the caster uses the spell. If a spell is unused, it remains in the caster's mind, even though sleep has occurred.

To reconstruct spells (called "memorizing" or "preparing" them), a caster must first have a night's rest (at least 4 hours of uninterrupted sleep) and no fatigue levels from exhaustion or lack of sleep, to regain the clarity and focus needed. The time required to prepare a spell is 10 minutes per spell level of uninterrupted concentration. For example, a third-level spell would require 30 minutes to prepare. A caster can prepare no more than two uses of the same spell.

**Spell Disruption**: If, between declaring a spell and casting it, the caster is hit by an attack or the like (even if no damage is dealt), or fails a saving throw, the spell is disrupted: it fails and its spell slot is emptied with no other effect. Note that only spells being cast can be disrupted. Spell effects from a rod, staff, wand, etc. and spell-like innate creature abilities are immune to disruption.

### The Schools of Magic

All spells belong to one of eight schools of magic. A caster can only learn spells from schools to which they have access. A caster gains access to a new school of their choice at every name level, learning random spells belonging to that school, one at each level they can cast. The schools are:

- **Abjuration**: Spells protective in nature. These frequently ward against damage or hostile effects, like gas, poison, possession, etc.
- **Conjuration**: Spells that summon creatures or objects, from a simple fog to extraplanar entities that serve your every whim.
- **Divination**: Spells that reveal information, from hidden traps and chambers to items and fell secrets.
- **Enchantment**: Spells that affect the minds of others and bend life to your will--men, monsters, and even plants--making them angry or ambivalent, docile or dependent.
- **Evocation**: Spells that shape raw magic itself. Most purely offensive spells (like _Magic Missile_, _Fireball_, etc.) belong to this school, making it nearly mandatory for any aspiring battle wizard.
- **Illusion**: Spells that deceive; imaginary sounds, smells, objects, creatures, and even entire environments are possible.
- **Necromancy**: Spells manipulating the energies of life and death, covering both healing the living and interactions with the dead (and undead).
- **Transmutation**: Spells that alter the properties of a creature, object, or environment. One can fly, breathe underwater, or gain great strength, alter the size of a creature or object, or transmute one type of material into another. Sometimes called "Alteration."

### Scrolls

Spells can be bound to scrolls; each holds one spell. Holding it with both hands and reading from it aloud casts its spell, disintegrating the scroll.

A spell on a scroll is not a prepared spell and can be cast even if the caster does not own the spell or isn't able to cast spells at that spell's level. The caster must still have access to the school to which the spell belongs, however. Spells on scrolls can't be modified through feats, though a caster can scribe a modified spell, and spells can't be prepared from scrolls.

For the purposes of range and so on, a scroll spell is treated as if the reader is casting it normally or is the minimum level required to cast it normally, whichever is higher.

Scrolls may be scribed by anyone who has the ability to both read scrolls and to cast the spell being scribed. It costs 250d. and one week per level of the spell, which can be broken up into multiple sessions. This is a Moderate (Arc x2) check, rolled in secret by the referee at the end of the week. On a roll of a 1, the referee rerolls: a result of 1-10 means that a cursed scroll has been created.

**Creating Magic Items:** Potions are created by alchemists, with the more powerful potions usually requiring the help of a Magic-User. A Magic-User seeking to create potions must employ an alchemist. A Magic-User must be 9th level to create potions on their own, and 11th level to create other magic items.

### Spell List

See full spell list [here](/spells.md).

## Mapping

Maps are usually best made simply: boxes and lines are sufficient to keep you from getting lost. The players' map represents an actual in-game object. If the players at the table are making a map, then a character must also be making one and have the tools to do so. This has several corollaries: the party must have light (they can only map what they see) and mapping supplies (something to write with and something to write on), and they must be moving at a cautious exploration rate. Perhaps most importantly, a map being actively made is a fragile item (see [item saving throws](#item-saving-throws))--if something happens to the map in-game, it happens to the players' map as well! If the party wants backup copies, the players must actually draw them. If the entire party dies in the dungeon, the only way their maps will survive is if copies were left on the surface.

## Moving Silently

Anyone can attempt to sneak. A check is called for when attempting movement that normally attracts attention, such as slipping past a guard, or maneuvering behind a target for a surprise attack.

Moving silently requires a successful Dex check, the difficulty of which is set by the referee, and which is rolled in secret by the referee. While a failed move silently check will alert the enemy in some fashion, it does not necessarily give away your position, let alone imply a bumbling, noisy disaster.

A move silently attempt reduces your movement to 1/4 (normally, to 10' per round). Every additional 10' per round added to that movement rate raises the difficulty by one level.

- **Alert Enemies**: The attention of most intelligent undead (e.g., skeletons, zombies) and constructs (e.g. golems) never wavers. As such, the difficulty of move silently checks against them is one difficulty higher.
- **Armour**: If wearing non-magical medium or heavy armour, increase the difficulty by one level.
- **Group Checks**: If a group attempts to sneak together, this is a group check, with the difficulty based on the group's least stealthy member.
- **Surprise**: Moving silently can be used to set up surprise attacks.

## NPC Spellcasting

Non-player characters may be hired to cast spells or perform other services. As a general guideline, spells cost _roughly_ the following, and will be subject to a host of in-the-fiction considerations:

| Spell Level | Cost per Casting |
| :---------: | :--------------: |
|     1st     |       25d.       |
|     2nd     |       50d.       |
|     3rd     |      100d.       |
|     4th     |      200d.       |
|     5th     |      500d.       |
|     6th     |     1,000d.+     |

Sages or alchemists not employed by a PC will often charge around 50d. to identify a potion (which takes an hour or so), or 100d.+ to identify a magical item (which can take upwards of a week).

## Perception Checks

Perception checks are always made in secret by the referee. There's no requirement for players to constantly state that they're doing basic investigative tasks that are repetitive and/or obvious, like "I'm looking at the floor" or "I'm listening for noises." The slow pace of cautious exploration accounts for these.

However, sometimes a scenario involves something unusually subtle or a creature has the abilities or has taken the effort to evade typical scrutiny, and calling out a specific action might be required.

Overall, checks aren't made just to use one's eyes or ears or otherwise notice the obvious. A Perception check only occurs when the rules call for one (e.g. looking for traps or secret doors), or if the referee decides one is needed.

For a group Perception check, the referee applies the group's average Per modifier, if any, rounding normally. For checks by individuals with a positive Per modifier, _twice_ the searcher's bonus is applied.

## Retainers

Retainers cost 50d. on initial hire (+50d. to request a class), plus ½ share of treasure. They will be level 1d3, but cannot be higher than the hiring PC’s level. Retainers' starting Morale typically ranges from 18 (the craven) to 6 (the elite), and can be randomly determined at hiring with a 2d6+6 roll.

Loyalty is checked with a Morale roll after each adventure, if the retainer is reduced to 1/4 or less of its full HP total, or if their loyalty is severely tested. If a success is rolled, the retainer’s Morale threshold decreases by one to a minimum of 6. On a failure, the retainer departs. If a retainer dies while in your service, your character is expected to pay the retainer's family a weregild of 100d. or its equivalent.

Porters/torchbearers come with no equipment. Equipment purchased by the PC is kept by the PC. Retainers come with the same basic starting equipment as PCs, but no starting silver. Stats, specializations & feats are rolled randomly, and no skills are included (but can be chosen if a player ends up playing the retainer as a replacement for a lost PC, for example).

Starting armour is based on class. Mages roll 1d6-1; Warriors roll 1d6+1:

- 0-1=No armour (AC 9)
- 2-3=Leather (AC 12)
- 4-5=Ring (AC 13)
- 6=Scale (AC 14)
- 7=Chainmail (AC 15)

Choose a weapon option:

- Option A: One medium melee weapon & a shield
- Option B: One large weapon
- Option C: Two medium one-handed weapons (+1 to hit)
- Option D: One medium melee weapon & one ranged weapon (plus ammo)

If appropriate, the referee can choose to roll on the Offer Reaction Table below--applying modifiers based on party reputation, the mission description, or lavish or miserly rates of pay if desired--to decide the potential retainer's reaction:

| 2d6  |  Reaction to Offer   |
| :--: | :------------------: |
|  2   | Hostilely declines\* |
| 3-5  |       Declines       |
| 6-11 |       Accepts        |
|  12  | Eagerly accepts\*\*  |

\* The reaction is so bad that the NPC spreads negative rumors about the PC and/or party, resulting in a -2 on further hiring rolls on this table if the PC and/or party attempt further recruitment in this area.  
\*\* Permanent -1 bonus to the retainer's Morale threshold.

## Sailing

Sea travel usually involves an individually owned vessel or a charter. Scheduled services are rarely available. Passengers must make inquiries at harborside, and pay for passage on a ship heading to their intended destination, or perhaps to some port along the way.

For game purposes, most trade occurs between important ports, separated by one week of sailing time. Ships typically spend one week in port off-loading and on-loading cargo, finding passengers, and perhaps engaging in a little recreation. Sailing to an intended destination is called a _voyage_, and each trip to a port on the way is called a _leg_. A voyage may have only one leg, or it may have several.

**Passengers**: While cargo is another matter entirely, there are two types of passengers: deck passengers and cabin passengers.

_Deck passengers_ pay a 20d. fee per leg to sleep on the deck with the rest of the crew. They provide their own food, or buy it from the crew. The wealthy can travel as _cabin passengers_ for 200d. per leg, and take a cabin. Most ships have one or perhaps two cabins, for the captain and the windcaster. Larger ships may have additional cabins for the owner and their family to use if aboard, and cabin passengers usually use these extra cabins for their accommodation. They also must provide their own food. _Working passage_ can be secured if the captain has a crew shortage; instead of paying wages, the captain provides passage. This usually does not continue for more than three legs of a voyage, or the individual is considered to be hired for standard salary.

**Ship Crew**: A merchant ship will have both an owner and a captain (who may or may not be the same person), a steersman, navigator, merchants on board, sailors, and rowers. Many positions can be taken by the same person.

**Navigation**: Compasses and astrolabes help sailors find their way, but advanced tools like sextants do not exist. Navigators try to keep the coast in sight at all times, looking out for landmarks along the route. At night, the ship pulls up on a beach or into a bay where it can shelter for the night, the crew camping on the beach. When storms threaten, ships likewise head for the safety of land. Some of the larger ports have lighthouses, guiding ships toward them rather than warning of dangerous reefs. Crossing the deep sea is a dangerous thing – here be monsters, and the tales are all true.

Once a ship has left port, it will be at sea for usually a week. The navigator makes a roll to successfully chart a safe course for the vessel, creating a dice result that the helmsman may have to then overcome with his pilot skill.

Navigator’s Result: 6 + 1d6 – navigator skill (1 if skilled, 2 if expert).

Next, the referee rolls 1d6 for that leg of the journey to determine any potential hazard. If a hazard occurs, the helmsman must avoid the hazard by rolling equal to or over the navigator’s result on 2d6. He may add his piloting skill as a positive modifier (1 if skilled, 2 if expert).

| Die | Type of Hazard                                           |
| :-: | -------------------------------------------------------- |
|  1  | **Reef**. Roll for damage +1.                            |
|  2  | **Prone to Storm**. Roll for damage. Immediate landfall. |
|  3  | **Sandbank**. Roll for damage.                           |
|  4  | **Prone to Squall**. Roll for damage -1.                 |
| 5-6 | No hazard.                                               |

**Encounters at Sea**: During the ship’s time at sea, it may encounter another ship or perhaps wreckage. The referee rolls at least once once per week, with the rolled encounter occurring during a point in the journey decided by the referee. If a dash is shown, then no encounter occurs. The encounter may be routine, or it may involve interaction, or even combat.

| Dice | Coastal Encounters   |
| :--: | -------------------- |
|  2   | Vessel in trouble    |
|  3   | Pirate/marauder ship |
|  4   | Wreckage             |
|  5   | Vessel with secret   |
|  6   | Merchant ship        |
| 7-8  | --                   |
|  9   | Military patrol      |
|  10  | Royal courier ship   |
|  11  | Familiar vessel      |
|  12  | Monster              |

| Dice | Deep Sea Encounters  |
| :--: | -------------------- |
|  2   | Vessel in trouble    |
|  3   | Merchant ship        |
|  4   | Wreckage             |
|  5   | Pirate/marauder ship |
|  6   | Monster              |
| 7-8  | --                   |
|  9   | Monster              |
|  10  | Pirate/marauder ship |
|  11  | Merchant ship        |
|  12  | Military patrol      |

### Maritime Trade

Usually ¼ of the profits of a given voyage go to the captain, from which he pays the crew and any outstanding expenses. The rest goes to the owner and any partners he may have. Many merchant captains own their own ship.

#### Ship Expenses

Some basic running costs:

1. **Supplies**: Food and water for each crewman, costing 4d./week.
   Passengers bring their own supplies.
2. **Wages**: Crew wages are paid every four weeks, typically at a
   port.
3. **Cargo Handling**: Ports charge every ship a fee for taking up
   space on the quayside, and for unloading cargos. The cost is usually
   4d./week. Merchant ships who shift their own cargo pay half this
   fee.
4. **Repairs**: Each ship strength point repaired takes one week and
   costs 20d. in materials.
5. **Taxes**: Vary, but usually 2% of the flat cost of cargo or trade
   goods. A captain does not pay the tax on a contracted cargo, the
   recipient awaiting delivery does that.

| Position    | Monthly Pay |
| ----------- | ----------- |
| Captain     | 250d.       |
| Navigator   | 175d.       |
| Helmsman    | 150d.       |
| Windcaster  | 100d.       |
| Senior Crew | 60d.        |
| Crew        | 40d.        |

#### Revenue

Ships generate revenue transporting cargo and passengers from one port
to another. The captain must inquire at the port for a week to determine
availability. Roll once for each column a maximum of once per week. The
cargo/passengers will be heading for the ship’s next destination (which
must be stated beforehand).

| Type of Port        | Deck Passengers | Cabin Passengers | Contracted Cargoes |
| ------------------- | --------------- | ---------------- | ------------------ |
| Minor (V and below) | 1d6-1           | 1d6-5            | 1d6-3              |
| Medium (III-IV)     | 2d6-1d6         | 1d6-3            | 1d6-1              |
| Major (I-II)        | 3d6-1d6         | 1d6-1            | 1d6+2              |

**Cargo**: The captain chooses either a small (1d6 ton), medium (1d6x5
ton) or large (2d6x10 ton) cargo, as fits the size of his ship. The
payment for shipping this cargo is received at the destination, at the
rate of 50d. per ton. Any losses must be made up by the captain/owner,
and the recipient at the destination unloads the cargo and pays the tax.
Most cargos will be low cost high bulk, such as grain or wool, oil or
timber. Contractors usually prefer to use well-known and reliable
vessels to transport more costly items.

**Passengers**: Cabin passengers pay well (200d. per leg) but require a
cabin for their journey. They are the captain’s guests and eat with him.
Deck passengers camp out on deck and bring along or buy their own food,
paying 20d. per leg.

**Private Messages:** Ship crews are routinely approached by civilians
to carry private messages, sometimes verbally, but more often in the
form of a letter. These messages will need delivering to an actual
address or location at the destination port. On a 9 or higher on a 2d6
roll, a crew member will be approached in this way. Small payment may be
offered, from 5d. to 25d. Rendering such service is a good way to make
friends and contacts, and perhaps find patrons.

**Speculative Trade Goods**: A designated crew member, usually a
merchant, can buy a cargo in hope of selling it for profit somewhere
else. It requires some money up front, and of course success (and
therefore profit) is not guaranteed.

### Ships

**Sailing Ships** (_knarr_): Tubby merchantmen (50'-70' long, 10'-15' wide) who stow their cargo
directly on the keel and ship’s frame. There’s a deck, used by the crew
for working and cooking and sleeping. A large hatch allows cargo to be
lowered down below deck. There are a pair of steering oars at the stern,
and larger vessels have one or more cabins below the stern deck as a
refuge for the captain, owner, windcaster, and perhaps a passenger. Each
has a mast, maybe two.

**Merchant Galleys** (_dromond_): Long (90'-130') and narrow (20'-30'), fast and
maneuverable. Sometimes used as warships. Helmsmen of merchant galleys
receive a +1 bonus to their skill rolls. The galley is rowed, with
benches down either side and a gangway for movement. There is no ‘below
decks;’ cargo is stacked up in the bow, at the stern, and tied against
the single mast. The advantage of the galley is its ability to row
through calm weather. Galleys have rams and can attempt to sink opposing
ships.

**Coastal Trader** (_karve_): With low sides and a flat bottom, this
ship (30'-50' long, 10'-15' wide) is ideal for coastal work and travel up rivers. It has a single
mast forward, with a square sail and a hatch for cargo. Additional cargo
can be tied down to the deck.

**War Galleys** (_longship_): Long (70'-100') and narrow (10'-15' wide) war galleys are used for royal courier
duties, patrolling, transport of important officials, and for battle.
They have rams at the bow, and raised platforms fore and aft from which
marines can shoot at opposing ships. Artillery pieces are fitted as
standard, and the crews are trained to fight. Most include cabins.

| Ship Type              | Passengers (cabin/deck) | Capacity (cwt\*) | Crew                               | Strength | Cost      |
| ---------------------- | ----------------------- | ---------------- | ---------------------------------- | -------- | --------- |
| Sailing ship, small    | 0/2                     | 70               | 8 sailors                          | 4        | 8,000d.   |
| Sailing ship, large    | 1/5                     | 250              | 12 sailors                         | 5        | 20,000d.  |
| Sailing ship, great    | 3/10                    | 500              | 24 sailors                         | 6        | 30,000d.  |
| Coastal trader, small  | 0/2                     | 10               | 6 sailors                          | 3        | 4,000d.   |
| Coastal trader, large  | 0/4                     | 20               | 10 sailors                         | 4        | 6,000d.   |
| Merchant galley, small | 0/4                     | 100              | 4 sailors, 20 rowers               | 3        | 10,000d.  |
| Merchant galley, large | 1/8                     | 300              | 4 sailors, 50 rowers               | 4        | 30,000d.  |
| War galley, large      | 2/15\*\*                | 4                | 10 sailors, 144 rowers, 15 marines | 4        | 40,000d.  |
| War galley, great      | 4/40\*\*                | 6                | 20 sailors, 270 rowers, 40 marines | 5        | 60,000d.  |
| War galley, colossal   | 6/60\*\*                | 10               | 30 sailors, 572 rowers, 60 marines | 6        | 100,000d. |

\* A hundredweight (cwt) for shipping purposes is equal to 10 stone (i.e. 10 slots)
\*\* usually the shipboard marines

### Naval Combat

When ships encounter one another, they may end up in a confrontation
depending on the situation. This ruleset assumes two sides, with each
comprised of one or more vessels.

#### Damage and Repair

All ships have a hull strength rating. When a vessel is in danger of
suffering damage, either from a reef, sandbank, squall, storm, shipboard
artillery, or monster of the deep, roll 1d6. If the result is equal to
or greater than the ship’s hull strength, lower ship strength by 1. When
a ship only has a strength of 2, it’s taking on water, or has damaged
rigging or sails, and now travels at ½ normal movement. When a ship’s
strength is reduced to 0, it founders at sea and is lost, taking 2d6
turns to sink. If half the crew works to save the vessel, it might (50%
chance) avoid this fate. This takes 1d6 turns and cannot be done if
under attack. All crew and passengers able to jump clear must roll a
Strength saving throw and hit or beat their AC to find debris which will
help them make it to shore. On a failure, usual [swimming rules](##swimming) apply.
Note that wearing medium or heavy armor will cause one to sink and begin
to drown immediately on a failed roll.

Hull strength can be repaired, though it requires a full week while the
ship is brought ashore. It costs 100d. of spare parts, plus timbers
felled from shore, to bring hull strength to full. The crew cannot carry
out any more repairs until those spare parts are replaced at a port.

**Fire**: When a vessel is struck by a flaming missile (or suffers an
incendiary mishap), the referee rolls 2d6. On a 5 or higher, the ship
catches fire with no immediate effect. Every turn after, he rolls again,
and each roll of 5+ results in lowering the vessel’s hull strength by 1.
The crew can try to put out the fire, but it gets more difficult each
turn: on a 2d6, roll 7+ before the first fire damage roll, 8+ before the
second fire damage roll, etc. until the ship sinks or the fire is
extinguished. The difficulty is modified by -1 if all sailors are trying
to put it out, -2 if it’s a galley and has stopped to allow large
numbers of rowers to help, and -1 if marines are trying to put it out.

**Pursuit & Evasion**: To track the distance between ships (or forces if
each side has allies), a range band is used with counters representing
the two ships moving forwards and backwards along the range band. Range
band correspond to certain real-life ranges measured in yards:

- Short: 0 bands – 1-5 yards
- Medium: 1-2 bands – 6-50 yards
- Long: 3-5 bands – 51-250 yards
- Very Long: 6-10 bands – 251-500 yards
- Distant: 11+ bands – 500+ yards

**Encounter Distance**: Under usual circumstances, combatants see each
other at Distant range (1d6+10 range bands). If the ships are ever
separated by 20 range bands or more, then contact between them is lost.

**Time Unit**: Each turn of pursuit, evasion, or combat takes 1 minute.
This is a ship turn.

**Favorable Winds**: One or other of the ships will have the winds in
their favor. A ship lying in ambush around a headland will always begin
combat with favorable winds; otherwise, each ship rolls a contested 1d6
at the start of each turn to determine who has the favorable wind.

**Movement**: A ship will move a variable number of range bands
depending on whether the wind is favorable to it, or unfavorable. In
addition, a successful Hard (14+) navigation check increases speed by 1
range band that turn. Galleys can ignore an unfavorable wind by lowering
the sails and rowing; oars will move galleys at 2 range bands per turn.

#### Into Combat

**Personal weaponry**: At Long range or shorter, missile combat can
begin between the crews of the two ships. Long range applies a -8
modifier to hit, Medium range applies a -4 modifier.

**Artillery**: Artillery weapons are ship-mounted weapons designed to
destroy sails, masts, and rigging, and to smash hull planking to sink
the enemy ship. Large ships may carry 1 artillery piece, great ships may
carry 2, and colossal ships may carry 4.

- Catapults (600 stone wgt., 4 crew, 600d., 1 attack per turn) have an arm under
  tension, flinging its stone or incendiary missile in a high arc. Roll
  2d6 and hit 8+, -4 at Very Long range, -2 at Medium range. Cannot fire
  at Short range.
- Ballista (200 stone wgt., 3 crew, 1000d., 2 attacks per turn) is a
  high-tension metal-framed crossbow throwing spherical stones or
  grappling hooks (up to Medium range). Roll 2d6 and hit 8+, -4 at Very
  Long range, -2 at Long range. Cannot fire at Short range.

**Ramming**: Getting into Short range is not enough, the captain must
also roll 8+ on 2d6. Success indicates a ram attack, with a 1d6+2 test
vs. the opponent’s hull strength. If the test is successful, the
target’s hull strength lowers immediately to 0, and the two ships are
locked together. Failure indicates a mild collision, with the boats
pushing past one another. To ‘unhook,’ a ramming galley can back-oar
with a roll of 7+, and pull away from a target vessel, allowing it to
sink.

**Oar-Shearing**: Rather than ram their ship into another, some captains
prefer to shear oars, smashing through the oars of opposing ships to
immobilize them. Once in Short range, the ship’s pilot must make a 9+
roll on 2d6. A success disables any oar-powered craft until it can raise
its mast (typically taking all available sailors 1d6+6 ship turns).

**Grappling**: If an aggressor does not ram, it can choose to grapple
with ropes and hooks, in an attempt to pull it closer for boarding. This
requires a successful roll of 6+ on 2d6. If the roll fails, the
defending ship may attempt to open range and flee if desired. The
defending ship can also cut the ropes, and will be successful on an 8+
roll on 2d6.

**Boarding**: A ship that has rammed another (successfully or
unsuccessfully) or that has pulled its target closer with grappling
hooks can send across a boarding party. Likewise, a ship that has been
rammed or grappled can send out fighting men to defend itself. Anyone
attacking from a ship that has rammed gets a single combat round of
surprise. When hand-to-hand combat is initiated, the ship turn is
dropped in favor of usual combat rounds.

**Using Fire**: Incendiaries can be shot from catapults, and each
catapult is capable of firing incendiaries up to three times in a single
battle.

## Speculative Trade

Characters can engage in speculative trade from one settlement to another. Profits are far from guaranteed, however, and getting cargo safely to its destination can be its own source of adventure.

Each major settlement will have categories of goods in surplus that it exports (and which thus are bought and sold for a price lower than average) and goods in demand that it imports (and which are thus bought and sold for a price higher than average).

Local prices are determined by a 2d10 roll, and compared to the following table, adding 10% to the resulting modifier if the goods are in demand, and subtracting 10% if the goods are in surplus, before applying the final modifier to the goods' base price. The rolled price modifier represents the characters' best attempts to negotiate a deal, and are good for one week before being re-rolled.

| 2d10 | Price Modifier |
| :--: | :------------: |
|  2   |      -9%       |
|  3   |      -8%       |
|  4   |      -7%       |
|  5   |      -6%       |
|  6   |      -5%       |
|  7   |      -4%       |
|  8   |      -3%       |
|  9   |      -2%       |
|  10  |      -1%       |
|  11  |       0%       |
|  12  |      +1%       |
|  13  |      +2%       |
|  14  |      +3%       |
|  15  |      +4%       |
|  16  |      +5%       |
|  17  |      +6%       |
|  18  |      +7%       |
|  19  |      +8%       |
|  20  |      +9%       |

Player characters may purchase bulk goods by hundredweight (cwt, where 1 hundredweight is 10 slots) up to their carrying capacity (or the carrying capacity of any pack animals, carts or wagons, or ships they may own).

## Strongholds & Domains

Strongholds and domains are as in OSE Advanced, with clarifications and detailed procedures as in [ACKS](https://alexmooney.github.io/ACKS_SRD/Chapter07.html#strongholds-and-domains).

## Swimming

All characters can swim, barring an unusual background. Assuming no current, a land-dweller swims at half their combat speed, and can do so for hours equal to 1/4 their Con score (3/4 speed and 1/2 Con with the Swimming skill); round down. If lightly encumbered, halve the amount of time a character can swim. Higher encumbrance (or wearing medium or heavy armour) causes one to sink and begin to drown if in deep enough water (see [Fatigue](#fatigue)).

## Trap Detection

Spotting a trap is a Perception check. A character can actively search a 10' square for traps. This takes 1 turn; only one person can search a given square at any one time. Subtle but ultimately visible traps and triggers (such as tripwires) should be automatically detected by this; a failed search usually does not trigger traps.

How well a trap is concealed determines the difficulty. The average concealed trap is Very Hard (17+) to spot during cautious exploration, or Daunting (11+) if actively being searched for and not visible.

**10-foot Poles**: Prodding ahead with one or more of these and using cautious exploration gives a 2-in-6 chance of triggering area traps (safely, unless the trap specifies otherwise).

**Area Traps**: Traps that are triggered by moving into a map square (e.g. pit traps, but not trapped doors) are area traps. During cautious exploration, a separate group check is automatically made for each area trap trigger within 10 feet.

# Upgrading Armour and Weapons

## Upgrading Basics

The process of upgrading a piece of equipment always has a number of basic requirements regardless of its type. The following general rules apply:

- Upgrades take the form of tags. Tags add new properties to equipment.
- Each tag is unique and can only be applied to a piece of equipment once.
- Upgrading a piece of equipment with a new tag can only be performed by a dedicated nonplayer craftsperson of the appropriate discipline in a workshop environment.
- Upgrading a piece of equipment with a new tag is a skilled endeavor, taking anywhere from an hour to more than a week depending on the task.
- On your adventures, you may come across equipment already possessing tags; either for sale, offered as rewards, or available through other means.

Due to their extraordinary artisanship and magical reinforcement, magic items can’t be modified using normal artisinal methods. As such, the upgrades presented here can’t be applied to magic items. Furthermore, none of the upgrades presented in this supplement confer “magic item” status to a piece of equipment, though certain upgrades may result in a piece of equipment being considered magical under certain circumstances.

## Upgrading Armour

There are a number of options available to a character to upgrade their armour, from high-cost armour proofing, to useful additions like insulation suitable for cold weather environments. A complete list of these options, as well as cost and any additional requirements, are shown in the Armour Upgrades table below. In addition to the basic rules for upgrading, the following rules apply when upgrading a suit of armour or a shield with a new tag:

- Any prerequisite conditions must be satisfied to apply a new tag, as shown in the Armour Upgrades table.
- Typically, it takes an artisan a full day of work (minimum 8 hours) to upgrade a suit of armour or a shield with a new tag.
- The armour proofing process normally requires a full workweek (5 days) and can only be undertaken by a master artisan. Once added, armour proofing tags can’t be removed from a suit of armour.

### Armour Proofing

The primary method of upgrading armour, proofing is the process of testing and improving a suit of armour’s ability to withstand blows of various types below a certain threshold, being certified as proof against swords, arrows, and warhammers. While all types of armour can be proofed against slashing damage, only medium and heavy armours can be proofed against piercing damage, and only heavy armour can be proofed against bludgeoning attacks.

### Other Upgrades

In addition to proofing, various other upgrades are available to armours meeting the prerequisites for each, as shown in the Armour Upgrades table. Certain upgrades are incompatible, such as the breathable and insulated tags, while others have specific requirements. Certain types of armour upgrade tags may be removable or temporary; when in doubt, consult with your referee.

## Armour Upgrades

| **Tag**                       | **Cost (d.)** | **Prerequisite**                                               | **Properties**                                                                                                                                                                                                                     |
| ----------------------------- | ------------- | -------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Armour proofing: 1st tier** | 1000d.        | Light, medium, or heavy armour                                 | While wearing this armour, if you would take 3 or less nonmagical slashing damage before resistance is applied, you take none of that damage instead.                                                                              |
| **Armour proofing: 2nd tier** | 2000d.        | Medium or heavy armour with the _1st tier armour proofing_ tag | While wearing this armour, if you would take 4 or less nonmagical slashing or piercing damage before resistance is applied, you take none of that damage instead.                                                                  |
| **Armour proofing: 3rd tier** | 3000d.        | Heavy armour with the _2nd tier armour proofing_ tag           | While wearing this armour, if you would take 5 or less non- magical slashing, piercing, or bludgeoning damage before resistance is applied, you take none of that damage instead.                                                  |
| **Breathable**                | 100d.         | Light or medium armour. Incompatible with _insulated_.         | While wearing this armour, you have a +2 bonus on saving throws against fatigue due to extreme heat.                                                                                                                               |
| **Climbing harness**          | 100d.         | Light, medium, or heavy armour                                 | This armour has been modified with a climbing harness around the midriff, comprising leather straps and quick- draws. While wearing it, you gain a +2 bonus to checks to scale vertical surfaces when using a rope or similar aid. |
| **Decorated**                 | 5d.           | Medium or heavy armour and shields                             | This armour or shield is adorned with a holy symbol and allows its bearer to cast _Turn Undead_ without holding a holy symbol.                                                                                                     |
| **Insulated**                 | 100d.         | Incompatible with _breathable_.                                | This armour counts as cold weather gear in conditions of extreme cold.                                                                                                                                                             |
| **Quick-release clasps**      | 200d.         | Light, medium, or heavy armour                                 | You can doff this light armour as an action, medium armour in 1 minute, and heavy armour in 5 minutes.                                                                                                                             |
| **Spiked**                    | 250d.         | Medium or heavy armour                                         | This armour has been modified with spikes, barbs, or another similar feature, and deals 1d4 piercing damage to creatures who hit its wearer with unarmed strikes or natural weapons that aren’t magical.                           |

## Upgrading Weapons

Upgrading weapons follows a branching path system, with available options split into multiple tiers. At first, a weapon can only be upgraded with a limited selection of 1st tier tags depending on its type, each of which “unlocks” one or more options from the next tier. The following additional rules apply when upgrading a weapon with a new tag:

- All prerequisite conditions must be satisfied to apply a new tag, as shown in the Weapon Upgrades table.
- 2nd tier upgrades can only be applied by a trained craftsman, with 3rd tier upgrades requiring the skills of a master artisan.
- Typically, it takes an artisan a full day of work (minimum 8 hours) to upgrade a weapon with a new tag.
- Once added, a tag can’t be removed from a weapon.

### Weapon Upgrade Cost Structure

Upgrading a weapon has a base cost associated with each tier, with subsequent upgrades of that tier costing twice the previous amount for that tier. For example, Erik decides to pay a visit to a local blacksmith in order to have a customized pommel attached to his dagger—adding the balanced tag—for the tier 1 base cost of 100d.. Later, he returns to have the blade honed—adding the sharpened tag—this time costing 200d., with the next 1st tier upgrade costing 400d., and so on.

Upgrades are grouped by tier for the purposes of this cost scaling: continuing with the above example, if Erik then wishes to have the blade of his dagger partially serrated in order to improve its effectiveness when slicing and cutting—adding the superior tag—it would cost 1,000d. (the 2nd tier base cost) provided that the dagger doesn’t already possess any other 2nd tier tags.

| **Tag**                    | **Prerequisite**                                                       | **Properties**                                                                                                                                                                                                                                                |
| -------------------------- | ---------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|                            |                                                                        | _1st Tier (base cost: 100d.)_                                                                                                                                                                                                                                 |
| **Balanced**               | \-                                                                     | You gain a +1 bonus to attack rolls made with this weapon.                                                                                                                                                                                                    |
| **Critical: Sharpened**    | Melee weapons that deal piercing or slashing damage only               | Attacks with this weapon score a critical hit on a roll of one lower than normal.                                                                                                                                                                             |
| **Critical: Sight pin**    | Bows and crossbows only                                                | Attacks with this weapon score a critical hit on a roll of one lower than normal.                                                                                                                                                                             |
| **Critical: Spiked**       | Melee weapons that deal bludgeoning damage only                        | Attacks with this weapon score a critical hit on a roll of one lower than normal.                                                                                                                                                                             |
| **Silvered**               | \-                                                                     | Attacks with this weapon count as silvered for the purposes of overcoming resistance and immunity to nonmagical attacks and damage                                                                                                                            |
| **Wounding: Keen**         | Melee weapons only                                                     | You gain a +1 bonus to damage rolls made with this weapon.                                                                                                                                                                                                    |
| **Wounding: Oiled string** | Bows and crossbows only                                                | You gain a +1 bonus to damage rolls made with this weapon.                                                                                                                                                                                                    |
|                            |                                                                        | _2nd Tier (base cost: 1,000d.)_                                                                                                                                                                                                                               |
| **Brutal**                 | _Sharpened_ or _Spiked_ tag                                            | When you attack with this weapon and roll the maximum result for the weapon’s damage dice, you can roll those dice again and add the new roll to the damage of the attack. If you roll the maximum amount again, you can repeat this process until you don’t. |
| **Enchanted**              | _Silvered_ tag. Can only be applied by a mage of 11th level or higher. | Attacks with this weapon count as magical for the purposes of overcoming resistance and immunity to nonmagical attacks and damage, and features such as the black pudding’s corrosive form.                                                                   |
| **Superior**               | _Balanced_ and _keen_ or _oiled string_ tag.                           | The damage die of this weapon is increased by one size (for example, 1d4 becomes 1d6, 1d6 becomes 1d8, and 1d8 becomes 1d10).                                                                                                                                 |
|                            |                                                                        | _3rd Tier (base cost: 10,000d.)_                                                                                                                                                                                                                              |
| **Masterwork**             | _Brutal_ or _superior_ tag                                             | You gain an additional +1 bonus to attack and damage rolls made with this weapon.                                                                                                                                                                             |

---

# Wilderness Exploration

In a campaign where the journey is as important as the destination (or where there isn't even necessarily a main destination _per se_), overland movement comes into play.

Travel overland is measured in 6-mile hexes. **Travel points** are spent to enter a hex; player characters have travel points based on their [encumbrance](#item-slots). A mounted party has speed 40 (8 travel points per day), and a party travelling with a cart or wagon has speed 30 (6 travel points per day).

The base cost in hex points to enter a hex depends on its terrain type. Unlisted terrain features like great rivers, canyons, etc. can further raise the cost.

|        Terrain Type         | Entry/Search Cost | Lost/Encounters |        Mounts & Vehicles        |
| :-------------------------: | :---------------: | :-------------: | :-----------------------------: |
|  Plains, steppe, farmland   |         2         |     1 in 6      |            May enter            |
| Hills, woods, desert, rough |         3         |     2 in 6      | Mounts must be led, no vehicles |
|  Mountains, jungle, swamps  |         4         |     3 in 6      |      No mounts or vechiles      |

If the party is travelling on a road and does not leave, a hex costs 2 travel points to enter; but only roadside features will be explored; features further from the road are missed.

Travel may be impeded by poor weather, reducing the party's travel points by 2. If this reduces the party's travel points to 0 or below, they can only progress by forced marching.

A party may choose one of two optional march types each day, reflecting its priorities: either caution or speed.

- **Cautious March**: Decrease travel points by one, apply a +1 bonus to all rolls for overland random encounters, and the party has a better chance of tactically favorable encounters.
- **Forced March**: Gain a 50% increase in travel points, but gain one fatigue level at day's end. Can be kept up until a marcher is heavily fatigued. A day of full rest is required to remove one level of forced march fatigue from most creatures.

## Entering a Hex

If a party wants to enter a hex, but lacks some of the points needed, they points they do have are spent towards entering it, but the party ends the day in their current hex. The party only enters the new hex once its full hex point cost is paid.

### Navigation and Getting Lost

If the party enters a hex they have not fully searched, the party makes a **navigation check** by rolling 1d6. The chance of getting lost depends on the terrain being explored (see table above).

There is no chance of getting lost if the party is following a road, and there is only a 1-in-6 chance of getting lost if the party is following a trail or track.

In conditions of reduced visibility, like a thick fog or blizzard, the chance of getting lost increases by 1, and in darkness by 2.

If the party has a member with the Fieldcraft feat for that hex's terrain type, the chance of getting lost decreases by 1.

This check is skipped if the party has a respectable map or knowledgeable guide, or if there is a road, trail, coastline, or river in the current hex they can logically follow to their next hex. The party is assumed to map any hex passed through.

If the check fails, the party is lost. To leave the hex, the party must spend hex points equal to the amount they spent to enter it originally, and then make a new navigation check. Failure means that the party is still lost.

### Searching

Entering a hex allows a party to determine its features. There are two types: **overt** and **hidden**.

Overt features require no special effort to find. Hidden features may or may not exist, but can only be found if the party searches the hex, moving off the beaten path to seek out points of interest there. A hex may have both types.

Searching a hex requires spending the same number of hex points that it cost to enter the hex, and, like entering a hex, is only complete when the full hex point cost is paid. Such a search will reveal any hidden features present in a hex. Once a hidden feature has been located, it can be found again without searching.

## Camping in the Wilds

### Setting up Camp

**Preparing the Campsite:** At least one character must remain at the campsite to clear away branches and rocks, set up tents and bedrolls, prepare a fire pit, and so forth.

**Fetching Firewood:** Each character who goes fetching wood can collect enough to keep a campfire burning for 1d6 hours. Situational modifiers for the amount of wood found may be applied, for example: -1 for damp conditions, -2 in snow, -4 in heavy rain.

### Fetching Water

Finding water to drink is assumed to have happened naturally while traveling, except in an exceptionally dry environment, when it is only found on a 2-in-6 chance per hex.

### Building a Fire

Given a means of producing flame (e.g. a tinderbox, magic) and a stash of wood (either gathered from the forest or carried in packs), a character may attempt to build a fire.

**Good conditions:** In favorable conditions, with decent wood and a relatively dry campsite, fire-building automatically succeeds.

**Bad conditions:** In more troublesome circumstances, getting a fire going requires a Daunting (11+) check, though "Dwarves can make a fire almost anywhere out of almost anything, wind or no wind" and will automatically succeed. However, the referee may reduce the chance of success to account for extreme cold or damp.

### Cooking

Given a fire, cooking pots, and ingredients (e.g., foraged food, fresh rations, hunted game), someone may cook a meal. The cook must make a Daunting (11+) cooking skill check. (Eating trail food does not give any bonuses to Con checks required to rest.)

**If the check succeeds:** An especially tasty dish is produced. All who eat the meal gain a bonus to any Con checks required to rest: +1 for meals made with poor ingredients, +2 for meals made with common ingredients, and +3 for meals made with fancy ingredients.

**If the check fails:** A palatable but not exemplary dish is produced. On a natural 1, the cook must make a Daunting (11+) saving throw or produce a ruined and utterly inedible meal, wasting the ingredients used.

### Camaraderie

Time spent around the fireside with one's companions may lift the spirits and induce restful sleep. A character may attempt to entertain with music, song, stirring tales, jokes, and so forth. The entertainer should make a Daunting (11+) check.

**If the check succeeds:** All characters gain a +1 bonus to any Con checks required to rest.

**If the check fails:** The attempt to entertain falls flat. On a natural 1, the entertainer must make a Daunting (11+) saving throw or incur ridicule and discord, incurring a -1 penalty to any Con checks required to rest.

### Rest Checks

When camping in the wild, characters’ ability to get a good night’s rest is determined by their equipment (whether they have a bedroll and/or tent), their warmth (whether they have a fire burning), and the season. Non-ideal circumstances require PCs to make a Con check, with the difficulty listed below.

| Fire | Bed             | Winter         | Spring         | Summer        | Autumn         |
| ---- | --------------- | -------------- | -------------- | ------------- | -------------- |
| N    | No bedding      | Auto failure   | Daunting (11+) | Moderate (8+) | Daunting (11+) |
| N    | Bedroll or tent | Auto failure   | Moderate (8+)  | Good rest     | Moderate (8+)  |
| N    | Bedroll & tent  | Daunting (11+) | Moderate (8+)  | Good rest     | Moderate (8+)  |
| Y    | No bedding      | Auto failure   | Daunting (11+) | Moderate (8+) | Daunting (11+) |
| Y    | Bedroll or tent | Daunting (11+) | Good rest      | Good rest     | Good rest      |

**If the check succeeds:** The character gets a good night’s sleep and regains 1 HP overnight if they ate a poor meal or trail food, 2 HP if they ate a common meal, and 3 HP if they ate a fancy meal.

**If the check fails:** The character fails to get a good night’s sleep and suffers one level of fatigue due to lack of sleep. For each spell the character attempts to memorize, there is a 1-in-6 chance of failure. If the roll fails, the attempt to memorize fails - the spell slot remains empty and unusable this day.

## Finding Food in the Wild

When on a journey, a party may try to find food in the wilds rather than rely on rations purchased in a settlement. The party may choose to fish, forage, or hunt.

If the party attempts to find food as they travel, the default difficulty of the check is Very Hard (17+). If the characters devote a whole day exclusively to finding food, without travel or rest, the difficulty is Daunting (11+). A single check is made for the entire party. A character with The Fieldcraft feat has an easier time finding food, and makes the check one tier easier.

### Fishing

Using a fishing pole, hook, and something for bait, fishing is possible in any hex which contains a lake or river. Successful fishing provides 2d6 rations.

### Foraging

Plants and mushrooms can be found in many hexes. Successful foraging provides 1d6 fresh rations (1d4 in winter, 1d8 in autumn). Rare and magical herbs may also turn up in the harvest.

### Hunting

Successful hunting means that the party has crept up on game animals, and must then attempt to kill them. The party has surprise and beginning combat 1d4 x 30' away from the quarry. A successful hunt yields fresh rations based on the HP of game animals killed: 1 ration per HP for small animals, 2 rations per HP for medium, and 4 rations per HPH for large.

## Weather

At the start of each day, the referee rolls 1d8 (the travel die) and 1d6 (the combat die).

On a roll of 1 on the travel die, heavy rain, snow, a sandstorm, or other similar natural environmental hindrance appropriate to the terrain occurs, and the party's travel points are reduced by 2. If rain is falling, the good roads hex terrain bonus does not apply that day to dirt roads (most of them), as they are rapidly reduced to mud.

On a roll of 1 on the combat die, strong winds occur: apply the poor conditions modifier to outdoor missile attacks that day, and _Fog_, _Stinking Cloud_, _Cloudkill_ and any similar effects do not function outdoors.

If both dice show a 1, then visibility is poor: the distance at which encounters occur is halved, and the chanced of getting lost while traveling off-road is increased by 1.

## Wilderness Random Encounters

One check for wandering monsters is made each day. The chance of an encounter depends on the type of terrain being traversed. If a party has one or more members with Fieldcraft for that hex's terrain type, add 1 to the roll.Wandering monsters are encountered 2d6 x 30' away. If both sides are surprised, this is reduced to 1d4 x 30'.

If the party spends the night in the wilderness, an additional random encounter check is made. If an encounter occurs, the referee randomly rolls to see on whose watch (if any) the encounter takes place.

# Hirelings

## Standard Hirelings

Short-term services of simple craftsmen and laborers are relatively easily procured, but it is harder to find individuals willing to take service for longer than a few days, especially if considerable travel is involved.

| Hireling                              | Daily Rate | Monthly Rate |
| ------------------------------------- | ---------- | ------------ |
| Groom, Laborer, Linkboy, Pack Handler | 1d.        | 24d.         |
| Cook, Servant                         | 1d. 2f.    | 30d.         |
| Limner                                | 2d.        | 50d.         |
| Teamster                              | 3d.        | 72d.         |
| Carpenter, Mason, Leatherer, Tailor   | 4d.        | 100d.        |

**Carpenter**: Skilled in the working of wood, a carpenter might be retained to construct anything from a table to a palisade. Their expertise is also invaluable for the manufacturing of shields and similar items.

**Cook**: Familiar with the preparation of various types of food, and sometimes also knows a little herblore.

**Groom**: Proficient in the care of horses, an attentive groom can usually tell a good mount from a bad; also known as an ostler or stable hand.

**Laborer**: Essentially unskilled, laborers are suitable for only the most menial sorts of work; this category includes bearers and porters, each of which is able to carry up to 12 slots of items, or twice that if a pole or other contrivance is utilized.

**Leatherer**: Capable of producing a wide range of leather goods, such as packs, belts or riding gear; a leatherer is indispensable for the making of scabbards, sheathes, shields and the other leather components of arms and armour.

**Limner**: Adept in the painting of signs and the illumination of heraldic devices, among other similar tasks.

**Linkboy**: Usually hired to bear a lantern or torch, a linkboy is typically (but not always) a youth.

**Mason**: Expert in the working of stone or plaster, masons are essential for the construction of many significant buildings and fortifications.

**Pack Handler:** Practiced in the burdening, handling and unburdening of various pack animals.

**Servant**: Typically serving as valets, butlers, maids, messengers or simple lackeys, servants are expected to look to the needs of their master.

**Tailor**: Accomplished in the repair and making of clothes or other cloth items; the services of a tailor are also required for the production of various types of textile based armour and coverings.

**Teamster**: Experienced drivers of carts and wagons, teamsters are usually experts at loading and unloading their vehicles, as well as handling the animals with which they are familiar.

## Mercenaries/Men-at-Arms

Mercenaries are as on pgs. 112-113 of _OSE Advanced._ The majority of regular men-at-arms are zero-level characters with 1d4+3 hit points. The following additional mercenaries are available (and in some cases required):

**Captain**: Equivalent to a 5th- to 8th-level warrior (1-4=5th, 5-7=6th, 8-9=7th, 0=8th). A captain may lead 20 men at arms and one lieutenant per level of experience, plus any necessary sergeants; the monthly wage demanded by a captain is equal to his level x 100d..

**Lieutenant**: Equivalent to a 2nd- (1-7) or 3rd- (8-0) level warrior. A lieutenant may lead ten men at arms per level of experience, plus any necessary sergeants. A lieutenant serving under a captain extends the number of troops the captain can effectively command and control. The monthly wage demanded by a lieutenant is equal to his level x 100d..

**Sergeant**: Equivalent to a 1st-level warrior. A sergeant can lead up to ten men independently or in service to a lieutenant or captain. In any given company, there must be one sergeant for every five to ten men at arms. The monthly wage required by a sergeant is ten times that of the troop type he leads.

A player character warrior of the appropriate level may serve as a sergeant, lieutenant or captain, as might an allied non-player character fighter or retainer.

## Expert Hirelings/Specialists

Obtaining the services of very skilled craftsmen and other professional servitors typically involves the expenditure of considerable time and resources. While it is possible to retain such hirelings for short periods, few will agree to a term of less than a month and most expect to serve considerably longer.

| Specialist                 | Monthly Wage |
| -------------------------- | ------------ |
| Alchemist                  | 500d.        |
| Animal Trainer             | 250d.        |
| Armourer                   | 250d.\*      |
| Blacksmith                 | 110d.        |
| Engineer (Architect)       | 250d.\*      |
| Engineer (Artillerist)     | 150d.        |
| Engineer (Miner or Sapper) | 150d.        |
| Jeweler/Gemcutter          | 100d.\*      |
| Sage                       | Special      |
| Scribe                     | 100d.        |
| Ship Crew                  | 60d.         |
| Ship Captain               | 250d.        |
| Spy                        | Special      |
| Steward/Castellan          | Special      |
| Weaponsmith                | 150d.\*      |

_\*Cost does not include all remuneration or special fees._

**Alchemist**: Identify potions and substances. Based on a sample or recipe, an alchemist can produce a potion at twice the normal speed and for half the normal cost (see _OSE Advanced, Magical Research, p126_). An alchemist may also research new potions, but this takes twice as long and costs twice as much as normal.

**Animal Trainer**: Specialized trainers are required for exotic animals or larger numbers of normal animals. A trainer can have up to six animals under their care at a time. It will take a minimum of one uninterrupted month to teach an animal the first new behavior or trick. After this first month, an animal has become accustomed to the trainer and can be taught additional behaviors at twice the rate (two weeks per behavior).

**Armourer**: Required for the production and maintenance of armour and shields; for every 60 men at arms or barded warhorses present, there must be at least one armourer available. Each must be provided with a workroom, forge, and assistants at an additional cost (~100d.). An armourer can use spare time (prorated based on number of supported troops) to make additional armour, helmets, or shields at 25% of their usual cost. Per month, an armourer can make three shields or one suit of armour.

**Blacksmith:** Essential for the basic maintenance of a stronghold and any resident soldiery; for every blacksmith retained the needs of up to one hundred and twenty men or horses can be met, but there must be at least one in every stronghold and a workroom and forge must be provided for each (~100d.). Besides the usual duties (horseshoes, nails, hinges, etc.) a hired smith can turn out some basic weaponry each month: 30 arrowheads or quarrel tips, or 10 spear heads, or 5 morningstars, or 2 flails or polearm heads.

**Engineer (Architect)**: Necessary for the successful construction of any but the most simple of surface structures. An architect requires payment by the month, even for short projects, and expects to receive an additional sum equal to 10% of the total building costs. Unless the construction site was approved by an architect, there is a 75% chance that any structure will collapse in 1d100 months.

**Engineer (Artillerist)**: Mandatory for the construction and correct operation of siege weapons, such as the trebuchet or ballista. No such engines can be made or properly used without the services of such an individual. If employment is for short term only, say a few months or less, then rates of pay and costs will be increased from 10% to 60%.

**Engineer (Miner or Sapper)**: Indispensable for the overseeing of any mining operations, underground construction, or siege and counter siege works that involve trenches, fortifications, assault towers and other similar siege devices.

**Jeweler/Gemcutter**: Able to speedily and accurately appraise the value of most gems, jewelry and other precious objects, a jeweler is also capable of repairing, enhancing or newly creating ornamented items and jewelry. The total value of the materials can be increased by from 10% to 40%, depending on the skill of the jeweler. Likewise, a gemcutter might well increase the value of a rough or poorly cut stone (those under 5,000d. base value), or the stone might be ruined in the process. Note that jeweler/gemcutters cannot be held responsible for damage. Dwarven jeweler/gemcutters add 20% to skill level determination rolls, but cost twice as much to employ.

| Jeweler Skill Level |                                                   |
| ------------------- | ------------------------------------------------- |
| 01-20               | Fair—10% increase 90% likely                      |
| 21-50               | Good—20% increase 50% likely, +10% otherwise      |
| 51-75               | Superior—30% increase 60% likely, +10% otherwise  |
| 76-90               | Excellent—40% increase 70% likely, +10% otherwise |
| 91-00               | Masterful—40% increase 60% likely, +20% otherwise |

| Gemcutter Skill Level |                                                    |
| --------------------- | -------------------------------------------------- |
| 01-30                 | Shaky—d12, one roll, 1 improves, 10-12 ruins stone |
| 31-60                 | fair—d12, one roll, 1-2 improves, 12 ruins         |
| 61-90                 | good—d12, one roll, 1-3 improves, 12 ruins         |
| 91-00                 | Superb—d20,1-5 improves, 20 ruins stone            |

_Note: Note any increase in value as “profit” in your notes (e.g., “ring \[200 d. profit\]”); this counts toward merchantile income for the month._

**Sage**: A person with a degree of knowledge on just about everything, a lot of knowledge in a few specific fields, and authoritative knowledge in his or her special fields of study. Each sage specializes in one or more minor fields of study, and a handful of special categories within a major field of study. Only fighters, paladins, rangers, and thieves are able to hire a sage, though anyone can consult one; a sage will only accept service on a permanent, lifetime basis. As a sage will bring nothing save thinking ability and knowledge, an offer of employment must consider the following:

|                              |                   |
| ---------------------------- | ----------------- |
| Support & Salary per Month   | 100 to 300d.      |
| Research Grants per Month    | 100 to 300d.      |
| Initial Material Expenditure | 5,000d. minimum\* |

_\*A 5,000d. expenditure will allow the sage to operate at 50% of normal efficiency, and for each additional 250d. thereafter, the sage will add 1% to efficiency until 90% is reached (upon expenditure of 15,000d.). After 90%, to achieve 100% efficiency the cost per 1% is 1,000d. (for the obviously erudite and rare tomes, special supplies and equipment, etc. - assuming such are available, of course). All told, expenditures must be 25,000d. for 100% sage efficiency in specific and exacting question areas._

**Scribe**: Practiced in the art of writing, a typical scribe is expected to keep records, write letters and copy documents. Others may possess additional skills, such as cartography, counterfeiting, cryptography, illuminating or the ability to write, read or otherwise comprehend more than one language. Such accomplished individuals might command up to ten times the standard wage.

**Ship Crew**: Skilled workers who can handle a ship. Sailors can fight to defend their ship, typically being equipped with a sword, shield, and leather armour.

**Ship’s Captain**: A captain is required for any large ship, is skilled like a sailor, and has an intimate knowledge of the particular coasts they frequent.

**Spy**: Recruited to secretly watch the actions of others and gather information, fees may vary wildly, from perhaps a mere hundred silver pieces to many thousands, depending on the individual and the difficulty of what is asked.

**Steward/Castellan**: Responsible for the administration of a stronghold in the absence or inability of a player character, a steward holds a position of great prestige and trust. Whilst serving within the stronghold, a steward is capable of leading forty men at arms and two lieutenants for every level of experience he possesses, as well as the necessary number of sergeants. The monthly wage due to a steward is equal to his level x 100d.. A retainer of an appropriate class and level could be appointed as steward.

**Weaponsmith**: Required for the production and maintenance of weaponry; for every sixty men at arms present, there must be at least one weaponsmith available. Each must be provided with a workroom, forge, and assistants at an additional cost (~100d.). A weaponsmith can use spare time (prorated based on number of supported troops) to make additional weapons at a rate of five weapons per month at 25% of their usual cost.
