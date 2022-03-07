# Attacking

When making an attack, a hit is guaranteed if the target doesn’t attempt to prevent it.

1. Hit is guaranteed, so no attack roll.

2. Defender responds:

 1. Block - Opposed Check Dexterity vs Dexterity

 2. Dodge - Opposed Check Agility vs Dexterity (Requires a shield)

 3. Parry - Opposed Check Visualisation vs Dexterity (Requires a weapon)

3. Damage is Tier x D10 +Tier Bonus +Strength + Weapon Damage

4. Damage is reduced by Damage Reduction of the same type as the damage. 
    Damage Reduction(Any) can be used to reduce any one type of incoming damage per attack.

5. If the Damage is not fully reduced, then it may cause [[Wounds]] and [[Pain]] to the target.

# Flow

```mermaid
graph TD
Hit[A hit is guaranteed unless the target reacts]-->Reaction[The target reacts]
Hit--->DamageReduction[Damage is reduced by Damage Reduction of the same type as the damage]
Reaction--->Block
Reaction--->Dodge
Reaction--->Parry
Block--->BlockCheck[Opposed check, attacker's Dexterity against the target's Dexterity]
Dodge--->DodgeCheck[Opposed check, attacker's Dexterity against the target's Agility]
Parry--->ParryCheck[Opposed check, attacker's Dexterity against the target's Visualisation]
BlockCheck--->BlockSuccess[Success]
BlockSuccess--->BlockResult[Add the blocking item's reduction to your damage reduction]
BlockCheck--->ReactionFailure[Failure]
DodgeCheck--->DodgeSuccess[Success]
DodgeCheck--->ReactionFailure[Failure]
ParryCheck--->ParrySuccess[Success]
ParryCheck--->ReactionFailure[Failure]
DodgeSuccess--->NoDamage
ParrySuccess--->NoDamage
NoDamage[The target avoids taking any damage]
BlockResult--->DamageReduction
DamageReduction--->ResolveWounds[If the damage is not fully reduced, then it may cause Wounds and Pain to the target as defined in Damage Types]
ReactionFailure--->DamageReduction
```
# Attacking Objects

Objects should be treated as though attacking a target with no Blood.

Determine the object's reductions by comparing its form against the Armour table and selecting the appropriate material.

# Attacking Weapons and Armour

Any equipment wielded by a creature is usually not subject to being damaged to the point of breaking.