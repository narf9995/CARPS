# Craps-based Accessible Role Playing System (CARPS)
[Skip to Rules](https://github.com/narf9995/CARPS/blob/main/README.md#proposed-carps-core-rules).


## Premise:
With accessibility in mind; could a narrative-focused RPG be created using the established odds of street craps (results of 2d6 summed) & mixed/complex interpretation of those results, while staying simple to read, understand, & run?


# Core Concepts
  - accessibility focus: WCAG compliant, screenreader compatible, limited images, & limited math
  - simple concepts for new players, kids, elderly, & cognitvely impared persons
  - markdown & YAML for easy formating/localization
  - generic, setting agnostic rules
  - limited resources required to play
  - require 2d6 only *(based on Street Craps)*
  - limit unnecessary dice rolls
  - dice can be cleary & quickly read
  - SRD can fit on 1 sheet of A4 paper
  - clear, yet narratively abstract rules
  - minimal, yet comprehensive rules
  - storytelling/narrative focus
  - players can meaningfully (& mechanically) affect narrative
  - connect players with world via mechanics
  - ages 5 and up with an adult 
  - open, modular, easy to homebrew
  - online, cross-platform, cheap to print
  - small & non-proprietary file formats
  - treated like an open-source code project
  - *Unintended Bonus: 1-digit addition practice disguised as game*


## Introduction
### Problem:
In my opinion, many popular role-playing systems have a major problem; which is their level of accessibility. Systems frequently require many specialized dice & books, on-boarding of system/setting specific rules for both gamemaster & player, & require a level of familiarity for adequate player risk assessment. This creates a "black box" situation where the gamemaster understands the inner working of the game & the associated risks to actions, but the players are blind as to how their actions are actually orchestrated mechanically & the mathematical odds of their success.

New players, particularly those unfamiliar with tabletop role-playing games (TTRPGs) or computer RPGs (JRPG, MMORPG, etc.), tend to have great ideas visually/narratively, but struggle to implement them within the mechanics of the system. This may be frustrating for all parties involved as it can be to the detriment of the players own fun, the fun of the party, & even take away valuable playing time while reviewing rules.

The following situation may be familiar to you:

    GM: Your turn Mage.
    New Mage: I cast a spell!
    GM: What Spell?
    New Mage: Uh...
    [5 Minutes Later]
    GM: ...Okay, so you cast fireball at the enemy.
    The spell has an area of effect within a 20-foot radius.
    It appears the Paladin is within that area.
    Paladin: God damn it, not again.
    GM: Give me a reflex save Paladin.
    New Mage: Wait... what?

#### For Gamemasters
It's easy to place the blame on the players for not learning the system you as a gamemaster had to learn, but keep in mind that people have different skill sets & learning methods. What makes sense to you might not make sense to them & vice versa. If this is a recurring issue across systems, players, & gamemasters, as I have observed; then there must be some core issue regarding accessibility in RPGs as a emerging form of [transmedia](https://github.com/narf9995/CARPS/blob/main/pages/transmedia.md) storytelling.


#### For Players
Placeholder Text.


### Pro/Con List of Existing Solutions:
- Powered by the Apocalypse
- FATE


## Thesis:
Placeholder Text


## Proposed CARPS Core Rules

### Table 1-1: Original Craps Names
|   |          1          |          2          |          3          |          4          |          5          |          6          |
|:-:|:-------------------:|:-------------------:|:-------------------:|:-------------------:|:-------------------:|:-------------------:|
| 1 |      Snake Eyes     |      Ace Deuce      |      Easy Four      |  Five (Fever Five)  |       Easy Six      | Natural (Seven Out) |
| 2 |       Ace Deuce     |      Hard Four      |   Five (Fever Five) |       Easy Six      | Natural (Seven Out) |      Easy Eight     |
| 3 |       Easy Four     |   Five (Fever Five) |       Hard Six      | Natural (Seven Out) |      Easy Eight     |      Nine (Nina)    |
| 4 |   Five (Fever Five) |       Easy Six      | Natural (Seven Out) |      Hard Eight     |      Nine (Nina)    |       Easy Ten      |
| 5 |       Easy Six      | Natural (Seven Out) |      Easy Eight     |      Nine (Nina)    |       Hard Ten      |     Yo (Yo-leven)   |
| 6 | Natural (Seven Out) |      Easy Eight     |     Nine (Nina)     |       Easy Ten      |    Yo (Yo-leven)    |  Boxcars (Midnight) |


### Table 1-2: Revised Craps Names
|   |         1        |      2     |      3     |      4     |      5      |         6         |
|:-:|:----------------:|:----------:|:----------:|:----------:|:-----------:|:-----------------:|
| 1 | Snake Eyes (Two) |    Three   |  Easy Four |    Five    |   Easy Six  |       Seven       |
| 2 |       Three      |  Hard Four |    Five    |  Easy Six  |    Seven    |     Easy Eight    |
| 3 |     Easy Four    |    Five    |  Hard Six  |    Seven   |  Easy Eight |        Nine       |
| 4 |       Five       |  Easy Six  |    Seven   | Hard Eight |     Nine    |      Easy Ten     |
| 5 |     Easy Six     |    Seven   | Easy Eight |    Nine    |   Hard Ten  |    Yo (Eleven)    |
| 6 |       Seven      | Easy Eight |    Nine    |  Easy Ten  | Yo (Eleven) | Midnight (Twelve) |


### Table 2-1: Craps Odds
| Dice Total | Odds |         Combinations         | # of Combos |  Odds vs. 7 |
|------------|------|------------------------------|-------------|-------------|
| 2          | 1/36 | 1+1                          |      1      | 6/1         |
| 3          | 2/36 | 1+2, 2+1                     |      2      | 6/2 = 3/1   |
| 4          | 3/36 | 1+3, 3+1, 2+2                |      3      | 6/3 = 2/1   |
| 5          | 4/36 | 1+4, 4+1, 3+2, 2+3           |      4      | 6/4 = 15/10 |
| 6          | 5/36 | 1+5, 5+1, 4+2, 2+4, 3+3      |      5      | 6/5 = 12/10 |
| 7          | 6/36 | 1+6, 6+1, 2+5, 5+2, 3+4, 4+3 |      6      | 6/6 = 1/1   |
| 8          | 5/36 | 2+6, 6+2, 3+5, 5+3, 4+4      |      5      | 6/5 = 12/10 |
| 9          | 4/36 | 3+6, 6+3, 4+5, 5+4           |      4      | 6/4 = 15/10 |
| 10         | 3/36 | 4+6, 6+4, 5+5                |      3      | 6/3 = 3/1   |
| 11         | 2/36 | 5+6, 6+5                     |      2      | 6/2 = 2/1   |
| 12         | 1/36 | 6+6                          |      1      | 6/1         |


### Table 2-2: Additional Odds

| Aspect             | Odds        | Effect               |
|--------------------|-------------|----------------------|
| Both: Odd          | 9/36 = 1/4  | Major Negative Bonus |
| Both: Even         | 9/36 = 1/4  | Major Positive Bonus |
| Sum: Odd           | 18/36 = 1/2 | Minor Negative Bonus |
| Sum: Even          | 18/36 = 1/2 | Minor Positive Bonus |


### Table 2-3: Critical

| Roll            | Odds | Effect                           |
|-----------------|------|----------------------------------|
| Identical: 2    | 1/36 | Negative Critical (Auto-Fail)    |
| Identical: 4,6  | 1/36 | Negative Critical (Major, Minor) |
| Identical: 8,10 | 1/36 | Positive Critical (Minor, Major) |
| Identical: 12   | 1/36 | Positive Critical (Auto-Win)     |


### Aptitudes
- Physical (Phy)
  - Represents physical strength & constitution
- Agility (Agi)
  - Represents dexterity & reflex
- Cognizance (Cog)
  - Represents perception & scrutiny
- Acumen (Acc)
  - Represents logical reasoning & mathematical ability
- Knowledge (Kno)
  - Represents memory & academic knowledge
- Personality (Per)
  - Represents charisma & presence
- Occultism (Occ)
  - Represents study of magic, alchemy, extra-sensory perception, astrology, spiritualism, religion, and/or divination depending on your setting.


Aptitudes are in a range of 6 from -2 to +3

New Characters have 1 Professional, 2 Skilled, 2 Average, 1 Poor, 1 Awful.


### Table 3-1: Aptitude Scores
| Score | Level        | Effect                                    |
|-------|--------------|-------------------------------------------|
| -2    | Awful        | Auto-Failure on most associated tasks     |
| -1    | Poor         | Roll on most associated tasks             |
|  0    | Average      | No Effect: Roll unless superfluous        |
| +1    | Skilled      | Auto-Success on Easy associated tasks     |
| +2    | Professional | Auto-Success on Moderate associated tasks |
| +3    | Legendary    | Auto-Success on Hard associated tasks     |


## Tasks & Actions (a.k.a Doing Things)
### Table 3-2: Difficulty
| Difficulty | Success Condition                 | Odds  |
|------------|-----------------------------------|-------|
| Mundane    | Auto-Success (unless interesting) | N/A   |
| Easy       | Success on a sum of 7 or higher   | 21/36 |
| Moderate   | Success on a sum of 9 or higher   | 10/36 |
| Hard       | Success on a sum of 10 or higher  | 3/36  |
| Impossible | Auto-Failure (unless Critical)    | 1/36  |


Characters in your games are going to do stuff, things, & stuff with things.
In this system we give stuff & things the name **Tasks**.


**Tasks** may entail a single **Action** or many **Actions** together.
**Actions** take **Time**. Simple **Tasks** take less **Time**, while complex **Tasks** take more **Time**.



For most things they do, there’s no need for dice & rules.
If the average person could do it on auto-pilot, so can your character.
Characters can stand, walk, talk, go shopping & otherwise do normal things without needing to roll dice.
They can even take mundane actions relevant to their aptitudes, like driving to work, without worrying about the dice.
The dice only come out when there is an interesting challenge with meaningful consequences, especially if it's related to one of the characters weaknesses.


When you need (or want) to roll dice, this is the procedure:

1. Determine Difficulty of Task & reassess after reviewing odds.
2. Roll 2 six-sided dice (2d6) on a flat surface or in a clear cup. *A dice app is also useful in many scenarios, but may not be truly random if you care about such things.*
3. Interpret results.

## Episodes & Scenes
**Episodes** are comprised of **Scenes**. **Episodes** are usually the length of the entire duration of the play session & can either be self-contained stories arcs that conclude at the end of the **Episode**, a segment of a larger story arc with cliff-hangers in-between, or an unabridged long-form story arc that suspends/resumes like nothing happened. Ultimately the decision is up to the **Table** & has no effect as to the actual gameplay.

### Time




### Health

Health is measured in **Body** & **Reflex**.


**Body**: The physical constraints of your body, measured by Physical.


**Reflex**: Your ability to avoid and respond to damage, measured by Agility + Knowledge.


### Stress

Stress



## Characters

There are 3 kinds of characters
- Player Characters (PCs)
- Named Non-Player Characters (NPCs)
- Nameless Non-Player Characters (NPCs)

The first two are defined as Named Characters.
Nameless Characters include generic background characters, groups, mobs, and other entities that don't require names.

### Aptitudes

Named Characters have the following array of scores to assign to their 7 aptitudes. Unnamed characters are handled differently.
- 1 Professional (+2)
- 2 Skilled (+1)
- 2 Average (0)
- 1 Poor (-1)
- 1 Awful (-2)



### Relationships

Named Characters start the game with 1 Major Ally, 1 Minor Ally, 1 Nemesis, 1 Major Debt they owe, & 1 Minor Debt owed to them.
You may choose these options yourself or roll for them on the tables below.


### Items

Named Characters start the game with 1 Major Significant Item, 1 Minor Significant item, & 5 Mundane Items.
You may choose these items yourself or roll for them on the tables below.

### 4-1: Significant Items, Major

First roll to select the column & then again select the row.

| Roll | Column | 1 | 2 | 3 | 4 | 5 | 6 |
|------|--------|---|---|---|---|---|---|
| 1    | 1      |   |   |   |   |   |   |
| 2    | 2      |   |   |   |   |   |   |
| 3    | 3      |   |   |   |   |   |   |
| 4    | 4      |   |   |   |   |   |   |
| 5    | 5      |   |   |   |   |   |   |
| 6    | 6      |   |   |   |   |   |   |

### 4-2: Significant Items, Minor

First roll to select the column & then again select the row.

| Roll | Column | 1 | 2 | 3 | 4 | 5 | 6 |
|------|--------|---|---|---|---|---|---|
| 1    | 1      |   |   |   |   |   |   |
| 2    | 2      |   |   |   |   |   |   |
| 3    | 3      |   |   |   |   |   |   |
| 4    | 4      |   |   |   |   |   |   |
| 5    | 5      |   |   |   |   |   |   |
| 6    | 6      |   |   |   |   |   |   |

### 4-3: Mundane Items

First roll to select the column & then again select the row.

| Roll | Column | 1 | 2 | 3 | 4 | 5 | 6 |
|------|--------|---|---|---|---|---|---|
| 1    | 1      |   |   |   |   |   |   |
| 2    | 2      |   |   |   |   |   |   |
| 3    | 3      |   |   |   |   |   |   |
| 4    | 4      |   |   |   |   |   |   |
| 5    | 5      |   |   |   |   |   |   |
| 6    | 6      |   |   |   |   |   |   |
