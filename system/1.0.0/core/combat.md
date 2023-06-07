# Combat
**Notation:**
- U = Unit (Yards or Meters)
  - For our purposes, there is 1 U (yard/meter) for every 3 feet.
    - So to convert from U to feet, divide the sum by 3.
    - To convert from feet to U, multiply the sum by 3.
  - Although yards & meters have slightly different lengths, a concession is made for easy localization.
    - You may replace U with the unit you are most comfortable with when reading anything with this notation.
    - You can even substitute another unit such as an inch or mile if your scale changes significantly.

## Core
This is the basic "rules light" version of combat that's intended to be simple & easy while still covering most things that could happen (with minor concessions). It's the core structure on which more advanced combat systems can be built. Hence why it is part of the Core System.

### Basics
#### Turn Order & Actions
If one side is ambushing the other, they and their allies go first. Otherwise, each combatant makes a COR save to see if they act before their targets. This save reoccurs at the start of each turn. 

### Zones
#### Overview
In combat, characters occupy one of 4 Zones which represent areas close to the combat.

The 4 zones during combat are:
- Grappling
- Close
- Near
- Far

In each zone you can make different attacks.

It takes a number of Move actions equal to the Distance Value of a Zone for a combatant to move in or out of that Zone.

**Name** | **Distance Value (DV)** | **Range (Feet)** | **Allowed Attacks**
:---:|:---:|:---:|:---:
**Grappling** | 0 | 0-1U (0-3ft) | Hand-to-Hand & Light Melee
**Close** | 0 | 1-2U (3-6ft) | Hand-to-Hand, Light Melee, Medium Melee, Heavy Melee†, & Magic
**Near** | 1 | 2-4U (6-12ft) | Heavy Melee, Ranged, & Magic
**Far** | 2 | 4-20U (12-60ft) | Ranged & Magic
**Evade** | 2* | State | Strong Magic

*This is a disengaged State with no relative position in combat. It only costs 2 Move Actions for game mechanic purposes & denotes no rank among the other distances.

†This attack gains Disadvantage in this Zone (without a Feat).


#### Details

In **Grappling - 0** *(0 yards)*, you can attack with:
- Hand-to-Hand
- Light Melee

In the **Close Zone - 0** *(1 to 2 yards)*, you can attack with:
- Hand-to-Hand
- Light Melee
- Medium Melee
- Heavy Melee†

In the **Near Zone - 1** *(3 to 4 U)*, you can attack with:
- Heavy Melee
- Close-Ranged

In the **Far Zone - 2** *(11 to 60 feet)*, you can attack with:
- Short-Ranged

When combat begins, if neither group is **Surprised** (or given other situational advantage/disadvantage), all combatants currently engaged with are in the **Near Zone**. If one group has a significant advantage/disadvantage such as **Surprised** or , the group with the advantage can pick which Zones they occupy 

Generally, Zones should viewed from the  perspective of the group with the advantage in combat with ties being decided by a simple majority at the beginning of combat. “I’m staying back at a Ranged Distance” or “I’m closing to Close Range” is one way to view it. Opponents & Allies move between Zones just as players can, instead of remaining “stationary” as the adventurers move around them.

Think of it like the center of the combat field is the eye of the storm and everything swirls around the combat... or consider it like the rings of an arrow/dart target. Obviously this is an extreme abstraction, as such, the GM should remember that both the opponents & the players actually move, and describe it that way. Zones are meant to abstract relative distance & add positional tactics to theatre of mind combat that lacks miniatures/grids.

Think of it like the combat is the eye of the storm & everything swirls around the center majority of the combat. Alternatively put, it's like the rings of an arrow/dart target. Obviously this is an extreme abstraction, as such, the GM should remember that both the opponents & the players actually move around in their space even when not traversing zones, and describe it that way. Zones are meant to abstract relative distance & add positional tactics to theatre of mind combat that lacks miniatures/grids.

It takes a number of Move actions equal to the Zone # for an combatant to move between zones. Those Move actions allow movement across one Zone. The only exception is moving between close & player can spend a move Action and move from Far to Close, or from Close to Near.

The size of combat is limited by the size of the environment. If the space is 60ft or smaller then Far is the greatest distance possible. If the space is 5ft or smaller then Ranged combat is not possible without Feats or some other sort of special equipment/abilities. Outdoors any distance is theoretically possible

## Extended
This is the slightly more advanced version of combat with less concessions that still comes as a complete standalone system. It's the structure on which more advanced combat can be built. Hence why it is part of the Extended System.

### Basics
#### Turn Order
At the beginning of combat, all engagaged combatants make a COR save called Initiative to see if they act before their targets. 

> Depending on your preferences, the initiative COR save either occurs once at the start of combat *or* it reoccurs at the start of each round. It can be made by each player individually *or* once for each side of the combat. Either way works fine, but **this system defaults to each player rolling individually at the start of each round.**

If one side is ambushing & their opponents are Surprised, the ambushers get a special round before initiative is rolled where they & any other non-suprised opponents go first. Once this round is complete, combat begins as normal. 

Turn order in combat is divided into 3 phases: before your opponent's turn, during your opponent' turn, & after your opponent's turn. Magic is always cast in the 3rd phase after your opponents turn unless you have a feat that says otherwise.

### Actions
On your turn in combat, you can perform one Move Action (move up to 10U) & perform up to two Main Actions. You cannot perform the same main action twice in a single turn.

A main action can be anything from: 

- Attacking a target
- Attempting a Utility Action
- Searching your pack
- Sprinting (Spend 2 main actions for an additional move action)

You can break up one or both main actions into two quick actions if you’d like. Quick actions are for minor things, like pulling a lever, picking up an item, passing off an item to an ally, drinking a potion, etc.

If you are acting in phase 1 (before your opponent), you can opt to hold an action until phase 2 (during your opponent's action) or phase 3 (after your opponent) & use it as a reaction to one of their actions.

#### Attack & Defense
When performing a melee attack, select a target within your weapon's range, then perform a COR save. For ranged attacks, select a target within your weapon’s range, then perform a SEN save. On a success in either case, you hit and deal weapon damage, then your turn ends. 
 
If a player character is getting attacked, they can defend themselves by attempting a SEN save. On a success, the attack deals half of its original damage. If the attacker is a monster that has already missed, no damage is dealt. 

If a player character rolls a natural 1 while attacking, their attack becomes Enhanced. If they roll a natural 1 while defending the enemy attack becomes Impaired. 


#### Enhanced & Impaired
Attacks can also be enhanced by attacking a prone target in melee, attacking an incapacitated enemy, exposing an enemy’s unique vulnerability, etc. Deal double the original damage and this attack cannot be defended against. Attacks can be impaired by attacking a prone enemy at a range, attacking an enemy that’s in cover, fighting unarmed, etc. Deal half the original damage.

#### Dual Wielding
Light weapons can be held in a character’s off hand. If dual-wielding weapons, do not make two attacks. Instead, you may reroll your to-hit save. If your weapons have effects, use whichever one of the two weapons you’d prefer (this may be decided after rolling). 


#### Mounted Combat
Being on a mount in combat lets you exchange your characters movement for the mounts. A horse and warhorse both have a 45ft move and a 25ft sprint. 

If you take critical damage while mounted, you must succeed a COR save to not fall prone on the ground. If your mount has a saddle, gain +2 to this roll. If your mount is a warhorse, you gain +2 to this roll as well. 
If attacking a mounted character, damage targeting the mount (unless it has an area-of-effect) is redirected to the rider. The rider makes the defense saves. Horses have 3 resolve, 1 DEF, 9 MOR; warhorses have 2 DEF. 

Melee attacks targeting unmounted targets while the attacker is mounted are enhanced. 

Unless the rider has a polearm, riders cannot target prone enemies while mounted. 


#### Utility Action
On their turn, a player to attempt a utility action as a main action. If you succeed a utility action, you get what you want, and your turn ends. 

Utility actions are the following: 
- Expose. Make a SEN save, you must have a weapon equipped and the target must be within range of the weapon. On a success, the next successful attack against the target by an ally or the exposer is enhanced. If unused, this effect ends at the end of the exposer’s next turn. 
- Hinder. Make a COR save. On a success, the next attack the target makes is impaired. 
- Push. Make a VIT save, target must be the same size or smaller than you and be in melee range. On a success, the target is moved up to 5ft in any direction. If this causes them to be pushed into impassible terrain (a wall) they take 1d4 damage. 
- Tackle. Make a VIT save, target must be the same size or smaller than you in melee range. On a success, you and the target are prone (melee attacks made against prone targets are enhanced, ranged attacks are impaired). 
- Taunt. Make a WIL save, the target must be within line-of-sight and earshot. On a success, the target must attack the taunter on their next turn or have their next attack impaired. 


#### Taking Damage
Incoming damage first reduces a character’s resolve. When all resolve is reduced to 0, they become bloodied. 

If a bloodied character takes regular damage (including damage that carried over from when they were pushed down to 0 resolve) they must attempt a VIT save minus the amount of damage they took over their resolve. If they fail, they take critical damage. 

If a bloodied character takes fear-related-damage, follow the same rules as above but with a WIL save. On a failure, the character gains the panic condition. 

#### Critical Damage & Death
When a character takes critical damage, they gain the wounded condition, and must make a WIL save. 

If they succeed, they press on. If they fail, they fall incapacitated, gain the peril condition. If a player’s entire pack is full of conditions, they fall incapacitated. Allies that see this must pass a WIL save or gain the panic condition. 

A player can spend a dungeon turn (10 minutes) tending to the incapacitated player, removing one random condition from them, and restoring them to consciousness. This is not a short rest. If left untended for 6 turns (1 hour) they die.

#### Monsters
On their turn, Monsters can perform a 30ft move and one full action (or two quick actions). They cannot perform utility actions.

Monsters replace all saves with MOR (morale) saves. If a monster fails an attack, they still deal half damage to the player. If a player successfully defends against a failed monster attack, the damage dealt is reduced to 0.

If a monster has “critical damage” in their stat block, it details an effect that occurs when the monster deals critical damage to a character.

Monsters can get over or through obstacles (cliffs, stuck doors, etc.) without needing a save, unless the players actively try to stop them. In which case, have the player make a roll to delay the monster’s inevitable advance.

In the case of nailing a door, barricading a path, or doing something else that relies more on the method than the user, the monsters succeed a MOR save.


##### Resolve & Defiance
Monsters’ resolve works the same way the player’s does. When a bloodied monster takes critical damage, and the attacking player succeeds on a VIT save plus the amount of damage dealt over the monster’s resolve, the monster loses 1 defiance (DEF). 

Anytime a monster would gain a condition, instead loses 1 DEF.

When reduced to 0 DEF, it is defeated (it flees, surrenders, or dies). 

##### Rallying
Whenever one of the following situations occurs, monsters that are **not immune to peril must make a rally save (using MOR)**.

- This monster takes critical damage for the first time
- An ally stronger than it is defeated
- This monster realizes its horribly outgunned or outnumbered

On a failure, the monster must flee or surrender.

Monsters can only make one rally save a turn.

Leader monsters allow allied monsters within 45ft to use their MOR for rally saves.


### Zones
#### Overview
In combat, characters occupy one of 6 Zones which represent areas close to the combat. There are 6 zones during combat: Grappling, Close, Near, Far, Removed, & Distant. In each zone you can attack with different weapons:

**Name** | **Distance Value** | **Range (Feet)** | **Allowed Attacks**
:---:|:---:|:---:|:---:
**Grappling** | 0 | 0-1U (0-3ft) | Hand-to-Hand & Light Melee
**Close** | 0 | 1-2U (3-6ft) | Hand-to-Hand, Light Melee, Moderate Melee, Heavy Melee, & Magic
**Near** | 1 | 2-4U (6-12ft) | Moderate Melee, Heavy Melee, Close-Ranged, & Magic
**Far**| 2 | 4-20U (12-60ft | Short-Ranged & Magic
**Removed** | 3 | 20-80U (60-240ft) | Mid-Ranged & Strong Magic
**Distant** | 4 | 80-160U (240-960ft) | Long-Ranged & Strong Magic
**Evade** | 2* | State | N/A
**Flank** | 2* | State | N/A

*This is a disengaged State with no relative position in combat. It only costs 2 Move Actions for game mechanic purposes & denotes no rank among the other distances.


#### Details

In **Grappling - 0** *(0 feet)*, you can attack with:
- Hand-to-Hand
- Light Melee

In the **Close Zone - 0** *(1 to 5 feet)*, you can attack with:
- Light Melee
- Heavy Melee

In the **Near Zone - 1** *(6 to 10 feet)*, you can attack with:
- Heavy Melee
- Close-Ranged

In the **Far Zone - 2** *(11 to 60 feet)*, you can attack with:
- Short-Ranged

In the **Removed Zone - 3** *(61 to 240 feet)*, you can attack with:
- Mid-Ranged

In the **Distant Zone - 4** *(241 to 1000 feet)*, you can attack with:
- Long-Ranged

Regular Magic Attacks or Spells can be used from any Zone.

**Evade** is tracked when the opponent passes straight through without engaging.

**Flank** is tracked when the opponent passes around the side. They are considering to be **Flanking**  & the players are **Flanked**. If flanked by 3 or more opponents in addition to 1 or more within the **Near Zone** then the players are **Surrounded**. 

## Advanced
This is a library of new modular systems (& variations of existing ones) that you can add to your gain without concern of upsetting game balance.
### Zones
Here are 2 other more Zones that may only come into play in niches (or late-game) scenarios & advanced playstyles.

In the **Visible Zone** *(Within 3 miles)*, you can attack with:
- Long-Ranged
- Strong Magic

In the **Remote Zone** *(Within 6 miles)*, you can attack with:
- Artillery/Siege
- Extreme Magic

Regular Magic Attacks or Spells cannot be used in the **Visible Zone** or **Remote Zone**.

### Cardinal Directions
The cardinal directions (a.k.a "compass directions") are listed in clockwise order:

**Cardinal Direction** | **Degree Value** | **Layman Terms** | **Clock Value**
:---:|:---:|:---:|:---:
North | 0/360° | "Up" | "12”
North East | 45° | "Up & Right" | ”3”
East | 90° | "Right" | ”6”
South East | 135° | "Down & Right" | "9 o'clock"
South | 180° | "Down" | "12 o'clock"
South West | 225° | "Down & Left" | "3 o'clock"
West | 270° | "Left" | "6 o'clock"
North West | 315° | "Up & Left" | "9 o'clock"

It costs a number of Move Actions (MA) equal to the Zones DV to move to an adjacent cardinal direction (ie. North to North East costs 1 MA while in the Close Zone [1x1] or 2 MA in the  Far Zone [1x2], while going from South to West costs 2 MA while in the Close Zone [1x2] or 4 MA in the  Far Zone [2x2]).


## Details
When combat begins, if neither group is **Surprised** (or given other situational advantage/disadvantage), all combatants currently engaged with are in the **Far Zone**.

Generally, Zones should viewed from the  perspective of the group with the advantage in combat with ties being decided by a simple majority at the beginning of combat. “I’m staying back at a Ranged Distance” or “I’m closing to Close Range” is one way to view it. Unlike other systems that use a similar system, opponents move between Zones, instead of remaining “stationary” as the adventurers move around them.

Think of it like the combat is the eye of the storm & everything swirls around the center majority of the combat. Alternatively put, it's like the rings of an arrow/dart target. Obviously this is an extreme abstraction, as such, the GM should remember that both the opponents & the players actually move around in their space even when not traversing zones, and describe it that way. Zones are meant to abstract relative distance & add positional tactics to theatre of mind combat that lacks miniatures/grids.

It takes a number of Move actions equal to the Zone # for an combatant to move between zones. Those Move actions allow movement across one Zone. The only exception is moving between close & player can spend a move Action and move from Far to Close, or from Close to Near.

The size of combat is limited by the size of the environment. If the space is 60ft or smaller then Far is the greatest distance possible. If the space is 5ft or smaller then Ranged combat is not possible without Feats or some other sort of special equipment/abilities. Outdoors any distance is theoretically possible


## Combat System
# Weapon Types
- Hand-to-Hand
- Melee, Light
- Melee, Medium
- Melee, Heavy
- Ranged, Close
- Ranged, Mid
- Ranged, Long
- Magic, Regular
- Magic, Strong
- Magic, Extreme
- Artillery


### Weapon Tags
- 1-Hand
- 2-Hand
- Crew [2-8]
- Pierce
- Slash
- Bludgeon
- Serrated
- Barbed 
- Tiny
- Huge
- Blind
- Deafen
- Stun
- Trip
- Grapple

# REFERENCE

# Crowns 
If one side is ambushing the other, they and their allies go first. Otherwise, make a COR save to see if they act before their targets. This save reoccurs at the start of each turn. 

On your turn in combat, you can move up to 30ft, and perform up to two main actions. 
You cannot perform the same main action twice in a single turn. 

- A main action can be anything from: 
- Attacking
- Sprinting (move an additional 20ft)
- Attempt a Utility Action
- Scrounging through your pack

You can break up one or both main actions into two quick actions if you’d like. 

Quick actions are for minor things, like pulling a lever, picking up an item, passing off an item to an ally, drinking a potion, etc. 


## Attack & Defense
When performing a melee attack, select a target up to 5ft away, then perform a COR save. For ranged attacks, select a target up to your weapon’s range away, then perform a SEN save. On a success in either case, you hit and deal weapon damage, your turn ends. 
 
If a player character is getting attacked, they can defend themselves by attempting a SEN save. On a success, the attack deals half of its original damage. If the 6attacker is a monster that had already missed, no damage is dealt. 

If a player character rolls a natural 1 while attacking, their attack becomes enhanced. If they roll a natural 1 while defending the enemy attack becomes impaired. 


## Enhanced & Impaired
Attacks can also be enhanced by attacking a prone target in melee, attacking an incapacitated enemy, exposing an enemy’s unique vulnerability, etc. Roll a 1d12 for damage, regardless of the weapon, and this attack cannot be defended against. 
Attacks can be impaired by attacking a prone enemy at a range, attacking an enemy that’s in cover, fighting unarmed, etc. Roll a 1d4 for damage regardless of the weapon.


## Dual Wielding
Light weapons can be held in a character’s off hand. If dual-wielding weapons, do not make two attacks. Instead, you may reroll your to-hit save. If your weapons have effects, use whichever one of the two weapons you’d prefer (this may be decided after rolling). 


## Mounted Combat
Being on a mount in combat lets you exchange your characters movement for the mounts. A horse and warhorse both have a 45ft move and a 25ft sprint. 

If you take critical damage while mounted, you must succeed a COR save to not fall prone on the ground. If your mount has a saddle, gain +2 to this roll. If your mount is a warhorse, you gain +2 to this roll as well. 
If attacking a mounted character, damage targeting the mount (unless it has an area-of-effect) is redirected to the rider. The rider makes the defense saves. Horses have 3 resolve, 1 DEF, 9 MOR; warhorses have 2 DEF. 

Melee attacks targeting unmounted targets while the attacker is mounted are enhanced. 

Unless the rider has a polearm, riders cannot target prone enemies while mounted. 


## Utility Action
On their turn, a player to attempt a utility action as a main action. If you succeed a utility action, you get what you want, and your turn ends. 

Utility actions are the following: 
- Expose. Make a SEN save, you must have a weapon equipped and the target must be within range of the weapon. On a success, the next successful attack against the target by an ally or the exposer is enhanced. If unused, this effect ends at the end of the exposer’s next turn. 
- Hinder. Make a COR save. On a success, the next attack the target makes is impaired. 
- Push. Make a VIT save, target must be the same size or smaller than you and be in melee range. On a success, the target is moved up to 5ft in any direction. If this causes them to be pushed into impassible terrain (a wall) they take 1d4 damage. 
- Tackle. Make a VIT save, target must be the same size or smaller than you in melee range. On a success, you and the target are prone (melee attacks made against prone targets are enhanced, ranged attacks are impaired). 
- Taunt. Make a WIL save, the target must be within line-of-sight and earshot. On a success, the target must attack the taunter on their next turn or have their next attack impaired. 


## Taking Damage
Incoming damage first reduces a character’s resolve. When all resolve is reduced to 0, they become bloodied. 

If a bloodied character takes regular damage (including damage that carried over from when they were pushed down to 0 resolve) they must attempt a VIT save minus the amount of damage they took over their resolve. If they fail, they take critical damage. 

If a bloodied character takes fear-related-damage, follow the same rules as above but with a WIL save. On a failure, the character gains the panic condition. 


## Critical Damage & Death
When a character takes critical damage, they gain the wounded condition, and must make a WIL save. 

If they succeed, they press on. If they fail, they fall incapacitated, gain the peril condition. If a player’s entire pack is full of conditions, they fall incapacitated. Allies that see this must pass a WIL save or gain the panic condition. 

A player can spend a dungeon turn (10 minutes) tending to the incapacitated player, removing one random condition from them, and restoring them to consciousness. This is not a short rest. If left untended for 6 turns (1 hour) they die.

## Monsters
On their turn, Monsters can perform a 30ft move and one full action (or two quick actions). They cannot perform utility actions.

Monsters replace all saves with MOR (morale) saves. If a monster fails an attack, they still deal half damage to the player. If a player successfully defends against a failed monster attack, the damage dealt is reduced to 0.

If a monster has “critical damage” in their stat block, it details an effect that occurs when the monster deals critical damage to a character.

Monsters can get over or through obstacles (cliffs, stuck doors, etc.) without needing a save, unless the players actively try to stop them. In which case, have the player make a roll to delay the monster’s inevitable advance.

In the case of nailing a door, barricading a path, or doing something else that relies more on the method than the user, the monsters succeed a MOR save.


### Resolve & Defiance
Monsters’ resolve works the same way the player’s does. When a bloodied monster takes critical damage, and the attacking player succeeds on a VIT save plus the amount of damage dealt over the monster’s resolve, the monster loses 1 defiance (DEF). 

Anytime a monster would gain a condition, instead loses 1 DEF.

When reduced to 0 DEF, it is defeated (it flees, surrenders, or dies). 

### Rallying
Whenever one of the following situations occurs, monsters that are **not immune to peril must make a rally save (using MOR)**.

- This monster takes critical damage for the first time
- An ally stronger than it is defeated
- This monster realizes its horribly outgunned or outnumbered

On a failure, the monster must flee or surrender.

Monsters can only make one rally save a turn.

Leader monsters allow allied monsters within 45ft to use their MOR for rally saves.

# Redhack
## Combat Rules


### Damage & Death
Damage is subtracted from the character’s remaining Hit Points (HP). Characters that are exactly at 0 HP are knocked out but wake d6 hours later at 1 hp. 

Any combatant that would reach negative HP is instead at 0 hit points and is dying. The dying immediately rolls a Luck Saving Throw:

2d6 | Result 
:---:|:---:
2 | **Snuffed out.** Instant death. Gone before they realize it. 
3-6 | **Deadman walking.** The PC can take one immediate, defiant last turn. Any proficient roll is treated as a critical success. The PC then collapses and watch themselves bleed out. There is no saving them, but they have enough energy for a few words after combat. Only strong magic could save them such as a resurrection.
7 | The PC rolls a DC 8 LUK save. On a success they 
8-11 | **Live to fight another day.** Unconscious at 0 hp. Also d4 damage to a randomly determined ability score. 
12 | **Dumb luck.** Character ignores 100% of the damage the last hit that took them down; it looked much worse than it actually was. 



## Additional Combat Rules
- **Attacks of Opportunity (AoO) & Disengage:** If a character moves out of an enemy melee range, the enemy may take a free attack. Spellcasting or using ranged weapons in melee also provokes AoO. Characters may disengage as an action to prevent being targeted by AoOs. 
- **Grappling:** Grapple is an opposed skill check. The winner deals damage equal to STR mod and throws the target 5 feet or pins the target to prevent movement and gives them disadvantage to all actions (including escaping). 
- **Reckless Attack:** A PC may make a reckless melee attack. The PC immediately rolls a DC 11 LUC check: 
  - **Success:** Advantage on the attack. If it hits, deal double damage. 
  - **Failure:** Disadvantage on attack. Enemy gets a free AoO. 
- **Firing into Melee:** When firing into melee and the attack misses, all adjacent from the original target roll a LUC save. The lowest number gets hit. If all Luck saves are over 11, the arrow misses everyone. 
- **Falling Damage:** Characters take d6 damage for each 10ft they fall (if the total is greater than 10ft).
- **Sneak Attack:** Attacks have advantage when a target is unaware or is flanked. If a target is completely helpless, GM may rule it an instant kill. 
- **Inspiration:** The GM can award inspiration to PCs for cool moments or good RP. Inspiration can be used at any moment to gain advantage. PCs can also buff their teammates with inspiration if they take a "bardic" feat.
- **Ongoing Fire Damage:** PCs may use an action to extinguish flames on themselves or in a small area (5’ by 5’). Fire deals d4 per round. 
- **Darkness:** PCs, and NPCs without infravision have disadvantage to perception, morale, and most actions or attacks (GM Discretion). Assume monsters have infravision. Stealth is rolled with advantage in darkness. 
- **Stunned:** Stunned PCs/NPCs can only use a move or action, but not both.
- **Exhaustion:** Exhausted PCs subtract their exhaustion dice from all d20 rolls. Exhaustion starts at d4 but escalates through the dice chain up to d12 as the PC becomes more exhausted. A level over d12 results in death. Exhaustion levels are gained for various sources, including every 24 hours without rest, from poison, being sickened, or from failing hex travel checks. Each day of rest removes one level of exhaustion.
