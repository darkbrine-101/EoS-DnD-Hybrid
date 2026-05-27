# Changes
## Characteristics
Your characteristics are changed in name, but their purpose remains fairly similar. 
- Strength: unchanged. 
- Dexterity: unchanged. 
- Constitution -> Toughness (TOU)
- Intelligence -> Reason (REA)
- Wisdom -> Intuition (INT)
- Charisma -> Prescence (PRE)

Additionally, they are mapped to a value between -10 and +10 with humans averaging around 0 with a deviation of 2. 
### Determining Characteristics
You start with -4 in each characteristic. You then have 30 points to spend to increase them, spending 1 point to increase a negative characteristic by 1, and 2 points to increase a positive or zero characteristic by 1. A characteristic cannot exceed 4. Backgrounds do not affect your characteristics. 

A calculator for this is linked [Here.](https://docs.google.com/spreadsheets/d/10han8H0nb-1awZGC-ARVeVARd61APtX8_FR0-KDm__k/copy)
### Characteristic Increases
General feats let you increase any characteristic in their selection by 1. Ability Score Increases let you increase any two characteristics each by 1. 
## Rolls
The standard d20 roll has been replaced with the Star Roll, where the higher the better. 
### Making a Roll
To make a roll you need 3d12 and potentially 3d6. Designate one of each of the 3d12 as the Hope, Fear and Neutral dice. To make a roll you roll the 3d12 and add to it the value of the relevant characteristic. 
### Outcome
- **Fumble.** Obtained if the Fear dice rolls equal to the Neutral dice. The worst possible outcome. 
- **Tier 1 (T1).** Obtained if you roll less than 20. The worst probable outcome.
- **Tier 2 (T2).** Obtained if you roll greater than or equal to 20, but less than 30. A middle of the road outcome. 
- **Tier 3 (T3).** Obtained if you roll greater than or equal to 30. The best probable outcome.
- **Critical.** Obtained if the Hope dice rolls equal to the Neutral dice, or all three dice roll the same. The best possible outcome.
### Hope and Fear
If the Hope dice rolls the highest the players gain 1 Hope. If the Fear dice rolls the highest the GM gains 1 Fear. Both pools have a maximum capacity of 2x the number of players or 10, whichever's higher. Players share a Hope pool and any player can spend Hope from it. Monster's share a Fear pool and any monster can spend Fear from it. Furthermore the GM can spend fear to increase the tension of the game or up the stakes. 
### Advantage and Disadvantage
Advantage and disadvantage cancel each other out, and stack to a maximum of 3. For each level of advantage you add 1d6 to the roll, and for disadvantage you subtract 1d6. 
## Skills
Skills are separated from characteristics, meaning (for example) you might use INT Awareness for one test, then PRE Awareness for another. Each skill has a rank from 0 (untrained) to 5 (superhuman). 
### Tests
Skills are used for tests, which replace skill checks. To make a test ask the GM if you can use any of the skills you wish to use, then make a Star Roll with one of the the characteristic(s) the GM has stated can be used and add to the tier of outcome your rank in the skill. Treat a fumble as a tier 0 and a critical as a tier 4. Then tell the GM what the result rank (RR) is, and they'll narrate the outcome based on the difficulty rank (DR). The below table states the outcomes based on the RR and DR. An S means success, an F means fail, a C means a (negative) consequence and an R means reward. 

| RR/DR | 1   | 2     | 3     | 4     | 5     | 6     | 7     | 8     |
| ----- | --- | ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| 1     | S+C | F + R | F     | F + C | F + C | F + C | F + C | F + C |
| 2     | S   | S+C   | F + R | F     | F + C | F + C | F + C | F + C |
| 3     | S+R | S     | S+C   | F + R | F     | F + C | F + C | F + C |
| 4     | S+R | S+R   | S     | S+C   | F + R | F     | F + C | F + C |
| 5     | S+R | S+R   | S+R   | S     | S+C   | F + R | F     | F + C |
| 6     | S+R | S+R   | S+R   | S+R   | S     | S+C   | F + R | F     |
| 7     | S+R | S+R   | S+R   | S+R   | S+R   | S     | S+C   | F + R |
| 8     | S+R | S+R   | S+R   | S+R   | S+R   | S+R   | S     | S+C   |
#### Pushing a Test
You can expend 1 Hope to push a test, rerolling the test. You can only do so once per test. 
## Abilities
DnD's abilities are altered to use the Star Roll system. Saving throws are replaced with potencies vs defences, and attack rolls are replaced with Star Rolls. Armour Class modifies hit points, explained in [Stamina](#Stamina). 
### Attack Rolls
You make a star roll using the relevant characteristic. On a T1 the damage is halved, on a T2 the damage is normal and on a T3 you add half the damage to the total. On a fumble the attack misses. On a critical the damage is doubled. 
### Defences
You have three defences, which are calculated as the highest of two characteristics. When an ability asks for a saving throw it should be converted to one of these based on the save it asks for. 
- Fortitude: STR and TOU
- Reflex: DEX and INT 
- Will: REA and PRE
### Potencies
When an ability causes a saving throw, the characteristic you use for the save DC is used to determine the potency. Low potency is the characteristic modifier minus 4 mid potency is the modifier minus 2 and high potency is the modifier. 
### Saving Throws
You make a star roll as normal. A creature fails the saving throw gaining all of the failed effects if its defence is less than the potency of the roll, or the success effects if it is greater than or equal. The damage is then calculated using the Attack Rolls section above. 

On a fumble, every target succeeds their saving throw regardless of their defences, and any damage becomes 0. On a critical, every target fails their saving throw regardless of their defences and all damage is doubled. 
### Limited generation
Some abilities require you to make multiple rolls as part of the same action. If this happens, only the first roll is able to generate Hope or Fear. 
### Example
Lets use the example of casting fireball as a wizard. REA would be their spellcasting modifier, lets say its 20 (+5 mod). 

They roll 3d12 and add 5, lets say the roll 7 (Neutral), 10 (Hope) and 10 (Fear) for a total roll of 27 and a total of 32, a T3 result. for a T3 the damage is increased by 50%, and the potency is equal to 5. Creatures with a reflex defence of 4 or less with take the average of $8d6*1.5$ damage, which is 42, and creatures with a reflex defence of 5 or more will take the average of $8d6*0.75$ damage, which is 21. 
### Advice
I strong advise you to write down at least the average damage of your most common damage dealing abilities, and ideally write them down including the amount of damage each tier does. Calculating the average damage of an ability mid-combat slows down the game significantly. 
## Stamina 
Creatures' HP are replaced with stamina, a measure of their armour's ability to block damage, their ability to dodge it, and their ability to endure through it. This is calculated as multiples of their recovery value. Their recovery value is equal to (HP + Level x AC modifier)/8. 

AC modifier is calculated as their AC divided by 2 and then subtract 5. For example an AC of 17 gives an AC modifier of +3. 
### Hit Locations
All non-minion creatures and some large objects have hit locations, each with a separate stamina pool. Area of effect abilities target all hit locations. Attack rolls target one hit location. Its type is determined by the Hope dice, and the specific hit location is determined by the Fear dice.

| Hope Dice | Hit Location Type | Description                                                                |
| --------- | ----------------- | -------------------------------------------------------------------------- |
| 11-12     | Crux              | A weak point on an enemy, such as their head.                              |
| 8-10      | Arm               | A limb used for manipulating objects or somatic components.                |
| 5-7       | Leg               | A limb used for movement.                                                  |
| 1-4       | Body              | The bulk of a creature, typically what attaches their limbs to their crux. |

#### 2 Limbs

| Fear Dice | Hit Location |
| --------- | ------------ |
| 6-12      | Right Limb   |
| 1-5       | Left Limb    |
#### 4 Limbs
| Fear Dice | Hit Location |
| --------- | ------------ |
| 10-12     | Right Limb 2 |
| 7-9       | Left Limb 2  |
| 4-6       | Right Limb 1 |
| 1-3       | Left Limb 1  |
#### 6 Limbs
| Fear Dice | Hit Location |
| --------- | ------------ |
| 11-12     | Right Limb 3 |
| 9-10      | Left Limb 3  |
| 7-8       | Right Limb 2 |
| 5-6       | Left Limb 2  |
| 3-4       | Right Limb 1 |
| 1-2       | Left Limb 1  |
### Concentration
If you take damage greater than your recovery value you must make a T2 TOU test or drop concentration. If the damage is greater than twice your recovery value, the tier becomes T3. If it is more than this, you automatically drop concentration. 
### Wound Levels
A hit location's stamina is reduced by any damage it receives, it can continue to be reduced indefinably, however complications arise based on how damaged a hit location is.

**Strain (>0).** Minor or negligible injury to a hit location. 

**Major (-Max to 0).** Significant injury to a hit location, affecting its ability to be used. This level of injury causes the following effects dependant on hit location:
- **Crux.** You become dazed.
- **Core.** You become agonised.
- **Limb.** The limb becomes disabled. 

**Critical (< -Max).** Lethal injury to a hit location, rendering the affected creature incapacitated and objects unusable.  This level of injury causes the following effects dependant on hit location:
- **Crux.** You become concussed.
- **Core.** You start bleeding.
- **Limb.** The limb is maimed. 
#### Dazed
You cannot concentrate. You can only take a bonus action or a move action. You cannot take reactions. 
#### Agonised 
Every time you take an action, bonus action, move or reaction the hit location takes damage equal to a number of d6 times your PB minus 1. (e.g. 2d6 at level 5)
#### Disabled
The limb cannot be used for actions. If it is used for walking you must drop prone and you cannot stand unless you are flying. If it is used for any other movement mode you cannot use this movement mode. 
#### Concussed
You are unconscious and dying. 
#### Bleeding
You are agonised and dying. 
#### Maimed
The limb is disabled and you are dying. 
#### Dying
You start with a pool of 3d12. At the start of each of your turns, and each time you take damage you must roll this pool and subtract from it each dice that rolls 4 or less. Once the pool is reduced to 0 you take a death action.
`Note: after 5 death saves you are more likely to die than not`

**Accept.** You accept death, allowing you to perform one last action which obtains a critical. You then die. 

**Deny.** You deny death, causing the affected area to be permanently injured. You lose the dying condition and fall unconscious until the wound level of the hit location that caused this condition is reduced to major. 
### Treating Wounds
A wound can be treated to negate its condition until the hit location receives further damage. A major wound can be treated by a DR 2 test negating its condition, and a critical wound can be treated by a DR 4 test which negates the dying condition. Additionally the Spare the Dying spell can be used to reduce the DR by 2 for the relevant test. Any healing to a hit location also treats the wound. 
## Resting
You recover stamina equal to your recovery value each period of time spent performing light activity, as detailed in the table below. It should be noted if something in the rules mentions a long rest, it instead functions of a medium rest. 

| Rest Type | Length of Time | Wound Recovery | Hope Gain    |
| --------- | -------------- | -------------- | ------------ |
| Short     | 1 hour         | Strain         | 0            |
| Medium    | 1 week         | Major          | 1 per player |
| Long      | 1 month        | Critical       | 1 per player |
## Initiative
Monsters act in groups where one group is approximately equivalent in power to one player. One monster and one player (those with the highest initiative) both make a Star Roll using their initiative bonus, and the side which rolls highest goes first.

**Surprise.** Any creatures that are surprised skip their first turn. 
## Lighting
Darkness is considered pitch black, and unseeable. Dim light is considered dark enough such that colour cannot be perceived. At night time the world enters a state of dim light, cast by the stars and moon. 

Dim light imposes DIS 1 on Star Rolls using sight and darkness prevents them entirely. 
# Skill List
EoS uses a different skill list to DnD that also combines tool proficencies. To increase a skill's rank you must spend skill points equal the rank you're increasing it to. You cannot increase a skill's rank above your proficiency bonus or above 5. 

**Gaining Skill Points.** Each time you gain a proficiency in a skill or tool you gain 1 skill point. Each time you gain expertise you gain 3 skill points. Every even level you gain 1 skill point.

**Changing Skills.** Each time you level up you can select a skill and gain skill points equal to its rank, then reduce its rank by one. You may then redistribute these skill points as you wish. 
### Crafting Skills
- Alchemy
- Architecture
- Artwork 
- Calligraphy 
- Cooking
- Forgery
- Jewellery 
- Leatherwork 
- Mechanics
- Smithing
- Songwriting
- Spellcraft 
- Textiles 
- Woodwork
- Tinkering
### Interpersonal Skills
- Awareness 
- Brag
- Disguise 
- Eavesdrop 
- Game
- Wrangle
- Insight 
- Interrogate
- Intimidate
- Lead
- Lie
- Perform
- Persuade
- Conceal
- Steal
### Exploration Skills
- Climb
- Jump 
- Endure 
- Escape
- Hide
- Lockpick
- Medicate 
- Navigate
- Operate
- Perceive  
- Ride
- Search
- Sneak 
- Swim
- Track
### Lore Skills
- Arcana
- Crime
- Culture
- History
- Law
- Monsters
- Nature
- Occult 
- People
- Politics 
- Psionics
- Religion
- Rumour
- Hierarchy  
- Tactics 
# Class Changes
You spend hope to use stronger abilities. Many will be worked out on a case by case basis, but here are a few examples.
## Common
### Spells
You spend hope to gain spell slots detailed below, based on your spellcasting level (see multiclassing rules to determine level). 

| Level | 1 Hope Spell Slot | 2 Hope Spell Slot | 4 Hope Spell Slot | 8 Hope Spell Slot |
| ----- | ----------------- | ----------------- | ----------------- | ----------------- |
| 1-2   | 1                 |                   |                   |                   |
| 3-4   | 2                 |                   |                   |                   |
| 5-6   | 2                 | 3                 |                   |                   |
| 7-8   | 2                 | 4                 |                   |                   |
| 9-10  | 2                 | 5                 |                   |                   |
| 11-12 | 2                 | 5                 | 6                 |                   |
| 13-14 | 3                 | 5                 | 7                 |                   |
| 15-16 | 3                 | 5                 | 8                 |                   |
| 17-18 | 3                 | 5                 | 8                 | 9                 |
| 19-20 | 4                 | 6                 | 8                 | 9                 |
### Attacks
You spend 1 hope to target an attack roll to a specific hit location of a creature. 
## Class Specific
`Note: nothing sublcass specific is here, that will be done on a case-by-case basis`
### Artificer
**Tinker's Magic.** 1 Hope per use.

**Replicate Magic Item.** You can produce one magic item per 8 hours of downtime. You must spend 1 Hope to produce an uncommon item or 2 Hope to produce a rare item. All other restrictions remain unchanged. 

**Drain Magic Item.** Gain 1 Hope for an uncommon item, or 2 Hope for a rare item. Can be used at will. 

**Transmute Magic Item.** Costs 2 Hope to produce a common or uncommon item and 4 Hope to produce a rare item. 

**Flash of Genius.** 1 Hope per use. 

**Refreshed Genius.** Removed.

**Magical Guidance.** If you have Attunement to at least one magic item, when you use Flash of Genius, roll 1d10 and if you roll less than the number of magic items you're attuned the use doesn't cost you any Hope. 
### Barbarian
**Rage.** 2 Hope or 1 Hope at level 6.

**Relentless Rage.** You can rage for free when initiative is rolled. 
### Bard
**Bardic Inspiration.** 2 Hope or 1 Hope at bard level 5.

**Font of Inspiration.** Removed (See Bardic Inspiration.)

**Superior Inspiration.** Gain 2 uses of bardic inspiration when you roll initiative. 
### Cleric
**Chanel Divinity.** 2 Hope or 1 Hope at cleric level 18.

**Divine Intervention.** 2 Hope. Has a cumulative 25% chance of failing after each use which resets on a medium rest. Failed uses still consume Hope. 

**Greater Divine Intervention.** 8 Hope. Has a cumulative 50% chance of failing after each use which resets on a long rest. Failed uses still consume Hope. 
### Druid
**Wild Shape.** See table.

| Level | 1 Hope         | 2 Hope | 4 Hope |
| ----- | -------------- | ------ | ------ |
| 2-3   | CR0            | CR1/8  | CR1/4  |
| 4-7   | CR1/8 or less  | CR1/4  | CR1/2  |
| 8+    | CR 1/4 or less | CR1/2  | CR1    |

**Wild Resurgence.** Removed.

**Nature Magician.** Removed.
### Fighter
**Second Wind.** 1 Hope to use. At fighter level 10 if the d10 rolls 5 or less you don't expend Hope. 

**Action Surge.** 4 Hope or 2 Hope at fighter level 17. 

**Indomitable.** 4 Hope or 2 Hope at fighter level 13.
### Monk
**Monk's Focus.** 1 Hope to gain focus points equal to half your monk level. 

**Uncanny Metabolism.** 2 Hope, only usable when initiative is rolled. 
### Paladin
**Lay On Hands.** 1 Hope to gain points equal to twice your paladin level. 

**Channel Divinity.** 2 Hope per use.

**Faithful Steed.** 1 Hope per use.
### Ranger
**Favoured Enemy.** At will.

**Nature's Veil.** 1 Hope.
### Rogue
**Stroke of Luck.** 2 Hope. 
### Sorcerer
**Innate Sorcery.** 2 Hope.

**Font of Magic.** 2 Hope to gain sorcery points equal to half your sorcerer level. 

**Sorcerous Restoration.** Regain sorcery points equal to half your sorcerer level when you finish a medium rest. 
### Warlock
**Eldritch Invocations.** Gift of Depths allows you to cast Water Breathing using a Pact Magic slot. 

**Pact Magic.** Regain a pact magic slot by expending 2 Hope or 1 Hope at Warlock level 17. 

**Magical Cunning.** Removed.

**Contact Patron.** 2 Hope. Has a cumulative 50% chance of failing after each use which resets on a medium rest. Failed uses still consume Hope. 

**Mystic Arcanum.** Use the spellcasting rules to determine how much Hope it costs to cast the relevant spell.

**Eldritch Master.** You contact your patron who gifts you back all Pact Magic slots. This feature has a cumulative 50% chance of failing after each use which resets on a medium rest. 
### Wizard
**Arcane Recovery.** When you finish a short rest you gain a spell slot equal to that obtained by spending 1 Hope. 





