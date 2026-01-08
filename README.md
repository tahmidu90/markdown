# Stuyrim

- Inspired by Avatar: The Last Airbender
- **>** symbol represents having greater damage done onto that bending and less damage done from that bending
Water > Fire > Air > Earth > Water > Fire

# Basic Attributes
Health
Shield
Dodge Rate
Accuracy
Damage

# Class Design
**Basic Attacks**: High chance of attack not hitting, but when directly getting hit, does a lot of damage
**Special Attacks**: High chance of attack hitting, but medium damage
**Support**: Little to no damage done onto anyone, helps teammates

### Waterbender

- **Status Effect**: `Frost` decreases accuracy and after multiple turns stuns target for one turn. (Buildup)
- **Status Effect**: `Healing` increases health over multiple terms and removes negative effects after healing is complete (Buildup)
- **Basic Attack**: `Water Slash` increases frost.
- **Special Attack**: `Tsunami` AOE attack, that gives a high level of **Frost** effect.
- **Support**: `Water Healing` gives **Healing** effect.

### Firebender

- **Status Effect**: `Burn` tick damage on target for 3 turns.
-  **Basic Attack**: `Fireball` applies damage and burn on a target, but also has a small chance to be an AOE. 
- **Special Attack**: `Blue Flame` can't move for 2 turns, 60% accuracy and high damage for 3 turns. 
- **Support**: `Flame Wall` Applies a wall of fire in front of opponents, decreasing their and team's accuracy for 2 turns

### Earthbender

- **Status Effect**: `Fortified` 90% reduced damage but cannot attack unless also Earthbender
- **Status Effect**: `Dizzy` greatly reduces affectors' accuracy
-  **Basic Attack**: `Rock Throw` Inaccurate, medium damage, gives **Dizzy**
- **Special Attack**: `Earthquake` AOE 70% accuracy, lo damage, gives **Dizzy** 
- **Support**: `Rock Armor` gives **Fortified** to one person

### Airbender
Overall higher dodge rates
- **Status Effect**: `Light as a Feather` high dodge rates 
-  **Basic Attack**: `Air Blast` lo damage, hi accuracy
- **Special Attack**: `Big Gust of Wind` removes opp. healing, all burning, opp. Fortified, and `Light as a Feather` to teammates
- **Support**: `Water Healing` gradually healing of target's health, at the end removes any negative status effects.

  ### Lord of Flame

- **Status Effect**: `Burn` tick damage on target for every 
-  **Basic Attack**: `Flame Spray` Fires a spray of fire on target, high accuracy and applies burn.
- **Special Attack**: `Blue Flame` Charge attack that leaves the boss vulnerable for 1 term before unleashing a high damaging attack on all opponents.
- **Support**: `Flame Giveth Strength` Lord of Flame imbues himself with the Forsaken Flame, granting him an attack buff that increases damage for 4 turns.
