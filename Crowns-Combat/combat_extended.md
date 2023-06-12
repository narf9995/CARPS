## Extended
This is a slightly more complicated version of combat with less concessions that still works as a somewhat standalone system. It's the structure on which much more advanced combat can be built. The this edition of the Extended System can also be used as an example of the Core System implemented into another another RPG system, in this case, Crowns 1e.

**Important Notation:**
- **U = Unit (typically *Yards* or *Meters*)**
  - For our purposes, there is **1 U (yard/meter) for every 3 feet**.
    - So to convert from U to feet, divide the sum by 3.
    - To convert from feet to U, multiply the sum by 3.
  - Although yards & meters have slightly different lengths, a concession is made for easy localization.
    - You may **replace U with the unit you are most comfortable with** when reading anything with this notation.
    - You can even substitute another unit such as an inch or mile if your scale changes significantly.
  - Alternatively, 2U is 6 feet, which is *almost* 5 feet. **If you don't care about specific measurements, you can just subsutitute 2U squares for the standard 5ft squares** with basically zero side effects to gameplay. 
  
  - **Ultimately, the only thing that matters is that you have a *standardized unit of space.***

### Basics
#### Turn Order
At the beginning of combat, all engagaged combatants make a COR save called Initiative to see if they act before their targets. 

> Depending on your preferences, the initiative COR save either occurs once at the start of combat *or* it reoccurs at the start of each round. It can be made by each player individually *or* once for each side of the combat. Either way works fine, but **this system defaults to each player rolling individually at the start of each round.**

If one side is ambushing & their opponents are **Surprised**, the ambushers get a special round before initiative is rolled where they & any other non-suprised opponents go first. Once this round is complete, combat begins as normal. 

Turn order in combat is divided into 3 phases: before your opponent's turn, during your opponent' turn, & after your opponent's turn. Magic is always cast in the 3rd phase after your opponents turn unless you have a feat that says otherwise.

### Actions
On your turn in combat, you can perform 2 Move Actions & perform up to two Main Actions. You cannot perform the same main action twice in a single turn.

A main action can be anything from: 

- Attacking a target
- Attempting a Utility Action
- Searching your storage
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
Being on a mount in combat lets you half the number (rounding up) of Move actions required for an combatant to move between zones. Those Move actions allow movement across one Zone.

If you take critical damage while mounted, you must succeed a COR save to not fall prone on the ground. If your mount has a saddle, gain +2 to this roll. If your mount is a warhorse, you gain +2 to this roll as well. 
If attacking a mounted character, damage targeting the mount (unless it has an area-of-effect) is redirected to the rider. The rider makes the defense saves. Horses have 3 resolve, 1 DEF, 9 MOR; warhorses have 2 DEF. 

Melee attacks targeting unmounted targets while the attacker is mounted are enhanced. 

Unless the rider has a polearm, riders cannot target prone enemies while mounted. 


#### Utility Action
On their turn, a player to attempt a utility action as a main action. If you succeed a utility action, you get what you want, and your turn ends. 

Utility actions are the following: 
- Expose. Make a SEN save, you must have a weapon equipped and the target must be within range of the weapon. On a success, the next successful attack against the target by an ally or the exposer is enhanced. If unused, this effect ends at the end of the exposer’s next turn. 
- Hinder. Make a COR save. On a success, the next attack the target makes is impaired. 
- Push. Make a VIT save, target must be the same size or smaller than you and be in melee range. On a success, the target is moved up to 2U in any direction. If this causes them to be pushed into impassible terrain (a wall) they take 1d4 damage. 
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
On their turn, Monsters can perform 2 Move Actions and one full action (or two quick actions). They cannot perform utility actions.

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

Leader monsters allow allied monsters within the Far Zone to use their MOR for rally saves.


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
