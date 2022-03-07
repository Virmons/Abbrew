# Equipment

## Materials

Materials affect equipment’s statistics.

### Structure

Structure is used as part of the damage a weapon would do, as well as the reduction it provides.

### Quality

The quality of an item affects how effective it is in use.

Items are listed at Quality 0.

For each level of quality an item is below this:

Any checks made using the item are Weak equal to the quality.

Its Structure is reduced by the quality.

Every time an ability is used where the item supports it, the item has a chance to break, roll 1d10, if the result is equal to or greater than 10 - the quality, the item breaks (the materials may still be intact, but the overall item is unusable).

The integrity of the item is halved for each negative quality e.g. an item at -2 quality would have 12 Integrity.

### Reduction

The reduction listed for a material is the damage type reduced by the material.

  

Type

Material

Tier

Structure

Reduction

Effects

Rarity

Cloth

Linen

1

1

Physical

-

1

Hide

Leather

1

1

Physical

-

1

Wood

Pine

1

1

Physical

-

0

Metal

Iron

1

3

Physical

-

1

## Encumbrance

Encumbrance is a penalty suffered for not meeting the requirements for equipment.

The encumbrance for each piece of equipment is calculated separately.

### Statistic Requirements

Increase your encumbrance by the difference between your statistic bonus and the requirement.

### Tier Requirement

For each tier that you lack, whether it be character tier or skill tier, increase your encumbrance by 5 multiplied by the difference.

### Example Encumbrance

You are attempting to wield a Steel Longsword, this requires 

## Armour

The armours below are listed without any material modifiers.

To determine the total damage reduction of armour, add the following:

The material’s Structure.

The material’s Tier x 5.

Any Reduction modifiers listed for the material.

E.g. The Crushing reduction of Steel Plate would be 9 + 3 + 5 + 0 = 17

  

Armour Type

Price

Rarity

Material Type

Required Strength

Damage Reduction

Properties

Crushing

Slashing

Piercing

Cloth

1gp

1

Cloth

1

2

2

2

  

Padded

5gp

1

Cloth

1

5

1

1

  

Hide

5gp

2

Hide

2

4

8

8

Restrictive 1

Leather

10gp

2

Hide

2

3

4

4

Chain

75gp

3

Metal

3

6

15

9

Plate

1500gp

4

Metal

5

9

18

12

Shield

2gp

1

Wood

1

1

1

1

  

Tower Shield

20gp

2

Wood

4

5

5

5

  

## Weapons

### Melee

To determine the statistics for weapons, combine the base weapons below with their materials using the table below.

  

Arc (Swinging attacks)

Thrust

Structure + (Strength Required x (1+ Minimum Effective Reach)) + (Tier x 5)

Structure + (Tier x 5)

#### Stowing / Drawing Weapons

You are able to stow up to 3 weapons on your person in or on a belt; they can be drawn / stowed using the interact ability.

#### Minimum Effective Reach (MiR)

The minimum effective reach of a weapon is the reach required to make full use of its damage e.g. an axe has a minimum effective reach of 1m, in order to leverage its full damage the target must be at least 1 metre away, any damage rolls below this are halved.

#### Maximum Effective Reach (MaR)

Any attacks made above the weapon’s maximum effective reach are misses.

#### Weapons with both Crushing and Slashing

If the weapon has both Slashing and Crushing Damage, the Crushing Damage roll is Weak.

#### Reach

The reach of a weapon (rounded down)  is added to the reach of a creature to determine its total reach.

e.g. a dagger with a reach of 0.25m (0m) combined with a creature of Size 0 (1m), they would be able to target creatures up to 1m away from them. This would be the same effective reach as for a shortsword but they handle differently.

  

Reach

Size

Priority

Actual/Size

Example

Natural

1

0

0

Unarmed 

Short

1

1

<0.125

Knife

Short

1

2

<0.25

Dagger

Standard

1

3

<1

Shortsword 

Long

2

0

1

Longsword 

Long

3

0

2

Greatsword

A weapon with lower actual reach within the same size bracket (shown here by priority) provokes reactions from those in the same bracket with higher priority. 

E.g. An Unarmed attacker (Size 1 Priority 0) would provoke an attack from a defender wielding a dagger (Size 1 Priority 1)

  

If a weapon is modified to either gain or lose reach, they should gain or lose priority as appropriate.

Once a weapon reaches -1 priority, it moves down a size. 

Once a weapon reaches 4 priority it moves up a size. 

Short Greatsword (Size 2 Priority 3)

Long Shortsword (Size 2 Priority 0)

##### Natural

This is the natural reach of the creature; weapons marked with this reach add no reach to attacks made with them.

Attacks made with weapons with Natural reach provoke Reactions from creatures wielding Short and Standard reach weapons.

##### Short

Weapons with the Short reach possess a maximum effective reach of at most one quarter of the creature’s size.

Attacks made with weapons with Short reach provoke Reactions from creatures wielding Standard reach weapons.

##### Standard

Weapons with Standard reach possess a maximum effective reach of at most half of the creature’s size.

##### Long

Weapons with Long reach possess a maximum effective reach of at least the creature’s size.

##### Smaller Creatures

A smaller creature counts its priority as 1 lower for each size smaller that it is. If a weapon would reach negative priority e.g. A small Greatsword, it moves down 1 in priority, so that greatsword would become Size 1 Priority 2. The minimum size for a weapon's reach is 1.

  

To become adjacent to a target, smaller creatures provoke 2^N reactions for each tile they move through, where N is their difference in size, this is reduced by the size of their weapon e.g. A small creature with a weapon at size 2 would not provoke when moving into range of a standard creature, however only one reaction can be used for each ability the smaller creature used e.g. Movement of a smaller creature through a threatened space would provoke twice but only one reaction could be taken if it only used the move ability once. 

### Weapon Traits

#### Brutal

Damage rolls made for this Weapon Attack activate their critical effect without requiring a critical damage roll.

#### Fine

The damage rolls for slashing attacks and crushing attacks made with a Fine weapon are Weak. 

#### Focused

These are weapons such as hammers and picks. 

Reduce the Push Trait of Focused weapons by 1.

Reduce any Weak attacks of the Weapon by 1.

Focused weapons have a damage multiplier equal to 1 + MiR on their Arc attacks.

#### Frightening

Creatures damaged by weapons with this trait must succeed on an opposed Will Check, gaining the converted damage suffered as the Fear condition. 

#### Hands 

This determines the number of hands that can be used to wield the weapon, if the weapon has Hands(2) and you wield it with 2 hands, half the Strength required when considering Encumbrance.

#### Light

Weapons with 0 strength required are Light.

The damage rolls of Light weapons are weak when making Arc attacks.

Attacks made with Light weapons either gain the Push(1) trait, or increase the Push trait by 1.

#### Natural

The damage rolls of Natural reach weapons are weak when making Arc attacks.

Natural weapons can be used to make arc attacks without the required space.

Attacks made with Natural weapons either gain the Push(1) trait, or increase the Push trait by 1.

#### Alternate Grips

If the weapon provides these grips, they can be swapped between using the Interact ability. 

##### Rear Grip

A grip running up the reverse side of the weapon, swapping to this grip changes the attack profile of the weapon, it becomes Natural reach and hits as many tiles as it has length. 

#### Oversized

Dexterity Checks made while wielding a weapon with this trait are Weak.

Damage rolls made while wielding a weapon with this trait are Strong.

#### Push

Attacks made with this weapon gain the Push trait equal to this value, or increase the Push trait by this value.

#### Short

The damage rolls of Short weapons are weak when making Arc attacks.

Short weapons can be used to make arc attacks without the required space.

Attacks made with Short weapons either gain the Push(1) trait, or increase the Push trait by 1.

#### Swift

Attacks made with Swift weapons either gain the Push(1) trait, or increase the Push trait by 1.

#### Weapon Attacks

##### Arc

To make a slashing attack, you require the space to the weapons equipped side to be empty, or the space behind and up to the target to be empty; if it is blocked by a creature or terrain, you are unable to make this attack.

##### Thrust

A thrusting weapon that does not possess the Short trait has an increased minimum effective range equal to the final range increment e.g. a Longsword has an effective reach of 1m, combined with the reach of a Size 0 creature this is 2m, any Piercing attacks within the first metre would have their damage halved.

### Ranged 

Ranged weapon attacks do not use the creature’s Strength directly to increase damage.

The damage is entirely based on the weapon and ammunition used.

#### Strength Bands

A ranged weapon with Strength bands will provide differing bonuses at different Strength Bonuses.

##### Range Increment

For each Strength Band you possess, increase the Range of the weapon by its Range Increment up to its Maximum Range.

##### Penetration

For each Strength Band you possess, increase the Penetration of Damage rolls made with the weapon.

### Thrown

Depending on your Strength and the object thrown, your range, and attack and damage rolls will vary.

  

Weapon Trait

Range

Damage

Light

Strength Score

Weak (C/S)

Short

Strength Score

Weak (C/S)

-

Strength Score / Strength Required

Weak (P)

Heavy

Strength Score / Strength Required

Weak (P)

Thrown

Strength Score x 2 / Strength Required

-

### Skill Requirements

Weapons possess skill requirements, gained by selecting the Weapon Skill associated with them. If you lack the ability to create the combination for the weapon, any attacks or reactions made with the weapon are Weak.  

### Example Melee Weapons

Weapon

Price

Rarity

MiR

MaR

Required Strength

Material

Reach

Skill Requirements

Damage

Crushing

Slashing

Piercing

Unarmed

-

0

0

0

0

Flesh

Natural

Unarmed, Crushing Thrust, Light, Short

Tier

-

-

Knife

5sp

1

0

0.125

0

Iron

Natural

Hands(1), Light, Short, Slashing Arc (Piercing Thrust)

-

8

8

Club

1sp

1

0

0.25

1

Iron

Short

Hands(1), Short, Crushing Arc

9

-

-

Staff

2sp

1

0

1

2

Wood

Long

Hands(2), Long, Crushing Arc

8

-

-

Hammer

2gp

1

0

0.25

1

Iron

Short

Hands(1), Short, Crushing Arc, Focused

12

-

-

Hatchet

2gp

1

0

0.25

1

Iron

Short 

Hands(1), Short, Slashing Arc, Focused

-

12

-

Dagger

2gp

1

0

0.25

1

Iron

Short

Hands(1), Short, Slashing Arc (Piercing Thrust)

9

9

8

Shortsword

10gp

2

0

0.5

2

Iron

Standard

Hands(1), Standard, Slashing Arc (Piercing Thrust)

10

10

8

Rapier

25gp

3

0

1

1

Iron

Long

Hands(1), standard, Piercing Thrust, Fine

9(W2)

9(W)

8

Longsword

20gp

3

0

1

4

Iron

Long

Hands(2), Long, Slashing Arc (Piercing Thrust)

12

12

8

Greatsword

50gp

4

0

2

8

Iron

Long

Hands(2), Long, Slashing Arc (Piercing Thrust)

16

16

8

Axe

30gp

2

1

1

1

Iron

Long

Hands(2), Long, Slashing Arc, Focused

-

20

-

Warhammer

15gp

2

1

1

2

Iron

Long

Hands(2), Long, Crushing Arc, Focused

24

-

-

Warpick

15gp

2

0.5

0.5

2

Iron

Long

Hands(1), Standard, Piercing Arc, Crushing Arc, Focused

11

-

11

Lucerne Hammer

30gp

3

1

1

2

Iron

Long

Hands(2), Long, Piercing Arc, Crushing arc, Focused, (Piercing Thrust)

24

-

24 (8)

Mace

5gp

1

0

0.5

4

Iron

Standard

Hands(1), Crushing Arc

12

-

-

Spear

1gp

1

2

2

1

Iron

Long

Hands(2), Long, Piercing Thrust

-

-

8

Shield

2gp

1

0

0

1

Pine

Natural

Hands(1), Crushing Thrust

6

-

-

Shortbow (Melee)

25gp

1

0

0.5

1

Yew

Standard

Hands(1), Crushing Arc

8

-

-

Longbow (Melee)

50gp

2

0

1

2

Yew

Long

Hands(2), Crushing Arc

9

-

-

### Example Ranged Weapons

  

Weapon

Ammunition

Range Increment

Maximum Range

Required Strength

Maximum Strength

Strength Bands

Damage

Properties

Crushing

Slashing

Piercing

Shortbow

Arrows

50

150

1

3

1/2/3

-

-

3

Penetrate  4

Longbow

Arrows

180

360

4

8

4/6/8

-

-

5

Penetrate  5

Crossbow, Hand

Bolt

-

250

4 (Reload)

-

-

-

-

5

Penetrate 15

### Example Ammunition

  

Type

Material

Tier

Total Damage

Crushing 

Slashing

Piercing

Arrow

Steel

1

-

-

5

Bolt

Steel

1

-

-

5

  

### Example Thrown Weapons

Weapon

Price

Rarity

MiR

MaR

Required Strength

Material

Reach

Skill Requirements

Damage

Crushing

Slashing

Piercing

Javelin

5sp

1

0

0.5

1

Steel

Standard

Hands(1), Standard, Piercing Thrust (Thrown Piercing)

-

-

8

### Weapon Patterns

Weapon

Complexity

Material Rarity Modifier

MiR

MaR

Required Strength

Material Type

Reach

Skill Requirements

Knife

1

x1

0

0.125

0

Metal

Natural

Hands(1), Light, Short, Slashing Arc (Piercing Thrust)

Club

0

x1

0

0.25

1

Metal

Short

Hands(1), Short, Crushing Arc

Hammer

1

x1

0

0.25

1

Metal

Short

Hands(1), Short, Crushing Arc, Focused

Dagger

1

x1

0

0.25

1

Metal

Short

Hands(1), Short, Slashing Arc (Piercing Thrust)

Shortsword

2

x2

0

0.5

2

Metal

Standard

Hands(1), Standard, Slashing Arc (Piercing Thrust)

Longsword

3

x3

0

1

4

Metal

Long

Hands(2), Long, Slashing Arc (Piercing Thrust)

Greatsword

4

x4

0

1

8

Metal

Long

Hands(2), Long, Slashing Arc (Piercing Thrust)

Axe

2

x2

1

1

1

Metal

Long

Hands(2), Long, Slashing Arc, Focused

Warhammer

2

x2

1

1

2

Metal

Long

Hands(2), Long, Crushing Arc, Focused

Warpick

2

x2

1

1

2

Metal

Long

Hands(2), Long, Piercing Arc, Focused

Mace

1

x1

0

0.5

4

Metal

Standard

Hands(1), Crushing Arc

Spear

1

x1

2

2

1

Metal

Long

Hands(2), Long, Piercing Thrust

Shield

1

x1

0

0

1

Wood

Natural

Hands(1), Crushing Thrust

Shortbow (Melee)

1

x1

0

0.5

1

Wood

Standard

Hands(1), Crushing Arc

Longbow (Melee)

2

x2

0

1

2

Wood

Long

Hands(2), Crushing Arc

  
  

## Adventuring Gear

### Bandage

1sp for 20

Bandages can be used as the Apply Pressure ability, replacing the Strength Bonus with the number of Bandage charges used.

### Torch

5cp

A torch sheds Light 2 in a 6m radius and Light 1 in a further 6m radius.

### Sheath

3sp

A weapon stored in a sheath does not contribute towards the number you are able to stow.

### Splint

When 

# Creatures

## Statistics

Creatures usually have eight statistics that govern their abilities to act as shown below.

### Strength

Strength governs the creature's ability to wield weapons regarding weight, how heavy the armour they can wear is and the amount of equipment they are able to carry.

It is used in grappling and otherwise exerting physical power.

You can carry up to 15kg of equipment without suffering adverse effects.

### Dexterity

Dexterity governs a creature’s ability to use its limbs, whether the skill with which it wields a weapon or performing an intricate craft.

Dexterity is used to contest attacks with weapons when the target reacts.

Additionally it is used as part of the initiative roll to determine combat turn order.

### Agility

Agility governs a creature's ability to move itself as a whole, whether running, dodging or balancing. Additionally it is used as part of the initiative roll to determine combat turn order.

### Constitution

Constitution governs a creature’s ability to resist physical ailments such as disease and poisons as well as its ability to recover from damage suffered.

### Intelligence

Intelligence governs a creature’s understanding of concepts, used in recalling information and determining the limit of magic it is capable of casting. You can cast spells of up to your Intelligence score in complexity.

You can memorise a number of Spells equal to your Intelligence Bonus per day.

### Will

Will governs a creature’s ability to produce and resist magical effects.

Add Will to any damage dealt using spells. 

The Check to resist spells is equal to 6 multiplied by the creature's Tier + Will. 

### Wits

Wits governs a creature’s ability to respond quickly and communicate with others. Additionally it is used as part of the initiative roll to determine combat turn order.

### Visualisation

Visualisation governs a creature’s imagination and ability to picture concepts making them easier to will into existence.

### Tier

The Tier of a character is an indicator of how powerful they are; player characters usually start at Tier 1. 

The Tier of a creature is determined by the average of each Statistic, rounded up.

A creature adds its Tier to each roll that it makes and has an innate Damage Reduction(Any) based on their Tier.

#### Damage Reduction (Any)

This type of damage reduction can apply to any incoming damage, though only once for each incoming source.

For example, if you were to be hit by an attack that dealt Piercing and Fire damage, you could select to use the Damage Reduction (Any) for either of the two types but not both.

  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  

Tier Name

Tier Bonus

Bonus required 

D10

Damage Reduction (Any)

Standard

1

1

1

5

Uncommon

2

6

2

10

Rare

3

12

3

15

Legendary

4

18

4

20

Mythic

5

24

5

25

Demigod

6

30

6

30

Deific Minor

7

40

7

35

Deific Major

8

55

8

40

Synonymous

9

74

9

45

Source

10

100

10

50

  

## Defining Creatures

## Size

The size of a creature is the size of its base e.g. a human’s size is 1m.

Size is used to calculate several factors about your character:

It is used along with their limbs to determine their Movement Speed.

Their reach is equal to their size.

It is the size of their Mental Domain.

  
  

Distance

Value

Base Movement Speed

Limbs(Agility) x Agility Score / 2 x Size

Reach

Size

Mental Domain

Size

Sight Range

Wits Score x 2 x Size

Hearing Range

Wits Score x Size

Scent Range

Wits Bonus x Size

## Limbs

The limbs of a creature will affect how it is able to interact, these are usually split into:  
Limbs(Agility) which are used to move.

Limbs(Dexterity) which are used for fine manipulation and attacking.

Your limbs are also used to provide your available total Grapple Score.

### Grapple Score

A Creature’s Grapple Score is the number of points it can commit to a grapple attempt.

A larger creature’s Grapple Score is increased by the Size difference between it and the target, likewise for smaller creatures grappling with larger ones.

Wielding or holding an item reduces the creature’s grapple score by 1.

If a creature commits Grapple Score but fails in the attempt, it does not regain those points until it spends its next action or its turn ends, whichever comes first.

### Base Abilities

Limbs provide creatures with these abilities:

#### Attack (Attack)

Ability - Cost:1 - Special

Fatigue: Physical

Provokes Reactions: No

Make an Attack using a wielded melee weapon.

You must turn to face the direction of your target such that they are in front of you before making the attack.

You can make as many attacks as you have Limbs(Dexterity), split between the attacks, you must push between each attack. 

E.g. Given you have two Making an attack with a hands(2) weapon, you could only make 1 per turn, whereas attacking with a hands(1) weapon, you could attack, push and make an attack with your other hand. 

Attack rolls made with your non dominant limb are Weak. 

#### Interact

Ability - Cost: 1 - Repeatable

Fatigue: Mental

Provokes Reactions: Yes

Interact with an object within reach e.g. open a door, take off your backpack, retrieve an item from the backpack / stored items, touch a creature or object within your reach.

#### Apply Pressure

Ability - Cost: 3 (Special) (Concentration) - Repeatable

Fatigue: Mental

Provokes Reactions: Yes

Apply pressure to a wound on a creature within reach; at the start of its turn, reduce the bleed that creature takes by your Strength Bonus + Tier (This applies even before the full action cost has been paid).

After each full round, if the creature suffers no bleed, its wounds become Healing Wounds.

#### Drop

Ability - Cost: 0

Fatigue: None

Provokes Reactions: Yes

Drop a held item.

#### Grab

Ability - Cost: 1 - Once per Round

Fatigue: Physical

Provokes Reactions: Yes

Make an attack (Dexterity Check) against a target, choosing a Grapple Score to commit..

If you succeed in hitting the target, it takes no damage but gains the Grabbed Condition with a value equal to the Grapple Score you committed.

When attempting to move a creature also in control of a grapple with another target, if they succeed on the Check, the target they are grappling may also be moved; make more checks as appropriate, reducing the distance travelled by the overall modifier.

Any vertical movement of Grabbed creatures is quartered and rounded down.

  

##### Restrain

Ability - Cost 1 - Once per Round

Fatigue: Physical

Provokes Reactions: Yes

Requires: Grapple Score equal to the Grabbed Creature’s total grapple score.

Make an opposed Strength Check.

Success: The Creature cannot use Struggle or Break Free.

##### Struggle

Ability - Cost 1 - Push

Fatigue: Physical

Provokes Reactions: Yes

Make an opposed Strength Check.

Success: The grabbing creature is moved at half your movement speed, subtracting its Strength bonus.

Failure: You cannot move.

##### Trip

Ability - Cost: 1 - Once per Turn

Fatigue: Physical

Provokes Reactions: No

Requires: Grapple Score of at least 1, Controlling Grapple Condition.

Attempt to force a grappled creature to fall prone, the Check to resist is a Strength Check.

You can follow the creature, falling prone along with it.

##### Break Free

Ability - Cost 1 - Once per Round

Fatigue: Physical

Provokes Reactions: Yes (Aside from the Grappling Creature)

Make an opposed Strength Check.

Success: reduce the grappling creature’s Controlling Grapple score by 1.

##### Shove

Ability - Cost 1 - Once per Round

Fatigue: Physical

Provokes Reactions: Yes

Contest your Strength against the target’s.

Success: you move them up to your Size.

##### Pull

Ability - Cost: 1 - Push

Fatigue: Physical

Provokes Reactions: Yes

Pull a target towards you using Dextrous limbs (arms), you can move the target a distance up to your Strength Bonus and modifying it as follows:

For objects: subtract the strength required of the item multiplied by your Size.

For creatures, requires you to have the Controlling Grapple condition against it, make an opposed Strength Check:

Success: Subtract their Strength Bonus

Failure: They are not moved.

##### Drag

Ability - Cost: 1 - Push

Fatigue: Physical

Provokes Reactions: Yes

Drag a target with you using Agile limbs (legs), you can move the target a distance up to your movement speed modified as follows:

Dragging an object equal to your size, move at half your movement speed.

Dragging a grabbed creature requires you to have the Controlling Grapple condition against it, make a contested Strength Check:

Success: The creature is moved at half your movement speed.

Failure: The creature is moved at half your movement speed, subtracting its Strength bonus.

#### Move

Ability - Cost:1 - Push (Physical)

Fatigue: None

Provokes Reactions: Yes

You move up to your movement speed.

This is reduced by your encumbrance multiplied by your base size.

Diagonal movement costs no additional movement.

You can change your facing before and after movement without provoking reactions.

Once you stop moving to take another action, your movement finishes.

#### Step

Ability - Cost: 1 - Once per Round

Fatigue: None

Provokes Reactions: No

The frequency of this ability cannot be increased.

Move up to your size.

#### Pass Through

Reaction

Fatigue: Physical

Provokes Reactions: No

Trigger: A use of the Move ability would cause you to move through an enemy creature’s space.

Make an opposed Agility Check against the creature’s choice of Dexterity or Agility.

Success: You pass through the space successfully, movement taken in this way costs double unless the creature is 2 sizes smaller or larger than you.

Failure: Your movement stops next to the creature, provoking Reactions.

#### Ram

Reaction

Fatigue: Physical

Provokes Reactions: Yes

Trigger: You are about to move into a target’s space.

Contest your Strength against the target’s.

Success: you move them up to your Size. 

#### Change Stance

Ability - Cost: 1 - Push(Physical)

Fatigue: None

Provokes Reactions: Yes

You change stance from:

Standing to Crouched or Prone.

Crouched to either Standing or Prone.

Prone to Crouched.

##### Crouched (Stance)

Your movement speed is halved.

Any attempts to move Stealthily are Strong

Any Agility Checks are Weak.

##### Prone (Stance)

Your movement speed is quartered.

Any attempts to move Stealthily are Strong 2.

Any Agility Checks are Weak 2.

#### Climb

Ability - Cost 1 - Push

Fatigue: Physical

Provokes Reactions: Yes

As Move, however you move at one quarter speed.

You may be required to make a Check to climb, climbing with assistance such as a rope makes the Check Strong.

#### Swim

Ability - Cost 1 - Push

Fatigue: Physical

Provokes Reactions: Yes

As Move, however you move at half speed.

You may be required to make a Check to swim, swimming with assistance makes the Check Strong.

#### Long Jump

Ability - Cost 1 - Push

Fatigue: Physical

Provokes Reactions: Yes

##### From Standing

Jump half of your Agility Bonus multiplied by your Size.

##### After Moving half of your speed

Jump your Agility Bonus multiplied by your Size.

#### High Jump

Ability - Cost 1 - Push

Fatigue: Physical

Provokes Reactions: Yes

##### From Standing

Jump one quarter of your Agility Bonus multiplied by your Size.

##### After Moving half of your speed

Jump half of your Agility Bonus multiplied by your Size.

#### Remain Upright

Reaction

Fatigue: Physical

Provokes Reactions: No

Trigger: You are about to fall prone.

Make a Contested Agility Check against the effect.

#### Prepare

Ability - Cost: 1 (Concentration)

Fatigue: None

Provokes Reactions: No

Prepare to use another ability as a reaction, and provide a trigger that will allow you to take the reaction.

You cannot prepare an action you are unable to take within your current turn, e.g. preparing to attack when you have made all possible attacks for the round.

#### Visualise

Cost: 1 - Once per Check ([Concentration](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.qe8v1w5xxrjw))

Fatigue: Mental

Provokes Reactions: No

Choose an action, you can add your Visualisation + your Tier to the next roll you make for that action.

You can continue to Visualise towards that action, increasing the bonus you have to add, the bonus is only reset when you take the chosen action, or are interrupted.

You cannot exceed the maximum natural check result using this. 

Once you make the roll for the chosen action, you lose the Concentrating condition.

#### Focus

Ability - Cost: 1 (Concentration) - Push

Fatigue: Mental

Provokes Reactions: No

Gain 2 actions that can only be used for Abilities with the Supplementary trait or Cast Spell.

### Identity

An identity determines what a creature is and how they may act in certain situations; it could be seen as the mind, sanity, personality or soul of the creature. 

##### Hold

Hold is the measure of an identity's control over a body.

Creatures usually start with 1 identity with a hold of 100. 

No matter how many identities a creature gains, the total hold between them must sum to 100.

###### Reaching 0 Hold

Once an identity reaches 0 hold it has no control, only gaining a chance on subsequent Identity Checks that result in a 100, for player characters this essentially ends with them as an npc.

A creature can willingly return their virtues to their own identity.

##### Will

Identities may possess different wills, for your Sins and Virtues this will be the same as your own Will, external effects causing identity damage will use their own will in the resulting identity.

##### Effects Dealing Identity Damage

Effects dealing Identity damage will include:

Damage: the amount lost. 

Drawbacks: An effect related to the trauma caused e.g. Fear of violence, gain Fear 1 whenever violence is perceived. 

Hardened: A lasting effect usually gained by reducing sin, e.g. Indifference to violence suffered by others. 

#### Sins and Virtues

Creatures have a tie towards Sins and Virtues, which may come into play to help prevent trauma from affecting a creature.

A sin or virtue with 0 hold is removed. 

##### Sins

Sins must be indulged in to suppress the negative conditions applied by identity loss e.g. Alcohol to avoid seeing the eldritch abominations. 

If the satisfaction effect of a sin is active, so are the drawbacks of the identity. 

###### Hardened Sin

These prevent a creature from being able to take part in actions that support the sin’s opposed virtue; though they may come with additional effects as appropriate.

###### Redemption

A creature can seek redemption for its Sins, replacing them with the appropriate virtues once earned.

##### Virtues

Virtues are always active and can help avoid traumas, they come with compulsions which can be ignored, but will reduce the virtue by half as a result, being replaced with the opposing sin.

###### Self Control 

A creature can exercise self control and reduce the value of a Virtue.

##### Alignment

Alignment determines your predilection for Sin or Virtue; most characters should start at 0 Alignment, giving a balance between the two.

Evil Characters will likely have negative alignment, while Good characters will likely have positive alignment, though circumstances can be hard on characters.

A good character can act as their virtues dictate to gain a boon.

An evil character can act as their sins dictate to gain a boon, doing so increases the hold of the Sin’s identity by 10%, minimum 1.

###### Shifting Alignment

When a creature shifts alignment due to its actions, add an identity with Hold 10, the creature must then make an Identity Check.

###### Boons

A boon can be activated at any point in a round; Virtues grant their Overcome effect for 1 round or make the next Check Strong where Sins grant their corruption effect for one round with no ill effect or until the end of combat, triggering their satisfaction thereafter.

A character can possess a number of boons equal to their alignment step + 1 e.g. a creature at -3 alignment would be able to possess 4 boons, whereas a creature at +1 alignment would be able to possess 2 boons.

##### Identity Structure

###### Name 

The name of the identity e.g. character name or Sin.

###### Hold

The current hold of the identity.

###### Will

The Will bonus of the identity.

###### Tier

The Tier of the Identity, used when Will is Checked.

###### Type

 Soul, Sin, Virtue, Curse, Hardened are some examples.

###### Effect

This could be anything e.g. When the character perceives spiders they gain Fear 2.

###### Indulgence

An action undertaken to keep a Sin in check.

###### Hardened Effect

This is the result of long running trauma or prevention; it becomes the effect for Hardened type identities.

##### Identity Priority

The order of Identities for your character should follow:

  

Main Identity

Greater Virtues 

Lesser Virtues

Hardened Strategies

Greater Sins

Lesser Sins

Any other Identities attached to you e.g. Corruption 

  

Additional Identities each then follow the above pattern along with their virtues etc. e.g. Werewolf. 

#### Identity Damage

Whenever a creature suffers identity damage, it must first reduce its current Identity and add one of the same value, noting which other identity it affects and adding any conditions specified by the effect causing the loss, e.g. A loss caused by a Fear effect of a spider, may include Phobia: Spiders - Fear 2 whenever in the presence of Spiders. 

  

The creature can then attempt an Identity check to determine how it is able to cope with this loss. 

#### Identity Checks

To make an identity check, roll 1d100, compare the result against your Identity values in order. Your alignment may affect whether you encounter Vices or Virtues for a given result.

  

Alignment ->

—--------------

Result v

+2 and above

+1

0

-1

-2 and below

Less than your identity divided by 10

Greater Virtue

Greater Virtue

Greater Virtue

Lesser Virtue

Minor sin

Less than half of your identity

Greater Virtue

Greater Virtue

Lesser Virtue

Minor sin

Greater Sin

Less than your identity

Greater Virtue

Lesser Virtue

Minor sin

Greater Sin

Greater Sin

Falls within the new identity

Lesser Virtue

Minor sin

Greater Sin

Greater Sin

Greater Sin

Result falls within another identity, or the virtues or sins of another identity

Another Identity

Another Identity

Another Identity

Another Identity

Another Identity

Within a Virtue

Empowered Virtue

Empowered Virtue

Empowered Virtue

Empowered Virtue

Empowered Virtue

Within a Sin

Empowered Sin

Empowered Sin

Empowered Sin

Empowered Sin

Empowered Sin

##### Greater Virtue

Roll for a Virtue, you have the effect until the end of the encounter. 

Rename the new Identity as appropriate for Virtue and change the type to Greater Virtue.

Replace a Sin with the hardened effect. 

##### Lesser Virtue

Roll for a Virtue, you have the effect until the end of your next turn. 

Rename the new Identity as appropriate for Virtue and change the type to Lesser Virtue.

Reduce a Sin's hold by half and add a new Identity with its hardened effect. 

##### Lesser Sin

Roll for a Sin and choose an Indulgence appropriate for it; rename the identity as the Sin, change the type to Minor Sin and add the Indulgence to it.

##### Greater Sin

Roll for a Sin and choose an Indulgence appropriate for it; rename the identity as the Sin, change the type to Greater Sin and add the Indulgence to it.

##### Another Identity

Make a Control Check against the Other Identity, and is referred to as “The Other” below..  
The new identity gains the following effect:  
Not My Problem: Whenever this identity’s drawbacks would be triggered, make a Control Check against The Other.

##### Empowered Virtue

The hold and effects of the new identity are added to the virtue. 

##### Empowered Sin

The hold and effects of the new identity are added to the Sin, removing the new Identity. The Sin's satisfaction effect is activated. 

  

Sin/Virtue

Temptation

Greater

Each day roll 1D10 with a bonus equal to the number of days since last satisfied.

If the result is above 10, suffer the Satisfaction.

Lesser

During downtime.

Random

During downtime.

  

Sin

Satisfaction

Corruption

Envy

Perception checks and those requiring it are Weak. Cannot Focus, cannot Concentrate.

When making an opposed check, you can choose to take the opponent’s dice roll as your own.

Greed

Perception checks and those requiring it are Weak. Cannot Focus, cannot Concentrate.

Taking an item from an enemy grants you an item that can be consumed for free to grant you an additional action. You can gain this effect once per enemy.

Gluttony

Mental Checks are Weak.

Any effects that restore blood, maximum blood, adrenaline or remove wounds are doubled.

Lust

Mental Checks are Weak.

Your movement does not provoke attacks of opportunity.

Pride

Refuse to aid and refuse the aid of other creatures.

Whenever you succeed t in a contested Check, the following Checks made until the start of your next turn are Strong.

Sloth

Physical Checks are Weak, speed is halved.

For each round you do not gain fatigue, gain 1 stack of Sloth; when gaining fatigue you can spend 1 stack of Sloth instead to avoid it.

Wrath

Creature gains the Rage Condition. Move into range with and attack the nearest creature. 

At the start of your turn, mark 1 creature, any checks made against that creature are Strong.

Discord

Mental Checks are Weak. Unable to Focus, unable to Concentrate.

When successfully damaging or affecting a creature with a spell, make an opposed Will Check:  
Success: They gain the Discord Satisfaction effect until the start of your next turn.

Apathy

Unable to Push, unable to focus.

You are immune to emotional conditions.

Violence

At the start of combat, the creature gains the Rage Condition. Move into range with and attack the nearest creature. 

Your attack and damage rolls are Strong.

  

Virtue

Overcome Effect

Kindness

Any checks made to heal an ally are Strong.

Charity

You can allow an ally to act on your turn using one of your actions.

Temperance

Checks made to resist physical conditions are Strong.

Purity

Checks made to resist mental conditions are Strong.

Humility

Increase the critical range of your damage by 1.

Diligence

One check (apart from damage) made each round is Strong.

Patience

You cannot unwillingly gain the Rage condition.

Concord

Any checks made to prevent gaining Emotional conditions are Strong.

Passion

Suppress the effects of an emotional condition.

Peace

Checks made to Reason are Strong.

##### Indulging a Sin

When a creature indulges in order to prevent the effect of an identity or the sin’s own Satisfaction effect e.g. drinking to stave off gluttony, they must make an Identity Check, if the check falls within the Sin, its hold increases by 10% (minimum 1).

##### Eventual Healing 

It may be possible to replace Sins and Virtues with less extreme coping strategies, or otherwise reduce their hold given time.

### The Soul

#### Binary Soul (Contract)

Your soul and body are two separate entities bound by Contract, most frequently this is Mortality and as such once the body dies, the soul returns to the Astral plane to whatever afterlife awaits it.

### Traits

#### Social

##### Gullible

When opposing a creature’s Lie, the response is Weak.

##### Fearful

When opposing a creature’s Intimidate, the response is Weak.

If they succeed, increase the Fear value gained by 1.

##### Easily Seduced

When opposing a creature’s Charm, the response is Weak.

##### Oblivious 

Any perception checks are Weak, but any checks to resist charm are Strong. 

  
  
  
  
  

##### Easily confused

When opposing a creature’s Reason, the response is Weak.

Roll 1d10:

  

Result

Effect

1-5

Increase the Relationship by 1.

6-10

The creature gains the Rage condition and becomes hostile.

##### Reasonable

When opposing a creature’s Reason, the response is Weak.

##### Hot headed

When opposing a creature’s Goad, the response is Weak.

If they succeed, gain the Rage condition.

# Perception

Creatures possess varying abilities to perceive the world around them, to notice something you make a Wits Check against the difficulty of the thing to be noticed

The most common senses for players are listed below:

## Sight

Your character has a sight range, any Wits checks made within this range are done without penalty normally, moving into the next range out you would be making Wits checks at Weak(ranges) e.g. you are a human with 15 Wits, within 30m you would make checks to notice things with no penalty, if you wanted to pick something out at 65m however you would be making the check at Weak(2) as you are looking past 2 sight ranges [30(0) + 30(1) + 5(2)].

Sight will also be listed for your character for light conditions e.g.

Light 1 (Poor) Weak(2)would denote that any attempts to find things by sight in dim lighting would be weak(2).

### Requiring Sight

Any checks made with Agility, Dexterity as well as Wits checks to see and make spell attacks follow the Sight table for Weakness. 

## Sound

Your character has a hearing range, any Wits checks made within this range are done without penalty normally, moving into the next range out you would be making Wits checks at Weak(ranges) e.g. you are a human with 15 Wits, within 15m you would make checks to notice things with no penalty, if you wanted to pick something out at 40m however you would be making the check at Weak(2) as you are looking past 2 hearing ranges [15(0) + 15(1) + 10(2)].

## Smell

Your character has a scent range, any Wits checks made within this range are done without penalty normally, moving into the next range out you would be making Wits checks at Weak(ranges) e.g. you are a human with 15 Wits, within 7m you would make checks to notice things with no penalty, if you wanted to pick something out at 20m however you would be making the check at Weak(2) as you are looking past 2 hearing ranges [7(0) + 7(1) + 6(2)].

# Character Advancement

In this system there are three types of points that you can use to advance your character, or create a new one, these are Focus Points (FP), Inspiration Points (IP), and Experience Points (XP).

## Focus Points (FP)

These are only used during character creation, or in the event  that a long time passes for your character. Each Focus Point indicates a new stage in the character’s life, growing through different age categories.

By spending Focus Points you will gain 5 Inspiration Points and thus 20 Experience Points to spend on your character.

## Inspiration Points (IP)

These are used to gain new Skills, increase your potency in known Skills and acquire new techniques to make use of them. Outside of character creation, keep track of the Inspiration Points you spend, as when you reach a period of time where you are able to reflect on your progress e.g. downtime between adventures, you gain four times that number in Experience Points and then reset your gained Inspiration Points to 0. You gain a number of Inspiration Points at the end of each session.

## Experience Points (XP)

These are used to increase the value of your statistics, each point can be spent to increase the value of one Statistic by 1.

  
  
  
  
  
  
  

# Character Creation

When creating a character, first select a race:

## Races

### Human

#### Size

1m

#### Perception

Eyes

  

Condition

Status

Light 4

Weak(2)

Light 3

Weak(1)

Light 2 (Bright)

-

Light 1 (Dim)

Weak(1)

Light 1 (Poor)

Weak(2)

  

Ears

Nose

Touch

Taste

#### Limbs

##### Primary - Agility

Legs x 2

##### Secondary - Dexterity

Arms x 2

##### Grapple Score

You have a total available grapple score of 4.

  

Grabbed Value

Status

0

-

1

Cannot use weapons with the Hands(2) trait.

2

Cannot use weapons with the Hands trait.

3

Movement Speed is halved.

Agility Checks to remain upright are Weak.

4

Movement Speed is 0.

Agility Checks to remain upright are Weak(2)

#### Requires

Food and Drink.

To Breathe.

To Sleep.

  

## Your Character’s Statistics

  

Your character starts with the baseline of your tier in each statistic, starting at Tier 1 you would have 1 in each. To determine your statistics, consider their background, how they grew to where they are today. Depending on their age they will have a number of Focus Points to spend on the option below. 

  

An adult has 2 focus points to spend in the choices below and will also be able to spend a number of XP to spend equal to their FP+1 multiplied by 20.

  
  

Age Category

FP

XP

Weak

Young

0

20

Physical 1, Mental 1

Adolescent

1

40

Mental 1

Adult

2

60

-

Venerable

3

80

Physical 1

## Choices

  

The choices will be listed as the following:

  

(1) Where did you grow up?

(2)FP-0/1R

(3)Urban

Rural

Wild

  

(4) How were you provided for?

You stole

(5) Gain...

  

(1) The question / choice

(2) The focus point cost for this option, here it is free for the first, then 1, it is also 1R which means you can repeat the choice as many times as you can buy it.

(3) The options to choose for (1)

(4) Further questions in the category (1)

(5) What you gain for the choice

  

## Where have you lived?

FP-0/1R

Gain the Knowledge skill for the area you lived in and 1IP to spend on it. 

Urban

Rural

Wilderness

  

### How were you provided for?

You were provided for by someone or something else. 

#### Practicing a trade.

See Practicing a trade

#### You were provided for:

How did you spend your time?

##### Spent your time doing what you wanted / training / studying for something specific:

Gain 3 IP, spend these on Skills that show how you spent your time. 

##### Martial Training

See Martial Training

##### Magical Training

See Magical Training

#### Hunted

Gain the Survival Skill

Gain 2IP to spend on the Survival Skill

#### Stole

Did you steal by:

##### Force

Gain the Cruel Skill

Gain 2 IP to spend in the Cruel Skill

  

##### Intimidation

Gain the Intimidation Skill

Gain 2 IP to spend in the Intimidation Skill

  

##### Cunning

Gain the Deception Skill

Gain 2 IP to spend in the Deception Skill

  

##### Keeping your presence hidden

Gain the Stealth Skill

Gain 2 IP to spend in the Stealth Skill

  
  

##### Quick hands

Gain the Sleight of Hand Skill

Gain 2 IP to spend in the Sleight of Hand Skill

  

##### Quick feet

Gain the Mobility Skill

Gain 2 IP to spend in the Mobility Skill

  

##### Distracting the mark for someone else

Gain the Diplomacy Skill

Gain 2 IP to spend in the Diplomacy Skill

  

## What have you been doing? 

FP-1/1R

Gain 2IP to spend.

### Practicing a trade

See Practicing a trade

### Martial Training

See Martial Training

### Magic Training

See Magic Training

  

### Joined an Organisation

You joined an Organisation e.g. A faith, a gang

See Joined an Organisation. 

### Something else

Gain 3IP to spend on Skills of your choice.

## Practicing a trade

### Starting a new Trade

Gain the Profession Skill for your trade or a relevant skill that would be used by that Profession.

Gain a Weapon Skill related to the tools you may have used. If there are none, choose one one-handed weapon. 

Gain 1IP to spend on either of those skills or skills relevant to the profession..

### Continuing a Trade

Gain 3IP to spend on the Profession Skill, related Weapon Skills and relevant skills for the Profession.

### Scholar

Gain 3IP to spend on one Skill of your choice.

  

## Martial Training

### You were trained by someone else 

Gain one Martial Style Skill

Gain 2IP to spend on it and related Skills. 

Or

Gain 3IP to spend on a previously trained Martial Style and related Skills

  

### You trained yourself

Gain the Martial Style - Personal Skill

Gain 2 IP to spend on it and related Skills. 

Or

Gain 3IP to spend on your Martial Style - Personal and related Skills. 

  

## Magic Training

What was the purpose of your magic training? 

### To harness an unstable power inside you

Gain the unstable magic Skill or the Emotional Magic Skill.

Gain 2 IP to spend on one Skill of your choice.

  

### To gain the aid of a patron

Gain the Patron skill

Gain 2 IP to spend in this Skill.

  

### To gain the aid of the spirits

Gain the Spirit Magic Skill

Gain 2 IP to spend in this Skill. 

  

### To make use of Stored Magics e.g. Scrolls / Stored in Gems

Gain the Magic Mover Skill

Gain 2 IP to spend in this Skill. 

  

### To harness the power available around you

Gain the Channeler Skill

Gain 2 IP to spend in this Skill. 

  

### To draw forth the power inside of you

Gain the Reservoir Soul Skill

Gain 2IP to spend on magic skills

  

### To Learn Magic Rituals

Gain the Ritualist Skill

Gain 2 IP to spend in this Skill. 

## Joined an Organisation

### A Faith 

Gain the Organisation Skill of your Faith

Gain one of:

Patron Skill

Ritualist Skill

Diplomacy

Gain 1IP to spend on these skills. 

## Equipment

Select up to 3 Rarity of Armour and Weapons

# Skills

Skills are something you have either learned, picked up or merely had a brush with to the point that you are more knowledgeable in their regard.

  

To gain access to a Skill, you must spend Inspiration Points.

  

For each tier you possess in a skill, you gain a +1 bonus to any knowledge based checks on that skill.

  

For example anyone could attempt to light fire on some dry grass, but if you possess skill with Fire then you would be better placed to make assessments of where the fire will spread.

  

As you spend points on a skill, its Tier will increase and you can select techniques or improve them.

  

The techniques you have available to you depends on the Skill's tier, this follows the same pattern as your Tier, however each point spent counts as the Bonus.

## Abilities

### Traits

#### Affix

This ability must be paired with a concept, it cannot be used on its own.

#### Attack

Abilities with the Attack trait all use the same pool for frequency of use and Push, so if you have one ability with Push 2 and the default attack ability, you could make one attack with the first ability, any limbs used in that ability would be taken into account for the attack ability and Push would be included appropriately.

#### Complete

This is usually paired with Concentration or a cost that exceeds one round, the frequency of the ability is to complete it e.g. if you were interrupted while Concentrating on the action, you do not lose that use of the ability. 

Regardless of frequency, you can continue to use the ability until the use has been expended.

#### Concentration

Each time you use this Ability, increase your [Concentrating](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.204g86fo4uy9) condition by 1.

#### Continuation

This will be tied to another ability which will likely have the Concentration trait; the use of this ability does not interrupt your Concentration.

#### Delay

When you select a skill with this trait, you cannot select any skill that lists it as a prerequisite using the same allotment of IP.

#### Implement

Each time this ability is used, increase your Implement score by 1.

#### Limit

When you select an ability with this trait, you cannot select it again using the same allotment of IP.

#### Spell

This ability can be modified by abilities with the Supplementary trait.

#### Supplementary

These abilities are used in conjunction with Cast to cast spells; they also possess the Concentration and Implement traits.

#### Tool

These abilities require a specific tool to perform them effectively if you do not possess the required tool any checks made are Weak 2. Improvised equivalents reduce this to Weak 1.

#### Visualise

Usually tied to abilities with the Supplementary trait, make a Visualisation Check and add the converted result to your Visualisation Total.

## Technique Improvements

You can select these improvements to abilities in the place of selecting a new Skill or Ability.

### Lucid

Reduce the Complexity of the technique by 1 when considering Intelligence required.  
You can select this improvement multiple times.

### Neglected

Remove the Concentration trait from this Technique.

### Quick

The action cost is reduced by 1 to a minimum of 1.

### Discrete

The action no longer provokes reactions. This can be taken multiple times to combat the Alert technique.

### Internalised

The spell no longer takes up a memorisation slot, it instead becomes an ability. expand

Increase for reduction

### Repeatable

The frequency for this action increases.

From

To

1/Year

1/Month

1/Month

1/Week

1/Week

1/Day

1/Day

1/Hour

1/Hour

1/Combat

1/Combat

1/Round

1/Round

Push 1

Push N

Push N +1

  

### Practiced

The spell fatigue caused by visualisation and manifestation for casting the spell is reduced by 1. 

This can be taken multiple times.

### Stocked

Increase the number of times the ability can be used by 1.

## Combining Abilities

You can spend Inspiration Points to combine two abilities, it costs the total number of abilities being combined into one e.g. Combining 2 abilities into 1 would cost 2, adding a third later to that first composite ability would cost 3.

They are put together as follows:  
They gain both of the types (Ability / Reaction)

The cost of the pair is added together (reactions count as 1).

Combine the frequencies, adding their values, taking the frequency that corresponds to the combined value. 

  

Frequency

Value

1/Year

>7

1/Month

7

1/Week

6

1/Day

5

1/Hour

4

1/Combat

3

1/Round

2

Push N

1

Repeatable*

1

  

*Abilities cannot be reduced to Repeatable, while they do exist.

  

The requirements of both individual Abilities must be met.

The fatigue is combined e.g. Fatigue: Physical/Mental or Fatigue:Physical(2)

The combined ability provokes reactions if either of the separate abilities did.

Any Triggers from the two Abilities are added to the new one.

All rolls from the separate abilities must be made.

The new ability acts as both of the separate abilities for the purposes of a creature reacting to it.

When combining complete Spells, include the Spell Point cost in the Cost of the Ability, the ability gains the Spell trait, combine the Cast Spell ability into the other ability.

## General Skills

### Crafting

The difficulty of crafting an item is equal to its complexity added to 6, then multiplied by its Tier.

Without possessing the required skill, any items crafted have their quality reduced by 1.

Without possessing the required Rank, any items crafted have their quality reduced by 1 for the difference.

Any creature with Limbs(Dexterity) is capable of making use of the Craft Ability:

#### Craft

Ability

Fatigue: Both

Provokes Reactions: Yes

Attempt to Craft or Repair an item.

Make a check with a bonus equal to your Ranks in crafting for the Tier of Material.

Success: Create the item at Quality 0

Failure: The item is created at Quality -1

#### Material Skills

You can select each of these abilities once per Tier; each time grants you Rank 1 for crafting material of that Tier.

##### Tailoring

Required to make items with the Cloth material type.

##### Woodworking

Required to make items with the Wood material type.

##### Leatherworking

Required to make items with the Leather material type.

##### Blacksmithing

Required to make items with the Metal material type.

#### Master Craftsman 1 ([Limit](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.34p0fdhrb9xq))

Prerequisite: Material Skill

Select one of your Material Skills, and each of the items crafted using that skill is improved when working with Tier 1 materials.

Gain 1 Rank in that material skill.

When succeeding with the Craft ability, increase the Structure of the material by 1 for each rank in Master Craftsman, up to a maximum of +3.

Master Craftsman only applies to the specific Tier of Material Skill it was chosen for.

#### Improvised Crafter 1

Passive

You can craft items of complexity 1 using appropriate materials of Tier 1.

#### Repair Proficiency

Passive

Any attempt to repair an item where you possess all of the parts is Strong.

### Diplomacy

There are 5 main checks used when attempting diplomacy, any can be attempted without training, however the checks are Weak.

Each has the following profile:

  

Ability - Cost: 1

Fatigue: Mental

Provokes Reactions: No

Choose one desired outcome and make the specified check

#### Charm

Attempt to charm or entice a target, make a Wits Check opposed by their Will.

Success: Increase the target’s Relationship Score by 1 towards the desired outcome.

Failure: Reduce the target’s Relationship Score by 1.

#### Goad

Attempt to goad or incite a target, make a Wits Check opposed by their Will.

Success: Reduce the target’s Relationship Score by 1 towards the desired outcome. The target must make an Identity Check using its Id, subtracting the difference in your Checks.

Failure: No Change.

#### Intimidate

Attempt to intimidate a target, make an opposed Will Check. If the target.

Success: Increase the target’s Relationship Score by 1 towards the desired outcome. The target must make an Identity Check using its Id, subtracting your Checks.

Failure: Reduce the target’s Relationship Score by 1. The target must make an Identity Check using its Id, subtracting the difference in your Checks.

#### Lie

Attempt to lie to a target, make an opposed Wits Check.

Success: Increase the target’s Relationship Score by 1 towards the desired outcome.

Failure: Reduce the target’s Relationship Score by 1.

#### Reason

Attempt to reason with a target, make an opposed Intelligence Check.

Success: Increase the target’s Relationship Score by 1 towards the desired outcome.

Failure: Reduce the target’s Relationship Score by 1.

#### Tier 1

##### Lasting Impression

Passive

Select one form of Diplomacy; any increases to Relationship Score are permanent when using this ability.

##### Presence - Intimidate

Passive

Add your highest Physical Bonus to the Check.

### Locksmith

#### Tier 1

##### Pick Lock

Ability - Cost: 1 - Once per Round

Fatigue: Mental

Provokes Reactions: Yes

Requires: Lockpick

Make a Dexterity Check against the Lock.

You can attempt this check up to 3 times.

Success: It becomes opened

Failure: It remains locked

Failure by 10 or more: The lock becomes Jammed.

### Medicine

#### Tier 1

##### Internal Healing

Prerequisites: Suture

Cause 5 Active Wounds to the target when using Suture, reduce the target’s internal value by the Check result divided by 10 (rounded down).

##### Studied Anatomy

Choose a type of Tier 1 creature e.g. Human, you have greater knowledge of that creature’s anatomy.

##### Suture

Prerequisites: Studied Anatomy

Ability - Cost: 3 (Special) (Concentration)

Fatigue: Mental

Provokes Reactions: Yes

Requires: Healer’s Kit (Tool) (Scalpel, Needle + Thread)

Cause 1 Pain to the target, make a Dexterity Check, and spend a number of charges of thread to gain a bonus to the result. Reduce the target’s active wounds by the roll result.

##### Tight Binding

Prerequisites: Studied Anatomy

When using the Bandage ability, add your Strength Bonus to the total charges.

##### Weak Spot Knowledge

Prerequisites: Studied Anatomy

Choose one of your selections for Studied Anatomy

Your critical range increases by 1 for damage rolls made against your selected type.

### Quick Feet(Delay)

Passive

Increase the movement speed by 1.

You can select this ability multiple times, up to 3 times per Tier.

### Mortal Bloodline

You gain two Skills, one from each parent.

### Extraplanar Bloodline

Your bloodline contains traces of the other planes.

When selecting your Vice this will come from the Skill tied to your plane e.g. for Fire you would select Wrath

You can select appropriate abilities from creatures with the same Planar type as you.

You may not select opposed Skills to your Bloodline Skill.

You gain Vulnerability to your Bloodline Skill’s opposed Skills.

Additionally you gain Bloodline Casting:

#### Bloodline Casting (Supplementary) 

Ability - Cost: 1 - Once per Spell

Fatigue: Mental

Provokes Reactions: No

Lose 12 blood to gain 1 Spell Point reduction. 

### Hybrid Soul

Your soul is merged with one of another, each has a split of your Identity.

Roll 1d100 and use the larger portion of 100 for your main Identity e.g. you roll a 36, the main Identity would have 64Id and the other 36Id.

If the majority split is ever reversed, e.g. the Identity with 36Id above ever gains more than 50, then it becomes the main Identity.

  

When spending IP and XP, you must spend for both Identities.

  

You can select Abilities from the entities type for it.

  

When you switch Identities, you do not share Skills or Abilities.

#### Control Points

After a full rest, your identity starts with 0 Control Points.

Any other identities retain their Control Points from the previous day.

  

If the other gains 5 Control Points, it will attempt a Control Roll, taking over the body if it succeeds.

#### Appeasing

You can lower the number of Control Points the other has by appeasing it e.g. Lycanthropy may call for the consumption of raw meat.

The other will have a stability value, whenever attempting to appease it, roll 1D100, if you roll below its stability it is appeased successfully reducing its Control Points by the value specified, otherwise it gains that amount instead.

#### Control Check

When rolling for control, make a contested Will Check for each identity. 

If the controlling identity wins, they remain in control. 

If an Identity that is not currently in control wins, it must then roll 1D100, if it rolls below its Hold, it succeeds in gaining control. 

#### Harness Power

Ability - Cost: 1 - Once per Day

Fatigue: Mental

Provokes Reactions: No

Make a contested Will Check.

Success: You gain 1 Control Point.

Failure: The other gains 1 Control Point.

#### Conflict Scenarios

You can select a number of Conflict Scenarios, granting an additional number of Control Points to each Harness Power result, though potentially resulting in an immediate loss of control.

For Scenarios with a known frequency, where you are guarantee you gain:

  

Frequency

Control Points

Once per Month

1

Once per Week

2

Once per Day

4

  

For scenarios without a known frequency you gain 1 Control Point e.g. seeing blood.

  

Whenever you encounter the conflict scenario e.g. for lycanthropy once per month being a full moon, the other immediately gains control without needing to make a Control Roll.

#### Spending Control Points

Reaction - Once per Round

Fatigue: None

Provokes Reactions: No

Trigger: You gain Control Points

Each of these selections lasts for one minute.

1 = Take one of the other’s statistics as your own.

2 = Gain one attack from the other.

### Soulbound Weapon

You have bonded your soul to a weapon, will it be worth the risk.

Add an identity with 20 Hold and a Will equal to your own, if this identity ever falls below 20 Hold, you lose the benefit of this skill’s abilities.

To use these abilities, the weapon must remain within your mental domain.

#### As One

Passive

Embrace the weapon, taking it as part of yourself, gain damage reduction equal to the weapon’s Structure. The weapon is concealed within you and you can draw it using the Interact ability.

#### Blood and Soul

Ability - Cost: 1 - Once per Day

Fatigue: Both

Provokes Reactions: Yes

Drive the weapon into yourself or otherwise supply blood to it, losing 12 maximum blood and 2 Adrenaline.

The damage rolls of that weapon are Strong for the next 24 hours or until your maximum blood is returned.

#### Call to Hand

Ability - Cost: 1 - Once per Round

Fatigue: Mental

Provokes Reactions: No

Requires: Unobstructed line of effect between you and the weapon.

The weapon flies into your hands.

#### Bound Whirlwind

Ability - Cost: 1 - Once per Combat

Fatigue: Both

Provokes Reactions: Yes

Kick or throw your weapon towards a point in space, perform an attack against all creatures within its reach.

#### Shatter

Ability - Cost: 2 - Once per Combat

Fatigue: Mental

Provokes Reactions: No

Cause the weapon to shatter, dealing 1d10 + Will Piercing damage to any target within its space before returning to normal.

## Martial Styles

These Skills provide bonuses to fighting with a specific style.

You must first purchase the style itself to gain access to the skills underneath.

To use the skills within a style you must have entered that style.

  

You gain the following Abilities for free:

### Enter Style

Reaction - Once per Combat

Fatigue: None

Provokes Reaction: No

Trigger: You are aware that combat has started.

Enter one of your Styles, gaining the bonuses it provides.

### Change Style

Ability - Cost: 1 - Once per Round

Fatigue: None

Provokes Reactions: No

Change your Style, entering another that you possess or exit your current one.

### Arcane Warrior (Style)

A melee focused spell duelist, you gain the Arcane Duelist ability.

#### Aether Release

Reaction

Fatigue: Mental

Provokes Reactions: No

Trigger: You hit a target with the melee attack ability.

Use the Activate Implement ability.

#### Arcane Duelist

Passive

While adopting the Arcane Warrior Style, the size of your Mental domain becomes your size; the Cast ability does not provoke reactions.

#### Close Magic Adept

Passive

Any Checks you make for your spells that only affect you are Strong.

#### Magic Strike

Passive

You can prepare a spell using the Cast ability to be delivered with a weapon attack.

#### Focused Strikes

Passive

The attack check of Magic Strikes gains the Visualise trait.

#### Reflexive Warding

Passive

Any spell you cast may automatically include Ward Caster.

#### Spell Combat

Passive

Reduce the Spell Point cost of spells prepared using the Magic Strike ability by the Hands trait of your equipped weapon.

### Battle Smith

A practitioner of forging that brings their strength to the battlefield.

When you select this style, you gain 1 rank in Smith’s Tools. 

Resource: Heat (Maximum 5)

#### Heat

Heat is reduced to 0 at the start of your turn.

Some abilities require you to invest Heat, you can still spend this on other abilities, though the invested ability deactivates once you do.

#### Tier 1

##### Fluid Metals

Ability - Cost: 1 + 1 Heat - Once per Round

Fatigue: Physical

Provokes Reactions: No

Requires: Holding your Smith’s Tools, wearing metal armour.

###### Defense to Offense

Move up to 5 Physical Damage Reduction from your Armour to a bonus on damage rolls for your Smith’s Tools.

###### Offense to Defense

Take up to a -5 penalty to your Smith’s Tools’ damage rolls and gain an equal bonus to your Physical Damage Reductions.

##### Hammer out the Dents

Ability - Cost: 1 - Once per Round

Weapon Skill: Crushing 1

Fatigue: Mental

Provokes Reactions: No

Remove Sunder from a target. 

  

##### Heated Tools

Reaction - Once per Round

Fatigue: Mental

Provokes Reactions: No

Trigger: You deal damage with your Smith’s Tools.

Deal additional damage equal to your current Heat.

##### Improve Arms

Ability - 1 Minute - Once per Day

Fatigue: Mental

Provokes Reactions: Yes

Enhance a weapon for 1 hour increasing its Critical Range by 1.

##### Lingering Heat

Passive

Any invested abilities at the end of your turn remain active for one more Round.

##### Living Furnace

Reaction - Once per Round

Fatigue: Physical

Provokes Reactions: No

Trigger: Your turn has started.

Do not reduce your heat, reduce your maximum Blood by your current Heat.

##### Smith’s Sunder

Ability - Cost: 1 + 1 Heat

Weapon Skill: Crushing 1

Fatigue: Mental

Provokes Reactions: Yes

Add 1D10 to the damage roll of your next attack, this does not increase the actual damage dealt aside from when considering Sunder. 

##### Sparks of Combat

Passive

Whenever you damage a creature with your Smith’s Tools, gain 1 heat.

##### Smith’s Tools

Select one weapon or object, this becomes your Smith’s Tools.

##### Smolder

Ability - Cost: 1 - Once per Round

Fatigue: Mental

Provokes Reactions: No

Erupt in flame taking 1D10 Fire damage, this cannot be reduced in any way.

You gain Heat equal to half the damage taken.

##### Specialist Tools

Ability - Start of Day

Select one of your known Temporary Modifications, your Smith’s Tools have this modification for the rest of the day.

##### Stoke the Flames

Ability - Cost: 1 - Once per Round

Fatigue: Mental

Provokes Reactions: Yes

Gain 1 heat.

##### Temporary Modifications

You can apply at most one of these modifications to any one weapon.

Each must be chosen individually:

  

Ability - Cost: 1 - Once per Round

Fatigue: Physical

Provokes Reactions: Yes

Requires: 1 Heat to be invested, you must be holding your Smith’s Tools.

###### Bladed Edge

Choose one Crushing Weapon Attack of the weapon, it gains a Slashing Attack of the same type.

###### Sharpen Point

Choose one Crushing Weapon Attack of the weapon, it gains a Piercing Attack of the same type.

###### Blunt

Choose one Slashing or Piercing Weapon Attack of the weapon, it gains a Crushing Attack of the same type.

###### Keen Edge

Choose one Slashing or Piercing Weapon Attack of the weapon, increase the critical range of this attack by 1.

###### Serrated Edge

One of the Weapon’s Slashing Attacks gains the Brutal trait.

###### Barbed Point

One of the Weapon’s Piercing Attacks gains the Brutal trait.

###### Increase Weight

Increase the strength required of the weapon by 1.

###### Decrease Weight

Decrease the strength required of the weapon by 1.

###### Increase Reach

Increase the reach of the weapon by 1 Size.

###### Decrease Reach

Decrease the reach of the weapon by 1 Size.

###### Focused

One of the Weapons Attacks gains the Focused trait.

###### Increase Grip

Increase the hands trait of the weapon by 1.

###### Decrease Grip

Decrease the hands trait of the weapon by 1.

##### Through the Fire and the Flames

Passive

Gain 5 Damage Reduction against Fire.

##### Warmed by Flame

Reaction - Once per Round

Fatigue: Mental

Provokes Reactions: No

Trigger: You take fire damage

Gain heat equal to half the damage taken.

### Berserker (Style)

Resource: Ire (Maximum 5 per Tier)

A reckless fighting style that focuses on dealing as much damage as possible with disregard for personal safety. When you select this style, you gain the Enter Rage Ability

#### Enter Rage

Ability - Cost: 1

Gain the Rage condition.

#### Fueled by Rage

Reaction - Cost: 1 - Once per Round

Fatigue: Physical

Provokes Reactions: No

Trigger: You would gain Physical Fatigue

#### Ire is my Strength

Ability - Cost: 1 - Once per Round

Fatigue: Physical

Provokes Reactions: No

Spend some ire.

The damage of your next melee attack made this turn is increased by the ire spent.

#### Raging Blow

Ability - Cost: 1 - Push 2

Fatigue: Physical

Provokes Reactions: No

As the Attack ability, for each successful hit, gain 1 Ire.

#### That’ll Make a Great Scar

Reaction - Cost: 1 Ire - Once per Round

Fatigue: Mental

Provokes Reactions: No

Trigger: You are being damaged by an enemy’s attack.

The damage causes no Active Wounds.

Gain healing wounds as though you were healing the damage taken instead.

#### Too Angry To Die

Passive

While you have the Rage condition, you do not suffer the effects of Shock, though the Shock condition can still increase.

#### Vicious Strike

Ability - Cost 3 - Once per Round

Provokes Reactions: No

Spend Ire to reduce the action cost.

The damage roll of your next melee attack made this turn is Strong.

### Bulwark (Style)

Resource: Duty (Maximum 5 per Tier)

A selfless fighting style, one where you put yourself in harm's way to shield your allies and prevent your enemies from reaching them.

When you select this style, you gain 1 rank in Selfless Defender or Shield Ally. 

#### Armour of Sacrifice

Reaction - Once per Round

Fatigue: Mental

Provokes Reactions: No

Trigger: You have just stood in the way of an attack targeted against an ally or blocked on their behalf. 

Increase your Damage Reduction by 1. 

You can select this ability multiple times, up to a bonus of +5 per Tier. 

#### Body Block

Reaction - Once per Round

Fatigue: Physical

Provokes Reactions: Yes

Trigger: An enemy has declared a melee attack against an ally you are adjacent to.

Gain 1 Duty.

Move up to your Size to place yourself in between the attacker and your ally, you must have a clear space to move into.

#### Bulwark of Duty

Reaction- Cost: 1 Duty - Once per Day

Fatigue: None

Provokes Reactions: No

Trigger: You would gain Active Wounds.

Reduce the active wounds to 0, instead gain healing wounds.

You suffer pain as normal.

#### Designate Charge

Ability - Once per Day

At the start of the day, designate one target as your charge, any abilities that grant Duty, grant 1 more if you use them for your charge’s sake.

#### Duty Unfulfilled 

Prerequisites: Designate Charge

Reaction - Cost: 1 Duty

Fatigue: Mental

Provokes Reactions: No

Trigger: You would fall unconscious due to lack of blood and your Charge is still alive.

Do not fall unconscious.

Once the combat is over you fall unconscious.

#### Get Down

Reaction - Once per Round

Fatigue: Physical

Provokes Reactions: Yes

Trigger: An enemy has declared a ranged attack against an ally.

Gain 1 Duty.

Make a standing long jump, if you can place yourself in the line of fire contest the attack with your Agility.

Success: You are hit instead of your ally.

Failure: The ally must attempt to avoid as normal.

#### Indignation

Prerequisites: Righteous Vengeance

Passive

As part of your Righteous Vengeance attack, spend Duty to increase the damage by the Duty spent.

#### In the Line of Duty

Reaction - Once per Day

Fatigue: Mental

Provokes Reactions: No

Trigger: You would take Pain.

Spend Duty to reduce the Pain taken, any remaining Pain is taken as normal.

#### In Your Stead

Prerequisites: Righteous Vengeance

Reaction - Once per Round

Fatigue: Mental

Provokes Reactions: No

Trigger: An enemy deals damage to your charge and the distance between you and your charge is equal to or less than your size.

Swap places with your charge taking the damage instead.

Make one attack against the enemy.

#### Intercept

Reaction - Once per Round

Fatigue: Physical

Provokes Reactions: Yes

Trigger: An enemy is going to move into a position where they have melee reach of an ally.

Gain 1 Duty.

Move up to your speed to stand in their way.

#### Retaliate

Reaction - Once per Round

Fatigue: Physical 

Provokes Reactions: No

Trigger: You fully reduce the damage of a blocked attack, you can reach the attacker with an equipped melee weapon. 

Make an attack against the attacker. 

#### Righteous Vengeance

Prerequisites: Designate Charge

Reaction - Once per Round

Fatigue: Mental

Provokes Reactions: No

Trigger: An enemy deals damage to your charge.

Make a melee attack against that enemy.

#### Selfless Defender

Passive

Gain a +1 bonus to block rolls provided you are not the target of the attack.

You can select this ability multiple times, up to a bonus of +5 per Tier. 

#### Shield Anything

Passive

As part of a successful block, add your Shield Reduction to your Any Reduction instead of Physical Reduction.

#### Stand Aside

Prerequisites: Body Block

Reaction - Once per Round

Fatigue: Physical

Provokes Reactions: Yes

Trigger: An enemy has declared a melee attack against an ally you are adjacent to.

Gain 1 Duty.

Move up to your Size to place yourself in between the attacker and your ally. If they are adjacent, make a roll using the Shove Ability.

Success: You move the enemy away and take their position.

Failure: You are unable to stand between them.

Alternatively the ally can move up to their size without provoking reactions, provided you stand between them and the enemy. 

#### Stand in the Way

Prerequisites: Get Down

Reaction - Once per Round 

Fatigue: Physical

Provokes Reactions: Yes

Trigger: A harmful effect is about to harm an ally, or an ally is targeted for an attack. 

Move up to your speed to position yourself in the way. 

Gain 1 Duty.

#### Wall

Reaction - Once per Round

Fatigue: Mental

Provokes Reactions: No

Trigger: An area of effect is going to affect both you and an ally. 

Gain 1 Duty.

Add your Damage Reduction to the allies behind you. 

#### Your Pain is my Pain

Prerequisites: Designate Charge

Reaction - Cost: 1 Duty - Once per Round

Fatigue: Mental

Provokes Reactions: No

Trigger: Your charge would take Pain from an enemy’s attack.

Take the Pain instead of your charge.

### Martyr (Style) WIP

Prerequisites: Bulwark Style, Tier 2

Martyrdom (resource) 

Spent where duty would be, adrenaline in a ritual to gain martyrdom, resets at the start of each of your turns. 

  

Rite of Armamemt

Drive weapon against yourself 5 times

Gain the weapon on unarmed 

  

Rite of Warding

Suffer damage from the type to gain resistance per martyrdom 

  

Raiment

No armour but reduce physical by 6xtier + martyrdom 

  

Bulwark

To gain Martyrdom as shield reduction / block without it 

  

Stigmata

Constant weak 1 to held items / Dex etc.

Martyrdom can't go below your tier. 

  

Greater Stigmata

-5 max blood per. 

Martyrdom min +1 

  

Blood

Collect it as a resource, spend for damage reduction 

  

Tears? (/of blood? For more martyrdom) 

  

Blood regeneration based on martyrdom? 

  

Blood does not count as missing re. Conditions until it has been spent or the round after combat. 

  

Blood return - send some blood back into the body 

### Butcher (Style)

A brutal fighting style, gain one rank in Anticipation of Bloodshed. 

#### Anticipation (Resource) 

You gain anticipation whenever the physical damage you deal to a target is fully reduced. Gain anticipation equal to your damage dealt. 

#### Bloodshed (Resource) 

You gain bloodshed whenever you deal physical damage to a target, gain bloodshed equal to the active wounds gained,damage suffered or blood lost. 

#### Anticipation of Bloodshed 

Passive

Gain the resources: anticipation and bloodshed, these are linked, you can only spend points from the higher of the two. 

At the end of combat, reduce these both to 0.

#### Bleed my own blood

Reaction - Once per Round

Fatigue: Mental

Provokes Reactions: No

Trigger: You gain Active Wounds

Increase your Bloodshed by your active wounds gained. 

#### Bleed Them Dry

Reaction - Cost: Anticipation (all)  - Once per Day

Fatigue: Physical

Provokes Reactions: Yes

Trigger: You cause a target to suffer active wounds.

The target gains Gushing Wounds.

#### Blood Drenched

Ability - Cost: 1 + Bloodshed - Once per Combat

Fatigue: Physical

Provokes Reactions: Yes

Convert the spent bloodshed, gain this as a bonus to Physical Reduction until the end of combat.

#### Blood for Blood

Reaction - Cost: Up to 10 Bloodshed - Once per Round

Fatigue: Physical

Provokes Reactions: No

Trigger: An enemy causes you to gain Active Wounds. 

Use the Melee Attack ability. 

#### Blood in the water

Passive

You gain a bonus to movement speed when moving directly towards injured enemies equal to their active wounds converted. 

#### Blood is Blood

Passive

Blood in the Water is now also triggered by injured allies.

#### Bloody Brutality

Passive 

If your weapons possess the Brutal trait and would gain it again, they gain the following:

Crushing: Pain is doubled. 

Piercing: Target gains another stack of gushing wounds. 

Slashing: Target gains gushing wounds. 

#### Bloody Tools

Passive

Any check using the Frightening trait of your brutal weapons gains a bonus equal to your current Bloodshed converted. 

#### Brutal Strikes

Passive 

While your anticipation is higher than your bloodshed, your damage rolls are Strong. 

While your bloodshed is higher than your anticipation, your weapons gain the Brutal trait. 

#### Butcher's Block

Ability - Cost: 1 + Bloodshed (20) - Once per Combat

Fatigue: Mental

Provokes Reactions: No

The damage roll of your next melee attack made this turn is Strong. 

#### Butcher the Meat

Passive

You can select [Dismember](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.lgi1f9jc0z7m) Skills, your resource for these skills is Bloodshed (convert the maximum required for each point e.g. 20=2). 

#### Calm Down

Ability - Cost: 1 - Once per Round

Fatigue: Mental

Provokes Reactions: No

Reduce one of Anticipation or Bloodshed to 0.

#### Carnage 

Passive

If the damage dealt by an attack empowered by Butcher's Block kills a creature, refund the Bloodshed spent. 

#### Enough

Ability - Cost: 1 + Anticipation (All) - Once per Combat

Fatigue: Mental

Provokes Reactions: No

Your next melee attack made this turn gains double the Anticipation spent (converted) as penetrate. 

#### Greased Tools

Passive

Convert your Bloodshed value, gain a bonus to damage equal to this (maximum +5).

#### Hurry, hurry

Ability - Cost: Anticipation - Once per Combat

Fatigue:  Mental

Provokes Reactions: No

Gain a bonus to move speed equal to converted anticipation towards your next move action. 

#### Let Me In

Passive

Convert your Anticipation value, gain a bonus to Penetrate equal to this (maximum +5).

#### Raring to Go (Limit)

Passive

After successfully resting, gain 10 Anticipation.

You can select this up to 5 times.

#### Terrifying brutality

Passive

When wielding weapons with the Brutal trait, they gain the Frightening trait. 

### Duelist (Style)

#### A Challenge

Passive

Gain 1 additional Duelist's Advantage each time you would gain 1, up to a maximum of the Tier of the creature you are fighting. 

You can select this once per Tier. 

#### Dismembering Duelist

Passive

You can select Dismember Skills, your resource for these skills is Duelists Advantage. 

#### Duelist's Advantage (Resource) 

Proof that you have managed to gain the upper hand against your foe. You can have a maximum of 5 per Tier. 

#### Dueling Footwork

Ability - Cost: 1 - Once per Combat

Fatigue: Physica

Provokes Reactions: No

Gain 1 Duelist's Advantage. 

#### Duelist's Parry

Passive

When you successfully Parry an attack, gain 1 Duelist's Advantage. 

#### Making Progress

Passive

When you deal wounds to a creature, gain 1 advantage. 

#### Wide Open

Reaction - Cost: 1 Advantage / Tier 

Fatigue: Mental

Provokes Reactions: No

Trigger: A creature within your reach uses the attack ability, you have 4 or more Advantage / Tier of the creature. 

Make an attack as the Attack ability. 

#### Press the Advantage

Passive 

Your melee attack checks have a bonus equal to your advantage

#### Seize the Advantage

Passive 

A creature's Debilitated value is added to your Advantage when attacking it.

#### Eldritch Zealot - WIP

Test Identity to avoid pain?

### Grappler (Style)

A style dedicating to grappling and pinning the opponent.

#### Quick Reversal

Reaction - Once per Round

Fatigue: No

Provokes Reactions: No

Trigger: You succeeded in a use of the Break Free ability, you have remaining grapple score.

Use the Grab ability against the target. 

### Hunter(Style)

A style dedicated to focusing on one particular prey.

When you select this style, you gain 1 rank in Designate Prey.

#### Designate Prey

Ability - Cost: 1 - Once per Round

Fatigue: None

Provokes Reactions: No

Designate one creature you can perceive as your Prey.

You can select this ability once per Tier.

#### Aim

Ability - Cost: 1 - Once per Round (Concentration)

Fatigue: Mental

Provokes Reactions: No

Your next ranged weapon attack made against your Prey gains a bonus to attack and damage equal to your Visualisation Bonus.

#### Adapt to Terrain

Prerequisites: Favoured Terrain 3

Ability - Cost: 1 Hour - Once per Day

Adapt to your surroundings gaining the appropriate bonus of Favoured Terrain in place of one of your Favoured Terrains.

This lasts until you spend a full 24 hours outside of this new terrain type.

#### Deadly Aim

Prerequisites: Aim

Ability - Cost: 1 - Once per Combat (Concentration)

Fatigue: Mental

Provokes Reactions: No

Your next ranged weapon attack made against your Prey gains a bonus to attack and damage equal to your Visualisation Bonus.

Your damage roll for this attack is Strong.

#### Perfect Aim

Ability - Cost: 3 - Once per Combat (Concentration)

Fatigue: Mental

Provokes Reactions: No

Your next ranged weapon attack made against your Prey deals maximum damage. Roll as normal to establish Critical damage.

#### Disengage

Reaction - Once per Combat

Fatigue: Physical

Provokes Reactions: No

Trigger: A creature makes a melee attack against you.

This ability acts as Dodge Away.

#### Hunt

Passive

Any checks made to track or detect your Prey are Strong.

#### Favoured Prey

Prerequisites: Studied Anatomy Any

Passive

Any attacks made against Prey for which you also have Studied Anatomy are Strong.

#### Favoured Terrain

Passive

You can select this ability once per Tier

##### Aquatic

You can swim at full speed.

##### Arctic

You aren’t affected by cold 1 or 2 temperatures, and you can walk across ice and snow at full Speed without needing to Balance.

##### Desert

You aren’t affected by hot 1 or 2 temperatures, and you can walk across ice and snow at full Speed without needing to Balance.

##### Forest, Mountain or Underground (One of)

You can climb at half speed.

##### Plains

You gain a bonus to your Move ability, increase your available movement by your Agility bonus multiplied by your size.

##### Sky

You gain a bonus to your Fly ability, increase your available movement by your Agility score multiplied by your size.

##### Swamp 

You can move across bogs at full Speed, even if they are deep enough to hinder your movement or to normally require you to Swim.

#### Pin Prey

Prerequisites: Pinning Shot

Ability - Cost: 1 - Once per Combat

Fatigue: None

Provokes Reactions: Yes

Requires: Ranged Weapon with Piercing Weapon Attack.

Make a ranged weapon attack against your prey.

If you deal damage, it gains the Pinned condition.

#### Quick Draw

Ability - Cost: 1 - Once per Round

Fatigue: None

Provokes Reactions: Yes

Draw ammunition from storage.

#### Spotter

Ability - Cost: 1 - Once per Round

Fatigue: Mental

Provokes Reactions: No

Grant one ally the benefits of an ability that you know that requires you target your Prey.

#### Take the Shot

Ability - Cost: 1 - Once per Round

Fatigue: Mental

Provokes Reactions: No

For your next ranged weapon attack made against your Prey this turn, it does not gain the benefit of cover granted by other creatures.

#### Throw Off

Reaction - Once per Combat

Fatigue: Mental

Provokes Reactions: No

Trigger: You miss an attack against your Prey.

Your next ranged weapon attack made against your Prey is Strong.

### Pain Drinker (Style)

### Honourable Duelist (Style)

When you select this style, gain 1 rank in Challenge.

#### Honour (Resource) 

Honour is the resource of the Honourable Duelist, provided you do not actively spend it or perform dishonourable acts you retain this until you rest.

You can have a maximum of 5 per Tier. 

#### Challenge

Ability - Cost: 1 - Once per Combat (Concentration)

Fatigue: Mental

Provokes Reactions: No

Challenge a target you can perceive; any attacks you make or successfully react to against this target grant you 1 honour.

If you flee before besting your Challenged target, you lose all honour.

#### Demanding Challenge

Prerequisites: Challenge

Passive

The attacks of a target you challenge are weak unless they are targeting you.

#### Fervorous Challenge

Prerequisites: Challenge

Passive

Any attacks you make against your challenge target gain a bonus equal to your Honour.

#### Group Challenge

Prerequisites: Challenge

Passive

When you use your Challenge Ability, you can Challenge your maximum number of targets at once.

#### Falling Somersault 

Reaction - Once per Day

Fatigue: Physical 

Provokes Reactions: Yes 

Trigger: You are falling towards a space from which you have reach to an enemy.

As part of falling make an attack against a creature that will be within your reach. 

#### First and Final

Ability - Cost: 2 - Once per Day

Fatigue: Both

Provokes Reactions: No

Expend all Honour, the damage roll of your next melee attack made this turn is Strong.

If this does not slay the target, you can no longer gain Honour until it is dead. 

#### Honourable Challenge

Prerequisites: Challenge

Passive

Any damage rolls you make against a target of your challenge have a bonus equal to your current honour.

#### Many Challenge

Prerequisites: Challenge

You can Challenge 1 more target, though only 1 can be challenged with 1 use of Challenge.

This ability can be selected multiple times.

#### Rising Strike (Limit) 

Ability - Cost: 1 - Once per Day

Fatigue: Physical

Provokes Reactions: Yes

Your next attack will launch you into the air, you move vertically as though making a standing high jump. 

#### Improved Rising Strike (Limit) 

Prerequisites: Rising Strike

Passive 

You jump as though you had a run up. 

#### Greater Rising Strike

Prerequisites: Rising Strike

Passive 

The damage roll of the attack is Strong. 

#### Strike Through

Prerequisites: First and Final 

Ability - Cost: 1 - Once per Day

Fatigue: Mental

Provokes Reactions: No

As part of your next melee attack, move up to half your speed as you strike, this movement does not provoke reactions. 

#### Strike as Wind

Prerequisites: Strike Through

Passive 

The movement of Strike Through does not have to be horizontal. 

#### Targeted First and Final (Limit)

Prerequisites: First and Final

Ability - Cost: 2 - Once per Day

Fatigue: Both

Provokes Reactions: No

Expend all Honour, provided the attack is being made against your challenged target, the attack and damage roll of your next attack made this turn is Strong.

#### Unending Thrusts

Reaction - Cost: 1 Honour - Once per Day

Fatigue: None

Provokes Reactions: No

Trigger: Your last piercing melee attack resulted in the target taking no damage. 

Make another attack as the Attack ability. 

### Personal Style (Style)

A self taught style, capable of combining many styles in one.

#### Training

This ability costs 2 IP.

Select one Ability listed under another Style Skill; you gain that ability provided you meet its prerequisites.

You can select this ability multiple times.

### Sapper (Style)

When you select this Style you gain 1 rank in Hamstring.

#### Sap (Resource)

You start each day with 1 Sap charge.

#### Extra Debilitation (Delay)

Select one negative condition, when a creature has this condition, treat its Debilitated value as 1 higher.

You can select this multiple times, selecting a different condition each time.

#### Increased Saps (Delay)

Gain +1 Sap charges/day.

You can select this multiple times up to +3/tier

#### Hamstring (Limit)

Ability - Cost 1 + Sap - Once per Round

Fatigue: Physical

Provokes Reactions: No

Invest 1 - 1 round

Spend 1 - permanent

The creature’s speed is reduced by one limb.

Its Debilitated condition increases by 1.

#### Weakening Hamstring 

Prerequisites: Hamstring, Anatomy

Any rolls requiring that bonus are weak.

#### Improved Sap (Limit)

Passive

Whenever the target pushes, it suffers pain equal to its Debilitated value.

#### Halting Sap

Prerequisites: Improved Sap

Passive

The creature cannot push while it has the Debilitated condition.

You can choose to apply this effect or not.

#### Blind

Prerequisites: Improved Sap

Ability - Cost 1 + Sap - Once per Round

Fatigue: Physical

Provokes Reactions: No

Invest 1/ eye - 1 round + 1 action for them to clear

Spend 1 / eye permanent

Creature gains the Blinded condition with value equal to the targeted eyes for the duration.

Its Debilitated condition increases by 1.

#### Gut shot (Limit)

Prerequisites: Improved Sap

Reaction - Cost: Sap - Once per Round

Fatigue: Physical

Provokes Reactions: No

Trigger: You dealt crushing damage to a creature.

Invest 1 - 1 round

Spend 1 - permanent

Make a Strength Check contested by the target’s Constitution.

Success: The target gains the Winded Condition.

#### Improved Gutshot

Prerequisites: Gut Shot

Passive

On a Success the target is also Nauseated

#### Bludgeon (Limit)

Prerequisites: Improved Sap

Reaction - Cost: Sap - Once per Round

Fatigue: Physical

Provokes Reactions: No

Trigger: You dealt crushing damage to a creature.

Invest 1 - 1 round

Spend 1 - permanent

Make a Strength Check contested by the target’s Constitution.

Success: Any Mental Checks the creature makes are Weak.

#### Improved bludgeon

Prerequisites: Bludgeon

Passive

On a Success the target falls unconscious.

#### Deafen

Prerequisites: Improved Sap

Ability - Cost 1 + Sap - Once per Round

Fatigue: Physical

Provokes Reactions: No

Invest 1 - 1 round + 1 action for them to clear

Spend 1 permanent

Creature gains the Blinded condition with value equal to the targeted eyes for the duration.

Its Debilitated condition increases by 1.

#### Throat Shot (Limit)

Prerequisites: Improved Sap

Reaction - Cost: Sap - Once per Round

Fatigue: Physical

Provokes Reactions: No

Trigger: You dealt crushing damage to a creature.

Invest 1 - 1 round

Spend 1 - permanent

Make a Strength Check contested by the target’s Constitution.

When Permanent, the creature can make a Constitution Check contested against your Strength to remove it as an action.

Success: The target cannot breathe.

#### Heart Stopper

Prerequisites: Throat Shot

Reaction - Cost: Sap - Once per Round

Fatigue: Physical

Provokes Reactions: No

Trigger: You dealt crushing damage to a creature.

Invest 1 - 1 round

Spend 1 - permanent

Make a Strength Check contested by the target’s Constitution.

When Permanent, the creature can make a Constitution Check contested against your Strength to remove it as an action.

Success: You stop one of the target’s hearts, it gains 1 Shock until it starts again.

### Snake (Style)

A style employing the use of two short weapons and relies on rapid speed and dodges.

When you select this style, you gain 1 rank in Poisoner or Prepare Poison. 

#### Coil

Reaction - Once per Round

Fatigue: Physical

Provokes Reactions: No

Trigger: You make a melee attack against a target.

Move up to your size without increasing the distance between yourself and the target.

#### Dash Through

Ability - Cost: 2 - Once per Round

Fatigue: Physical

Provokes Reactions: Special

Move up to twice your speed, the first part provokes reactions as normal, the second part does not.

#### Distract 

Ability - Cost: 1 - Once per Day

Fatigue: Physical

Provokes Reactions: No

Target the space opposite yourself on a creature, you gain a +2 bonus to any attack rolls made against the creature.

Make a contested Will Check against the creature:

Success: Any creature attacking it gains the bonus.

  

#### Extend Preparation

Reaction - Once per Round

Fatigue: Physical

Provokes Reactions: No

Trigger: You would spend Preparation on an attack or damage roll.

Do not spend Preparation on this attack.

#### Hasten Preparation

Reaction - Cost: All Preparation - Once per Round

Fatigue: Physical

Provokes Reactions: No

Trigger: You would spend Preparation on an attack or damage roll.

Gain the effects of one Ability you possess that affects your next attack or damage roll.

#### Glance

Reaction - Once per Round

Fatigue: Physical

Provokes Reactions: No

Trigger: A creature stops your movement with an attack of opportunity

Taking a glancing hit, your movement is not impeded.

#### Lie in Wait

Reaction - Once per Round

Fatigue: Mental

Provokes Reactions: No

Trigger: You make use of an ability that mentions “your next attack/damage roll this turn”.

Extend the effect to your next attack / damage roll made this combat.

#### Preparation

Resource

Gain 1 preparation whenever you use an ability that specifies “your next attack/damage roll this turn”

When you make an attack, increase the attack and damage rolls by your preparation then reduce your Preparation to 0.

#### Prepare Poison

Ability - 1 hour - Once per Day

Prepare 1 dose of Poison, this poison lasts on your weapons for 1 combat, it deals 1 Necrotic Damage.

#### Prepared Lunge

Prerequisites: Lunge

Passive

Spend one preparation as part of Lunge, the return movement does not provoke reactions. 

#### Ready… Go

Ability - Cost: 1 + 2 Adrenaline - Once per Round

Fatigue: None

Provokes Reactions: No

Gain 1 Preparation.

#### Recoil

Reaction - Once per Day

Fatigue: Physical

Provokes Reactions: No

Trigger: You take damage from an attack.

Move up to half your move speed, this movement does not provoke reactions.

#### Shed Skin

Reaction - Once per Day

Fatigue: Physical

Provokes Reactions: No

Trigger: You are the target of an attack.

Move to a space within long jump distance leaving behind a decoy that the enemy creature must attack.

#### Slip Through

Reaction - Once per Combat

Fatigue: Physical

Provokes Reactions: No

Trigger: You would trigger a reaction while moving.

Make a contested Agility roll against the threatening creature’s Wits.

Success: They are unable to take reactions for this use of the Move ability.

Failure: They are able to take reactions as normal.

#### Smoke Bomb

Ability - Cost: 1 - Once per Day

Fatigue: Physical

Provokes Reactions: No

Throw a smoke bomb (Strength Required 1) creating a cloud of smoke in a 3x3 space, everything within 1 metre gains Cover, anything further than that gains Concealment.

The smoke lasts until the start of your next turn.

#### Spring

Ability - Cost: 1 - Once per Combat

Fatigue: Physical

Provokes Reactions: No

Gain momentum equal to twice your Preparation. 

Your Preparation is set to 0.

#### Twin Fang

Ability - Cost: 2 - Once per Combat

Fatigue: Physical

Provokes Reactions: No

Make an attack with a weapon in each hand, if they both hit, increase the critical range of the damage rolls by 1.

### Thrown Specialist (Style)

A specialist fighter in thrown weapons, when you select this style you gain 1 rank in Tethered Proficiency.

#### Full Withdraw

Passive

When using the Pull ability, use your Strength Score instead of your Strength Bonus.

#### Impale

Reaction - Once per Round

Fatigue: None

Provokes Reactions: No

Trigger: You deal piercing damage to a creature with a thrown weapon.

The weapon remains embedded; the creature can use an action to remove the weapon, Whenever the weapon is removed, the creature gains 5 active wounds. 

If the weapon possesses the Tethered trait, the creature can remove the effect by leaving its range.

You can Pull the weapon to return it to you as normal.

While the creature is impaled, it suffers 1 pain whenever it pushes.

#### Improved Impale

Passive

When you have impaled a creature, increase it’s Grabbed Condition by 1, increase your Controlling Grapple Condition by 1 while holding the weapon.  
The creature can no longer remove the weapons by leaving their range.

#### Pass Through

Prerequisite: Improved Impale

Reaction - Once per Turn

Fatigue: Mental

Provokes Reactions: No

Trigger: You deal piercing damage to a creature with a thrown weapon.

The weapon continues to travel in a straight line up to its maximum range; any Attack checks you make past the first are Weak equal to the number of creatures the weapon has travelled through.

If the weapon is tethered, the creature is treated as under the effect of Improved Impale, it can only be removed by taking 3 actions, acting as Impale.

#### Improved Pass Through (Delay)

Prerequisite: Pass Through

Passive

Reduce the Weak value of attacks made as part of Pass Through.

You can select this ability multiple times.

#### Improved Ricochet Toss

Prerequisites: Ricochet Toss

Passive

Increase the number of available ricochets by 1.

#### Quick Withdraw

Passive

When using the Pull ability, you can add your Dexterity Bonus to the distance.

#### Ricochet Toss

Ability - Cost: 1 - Once per Turn

Fatigue: Mental

Provokes Reactions: No

The next thrown weapon attack you make this turn ricochets once it hits its target, travelling up to its remaining range. Use the hit surface as the origin of the next attack, i.e. you cannot target anything behind or directly to the side of the original target. Any attack checks made are Weak equal to the number of Ricochets.

#### Tethered Weapon Proficiency

Passive

When wielding a weapon with the Tethered trait, you qualify for the requirement provided you meet all others.

#### Whiplash

Prerequisites: Impale

Ability - Cost: 1 - Once per Turn

Fatigue: Physical

Provokes Reactions: Yes

Pull your weapon from the target and make an attack using the Ranged Attack ability against another target, your weapon must pass through your space and can only travel as far as half the distance the Pull ability would grant you.

#### Improved Whiplash

Prerequisites: Whiplash

Passive

Your weapon no longer needs to pass through your space.

You cannot increase the distance from yourself.

#### Far Whiplash

Prerequisites: Whiplash

Passive

You can use Whiplash against a new target within the full distance allowed by the Pull ability.

  

Chain Slinger (Style) WIP

Prerequisites: Tier 2, Thrown Weapon Specialist 

1 action per turn or on return 

Keep weapon close and moving, select one side, gain extra reduction there / free attack / bonus parry 

  

Could give reaction for on return 

  

All around, of above as a thing 

  

Gain momentum for ^

### Torturer (Style)

#### Cruelty

Ability - Cost: 1 - Once per Round

Fatigue: None

Provokes Reactions: No

Increase the attack roll of your next attack this turn by the adrenaline the creature is missing (Maximum 5).

#### Malice

Ability - Cost: 1 - Once per Round

Fatigue: None

Provokes Reactions: No

Increase your Critical Range of your next damage roll this turn by the amount of Shock the target has (Maximum 5).

#### Sadism

Ability - Cost: 1 - Once per Round

Fatigue: None

Provokes Reactions: No

Restore Adrenaline equal to the amount of Pain you deal with your next weapon attack this turn.Weapon Skill

You are trained in the use of particular weapons. 

Choose a number of weapon traits, or specify a specific weapon for this Skill. 

These Traits must be used together when qualifying for prerequisites e.g. Given you choose 1-handed, bladed, piercing, short, light weapons (which could otherwise be summed up as a dagger) you would qualify for any prerequisites that are in that group, however, you could not later gain the Weapon Skill - 2-handed, and attempt to qualify for a 2-handed, bladed Ability. 

Likewise you could not use it to qualify for a 1-handed, heavy Ability. 

### Weapon Training (Delay, Limit)

Prerequisites: Weapon Skill(Any)

Choose one of your Weapon Skills

You gain a bonus to attack rolls made with the selected Weapon Skill equal to half of your ranks (rounded up) in this Skill.

You can select this multiple times, up to 5 times per Tier.

Weapon Training for multiple Weapon Skills does not stack, the highest takes effect.

### Feint

Prerequisites: Weapon Skill

Passive

You can use the Lie ability with a bonus equal to your Weapon Training if they apply to your current weapon, the enemy can add the same for theirs, this changes the results for success and failure. 

Success: The target gains 1 mental fatigue. 

Failure: None 

### Mordhau

Prerequisites: Weapon Skill

Ability - Cost: 1

Fatigue: None

Provokes Reactions: Yes

Requires: Weapon with Arc(Slashing) that does not have the Focused Trait. 

Shift to Mordhau grip, the weapon loses all traits aside from form traits and gains the Focused trait, it gains a MiR equal to its MaR, loses all attacks, gains an Arc(Crushing) attack with its original crushing damage. 

### Shift Grip

Prerequisites: Weapon Skill

Ability - Cost: 1

Fatigue: None

Provokes Reactions: Yes

Either:

Shift the grip on a weapon and wield it with 2 hands to reduce the MaR and MiR of the weapon; any Arc Attack and Damage rolls made are Weak equal to the number of your Size that you reduced it by rounded up; any Piercing Thrust attacks gain an additional 5 Penetrate per Tier of the Weapon.

Or:

Shift to an alternate grip provided by the weapon. 

  
  
  

### Dual Blades

Prerequisites: Weapon Training 3 (Any)

Passive

Select one of your Weapon Training combinations.

Your attack rolls made with your non-dominant limbs(Dexterity) are not Weak. 

## Dual Ease

Prerequisites: Weapon Training 5 (Any)

Passive

Select one of your Weapon Training combinations.

Your attack rolls made each separate limb(Dexterity) no longer affect each other with regards to Push i.e. Your first attack made with each additional limb does not require push. 

### Shield Training (Delay, Limit)

Prerequisites: Weapon Skill(Shield)

Passive

Select one type of Shield, you have a bonus of +1 to any block attempt made with that type of shield.

### Nimble Step ([Limit](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.34p0fdhrb9xq))

Prerequisites: Weapon Training(Any)

Choose one of your Weapon Trainings. You no longer provoke reactions when making attacks against targets with reach 1 category higher than yours.

You can select this ability multiple times.

### Step Inside ([Limit](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.34p0fdhrb9xq))

Prerequisites: Nimble Step

Choose one of your Nimble Steps. Your attacks made against creatures with long reach are strong. You can select this ability multiple times, each time reducing the maximum reach that this ability applies to; you cannot gain strong attacks against your own reach in this way.

### Fault Finder

Ability - Cost: 1 - Once per Round

Weapon Skill: 1-handed, piercing, short 1

Fatigue: Mental

Provokes Reactions: No

Your next melee attack made this turn while standing directly behind a target gains penetrate equal to the distraction penalty the target currently has.

### Lunge

Ability - Cost: 1 - Once per Round

Weapon Skill: 1-handed

Fatigue: Physical

Provokes Reactions: No

Requires: 1-handed weapon

As attack, increasing your reach by up to your size as you step in to lunge, as part of the lunge then move back to your original position, this return movement provokes reactions. 

### Backstab 

Ability - Cost 1 - Once per Round

Weapon Skill: 1-handed, piercing, short 1

Fatigue: Mental

Provokes Reactions: No

When you make your next melee attack this turn, also make a Visualisation roll.

If you manage to beat the target's response with this roll, increase the critical range of the attack by 1.

### Feint Follow-up 

Passive 

When successfully feinting, the attack roll of your next melee attack made this turn is Strong. 

### Hammer Blows

Reaction - Once per Day 

Weapon Skill: Crushing 1

Fatigue: Mental

Provokes Reactions: No

Trigger: Your last crushing damage roll didn't penetrate through reduction. 

Your next crushing damage roll made this turn gains penetrate equal to the last damage roll.

This can never stack with itself.

### Momentum

Passive

Weapon Skill: Any 1

Each time you make a melee attack or use the Move ability, gain one stack of Momentum.

You can have a number of stacks equal to five multiplied by your Tier.

#### Chaining Attacks

Ability - Cost: 2 Momentum - Once per Round

Fatigue: None

Provokes Reactions: No

Use the Melee Attack ability, this attack does not generate Momentum.

#### Improved Chaining Attacks

Passive

Attacks made as part of the Chaining Attacks ability now generate Momentum as normal.

#### Momentum Carries Me

Ability - Cost: X Momentum - Once per Round

Fatigue: Physical

Provokes Reactions: No

Use the Move ability where your movement speed is considered the number of Momentum you spent.

#### Vault

Ability - Cost: 5 Momentum - Once per Round

Fatigue: Physical

Provokes Reactions: No

Move as though making a long jump.

You can pass directly through spaces occupied by hostile creatures.

#### Wind Up

Reaction - Cost: X Momentum - Once per Round

Fatigue: Physical

Provokes: Reactions No

Spend X Momentum to make your next damage roll deal X more physical damage.

### Dismember

Prerequisites: Style granted access. 

Reaction - Once per Day

Fatigue:Mental

Provokes Reactions: No

Trigger: You deal Wounds to a creature with a melee weapon. 

The following are each separate skills that can be selected and then used as part of Dismember. Modifications to the skill are all done at the subskill level. 

Each has a resource cost associated, the value is per each Tier of the creature. The resource will be specified by your Style. 

When you first gain Dismember, you gain 1 rank in Dismember - Finger.

#### Dismember - Finger (Limit) 

Cost: 1 / Tier

Requires: Slashing 

Remove one of the creature's fingers, it must succeed on a Will Check against the damage roll, or else drop what it is holding.

#### Dismember - Hand (Limit)

Prerequisites: Finger

Cost: 2 / Tier 

Requires: Slashing 

Remove one of the creature's hands.

#### Dismember - Arm (Limit)

Prerequisites: Hand

Cost: 3 / Tier

Requires: Slashing 

Remove one of the creature's Arms. 

#### Dismember - Leg (Limit)

Prerequisites: Hand

Cost: 3 / Tier

Requires: Slashing 

Remove one of the creature's legs. 

#### Dismember - Behead (Limit)

Prerequisites: Arm, Leg

Cost: 5 / Tier

Requires: Slashing

Remove one of the creature's heads. 

#### Dismember - Skullsplitter (Limit)

Prerequisites: Arm, Leg

Cost: 5 / Tier

Requires: Piercing

Strike the creature in the head, destroying one of its brains. 

#### Dismember - Bisect (Limit)

Prerequisites: Behead

Cost: 5 / Tier

Requires: Slashing

Cut the creature in half. 

### Reject Advantage

Ability - Cost 2 - Once per Round

Weapon Skill: Any 1

Fatigue: Physical

Provokes Reactions: No

Make one attack against a creature, and then another attack against a creature directly opposite it, you suffer fatigue after making both attacks.

### Follow Through

Ability - Cost 2 - Once per Round

Weapon Skill: Any 1

Fatigue: Physical

Provokes Reactions: No

Use the Melee Attack ability against a creature, and then again against another creature within your reach, taking the distraction penalty of their position against the second attack.

### Overwhelming Strikes

Passive

Weapon Skill: Any 1

When making an attack contest where you are being parried, gain a bonus equal to your weapon’s Strength Required.

### Riposte

Reaction - Once per Round

Weapon Skill: Any 1

Fatigue: Physical

Provokes Reactions: No

Trigger: You parried an attack and the attacker is within your reach

Use the attack ability against that target.

### Sundering Blows

Ability - Cost: 3 - Once per Combat

Weapon Skill: Crushing 1

Fatigue: Physical

Provokes Reactions: No

As the Attack ability, cause 5 additional sunder.

### Cleave

Ability - Cost: 2 - Once per Round

Weapon Skill: Any 1

Fatigue: Physical

Provokes Reactions: No

Use the Melee Attack ability once each for two adjacent targets, do not increase your fatigue until you have made both attacks.

### Shared Cleave

Ability - Cost: 2 - Once per Round

Weapon Skill: Any 1, Cleave

Fatigue: Physical

Provokes Reactions: No

Use the Melee Attack ability once for two adjacent targets, roll damage twice and half the total, each target takes that much damage. 

  

### Greater Cleave

Ability - Cost: 2 - Once per Round

Weapon Skill: Any 1, Cleave

Fatigue: Physical

Provokes Reactions: No

Use the Melee Attack ability once each for all targets in front of you, do not increase your fatigue until you have made all attacks.

### Whirlwind

Ability - Cost: 3 - Once per Round

Weapon Skill: Any 1, Greater Cleave

Fatigue: Physical

Provokes Reactions: No

Use the Melee Attack ability once each for all targets within your reach, applying any distraction penalties from your starting position.

### Greater Whirlwind

Ability - Cost: 3 - Once per Round

Weapon Skill: Any 1, Whirlwind

Fatigue: Physical

Provokes Reactions: No

As Whirlwind, but do not apply distraction penalties.

### Whirling Stance

Reaction - Cost: 1 - Once per Round

Weapon Skill: Any 1, Whirlwind

Fatigue: Physical

Provokes Reactions: No

Trigger: The last ability you used on your last turn was Whirlwind 

Make another use of the Whirlwind ability. 

### Power Attack

Ability - Cost: 1 - Once per Round

Provokes Reactions: No

Your next melee damage roll made this turn is Strong.

Take either:

-5 penalty to hit.

4 physical fatigue in addition to the attack fatigue.

### Heavy Blows

Passive

Weapon Skill: Heavy

Add your weapon’s Strength Required to its damage.

### Taunt

Reaction - Once per Round

Fatigue: Mental

Provokes Reactions: No

Trigger: A creature is attacking an ally with a melee weapon, you are also within that creature's reach. 

Contest your Wits against the creature's Will

Success: the creature must direct the attack towards you. 

Failure: The creature can choose its target as normal.

  

### Open Opportunity

Ability - Cost: 1 - Once per Round

Weapon Skill: Shield 1

Fatigue: Physical

Provokes Reactions: No

Your next melee attack made this turn with a Shield causes the target to gain the Destabilised(1) Condition until the start of its next turn. 

### Shield Block

Ability - Cost: 1 - Once per Round

Weapon Skill: Shield 1

Fatigue: Physical

Provokes Reactions: No

Add your bonus to attack rolls gained from Weapon Training: Shield to your shield’s damage reduction until the start of your next turn.

### Shield Deflect

Reaction - Once per Round

Weapon Skill: Shield 1

Fatigue: Physical

Provokes Reactions: No

Trigger: You are being attacked with a Piercing attack. 

Make a strength roll, reduce the Penetration of the attack by the result. 

### Rowdy Shield Bearer

Passive

Weapon Skill: Shield 1

Your attack rolls made with a shield using your non-dominant limb(Dexterity) are no longer Weak. 

### Shield Slam

Ability - Cost 1 - Once per Round

Weapon Skill: Shield 1

Fatigue: Mental

Provokes Reactions: No

Your next melee attack this turn that does Crushing damage causes the target to make a Constitution Check against 6 multiplied by your Tier +  Your Strength Bonus or gain the Winded Condition.

### Pummel

Reaction - Once per Round

Fatigue: Physical 

Provokes Reactions: No

Trigger: You are aware that a creature within your reach is casting a spell. 

As the Attack ability, increase the difficulty of the Wits Check the caster can make by 5.

### Shield Ally

Reaction - Once per Round

Weapon Skill: Shield 1

Fatigue: Physical 

Provokes Reactions: No

Trigger: A creature has declared an attack against a creature you are adjacent to. 

As the Block ability, you do not move for this, nor need to physically be in the way of the attack. 

Success: Add your Shield's reduction to your ally's total reduction. 

Failure: The ally must deal with the attack as normal. 

### Impact

Your crushing attacks cause various maladies. 

For each of the skills below the target creature must make a Wits Check against the Dice Roll added to your damage Statistic and the weapon's weight, half the weight for slashing / piercing, multiply by 1+MeR for Focused. 

#### Destabilising Blow

Reaction - Once per Combat

Fatigue: Physical

Provokes Reactions: No

Trigger: You deal Crushing Damage

Check: Wits

Failure: the creature gains the Destabilised(1) condition. 

#### Felling Blow

Reaction - Once per Combat

Fatigue: Physical

Provokes Reactions: No

Trigger: You deal Crushing Damage

Check: Strength

Failure: the creature falls prone.

#### Improved Felling Blow 

Prerequisites: Felling Blow

Passive

On a successful Check, the target creature falls to a crouched stance. 

#### Pushing Blow

Reaction - Once per Combat

Fatigue: Physical

Provokes Reactions: No

Trigger: You deal Crushing Damage

Check: Strength

Failure: move the creature as with the Push Ability. 

#### Rupturing Blow

Reaction - Once per Combat

Fatigue: Physical

Provokes Reactions: No

Trigger: You deal Crushing Damage

Check: Constitution

The creature gains the Internal condition with a value equal to the attack's converted damage. 

#### Winding Blow

Reaction - Once per Combat

Fatigue: Physical

Provokes Reactions: No

Trigger: You deal Crushing Damage

Check: Constitution

Failure: the creature gains the winded condition. 

### Reduce Momentum

Passive

When you block successfully with a shield, if the attacker would have gained momentum, they do not. 

### Absorb Momentum

Prerequisites: Reduce Momentum

Passive

When you block successfully with a shield, if the attacker would have gained momentum, you gain it instead of them. 

### Reckless Abandon

Passive

When you select this ability choose one resource gained through another Ability.

Each time you are attacked and take the hit intentionally, gain 1 of that resource.

### Rebounding Blow

Ability - Cost: 2 - Once per Round

Fatigue: Physical

Provokes Reactions: No

The damage roll of your next melee attack this round is Strong.

You gain healing wounds as though healing the damage you deal.

### Shield Rebound

Prerequisites: Weapon Skill (Shield) 

Reaction - Once per Round

Fatigue: Mental

Provokes Reactions: No

Trigger: You hit your intended target with your thrown shield. 

Make a Dexterity Check against 3 multiplied by the distance / your size. 

Success: the shield rebounds directly toward you, it travels the remaining throw distance you had. 

Failure: It falls in the target's space as normal

### Adrenaline Rush

Ability - Cost: 1 - Once per Round

Fatigue: Physical

Provokes Reactions: No

Spend one Adrenaline to gain two actions.

These actions cannot be used to Focus or Adrenaline Rush.

### Adrenaline Surge

Ability - Cost: 1 - Once per Round

Fatigue: Physical

Provokes Reactions: No

Spend one Adrenaline to make the next Strength Check you make this turn Strong.

### Fuelled by Adrenaline 

Reaction - Once per Round

Fatigue: None

Provokes Reactions: No

Trigger: You would suffer Physical Fatigue

Spend Adrenaline equal to the Fatigue you would have gained, you gain no Fatigue.

### The Will to Survive

Ability - Cost: 1 - Once per Day

Fatigue: Mental

Provokes Reactions: No

Gain Adrenaline equal to your Will Bonus, this cannot exceed your maximum Adrenaline.

### Can’t Slow Down

Reaction - Cost: 1 Adrenaline

Fatigue: Mental

Provokes Reactions: No

Trigger: You would gain 1 Physical Fatigue

Do not gain 1 Physical Fatigue.

### Imperfect Instinct

Reaction - Cost: 1 Adrenaline - Once per Day

Fatigue: Both

Provokes Reactions: No

Trigger: You are the target of an ability that would deal damage.

Determine how much damage it would have done and suffer the appropriate pain, any other effects are ignored. 

### Pinning Shot

Prerequisites: Weapon Skill (Any Ranged, Weapon Attack Piercing)

Ability - Cost: 1 - Once per Combat

Requires: Ranged Weapon with Piercing Weapon Attack.

Fatigue: None

Provokes Reactions: Yes

Your next ranged weapon attack roll made this round  is weak.

If you deal damage, it gains the Pinned condition.

### Impaling Shot

Prerequisites: Weapon Skill (Any Ranged, Weapon Attack Piercing)

Ability - Cost: 1 - Once per Combat

Fatigue: None

Provokes Reactions: Yes

Requires: Ranged Weapon with Piercing Weapon Attack.

Your next ranged weapon attack roll made this round  is weak.

If you deal damage, it gains or increases the Impaled condition by 1.

### Penetrating Shot

Prerequisites: Weapon Skill (Any Ranged, Weapon Attack Piercing)

Ability - Cost: 1 - Once per Combat

Fatigue: None

Provokes Reactions: Yes

Requires: Ranged Weapon with Piercing Weapon Attack.

If you deal damage with your next ranged piercing weapon attack, make another attack against a target that the original target would grant cover to, this attack roll increases its Weak trait by 1.

You can select this ability up to twice per Tier, each time increasing the number of targets it can affect by 1 and increasing the Weak trait of the additional attacks by 1. 

### Covering Fire

Prerequisites: Weapon Skill (Any Ranged, Any Thrown)

Reaction - Once per Round

Fatigue: Physical

Provokes Reactions: Yes

Trigger: An ally provokes an attack of opportunity.

Requires: Ranged/Thrown Weapon.

Make a ranged/thrown attack to distract the attacker, your ally gains a +5 bonus to their response.

### Multidraw

Ability - Cost: 2 - Once per Round

Fatigue: Mental

Provokes Reactions: Yes

As Draw Ammunition, but draw one additional piece of ammunition.

### Multishot

Prerequisites: Weapon Skill (Bow)

Ability - Cost: 1 - Once per Round

Fatigue: Mental

Provokes Reactions: Yes

Requires: Multiple pieces of Ammunition drawn.

As Attack, but make one more ranged attack, these attacks are weak.

You can target the same or multiple creatures within your reach.

You can select this ability up to twice per Tier.

### Improved Multishot

Prerequisites: Weapon Skill (Bow)

Ability - Cost: 1 - Once per Round

Fatigue: Mental

Provokes Reactions: Yes

Requires: Multiple pieces of Ammunition drawn.

One of the attacks made as part of Multishot is not weak.

You can select this ability up to twice per Tier.

### Distracting Shot 

Prerequisites: Weapon Skill (Any Ranged)

Reaction - Once per Round

Fatigue: Physical

Provokes Reactions: Yes

Trigger: An ally makes an attack of opportunity within your movement range.

Requires: Ranged Weapon.

Make a ranged attack to distract the target, your ally gains a +5 bonus to their attack.

### Suppressing Fire 

Prerequisites: Weapon Skill (Any Ranged/Thrown) 

Ability - Cost: 2 - Once per Turn

Fatigue: Mental

Provokes Reactions: No

Select one Ally you can see, any creature moving into a square that would provide it reach to your ally provokes an attack of opportunity from you.

  

### Ricochet 

Prerequisites: Weapon Training (Ranged) 5

Ability - Cost: 1 - Once per Round

Fatigue: Mental

Provokes Reactions: No

Your next ranged weapon attack can be made to rebound from a solid surface.

The total distance travelled must be within the range of the weapon.

### Volley

Ability - Cost: 1 - Once per Turn

Fatigue: Mental

Provokes Reactions: No

Requires: You are outdoors.

Your next ranged weapon attack made this turn is not subject to cover, it also targets a space instead of a creature.

You can select this ability multiple times, for each rank purchased, you can include another weapon attack that you are able to make either targeting the original space, or an adjacent one.

## Magic

In this system magic and similar effects are brought about by willing them to be, or manifesting them. To start with some basic terms before breaking down an example.

N.B: You must first pick up a Signature Skill to be able to use Spell Points.

### Some Terms

#### Spell Points

A creature is capable of spending a number of Spell Points equal to the average of all their Mental Statistic Scores.

##### Investing Spell Points

When an ability requires that you invest spell points, you must have that number of spell points available, they are not spent, however if you ever lack the required number of spell points the effect ends.

#### Complexity

The complexity of a spell or technique is as it sounds, how hard it is to understand or wrap your head around the very concept. When you use a spell / ability with Complexity, this is the number of Spell Points required to use it.

##### Pump

When a spell component is listed with Pump (n), you can spend n Spell Points spent to add an additional effect. Unless stated, you can apply this effect as many times as you have the Spell Points to spend.

#### Will

The will of a creature is used to bring magic into existence.

A creature’s Will bonus is added to the damage of any spells it casts.

The Check to resist a spell effect is equal to 6 multiplied by the spell’s Tier and then added to the creature’s Will.

##### Cast

Ability - Cost: 1 - Repeatable

Fatigue: Mental

Provokes Reactions: Yes

Cast a spell, reduce your Spell Points by the Complexity of the Spell.

Gain mental fatigue equal to your Implement value.

#### Visualisation

Visualisation is used to make a spell easier to cast.

##### Visualisation Total

When you use the Cast ability, reduce the spell points spent by this value.

##### Visualise Concept

Ability - Cost: 1 - Once per Spell ([Concentration](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.qe8v1w5xxrjw), [Implement](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.mapn4k9bg053), [Supplementary](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.46dlk714bqt4), [Visualise](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.yhpfirv3x2ga))

Fatigue: Mental

Provokes Reactions: No

Make a Visualisation Check and add the converted result to your Visualisation total.

#### Mental Domain

The root of all concepts, your spells being no exception, is the astral plane - the plane of thought. When you will a concept into reality you are doing so within your mental domain. Your mental domain is split up into different sectors with sector 0 being your own space.

By default, a creature’s domain only reaches sector 0. It is possible to increase this by increasing ranks in the Esotericism branch. This domain defines how far you are able to cast magic, for each sector boundary that you cross the increase the Spell Point cost by the total number crossed e.g. crossing the first from 0 -> 1 would cost an additional 1, crossing then into the second from 1->2 would cost an additional 2.

#### Concepts

Concepts can be anything, from fire and air to your body or life itself; when creating a spell you will require a concept to act upon.

#### Supplementary

These abilities allow for more powerful spells to be cast by reducing their spell point cost; they can be used at any time, but using Focus will grant you two actions for supplementary abilities for the cost of one.

#### Applicators

These are used to act on concepts e.g. creation applicators include choices such as manifestation which will attempt to bring the concept into existence, or stop applicators which contain choices such as protect which grants a measure of damage reduction against a given concept.

#### Example

Taking the example spell below we can break it down and see how a creature would attempt to cast it.

  

(1) Fire Bolt

(2) Range: 0-1

(3) Complexity: 4

(4) Launch a bolt of fire at a target dealing 2d10 fire damage.

  

(1) The name of the spell / technique.

(2) These are the sectors within which the spell / technique can be used, here it can be used in sectors 0 and 1.

(3)  The complexity of the spell is the total number of spell points required to cast the spell.

(4) Description of what the spell / technique does.

  

So for the above spell, given a Tier 1 medium creature had 4(8) Intelligence, 4(8) Visualisation and 4(8) Will, and they have taken a skill to increase their mental domain to having a sector 1 (this would be 8m, 4m each from Visualisation and Will multiplied by their size of 1m).

  

The above spell would cost 4 spell points, by using the Visualise ability once they could reduce it by 1 (4 => 10 => 1). They would need to use it a total of 3 times to reduce it by 2 (12 => 20 => 2).

  

Given they cast it successfully they would deal 2d10+Will fire damage to their target given they do not manage to dodge or block it.

#### Breakdown of the Above Spell

The above spell was shown without this for simplicity, but it is actually made up of several component parts which would be:

  

(1) Ward Caster - (2) Manifest - (3) Fire 1 - (4) Project (5)(Sectors 0-1)

  

(1) Ward Caster is a common component, used to protect the individual casting the spell. Without this any manifested concept would immediately interact with the first thing they touch i.e. the caster. It is found in the Stop tree.

Complexity 1

  

(2) Manifest is another basic component used to bring a concept into existence, here it is linked with Fire 1. It is found in the Creation tree.

Complexity 1

  

(3) Fire 1 is a Tier 1 potency flame, it deals 1d10 fire damage to the first thing it touches. It is in the Fire tree.

Complexity 1

  

(4) Project is a component that causes a linked concept to move, here linked to Fire 1 it causes the Fire to move towards a target. It is in the Move tree.

Complexity 1

  

(5) Sectors 1 is the range of the spell, here it can be cast from sector 0 out to sector 1. Increasing the range at which you can cast spells can be done by spending points in the Esotericism tree.

Cost 5

### General Magic Skills

#### Activate Implement

Ability - Cost: 1 - Push

Fatigue: Mental

Provokes Reactions: No

Spend the spell points required to activate an implement.

#### Understanding

Passive

This ability can be taken up to 5 times per Tier for a selected Skill.

Gain the number of ranks in this skill as a bonus when determining the complexity of a spell.

### Signature Skills

Signature skills are similar to Styles, however they are always in effect. 

You can only possess one Signature Skill.

Once you possess a Signature skill, you can make use of Spell Points.

#### Aether Wielder (Signature)

You cast spells by wielding the aether from which all things manifest. Gain one rank in Prime Concept.

##### Prime Concept

Select one Concept when you gain this.

#### Balance (Signature)

You cast spells of one concept by internalising its antithesis, there must be balance.

##### Balance in All Things

Prerequisites: [Internal Balance](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.uabfpturcuop)

Reaction - Cost: 1 Equilibrium- Once per Round

Fatigue: Mental

Provokes Reactions: No

Trigger: A dice roll is made by a creature you can perceive as part of an action that you are aware of.

Cause the result of one D10s per Equilibrium spent to be 5.

##### Balanced Manifestation

Ability - Cost: 3 - Once per Round

Fatigue: Mental

Provokes Reactions: No

This ability acts as Manifest.

When you choose this Ability, select one Concept (the primary), also select one Concept from its Antitheses.

You can manifest a spell containing only the primary concept with this ability by spending 1 spell point.

You suffer the effects of the Antithesis Concept of the same Tier.

##### Delayed Consequences

Prerequisites: [Balanced Manifestation](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.gu86hsa5hgpa)

Reaction - Cost: 1 Spell Point - Once per Round

Fatigue: Mental

Provokes Reactions: No

Trigger: You would suffer the Antithesis effects of Balanced Manifestation.

You delay the effect of the Antithesis for 1 Round.

You suffer the effect at the start of your turn.

##### Internal Balance

Prerequisites: [Balanced Manifestation](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.gu86hsa5hgpa), [Delayed Consequences](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.ii4inwihhgjn)

Gain Resource: Equilibrium

Ability - Cost: 1 - Once per Round

Fatigue: Mental

Provokes Reactions: No

This ability acts as Manifest

Make an opposed Will Check against yourself, the first roll is for your Primary (for you), the second is its Antithesis.

Success: Gain 1 Equilibrium

Failure: Suffer the effects of the Antithesis

##### Reflect

Prerequisites: [Internal Balance](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.uabfpturcuop)

Reaction - Cost: 1 Equilibrium - Once per Round

Fatigue: Mental

Provokes Reactions: No

Trigger: You are subject to an effect that you are aware of and perceive the source.

Cause the effect to also affect its source, you must spend 1 Equilibrium per Tier of the Concept or Creature (in the case of a non magical attack).

The target must be within your mental domain.

##### Vent

Prerequisites: [Balanced Manifestation](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.gu86hsa5hgpa), [Delayed Consequences](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.ii4inwihhgjn)

Ability - Cost: 3 - Once per Round

Fatigue: Mental

Provokes Reactions: Yes

You will not suffer the effects of any currently delayed Antithesis.

#### Channeler (Signature)

A channeler is trained in the arts of drawing free astral energies through their own body, lessening the mental load of their magics. 

##### Channel

Cost: 1 - Once per Day (Complete, Concentration, Implement, Supplementary) 

Fatigue: Mental 

Provokes Reactions: Yes

Signature 

As Visualise, however, you do not add your Concentrating value to your spell fatigue. 

This does not allow you to ignore spell fatigue that would put you above your daily limit.

##### Overchannel

Cost 1 - Once per Day (Concentration, Implement, Supplementary)

Requires: Channel

Fatigue: Mental

Provokes Reactions: Yes

As part of using Channel you can suffer a number of wounds and pain up to your Constitution Bonus to increase your maximum Spell Fatigue for that spell, this damage and pain cannot be reduced in any way.

#### Conduit for Magic (Signature)

Resource: Flow

##### Flow

For each point of Flow that you possess, you gain a bonus to Will Checks made as part of [Conduit](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.90ycssqk0225) equal to half of your Visualisation Bonus; you suffer the same as a penalty to all other checks.

##### Conduit

Ability - Cost: 1 - Once per Round

Fatigue: Mental

Provokes Reactions: No

Select one Concept that can be used with this ability.

This ability acts as Manifest.

Whenever you manifest a spell using this ability, gain 1 Flow for each spell point spent.

##### Divert Flow

Ability - Cost: 3 - Once per Round

Fatigue: Mental

Provokes Reactions: No

Manifest the concept of your Flow depending on the number of Flow points you have.

Your Flow is reduced to 0.

  

Flow

Effect

1-2

Manifest the concept within your first mental domain. The damage roll is minimised.

3-4

Manifest the concept in your hand as though it was affected by Ward Caster+Hold Spell. If unused within 1 minute it takes effect as though you had 5 flow.

5-6

Manifest the concept in your space.

#### Eldritch Apprentice - WIP

Gain Eldritch Knowledge identity

Test identity on spell cssting

Can replicate other concepts and applicators through unknown means

#### Emotional Magics

#### Gamesetter - WIP

E.g. Me First

When attacked hit them with the same on a Will check?

Otherwise impose other games on them

#### Implement Caster

You are capable of making better use of implements than others.

##### Increase Durability

Passive

Increase the number of times an implement can be used before breaking by 1.

#### Mental Duelist

##### Mental Duels

A literal duel of the minds, any damage dealt is usually converted into Exhaustion with the winner being the first to force their opponent to suffer from Exhaustion 10. Exhaustion does not take effect until after the duel has ended.

  

In a mental duel participants can make use of the following abilities without training:

###### Mental Attack

Ability - Cost: 1 - Push

Fatigue: Mental

Provokes Reactions: No

1d10 Mental Damage. This can be treated as a concept or attached to other spells within mental duels.

The Damage Statistic is the lowest out of your Intelligence, Will and Visualisation.

Damage suffered is reduced by 6, multiplied by your Tier, added to your Will Modifier.

###### Comprehend

Reaction

Fatigue: Mental

Provokes Reactions: No

Trigger: You are the target of a Mental Attack

Make a Wits or Intelligence Check, whichever is lower, against the enemy’s Intelligence.

Success: Determine the Concept components of the attack.

###### Evade

Reaction

Fatigue: Mental

Provoke Reactions: No

Trigger: You are the target of a Mental Attack

Make a contested Wits Check.

Success: You avoid the Attack

###### Brace

Reaction

Fatigue: Mental

Provokes Reactions: No

Trigger: You are the target of a Mental Attack

Make a mental attack of your own, reduce the mental damage suffered by the result.

#### Patron

You have gained the aid of a Patron, who may lend you their aid.

You gain the Belief and Favour resources, and the Worship ability.

##### Belief (Resource)

You can call upon your Patron to aid you, belief is the resource used for this. After each full rest your Belief is reset to 0.

##### Favour(Resource)

By fulfilling the tenets of your Patron, you gain 1 Favour; you can have up to 2 Favour per Tier.

Favour can be used in place of all Belief required to use Pray; the success chance is not reduced by Aid.

##### Grace (Delay) 

Passive

Reduce the cost of any Divine Ability by your current Favour, up to a maximum of 1.

You can select this ability multiple times, increase the maximum reduction by 1 each time.

##### Pray

Ability - Cost: 1 - Push

Fatigue: Mental

Provokes Reactions: No

Use a divine ability made available by your Patron. 

##### Worship

Passive

During a rest, or at the start of the day, you can convert any number of Spell Points to additional Belief. 

#### Improved Worship

Passive

When making use of Worship, regardless of Spell Points converted, if you have no Favour, gain 1 Favour.

You cannot gain the benefit of this again until you have gained Favour in another way.

##### Divine Abilities

These must be selected using Inspiration Points.

###### Aid

Cost: 4 Belief

The next Check you make is Strong.

###### Divine Armament

Cost: 4 Belief

The damage of your next attack or spell made this round is treated as Divine.

###### Divine Raiment

Cost: 4 Belief

Your damage reduction is treated as Divine until the end of combat.

###### Miracle

Cost: 1 Favour

Call upon your patron, making a request, how and whether this request is resolved is at the discretion of the Patron.

###### Smite

Cost: 4 Belief

A target that you can perceive is struck by Holy or Unholy damage, depending on your patron. The additional damage of the smite is 1d10 and is modified by your Will.

#### Shaman / Medium

Shaman - soul collector / spirit collector, manifest instantaneous actions from them / give them power so they can act.

Where do souls exist?

#### Reservoir Soul

##### Draw Power

Prerequisites: [Restore Reserves](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.d3yd3ocwb6lq)

Passive

Whenever you use Restore reserves in an area aligned  with a concept you know, gain a further quarter of your Internal Reserves. These Internal Reserves can only be used for the aligned concept. 

##### Internal Reserves

Passive

You gain an internal reserve of Astral Potential, when you select this ability you gain an additional resource that can be used to cast spells in addition to Spell Points.

This resource can be increased by spending XP.

This resource is taken into account when determining your Tier.

##### Restore Reserves

Prerequisites: [Internal Reserves](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.906w3i2lj01p)

Gain Resource: Restore Reserves

Ability - Cost: 1 Restore Reserves

During a rest, regain half of your Internal Reserves rounded down.

You can select it once per Tier gaining another charge.

You can spend as many charges in a day as you desire, however you only regain one per long rest.

#### Domain Caster (Signature)

##### Create Ring

Ability - Cost: 1 - Once per Round

Fatigue: Mental

Provokes Reactions: No

Duration: 1 minute

Create an astral ring surrounding your space.

You can have a number of rings active equal to your tier.

You can use this ability a number of times equal to your highest mental bonus.

The limit of any ring is your mental domain.

You can expend more uses to extend the duration.

##### Resize Ring

Ability - Cost: 1 - Push

Fatigue: Mental

Provokes Reactions: No

Increase or decrease the size of the ring by up to your size, it cannot be reduced to a size smaller than your space however.

The damage of any infusions is reduced by 1d10 for each region of your mental domain it passes through.

The effects infused in the ring only affect creatures in the following circumstances:

The ring enters their space.

The creature enters a space covered by the ring.

  

##### Infuse Ring

Requires: Infusion 1

Passive

Whenever you cast an infusion spell that takes effect on yourself, you can instead redirect the effect to one of your active rings.

##### Reaction: Infuse

Reaction - Once per Round

Fatigue: Mental

Provokes Reactions: No

Trigger: An object passes through one of your active rings.

Infuse the current active effect of the ring onto the object, any damaging/healing effects deal 1 damage or heal 1 wound.

##### Reaction: Transfer

Reaction - Once per Round

Fatigue: Mental

Provokes Reactions: No

Trigger: An object passes through one of your active rings.

Transfer the current active effect of the ring onto the object, the object carries the full effect of the spell infused into the ring.

##### Create Focus

Ability - Cost: 1 - Once per Round

Fatigue: Mental

Provokes Reactions: No

Create a focus within a space within your mental domain.

You can use this ability a number of times equal to your highest mental bonus.

##### Transfer Ring

Ability - Cost: 1 - Once per Round

Fatigue: Mental

Provokes Reactions: No

Transfer one of your active rings to another creature or one of your foci.

##### Invert Ring

Prerequisites: Resize Ring

You can use the ability “Resize Ring” to reduce the size of the ring through a point, any creatures in the space will be affected by it.

##### Swap Ring

Prerequisites: Must be able to produce 2 or more rings

Ability - Cost: 1 - Once per Round

Fatigue: Mental

Provokes Reactions: No

Swap the anchoring points of two rings.

##### Reaction: Infuse Ring

Reaction - Once per Round

Fatigue: Mental

Provokes Reactions: No

Infuse a ring that comes into contact with a spell you have passed through it.

##### Ring of Focus

Prerequisites: [Circle of Focus](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.r3p3uo6vjlzf) (Creation)

Ability - Cost: 1 - Once per Day

Fatigue Mental

Provokes Reactions: No

Requires a ring with size equal to your size, once infused with this ability it cannot be resized. You can remove this infusion for the same cost as applying it. 

Infuse your ring with the properties of the Circle of Focus, this is the only infusion the ring can possess.

##### Ring of Peace

Prerequisites: [Circle of Peace](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.la58j270kuif) (Creation)

Ability - Cost: 1 - Once per Day

Fatigue Mental

Provokes Reactions: No

Infuse your ring with the properties of the Circle of Peace, this is the only infusion the ring can possess.

##### Ring of Power

Prerequisites: [Circle of Power](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.2al4pt4wr7rk) (Creation)

Ability - Cost: 1 - Once per Day

Fatigue Mental

Provokes Reactions: No

Requires a ring with size equal to your size, once infused with this ability it cannot be resized. You can remove this infusion for the same cost as applying it. 

Infuse your ring with the properties of the Circle of Power, this is the only infusion the ring can possess.

##### Ring of Protection

Prerequisites: [Circle of Protection](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.ubwdghfi6evs) (Creation)

Ability - Cost: 1 - Once per Day

Fatigue Mental

Provokes Reactions: No

Infuse your ring with the properties of the Circle of Protection, this is the only infusion the ring can possess.

##### Selective Ring

Reaction - Once per Round

Fatigue: Mental

Provokes Reactions: No

Trigger: Your ring passes through a target.

You can choose to not affect a number of targets equal to twice your Tier.

#### Ritualism

##### Rituals

Rituals are formed from several component parts and will likely require a multiple step process. 

To attempt a ritual, one must simply possess the required materials and know the steps and order to take them in.

Alternatively, by taking the Rituals skill and investing in the underlying abilities, bespoke rituals can be created.

Complete rituals are given a score, this is the total of:

Required Steps / Components.

The highest Tier of any materials used.

  

The score cannot be reduced below the highest Tier of material used. 

  

The score increases the time required to enact the ritual as below:

  

Ritual Score

Time Required

1

1 Minute

2

5 Minutes

3

10 Minutes

4

30 Minutes

5

1 Hour

6

2 Hours

7

4 Hours

8

8 Hours

9

1 Day

10

2 Days

11

3 Days

12

1 Week

13

2 Weeks

14

1 Month

15

2 Months

16

4 Months

17

8 Months

18

1 Year

19

5 Years

20

10 Years

  

###### Ritual Materials

The materials used will denote the potency of the ritual, e.g. Tier 2 Fire materials as part of a ritual of protection against fire would provide protection up to Tier 2.

  

The cost of any materials is shown below:

  

Tier of Material

Cost

1

10gp

2

20gp

3

50gp

4

100gp

5

200gp

6

-

7

-

8

-

9

-

10

-

  
  

The materials used as part of a ritual component are consumed in the process, whether directly or becoming otherwise inert and valueless. 

###### Stability 

Each Ritual Component will have a Stability value, once the ritual is complete, roll 1D100 for each component, if you roll below the component's stability, it was a success and nothing unexpected happened. 

If you roll above the component's stability, a rebound occurs, roll on the rebound table starting from the first component that rebounded to the last. 

So long as one component succeeds, the ritual effect takes place, otherwise if all components rebound, the ritual was a failure. 

A roll of 100 always triggers a rebound. 

###### Conditions

Conditions of the ritual may increase or decrease the stability of the ritual. 

###### Rebounds 

Unexpected events that may occur as part of the ritual, potentially making further steps more risky, or otherwise being outright harmful. 

  

If more than one rebound occurs, roll on the greater rebound table to determine further effects. 

###### Binding 

Ritual Score: Tier of Spirit multiplied by 2

Stability: 50

Enter into a pact by speaking the words of power, binding a spirit into an appropriate vessel for the type and tier of the spirit; the main ritualist must have created the vessel. 

A vessel must be supplied to contain a spirit and later called upon.

Example vessels below:

  

###### Vessels

  

Concept

Vessel

Fire

Worked Metals (Blacksmithing/Jewelcrafting)

Earth

Gemstones and Stone (Jewelcrafting/Stonemason)

Water

Water (Jewelcrafting)

Air

Cloth (Tailor)

Any (Internal Binding)

Representative Tattoo

  

  

A spirit bound by pact to a vessel can be called upon to aid the binder, though depending on their disposition and the danger/difficulty of the task they may refuse.

  

When using Internal Binding the spirit is bound to you, add an identity for the creature to your identities at Hold 20, reduce your main Identity as appropriate, this is treated as [Hybrid Soul](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.uoh0pgljeq6m)

  

Condition 

Stability

Spirit is hostile

-   20
    

Spirit is not contained 

-   20
    

Words of power spoken in a language, not of the spirit. 

-   20
    

Vessel Quality

-   Quality x 10
    

Location Favoured by Spirit

-   10
    

Offering Given 

-   10
    

  
  

Rebound roll

Rebound

1

Parting Strike

The spirit demanifests after making an attack. As also with Greatly displeased. 

2

Possession

The spirit attempts to possess any among those present, make a contested will check for each, the spirit gains Hold equal to 100 - Stability. As also with Greatly Displeased. 

3-4

Greatly Displeased

The attempt has displeased the Spirit greatly, you may not attempt to bind spirits in this location again. 

5-9

Displeased

The attempted has displeased the Spirit, you may try again in a week. The Spirit will be hostile to you. 

10

Indifference

The Spirit ignores you returning to what it was doing, you may attempt again in 24 hours. 

  

###### Blessing

Ritual Score: 1

Stability: 60

By invoking the blessing of a Patron you may request greater stability in the rest of your ritual.

Completion: +10 Stability to all other Ritual Components. 

Condition

Stability

Relationship of any present with Patron

-   Favour x 5
    

Location favourable

-   10
    

Offering

-   10
    

  

Rebound Roll

Rebound

1

Smote by Patron

Receive appropriate damage or condition from the Patron

2

Greater Lost favour 

Lose 2 Favour with your Patron. 

3-5

Lost favour 

Lose 1 Favour with your Patron. 

6-9

Ignored

Your Patron will not answer your requests for 24 hours. 

10

Lucky Nothing

Nothing happens

  

###### Circle of Enclosure

Ritual Score: 1

Stability 80

An uninterrupted circle drawn to enclose the rest of a ritual.

Any Rebounds within the circle are contained. 

The circle is your size in radius, increase the Ritual Score by 1 for each size increase e.g. +1 for a 2m radius circle.

The material used must at least be of the highest Tier in the ritual to be effective.

  

Condition

Stability

Indoors

-   10
    

Dry

-   10
    

Rebound roll

Rebound 

1-2

Instability

Any further ritual components have their stability decreased by 20

3-4

Inverted 

Any Rebounds of further ritual components only affect outside of the circle. 

5-10

Uncontained

Any Rebounds of further ritual components affect the outside of the circle. 

  

###### Circle of Separation

Ritual Score: 1

An uninterrupted circle drawn to enclose one or more entities.

This separates them from any other combinations that may take place within the ritual.

###### Inner Circle of Protection

Ritual Score: Tier of the Material Used

An uninterrupted circle drawn to separate one or more entities.

The circle is your size in diameter, increase the Ritual Score by 1 for each size increase e.g. +2 for a 4m circle.

The material used must at least be of the highest Tier in the ritual to be effective.

Prevents a specified type of concept from leaving. 

###### Outer Circle of Protection

Ritual Score: Tier of the Material Used

An uninterrupted circle drawn to separate one or more entities.

The circle is your size in diameter, increase the Ritual Score by 1 for each size increase e.g. +2 for a 4m circle.

The material used must at least be of the highest Tier in the ritual to be effective.

Prevents a specified type of concept from entering. 

###### Transfer

Ritual Score: 1

A symbol of transfer, e.g. pouring water from one vessel to another.

Denotes the transference between two circles.

###### Roads of Transfer

Ritual Score: 1

Used to denote a route for transfer between, into and out of circles, or between locations. 

###### Pillars of Time

Candles or other consumed items that will be lost in time.

Reduce the Ritual’s Score by the material’s Tier; it cannot be reduced below the maximum Tier of material used.

###### Contract of Price

Ritual Score: 1

Requires symbolism of Trade, by intersecting several Circles of Separation and placing e.g. the scales between them, it is possible to pay between them, whether this be a material loss or otherwise e.g. soul.

###### Contract of Loss

Ritual Score: 1

Requires the item to be lost to be destroyed within a box.

If the item is ever restored, the ritual effect ends.

###### Contract of Time

Ritual Score: 1

Requires an item of significance to the time period to be bestowed, e.g. a candle will burn for 1 hour, this would grant an effect of 1 hour.

By leaving water under sun and moonlight for a full 24 hours, one could harness this as the duration.

The combination of Contract of Price and the Contract of Time with the life of an individual presents a tempting chance at long lasting power.

###### Runes

It is possible to use any runes you may possess in the place of a symbolic item marked with the same rune. 

###### Calling

Ritual Score: Tier of the Entity you are calling multiplied by 5.

Requires an item or sacrifice that the being would enjoy.

This ritual calls out to an entity of your choosing, whether they choose to heed the call is another matter, and it is entirely possible that another entity may take its place.

###### Greater Rebounds

  

Rebound Roll

Interested Entity 

Rebound 

1-33

Thellon, Firstborn of Rituals

Your body is consumed by the ritual

2

  

Your Head

3

  

Your Eyes

4

  

One of your Eyes

5

  

Your ears 

6

  

Your mouth, closes over. 

7

  

Your Nose

8

  

Your Teeth

9

  

Your sense of smell

10

  

Your sight 

11

  

Your sense of taste

12

  

Your hearing

13

  

Your fingernails

14

  

Some of your fingers

15

  

Some of your hands and feet

16

  

Your hands

17

  

Your feet

18

  

Your hands and feet

19

  

Your arms

20

  

Your legs 

21

  

Some of your limbs

22

  

Your blood

23

  

Some of your blood

24

  

Your adrenaline is consumed by the ritual, you are wracked by 1d10 further pain. 

25

  

Some of your Identity replaced with nothing, roll 1D100 for its hold, add Void as an identity, whenever it is in control you have the confused condition. 

26

  

Some of your identity, replaced by another , roll 1D100 for an appropriate identity's hold. 

27-33

  

Reroll, taking results 1-33 only, otherwise continue rerolling. 

34-66

Larsuus, the Scholar

Discipline

67-99

The Coven 

Chaos

100

All

Roll 3 more times

  

##### Ritualist

You are skilled in the use of Rituals, you are more likely to succeed them, and can likely enact them with greater haste.

###### Hasten Ritual

Decrease the time by 1 ritual score / 2 for a documented one

###### Imbue Will

Add your will to the ritual roll

###### Document Ritual

Document the steps of a ritual

##### Runes

Runes are capable of holding magics, though the exact nature is difficult to ascertain immediately or by deciphering, it is only possible to determine the intent of a rune through reading its Aura.

###### Inscribe Rune

(Imbue Implement, Infusion 1, Contract 1, Obscure 1)

Cost: 1 hour and 100gp for each point of Complexity

Requires an appropriate implement with which to etch the rune in the target surface.

Infuse an effect into an object, the runic representation is visible on the object.

###### Runic Binding

Prerequisites: Esotericism 1

Complexity 2

Inscribe a Rune onto a surface or object. By repeating this spell and inscribing the same rune on another surface or object you can treat each inscribed object as the other, and casting spells targeting one will affect the other, increase the complexity of the spells by 3 for each connected Rune. 

#### Scholar

##### Lucid Training

Passive

Requires: A location in which to study or a creature to learn from.

As part of downtime, select one concept or applicator you meet the prerequisites for, you gain that skill.

#### Spirit Magic

By making a contract with local spirits, you may gain some of their power.

##### First Vessel

Select one [vessel](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.yksrsfb0m69s), you gain the vessel, it can only be used for one Spirit.

##### Language of the Spirits

Passive

Select one concept you have access to, and you can speak the language of Spirits of this Concept.

You can select this skill multiple times.

##### Spirit Detection

Passive

You can sense the presence of spirits and the wherein they reside.

##### Pact Training

Passive

You can form one more pact with Spirits.

##### Pact Binder

Passive

When performing the Ritual of Binding to bind a Tier 1 Spirit , increase the ritual component stability by 30. 

##### Able Appeaser

Passive

Increases the stability of all bound Spirits by 5 to a maximum of 95.

##### Call Lesser Spirits (Supplementary)

Prerequisites: Language of the Spirits

Ability - Cost: 1 - Once per Day

Fatigue: Mental

Provokes Reactions: Yes

Call upon lesser spirits to aid in your spells, roll 1D10 + 1D10 for each Tier you possess, add the converted result to your Visualisation Total.

#### Unstable Magics

While the mental load of your spells is lessened, the physical toll could be your end.

Resource: Instability (Max 5)

##### Instability

When you have Instability, you are Vulnerable to all damage.

Increase the critical range of your spell damage by your instability. 

##### Brace (Supplementary)

Ability - Cost: 1 - Once per Round

Fatigue: Physical

Provokes Reactions: No

You do not suffer Pain as part of your next Unstable Manifestation.

##### Destabilise 

Ability - Cost: 1 - Once per Round

Fatigue: Physical

Provokes Reactions: No

When you touch a creature this turn, you can choose to transfer instability to it. They suffer vulnerability to all damage. You suffer pain equal to the Instability transfered. 

##### Internalise Instability

Prerequisites: [Unstable Manifestation](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.ow92b2hwhlk2)

Reaction - Once per Round

Fatigue: Physical

Provokes Reactions: No

Trigger: You used Unstable Manifestation

Do not suffer any healing wounds or pain, do not reduce your current blood by your Healing Wounds. 

Gain Instability equal to the damage rounded to the next 10 and then divided by 10.

##### Stabilise

Ability - Cost: 1- Once per Round

Fatigue: Physical

Provokes Reactions: No

Suffer your current Instability as Pain. 

Reduce your Instability to 0.

##### Unstable Casting 

Ability - Cost: 1 - Push

Fatigue: Both 

Provokes Reactions: Yes

This ability acts as Cast. 

Suffer healing Wounds equal to the converted Spell Point cost instead of spending Spell Points.

Reduce your blood by your Healing Wounds.

#### Willful Instability

Prerequisites: Unstable Casting

Ability - Cost: 1 - Push

Fatigue: Both

Provokes Reactions: Yes

This ability acs as Unstable Casting. 

Make a Will Check, reduce the healing wounds suffered by the converted result. 

##### Unstable Visualisation (Implement, Supplementary)

Ability - Cost: 1 - Push

Fatigue: Both

Provokes Reactions: No

As Visualise, but gain 1 instability make the check Strong.

### Supplementary

All of the following possess the [Supplementary](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.46dlk714bqt4) trait.

#### Incantations

Incantations are spoken words that must be heard to take effect; they lessen the cost of manifesting magic.

##### Incantation (Delay, Limit, [Visualise](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.yhpfirv3x2ga))

You may select this Ability multiple times, up to 10 times for a given Skill and once per Tier e.g. Incantation of Fire 1. 

Each selection of this ability grants the 1st verse of the Incantation, for each incantation there are a number of verses equal to its number e.g. 8th Incantation has 8 verses.

The separate Incantation abilities 1st Incantation through to 10th Incantation as well as each of their verses are used as separate abilities e.g. using Incantation of Fire 2 and speaking both verses would cost 2 actions.

The level of Incantation is connected to the Tier of spells that it will affect e.g. Incantation of Fire 3 only affects Fire spells of Tier 3.

  

Cost: 1 - Once per Verse per Spell

Fatigue: Mental

Provokes Reactions: Yes

Speak the words of power for your magic, add 1 to your Visualisation Total.

##### Additional Verses (Limit, [Visualise](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.yhpfirv3x2ga))

Prerequisites: Incantation

You may select this Ability Multiple times, each time adding the Verse’s number to the Incantations Spell Point Cost reduction e.g. you could select Additional Verses twice for 3rd Incantation of Fire, speaking the 1st and 2nd Verse of the 3rd Incantation would grant you a reduction of 3 (1+2), speaking all three would grant you 6 (1+2+3).

#### Somatics

##### Gestures ([Visualise](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.yhpfirv3x2ga))

Ability - Cost: 1 - Once per Spell

Fatigue: Physical

Provokes Reactions: Yes

Requires: an empty hand.

Select one concept when you select this ability. Gestures can only be used for spells containing that concept.

##### Dual Gestures ([Visualise](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.yhpfirv3x2ga))

Prerequisites: Gestures

Ability - Cost: 1 - Once per Spell

Fatigue: Physical

Provokes Reactions: Yes

Requires: two empty hands.

##### Dance ([Visualise](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.yhpfirv3x2ga))

Prerequisites: Gestures

Ability - Cost: 1 - Once per Spell

Fatigue: Physical

Provokes Reactions: Yes

Select one concept when you select this ability. Dance can only be used for spells containing that concept.

#### Casting Implements

Prerequisites: Gestures

Passive

Designate one item, when wielding it it is treated as an empty hand for Gestures and Dual Gestures.

#### Martial Casting Implements

Prerequisites: Casting Implements

Passive

Select one of your Casting Implements choices, while wielding this item, any Visualisation check made as part of Gestures gains a bonus equal to your ranks in Weapon Training and Dual Gestures gains a bonus equal to your ranks in Weapon Training for each hand occupied.

#### Symbolic Assistance ([Visualise](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.yhpfirv3x2ga))

Prerequisites: Read Magic

Ability - Cost: 1 - Once per Spell

Fatigue: Mental

Provokes Reactions: No

This ability must be used first among any others with the Supplementary trait.

The symbol must remain visible throughout any abilities with the [Supplementary](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.46dlk714bqt4) trait.

#### Channel Essence ([Delay](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.9kmijrs15kks), [Visualise](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.yhpfirv3x2ga))

Prerequisites: One rank in Esotericism

Ability - Cost: 1 - Once per Spell

Fatigue: Mental

Provokes Reactions: Yes

Draw the essence from a nearby object to empower your spellcasting.

Select one concept tied to an object you are holding or touching, or an area you are stood within, this must be a concept used in the next spell you are going to cast.

You cannot use this ability more than once per object.

#### Domain Essence

Prerequisites: Channel Essence, Mental Domain Increase

Passive

You are able to use Channel Essence using any Concept within your mental domain’s first area.

#### Enduring Essence ([Limit](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.34p0fdhrb9xq))

Prerequisites: Channel Essence  
Passive  
You are able to use the same instance of a concept 1 more time, when drawing from an object.

You can select this ability multiple times, up to twice per Tier.

#### Physical Offload (Delay) 

Ability - Cost: 1 - Once per Day

Fatigue: Mental

Provokes Reactions:  No

Reduce the spell point cost of the spell you are casting by half. Suffer the original spell point cost multiplied by 5 in Active Wounds and converted value in pain. 

The spell complexity cannot exceed your Spell Point total.

#### Improved Physical Offload (Delay) 

Prerequisites: Physical Offload 

Ability - Cost: 1 - Once per Day

Fatigue: Mental

Provokes Reactions:  No

Reduce the spell point cost of the spell you are casting to 1. Suffer the original spell point cost multiplied by 5 in Active Wounds and converted value in pain. 

The spell complexity cannot exceed your Spell Point total.

#### Mental Offload (Delay) 

Prerequisites: Improved Physical Offload, Write Magic

Ability - Cost: 1 - Once per Month

Fatigue: Mental

Provokes Reactions: Yes

The symbol representing the spell you are casting is visibly manifested.

Reduce the Spell Point Cost caused by this spell to 1 when it is manifested.

The frequency of this ability cannot be increased to more than Once per Week.

You must be able to cast the spell.

The spell complexity cannot exceed your Spell Point total.

Gain the Exhausted Condition.

#### Improved Mental Offload

Prerequisites: Mental Offload

Passive

Mental Offload no longer causes Exhausted.

### Applicators

#### Contract

The skill of forming contracts, whether it be to increase the duration of a manifestation or just hold it until it is used.

##### Terms

###### Contract: 

Expected short duration, payment for services rendered; there is no limit to the number of Contracts a creature can make.

###### Pact: 

Long term, likely a binding between two or more entities; a creature can normally only enter into one Pact at a time.

###### Covenant:

A permanent binding between parties extending past the individual e.g. throughout a bloodline or for anyone living within a given area; a creature can normally only have one Covenant at a time.

##### Contract Power

Where a contract provides Contract Power, you can use that for the following effects:

###### Duration

The contract allows an effect to last for the listed duration, or until the contract is broken.

  

Contract Power

Duration

1

1 Round

2

1 Minute

3

10 Minutes

4

1 Hour

5

8 Hours

6

24 Hours

##### Tier 1

###### Follow

Complexity 1

The spell will follow the caster at its relative position as they move.

It can still be moved independently.

###### Hold Spell 1

Complexity 1

You can hold the effect of the linked spell of up to tier 1 to use later. The Cast ability gains the Concentration trait.

###### Transfer Contract

Complexity: 2

Transfer the holder or target of one contract to another holder or target. 

###### Contract Ally (Affix)

Complexity: 2  
Affixed Concept will treat the caster and their allies as allies.

###### Contract of Investment 1 (Delay)

Complexity: 1 (Invest)

This contract provides Contract Power 1.

Pump: 1 (Invest) Double the duration.

###### Contract of Investment 2 (Delay)

Prerequisites: Contract of Investment (1 Round)

Complexity: 1 (Invest)

This contract provides Contract Power 2.

Pump: 1 (Invest) Double the duration.

###### Contract of Investment 3 (Delay)

Prerequisites: Contract of Investment (1 Minute)

Complexity: 1 (Invest)

This contract provides Contract Power 3.

Pump: 1 (Invest) Double the duration.

###### Contract of Investment 4 (Delay)

Prerequisites: Contract of Investment (10 Minutes)

Complexity: 1 (Invest)

This contract provides Contract Power 4.

Pump: 1 (Invest) Double the duration.

###### Contract of Weakness

Complexity: 1

Choose one Statistic, any checks made that Statistic are Weak and any values calculated using this Statistic are halved for the next 24 hours. 

This contract provides Contract Power 6.

###### Contract of Blood

Prerequisites: Blood 1

Complexity: 1

Reduce your maximum blood by 12.

If your maximum blood is restored to heal this, the contract is broken.

This contract provides Contract Power 6.

###### Contract of Vulnerability

Complexity: 1

You are vulnerable to all damage, any damage checks made against you are strong for the next 24 hours. 

This contract provides Contract Power 6.

###### Contract of Transfer

Complexity: 2

Prerequisites: Ward Infusion

Transfer the affixed concept to a creature in contact. 

###### Contract on… 

Complexity: 2

Specify linked applicators and concepts, the contract will trigger in their event, e.g.

Contract on Death, would be triggered upon the target's death. 

Contract on Contact, would be triggered when the affixed spell hits a target. 

Contract on Fire 1 would be triggered when hit by Fire 1.

Contract on Hear-Unknown_Language would trigger when an unknown language is heard. 

###### … Contact

Prerequisites: [Contract on…](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.ts9gjuo3ij65) 

Complexity: 1

Forms a contract when combined with 'Contract on', triggered when the affixed spell makes contact. 

###### … Death

Prerequisites: [Contract on…](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.ts9gjuo3ij65) 

Complexity: 1

Forms a contract when combined with 'Contract on', triggered when the affected creature dies. 

###### … Location

Prerequisites: [Contract on…](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.ts9gjuo3ij65) 

Complexity: 1

Forms a contract when combined with 'Contract on', triggered when the affixed spell reaches a specified location. 

###### Limit (Harmless)

Complexity: 0

Limitation: The spell cannot deal damage.

Complexity Modifier: 1/4 

#### Creation

Antithesis: Destruction

This is the skill of bringing a concept into existence.

##### Tier 1

###### Manifest

Complexity: 1

Manifest a concept of up to Tier 1 at a range of 0m, if this is within the first sector of your mental domain you are treated as being in contact with it.

###### Area (Form)

Prerequisites: Manifest

Complexity: 1

The effect takes the form of an area with dimensions equal to your size; It is not blocked by cover.

Pump (2): Increase each of the dimensions by 1.

###### Arm (Form)

Prerequisites: Manifest

Complexity: 1

Grants a Dextrous Limb to the concept with reach equal to its size.

Pump 1

Grant another arm with a reach equal to the concept’s size.

###### Corner (Form)

Prerequisites: Line (Form)

Complexity 1

Add a corner to a manifested line.

###### Aura (Form)

Prerequisites: Manifest

Complexity: 1

The effect takes place originating from a point and emanating outward with a radius equal to your size; it is blocked by cover.

Pump(1): Double the radius of the Aura. 

###### Line (Form)

Prerequisites: Manifest

Complexity 1

The effect takes the form of a line with length equal to your size, it affects all creatures along its length.

The line is your size in height.

Pump (1): Double the length of the line.

###### Weapon (Form)

Prerequisites: Manifest

Complexity 2

The effect takes the form of a one handed short light weapon.

Any damage dealt by the weapon is purely from the concept.

It cannot be used to parry other weapons aside from those made of the same concept.

You can increase the cost to add further form changes:

  

Additional Spell Point Cost

Effect

1

Increase the Strength required by 1.

You can apply this up to 8 times.

2

Increase the reach of the weapon by 1m.

3

The weapon gains the Focused trait.

2

The weapon becomes Slashing.

2

The weapon gains Piercing damage.

###### Grant Physicality 

Prerequisites: Manifest

Complexity: 1

Grant physical form to a concept, it can be handled as an inert object.

Any damage dealt by the concept is reduced by appropriate physical damage reduction, though carries the damage, wound and critical effects as its concept.

###### Circle of Focus (Form)

Prerequisites: Write Magic (Symbolism), Ring (Form)

Complexity 1

Any creature standing within the circle gains one action that can be used for abilities with the Supplementary trait.

###### Circle of Peace (Form)

Prerequisites: Write Magic (Symbolism), Ring (Form)

Complexity 1

Any creature standing within the circle must succeed on a contested Will check or be unable to attack.

###### Circle of Power (Affix, Form)

Prerequisites: Write Magic (Symbolism), Ring (Form)

Complexity 1

The damage rolls of spells containing the affixed concept cast by creatures standing within the circle are Strong 1.

###### Circle of Protection (Affix, Form)

Prerequisites: Write Magic (Symbolism), Ring (Form)

Complexity 1

The damage rolls of spells containing the affixed concept are Weak 1 when affecting creatures standing within the circle.

##### Tier 2

###### Manifest 2

Complexity: 2

Manifest a concept of up to Tier 2 at a range of 0m, if this is within the first sector of your mental domain you are treated as being in contact with it.

###### Dual Manifest

Complexity: 1

Combine two spells including Manifest 1 at that point, they become one spell and only 1 instance of Manifest 1 is required in the spell.

#### Destruction

Antithesis: Creation

The magic of reversing the manifestation process, able to unpick spells and stop their effects, potentially removing important parts to leave others in effect.

##### Tier 1

###### Destroy Concept

Complexity: 1

Remove a concept of up to Tier 1.

#### Detect

The skill of detecting auras and reading magic signs.

##### Tier 1

###### Hear

Complexity: 2

Allows the linked concept to be heard. 

###### Symbolism

You are trained in the arts of recognising magical symbols, these may take the form of one of the below:

###### Magic Symbols

The mnemonics of a spell caster given written form, indecipherable diagrams to some, you have gained knowledge of how to make use of them.

  

Decipher Magic

Prerequisites: Read Magic

Ability - Cost: 1 - (Concentration)

Fatigue: Mental

Provokes Reactions: No

Attempt to decipher a given symbol, making an Intelligence Check against the Complexity of the symbol (Tier x 10 + Complexity).

  

Reactive Decipher

Prerequisites: Decipher Magic

Reaction - Once per Turn

Fatigue: None

Provokes Reactions: No

Trigger: You perceive a magic symbol

Attempt to decipher a given symbol, making an Intelligence Check against the Complexity of the symbol (Tier x 10 + Complexity).

  

Concept Breakdown

Prerequisites: Decipher Magic

Ability - Cost: 1 - (Concentration)

Fatigue: Mental

Provokes Reactions: No

Determine the conceptual make up of a spell you can perceive.

Make a contested Will Check against the caster of the spell.

Success: Determine the spell components used.

  

Reactive Breakdown

Prerequisites: Concept Breakdown

Reaction - Once per Round

Fatigue: Mental

Provokes Reactions: No

Determine the conceptual make up of a spell you can perceive.

Make a contested Will Check against the caster of the spell.

Success: Determine the spell components used.

  

Read Magic

Passive

Requires you to have the magic symbol visible.

You are able to use the Cast ability for the magic symbol as long as it is visible.

It must remain visible throughout any abilities with the [Supplementary](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.46dlk714bqt4) trait.

  

Imbue Implement 1

(Write Magic, Infusion 1, Contract 1)

Cost: 1 hour and 100gp for each point of Complexity

Infuse a spell effect into an object, none of the components can be above Tier 1; this effect can be activated as per any contracts imposed upon it and interact with other spells.

E.g. Infuse Fire onto a sword with an on use contract, the spell can be activated to allow the sword to deal additional damage.

  

Living Spellbook

Requires: Write Magic, Detect 2

As Write Magic, but using yourself as the canvas.

  

Read Self

Requires: Read Magic, Detect 3

You treat any symbol written on your body as visible.

  

Write Magic

Requires: Creation 1, Detect 1

Cost: 1 hour and 10gp for each point of Complexity

You may create and write a spell using the magic abilities you know.

This spell does not need to be memorised in order to use it, only read.

Only you are capable of reading this symbol without first deciphering it.

#### Esotericism 

Magics involving the Planes, Astral Travel and the phases of reality.

##### Concept Suffusion / Drain

An area suffused with a concept reduces the cost of any spells cast containing that concept by the suffusion; additionally any damage rolls of the concept within that area are strong.

Conversely, an area drained of a concept increases the cost of any spells cast containing that concept by the drain, additionally any damage rolls of the concept within that area are weak.

##### Concept Aligned / Opposed

If an area is aligned with a concept, it is conceptually closer to it than elsewhere e.g. A volcano is aligned to fire, the conceptual distance to the plane of fire is lower here. 

##### Tier 1

  

###### Awaken

Complexity: 4

Grants a mind to a concept, it can think and act as its form dictates.

  

###### Split

Complexity 1

Split a spell’s effect into two separate instances.

The damage of each instance is equal to the total spell’s damage divided amongst the new instances.

The Check to resist the effects of a spell are Strong equal to the number of extra instances.

Pump 1: Increase the number of instances.

  

###### Detect Phase Conjunction (Affix)

Prerequisites: Detect 1

Complexity: 1

Determine the conjunction between your current phase and the affixed phase.

  

###### Open Connection

Requires: Esotericism 1

Complexity: 1

Adds an open connection to a spell, an open connection allows any connected nodes to be added to another spell, the costs of any connected nodes must be met in addition to this other spell. 

  

###### Input Rune

Requires: Esotericism 1  
Complexity: 1  
Allows an implement spell to be supplied with Spell Points.

  

###### Invert Phase Conjunction (Affix)

Prerequisites: [Detect Phase Conjunction](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.tg0xww2vzo0l)

Complexity: 2

The targeted concept switches phase for manifestation. 

An example of usage would be to invert a door in two separate phases to create a gateway between them. 

  

###### Mental Domain Increase

Passive

Your Mental Domain gains an additional Sector with range equal to your (Will Bonus + Visualisation Bonus) x your Size

  

###### Mental Link (Affix)

Prerequisites: [Mental Link - Command](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.opgiv1b35v4q)

Complexity 2

This must be combined with another Applicator e.g. Animate, while the effect is active, you gain the following ability:

  

Activate Mental Link - Applicator (Push) 

Ability

Fatigue: Mental

Provokes Reactions: No

Use the Applicator or Concept specified on the concept. 

  

###### Mental Link Control 1

Prerequisites: Mental Link

Passive

When using Activate Mental link you can activate if for one additional concept. 

  

###### Infuse Potential

Requires: Source, Infusion 1

Complexity: X

Fills a Source with the Complexity specified.

  

###### Source

Complexity: 1

A Source contains the will to manifest attached concepts.

The Size is the maximum will it can contain.

  

###### Create Phase

Complexity: 5

Create a new phase with size equal to yours.

  

###### Align Phase (Affix) 

Align a phase to the affixed concept. 

  

###### Diverge Concept

Split a concept such that it can exist in another phase. 

  

###### Parallel Cast

Passive

You can cast two spells using one use of the Cast ability.

Combine their Complexity when considering Intelligence and your ability to cast them. 

Any Checks you make for the spells are Weak(N) where N is the number of additional spells e.g. Manifesting and projecting three instances of Fire 1 would leave the attack rolls at Weak(2).

  

###### Expanded Parallel Cast

Prerequisites: Parallel Cast

Passive

Increase the number of spells you can combine as part of Parallel Cast.

You can select this multiple times, up to 3 times per Tier.

  

###### Parallel Control 

Prerequisites: Parallel Cast(3)

Passive 

If you choose to cast only one half of your available spells (rounded down), the Checks you make are not Weak. 

  

###### Mirror Cast

Prerequisites: [Parallel Cast](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.4yittlv8jcm8)

Passive

Whenever you make use of Parallel Cast where two of the spells are the same, the complexity of the second spell is three quarters of the original .

You can take this ability multiple times, increasing the number of additional spells it affects.

  

###### Reactive Cast

Reaction - Once per Round

Fatigue: Mental

Provokes Reactions: No

Trigger: You perceive a concept or spell on another creature’s turn.

Use the Cast Ability.

  

###### Domain Sense

Prerequisites: Mental Domain Increase, Detect 1

Reaction

Fatigue: Mental

Provokes Reactions: No

Trigger: A creature is casting a spell within your mental domain.

Treat the spell as perceived before it is fully cast.

##### Tier 2

  

###### Mirror Cast 2

Prerequisites: [Mirror Cast](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.7ej9i6ltq2jc)

Passive

The complexity cost of additional spells becomes one half of the original. 

##### Tier 3

###### Mirror Cast 3 

Prerequisites: [Mirror Cast (Tier 2)](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.75tykepui86l)

Passive

The complexity of additional spells becomes one quarter of the original. 

#### Infusion

The magic of adding effects to another concept, these do not inherently change the concept itself which may leave it vulnerable to the newly infused abilities.

A material has a limit to the number of infusions it can accept, this is usually one of equivalent Tier, or multiple of lower Tiers that sum to the material’s Tier.

##### Tier 1

###### Infuse 1

Complexity 1

You infuse a linked concept, this takes effect instantaneously.

#### Move

Antithesis: Stop

The skill of moving a concept from one place to another, or otherwise causing it to move.

##### Tier 1

###### Animate

Complexity: 1  
Manipulate a concept of up to your size as a limb using an ability that costs 1 action, e.g. making an attack using a tree branch.

Any Dexterity or Agility Checks made using the concept use your Wits.

Any Strength Checks made using the concept use your Will.

Divide your Wits and Will equally among all limbs you have animated.

You suffer Mental Fatigue for any abilities used.

###### Homing

Prerequisites: Project

Complexity: 4

The concept will home in on the target, it is unable to dodge.

###### Project

Complexity: 1

This allows you to move a concept of Tier 1 or below to another location within your Mental Domain.

###### Range

Prerequisites: Manifest

Complexity 1

Allows a spell effect to originate from a point within 1m, specifying the target or point in space (this must be either a single space or an intersection between spaces) 

Pump 1: Double the available distance.

#### Obscure

Magics that hide or otherwise appear to obfuscate creatures or information, including making it harder to determine the spells you are casting.

#### Stop

Antithesis: Move

This is the skill of preventing a concept from being moved, or protecting against its effects.

##### Tier 1

###### Ward Caster

Complexity 1

This protects you from any instantaneous effects of a concept you are manifesting.

###### Ward Infused

Prerequisites: Ward Caster

Complexity 1

This protects an infused object or creature from the infused spell.

###### Ward Wielder

Prerequisites: Ward Caster

Complexity 1

This protects any wielder of an item you have affected from the instantaneous effects of a concept.

###### Ward Ally

Prerequisites: Ward Caster

Complexity: 2

This protects one ally from any instantaneous effects of a concept you are manifesting.

Pump 1: Increase the number of allies warded by 2.

#### Protection 1

Prerequisites: Infuse 1

Complexity 2

This protects against 5 damage that would be caused by a linked concept.

#### Transmutation

The magic of changing one concept into another, polymorphing in whole or in part.

##### Tier 1

###### Transmute 1

Transmute is a versatile Applicator, though depending on what you are changing the complexity will vary:

Concept

Complexity: 2

Change one concept into another, e.g. Fire to Ice.

Creature Part

Prerequisites: Studied Anatomy 1 (Any 2)

Complexity: 3

Change part of a tier 1 creature to that of another tier 1 creature e.g. Human finger nails to wolf claws, granting the effects of that part. Any base statistics of the base creature are retained, though their abilities may be limited by the new form. 

The creature must make a contested Will check against you:

Failure - Gain an Identity and make a Control Check against it. 

Name: of the new form. 

Hold: 10 or half, whichever is lower

Will: Your Will

Tier: Your Tier

Type: Alternate Identity

Creature Type

Prerequisites: Studied Anatomy 2(Any 2)

Complexity: 8

Change the type of a tier 1 creature to that of another tier 1 creature, they gain the form of that creature. Any base statistics of the base creature are retained, though their abilities may be limited by the new form.

The creature must make a contested Will check against you:

Failure - Gain an Identity and make a Control Check against it. 

Name: of the new form. 

Hold: 40 or half, whichever is lower

Will: Your Will

Tier: Your Tier

Type: Alternate Identity

Concept Form

Prerequisites: Transmute 1, Form(any 2)

Traits: Affix

Complexity: 2

Change the known form of a concept or by an affixed known form. 

# Concepts

## Blood

### Tier 1

#### Blood 1

Complexity 1

12 Tier 1 blood.

#### Blood Casting (Supplementary) 

Ability - Cost 1 - Once per Round

Fatigue: Mental

Provokes Reactions: No

For every 4 points of blood you have available as a material, gain a +1 bonus to visualisation rolls.

This consumes the blood used.

For something to be available as a material, it must be in your hands.

#### Harmful Casting 

Ability - Cost 1 - Once per Round

Provokes Reactions: Yes

Fatigue: Physical

Attack yourself with a slashing weapon, you can use bleed gained in this way towards Blood Casting.

#### Prevent Bleed

Tier 1

Prerequisites (Blood 1, Stop (Any))

Complexity 1

Reduce the amount of bleed taken by 1d10

#### Blood Casting - Helpless

You can use the blood of a bleeding helpless target to use Blood Casting

## Cold

### Tier 1

#### Cold 1

Complexity 1

Deals 1d10 Cold damage.

#### Slow Reactions 1

Prerequisites: Cold 1

Complexity 1

The creature must succeed on a Constitution Check opposed to your Will or gain the Slow condition.

#### Freeze

Prerequisites: Slow Reactions 1

Complexity 2

The creature must succeed on a Constitution Check opposed to your Will or gain the Restrained Condition.

## Curse

### Tier 1

#### Curse 1

Traits: Affix

Complexity: 4

Due to the negative emotion involved in cursing, only enemies suffer the effects of the curse, any other targets hit wil suffer the normal spell's effect. 

Affected targets add an Identity with hold 0 that contains the affixed spell effects. 

Name: Curse

Hold: 0

Will: Your Will

Tier: Your Tier

Type: Curse

Effect: The affixed spell effects. 

  

You gain an Identity:

Name: Corruption

Hold: The base complexity of the affixed spell (curse included) 

Will: Your Will

Tier: Your Tier

Type: Corruption

Effect: Gain Corruption 1, whenever you would gain this identity again, keep the highest hold and increase the Corruption value. 

## Death

### Tier 1 

#### Death 1

Complexity 1

1d10 Necrotic Damage.

#### Decay

Prerequisites: Death 1

Complexity 2

Convert the full Necrotic damage of the spell, the target’s body decays, losing:  
  

Converted Damage

Lost

1

Finger (Dexterity Checks made with that limb are Weak 1)

2

Hand

3

Arm / Leg

5

Head / Torso

  

The target must succeed on a Will Check, the difficulty is modified by the converted damage.  
Failure: Gain Fear 1.

#### Nauseating Display

Prerequisites: Slough

Complexity: 2

Any creature that can perceive the creature affected must make a Constitution Check:  
Failure: Gain Nauseated.

#### Slough

Prerequisites: Decay 

Complexity: 2

Causes decayed tissue to fall within 1m of the target.

The target and any creatures affected must make a Constitution Check, the difficulty is modified by the converted damage:

Failure: Gain Nauseated.

#### Terrifying Display

Prerequisites: Fear 1, Decay

Any creature that can perceive the creature affected must make a Will Check:  
Failure: Gain Fear 1.

#### Vampiric

Prerequisites: Death 1

Complexity: 1

Gain the converted damage as Blood and Maximum Blood.

## Electricity

### Tier 1

#### Electricity 1

Complexity: 1

1d10 Electricity damage.

## Fear

### Tier 1

#### Doom

Complexity: 3

Any checks that the target fails while this effect is active increase their Fear condition by 1.

#### Dread

Complexity: 2

Any subsequent checks for Fear 1 are strong.

#### Fear 1

Complexity: 1

Make a Will Check with 1d10 as the bonus against the targets Will Check:

Success: Target gains the converted difference in Fear.

#### Unease

Complexity: 2

Any attack checks the creature makes suffer a -1 penalty. Any checks to resist Fear are Weak. 

## Flesh

## Fire

### Tier 1

#### Fire 1

Complexity 3

Composite: [[Heat 1](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.dgsjmm2922hu)] + [Limit(Harmless)>[Light 1](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.qujvo99yssem)(Pump2)>[Aura(Form)](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.6c9j56r5xs8h)(Pump2)>[Fade](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.gjlhn6d7ffc)]

Flames that deal 1D10 Heat damage, shining light +3 in a 3m radius and Light +2 for a further 3m.

#### Char (Affix)

Prerequisites(Fire 1)

Complexity 2

If the spell deals its critical effect, remove the burned condition.

Reduce the creature’s current blood by the damage dealt.

The creature must make an opposed Will Check against the caster.

Success: Nothing

Failure: Suffer the damage as Identity damage.

#### Cauterise

Prerequisites (Fire 1)

Complexity 1

A creature gains Healing Wounds.

The creature removes 1d10+Will Active Wounds.

The creature suffers pain as normal.

#### Ignite 1 (Affix)

Prerequisites: Fire 1

Complexity 3

Fire damage suffered by a creature lingers, at the start of each of their turns they take additional damage.

The damage they suffer is equal to the spell’s damage, but Weak.

They can drop prone and roll (move while prone) to attempt to remove the effect; make a contested Will Check against their Agility:

Success: The effect remains.

Failure: The effect is removed.

Alternatively this can be removed by Water 1.

#### Purifying Flames

Prerequisites: [Cauterise](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.d47lx9bd2avp), [Cure Disease 1](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.6k0c4kpkhhfo)

Complexity: 4

Make a damage check against the Disease’s difficulty:

Success: Remove the disease.

The creature suffers all of the usual effects of the Fire damage.

## Force

Force acts as though it has tangibility.

### Tier 1

#### Force 1

Complexity 2

Choose one:

1d10 Crushing

1d10 Slashing

1d10 Piercing 

When force is applied using the Stop Applicator, the values used are one quarter, it is treated as Reduce Any.

#### Tune Protection

Prerequisites: Force 1

Complexity 1

You can increase the value of one concept when applied with the Stop Applicator to half its usual value, the value used for the antithesis concept becomes 0 e.g. Fire tuned to half effectiveness would drop Water to 0. 

#### Force Bandage

Prerequisites: Force 1

Complexity 1

Immediately gain Concentrating(3), this acts as the Bandage ability with charges equal to your Force roll (Tier d10+1d10+Will). Once 3 actions have passed on your turns since casting the spell, the effect ends.

#### Telekinesis - WIP

Prerequisites: Force 1

Complexity 2

Manipulate a target with Telekinetic power, using your Wits in place of Dexterity and Agility, and Will in place of Strength.

Divide your Wits and Will among all affected targets.

Provided you can assign a Will greater than or equal to the weight of the target divided by 15, it gains the Fly and Hover traits, with movement speed as appropriate.

You can make use of any abilities that would require you to wield a weapon; it can also use the Fly ability.

The target also gains the Grabbed(1) condition and you gain the Controlling Grapple(1) condition.

## Heat

### Tier 1

#### Heat 1

Complexity 1

Deal 1D10 Heat damage.

## Language

### Tier 1

#### Message 1

Complexity: 1

Up to 10 words will be heard by target. 

#### Known Language 

Complexity: 1

A known language of the caster. 

#### Unknown Language

Complexity: 3

Used as a placeholder for languages not known. 

## Light

### Tier 1

#### Light 1

Complexity 1

Increase the light level by 1.

Pump 1  
Increase the light level by 1.

#### Fade 1 (Affix)

Complexity 1

Increase the light level to 1 below the affixed Light concept in a radius equal to that of the affixed Light concept

## Nature

### Tier 1

#### Nature 1

Complexity 1

Cause plantlife to grow within a target dealing 1d10 piercing damage. This is not reduced by reduction external to the creature itself.

## Pain

### Tier 1

#### Pain 1

Complexity 1

Manifest Pain of 1d10 converted. 

#### Suppress Pain

Prerequisites (Pain 1, Stop 1)

Complexity 2

Suppress up to 1d10 converted Pain.

#### Adrenaline

Prerequisites (Pain 1, Destruction 1)

Complexity 2

Up to 1d10 of Adrenaline converted. 

## Poison

It is possible to apply Poison to objects using the Apply Poison Ability:

### Apply Poison

Ability - Cost: 1 - Once per Round

Fatigue: Mental

Provokes Reactions: Yes

Apply poison to an object.

You must make a Dexterity check equal to 10 multiplied by the Tier of the Poison.

Success: You apply the poison to the object.

Failure: You suffer the effects of the Poison.

### Tier 1

#### Poison 1

Complexity: 1

Affected creatures take 1d10 Necrotic damage.

#### Poisoner 1

Passive

You can safely apply poisons of up to Tier 1 without risk of affecting yourself.

#### Venom 1 (Affix)

Complexity 1

Affected creatures must succeed on a Constitution Check or gain the Envenomed Condition.

#### Venom Extraction

You are capable of extracting Venom from a helpless creature.

#### Affliction (Affix, Delay)

Prerequisites: Requires Poison 1

Complexity: 2

The target must make a Constitution Check at the start of its turn:  
Success: The effect ends

Failure: Suffer the Poison’s damage again

#### Persistent Affliction

Prerequisites: Affliction

Complexity: 1

The creature must succeed on two Constitution Checks instead of one to remove Affliction.

#### Lingering Affliction

Prerequisites: Affliction

Complexity: 1

Affliction does not end with a successful Constitution Check; the creature must make a further Constitution Check at the start of its next turn to truly end it; the Check  is Strong.

#### Virulence Affliction

Prerequisites: Affliction

Complexity: 1  
A creature’s checks against Affliction are Weak.

#### Deteriorating Affliction

Prerequisites: Affliction

Complexity: 1

The Check to remove Affliction increases by 1 for each failure.

#### Pestilence Affliction

Prerequisites: Affliction, Disease 1

Complexity: 2  
Affliction acts as an airborne Disease within a range equal to your size.

#### Delayed Recovery

Prerequisites: Affliction

Complexity: 1

On the turn following the end of the condition, the creature still suffers damage, though the roll is Weak.

#### Haemorrhaging (Affix) 

Prerequisites: Poison 1, Blood 1

Complexity: 4

The Poison does not deal necrotic damage. 

The creature suffers active wounds instead. 

The creature gains the Internal condition for the converted active wounds. 

## Rage

### Tier 1

#### Reactive Anger

Prerequisites (Rage 1)

Complexity 1

Affected Creatures must succeed on an opposed Will Check or else take on the below actions:

Attack themselves as best they can.

Attack their nearest Target.

## Slashing

### Tier 1

#### Slashing 1

Complexity: 1

1d10 Slashing Damage.

## Time

### Tier 1

#### After Image

Complexity 2

The creature gains one charge that can be spent upon triggering a reaction; the reaction still takes place, however it does not affect the creature. 

A creature with Speed 2, can react and affect the creature as normal. 

#### Haste 1

Complexity 2

Grant a creature a separate turn with one action; they must roll initiative for this separately.

The creature has Speed 2.

#### Revert

Prerequisites

Complexity 2

Reverts time for matter in the palm of your hand by one round.

#### Revert Wounds

Prerequisites (Revert, Studied Anatomy)

Complexity 2

Choose 1:

Revert 1D10 Healing Wounds (Converted) to that number of Active Wounds multiplied by 10.

Revert 1D10 Active Wounds.

#### Replenish

Prerequisites (Time 1, Infuse 1)

Complexity 1

Refill a target with a material, this target must have previously contained the material e.g. blood in a body, water in a waterskin.

This must be combined with the material to refill with.

#### Slow 1

Complexity 2

Creatures lose one action; if this would cause one of their turns to be reduced to 0 actions, it is lost.

A creature can only be reduced to a minimum of 1 action.

#### Stop

Prerequisites (Slow 1)

Complexity 2

Creatures lose one action; if this would cause one of their turns to be reduced to 0 actions, it is lost.

If the creature has no actions available due to this effect, it loses its turn.

### Vitality

##### Tier 1

###### Vitality 1

Complexity 1

Restore 1D10 Maximum Blood for Tier 1 Creatures.

Remove Necrosis equal to the converted value.

###### Cure Disease 1

Complexity 3

Make a contested Will Check against the Difficulty of one Tier 1 Disease.

Success: Remove the Disease, any underlying conditions persist.

###### Agility 1

Complexity 2

Grant 1 Agility Score.

Pump 2: Grant 1 additional Agility Score.

##### Tier ?

###### Regeneration

Prerequisites: Vitality ?, Advance Time ?

Regrow a limb

# Spells

## Tier 1

### Magic Missile

[[Ward Caster](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.719193qp26wb)]>[[Project](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.qzo8iwhzzsol)]>[[Homing](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.hkbot98kjfcq)]>[[Manifest](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.d0blrcekwf9h)]>[[Split](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.od4voza0vcnm)(Pump 1)]>[[Force 1](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.yniphmxjs2a9)]

IP: 6

Complexity: 11

Launch 3 homing bolts of force that each deal 2d10+Will /3 damage. 

### Bane

[[Ward Caster](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.719193qp26wb)]>[[Ward Ally](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.zeyf9o6fiak)(pumpN)] >[[Manifest](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.d0blrcekwf9h)]>[[Aura](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.6c9j56r5xs8h)(Pump4) ]>[[Curse](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.cgihv9dgk46n)] >[[Unease](https://docs.google.com/document/d/1vI-IAbJokljZw4UKFW5vd6wz5fVYj52uFDCSoCZacHQ/edit#heading=h.vj4hmio4ugb5)]

IP: 5

Complexity: 16 + 2 for each additional ally

Curse of unease affecting all targets within 16m, preventing this from affecting one ally. 

### Fireball

Limit(Harmless) (WardCaster > Manifest > Fire1 > Project) > Contract on Location (manifest > Fire 1 > Aura(pump3) 

IP: 10

Complexity: 14

Launch harmless fire at a location, upon reaching that location it explodes out in an 8m radius. 

### Baleful Polymorph

Range(Pump3) + Curse + Polymorph

Complexity: 16

Curse a creature within 8m into a new form.

### Curse of Immolation

Range(Pump3) > Manifest > Curse (Fire 1)

IP: 4

Complexity: 12

Target creature within 8m must make a contested Will Check: 

Failure - They gain an identity with Fire 1 as the effect, burning each round for your Fire 1 damage until decursed. 

### Bless

### Blood Mist

### Dispel Magic

### Divine Favor

### Message

### Neutralize Poison

### Polymorph

### Stoneskin

### Summon Nature's Ally I

### Vampiric Touch

### Water Breathing

### Trap the Soul

# Items

## Stone of Sending

[Contract of Transfer] > [Message 1]

[Mental Link] > [Message 1]

Runic Binding

## Breakthroughs

A breakthrough is earned when a creature reaches a new Tier.

### Demigod

#### Domain 

Select one Skill that you possess, this becomes one of your Domains

Once you possess this breakthrough you can select up to 4 Domains by spending IP.

### Deity Minor

#### Improved Domain

Select one of your Domains, the Tier of Power you can grant increases by 1.

#### Minor Domain

As Demigod-Domain

  

# Spirits

## Bound Spirits

A Bound Spirit is one that is connected to a concept through some contract, a mortal soul to the body through the contract of mortality, a ghost through the contract of its obsession or emotion, and elementals to their concept.

  

A Bound Spirit can pass through its bound concept at will without being obstructed or detected by normal vision as well as interact with that concept as though it was manifested, even when not. If the bound concept already hosts another spirit that opposes their passage, they can attempt an opposed Will Check.

  

Once manifested, they behave as their Concept and Spirit would allow.

  

Once they lose Integrity, they lose their manifestation and cannot directly affect other targets aside from their own concept until they use Manifest Self once again.

### Unary vs Binary Systems

A unary system is one where the mind and soul are one element, and any memories are stored within the Soul. 

  

A binary system is one where the body and soul are two separate and distinct entities, any memories are stored within the body, only accessible by the Soul. Though the soul retains any general behaviours, it will find itself unable to make use of the knowledge it should possess, should it become unbound. 

### Will to Remain

A Bound Spirit may spend Spell Points instead of Integrity to remain manifested.

### Gather Essence

While it is not manifested, a Bound Spirit may gather essence by spending spell points.

### Manifest Self

A Bound Spirit may manifest itself directly, requiring a total Essence equal to double the total of Physical Scores required.

### Armour of Will

Manifested Spirits can add their Will to their Reduction(Any)

## Unbound Spirits

Unbound spirits, i.e. those who have lost or had their Contract destroyed, unless otherwise contracted, will return to the Astral Plane.

  

Given an unbound spirit is capable of expending enough Spell Points, it is possible for them to create a new body or binding point.
