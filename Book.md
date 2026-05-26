# Sway System
A small setting-adaptive tabletop role-playing game system by Tommy Ettinger.

## The Basics

There is one Narrator at the table, and one or more players. The Narrator lays out a setting and describes the actions of Non-Player Characters (NPCs), while each Player controls one Player Character (PC) directly. Players create the mechanical details for their PCs fairly quickly in this system, and before play starts, the focus should be mostly on the interactions between PCs and how they know each other. NPCs follow similar rules to PCs, and may be friends, foes, or just neutral observers.

The success or failure of actions are determined by dice. Unlike many other role-playing games, in combat players know the values of their dice at the start of each round, before they decide to take actions. The dice rolled at the start of the round also determine the order in which characters, both PCs and NPCs, will act. Outside of combat, situations involve a mix of dice rolled for everyone at the start of the encounter, and dice rolled additionally over time.

Dice rolls are normally done by rolling and adding up 3 six-sided dice at the start of the round, then adding any relevant modifiers at the time an action occurs. The lowest dice rolls go first in a round, and when those characters act, their actions are the least likely to succeed, if they are difficult or challenged activities like attacks. The highest dice rolls go last in a round, and are the most likely to succeed. A character can choose to delay their turn until after any another character's turn, or after a declared event happens. If the declared event doesn't ever happen, that character's turn is wasted. Some actions may involve rolling a few different dice when you choose an action; these are always six-sided dice, and they do not change your dice for the round.

Typically, the PCs travel as a group along with some friendly NPCs, who might include hired workers, beasts of burden, or people the PCs are aiding or escorting. Friendly NPCs usually don't fight; that responsibility lies with the PCs. Friendly NPCs can also include former PCs who aren't able to act normally for some reason (such as their player not being at the table). The reason is up to the Narrator while a Player isn't present, and could range from a sprained ankle to a random fever making it better that that character sits out during combat. When the Player returns, control of their PC returns to them unless they want to create a different character or control a friendly NPC (with the Narrator's approval).

## Characters

A character has a general concept that can be anything appropriate for the setting the Narrator has laid out.
Before play starts, the Players and Narrator should work as a group to establish concepts that make sense to the group and in the setting. How the PCs know each other, and what they know about each other, is important, and is expected to evolve over time.

Each character is defined in permanent terms by their Stats, their training and specialties in Skills, and the Techniques they know. A character also has Items, which are not permanent and can be given to other characters, stolen, broken, weakened, strengthened, and so on. A PC starts with {{FIXME: NO IDEA YET}} Hit Points, which go down as they suffer close calls or physical harm. During a battle, every character has Offense and Defense tracks, which each start at 0 and can go down to `-`, `--`, or `---`, or up to `+`, `++`, or `+++`. Your Offense track applies a modifier to the success chance for your attacks, and your Defense track applies a modifier to the success chance for attacks against you. Outside of combat, you can accrue Favor Dice, which are additional dice that can be rolled and applied as a bonus to succeed on tasks, then are given back to the Narrator.

A character's role in both combat and non-combat situations is determined by their Skills, and all Skills can become applicable in any situation where they make sense. A character's personality and special abilities are reflected in combat by the Techniques they know. Techniques can include magical abilities in settings that permit them, as well as things like being able to attack recklessly, calmly, or deceitfully. A Technique applies to an attack with a Combat Skill in combat, but outside of combat, Techniques can be applied to how you handle a relevant task. This can play to your advantage, or applied as a handicap in order to gain Favor Dice.

Your stats do not change over time, but your equipment can change often, and your skills occasionally improve. Most improvements a character gains over time take the form of their Items, and if a Player Character dies, their Player typically takes control of a friendly Non-Player Character and awards their Items to them.

## Stats

- **Toughness** (T) represents your physical strength, bulk, and healthiness.
- **Agility** (A) represents your speed, reflexes, and physical awareness.
- **Persona** (P) represents your confidence, willpower, and social awareness.
- **Expertise** (E) represents your intelligence, reasoning, and ability to learn.

You have 10 points to allocate to stats, which can each be between 1 and 4. Typical spreads include:
- `4, 3, 2, 1` for someone with one especially-good stat and one especially-bad one,
- `4, 2, 2, 2` for someone with one especially-good stat but no other strengths or weaknesses,
- `3, 3, 2, 2` for someone with two equally-good stats and two normal ones, or
- `3, 3, 3, 1` for someone with three equally-good stats but one glaring weakness.

The higher a stat is, the better you are at relevant uses of that stat with a skill. Each point in a stat also has specific other advantages in combat:

- Toughness reduces the damage you take from Light attacks, which are fast and can't easily be dodged.
- Agility reduces the damage you take from Heavy attacks, which are powerful attacks that armor won't stop.
- Persona increases the effectiveness of all of your Talk actions in combat, which support allies or hinder foes.
- Expertise gives you more Technique Points every round, which are used to improve your attacks in special ways.

## Non-Combat Skills:

- **Acrobatics**: Catch {A}, Escape {T/A}, Maneuver {A}, Tumble+ {A}, Moving Recovery {T&A}
- **Athletics**: Climb {T}, Endure {T}, Jump {T/A}, Swim {T/A}, Team Play {A&P}
- **Deception**: Bluff {P}, Disguise {P}, Forgery {E}, Legerdemain {A&P}, Feign Health {T}
- **Education**: Decipher {E}, Solve+ {E}, Research {E}, Write {P/E}, Broad Learning {E}
- **Focus**: Calm {P}, Concentrate {T}, Second Wind {T}, Resist Pain {T}, Courage {T/P}
- **Healing**: First Aid {T/E}, Pharmacology+ {E}, Surgery+ {A&E}, Therapy {P}, Care {P}
- **Influence**: Bargain {P}, Befriend {P}, Bribe {P&E}, Intimidate {T/P}, Entertain {P}
- **Mechanics**: Demolish+ {E}, Fine Tune+ {A&E}, Jury Rig {T/A}, Repair {E}, Gauge {E}
- **Nature**: Handle Animal {P}, Wild Lore {E}, Survival {T}, Track+ {A}, Ride {T/A}
- **Perception**: Insight {P}, Search {E}, Sense {A}, Vigilance {T}, Self Awareness {T/P}
- **Stealth**: Camouflage {A}, Bypass+ {A&E}, Sneak {A}, Subtlety {P}, Culture Blend {P}

## Combat Skills:

Melee Weapon Group:

Melee Weapon attacks need you to be near your target and have your weapon ready. Training with any Melee Weapon skill makes you resistant to Melee Weapon and Unarmed attacks (you take 1 less damage). Training with any Melee Weapon skill and any Unarmed skill stacks (you take 2 less damage), but multiple Melee Weapon skills do not stack.

- **Melee (Large)**: Power Smash {T}, Sweep+ {T}, Maintain {E}, Execution+ {T&P}
  - Two-handed melee weapons, except spears. Axes, hammers, cudgels, big polearms, etc.
  - These are weapons that generally are big enough that dodging is your best defense.
- **Melee (Balanced)**: Measured Strike {T/A}, Parry+ {A&E}, Maintain {E}, Flourish+ {P}
  - One-handed swords, all spears, fencing weapons, shields.
  - These are weapons that can be used to block an opponent's close-quarters attacks.
- **Melee (Small)**: Aggressive Flurry {A/P}, Close Combat+ {T}, Maintain {E}, Quick Draw+ {A}
  - Concealable melee weapons, knives. Chains, whips, and other tricky, flexible weapons. 
  - These are weapons that might be useful when grabbed or grabbing, and can be drawn quickly.

Ranged Weapon Group:

Ranged Weapon attacks need you to be away from your target and have your weapon ready. Training with any Ranged Weapon skill makes you resistant to Ranged Weapon attacks (you take 2 less damage). Training with multiple Ranged Weapon skills does not stack. Weather conditions can weaken Ranged Weapon attacks.


A setting chooses which skill to have, either **Ranged (Military)** or **Ranged (Energy)**.

- **Ranged (Forceful)**: Mighty Launch {T&A}, Heave+ {T}, Maintain {E}, Rapid Fire+ {A}
  - Bows, thrown projectiles, ranged weapons that require physical force to use.
  - This does not include grenades or other explosives.
- **Ranged (Precise)**: Targeted Shot {A/E}, Aim+ {E}, Maintain {E}, Rushed Load+ {A}
  - Crossbows, blowguns, whatever firearms are common in the era. Simple traps.
  - In the modern day, this includes all firearms except those mounted on vehicles.
  - In periods before The Renaissance, this does not include any firearms.
- **Ranged (Military)**: Honed Assault {A&E}, Calibrate+ {E}, Maintain+ {E}, Make Way {P}
  - Siege and vehicle weapons; flamethrowers, grenades, explosives. Any new ranged weapons.
  - In periods before The Renaissance, this can include firearms if they are available.
- **Ranged (Energy)**: Energy Barrage {A&E}, Infuse+ {E}, Maintain+ {E}, Make Way {P}
  - Magical wands, staves, rods, tomes, and so on that allow attacks with basic magic.
  - Some settings may use this skill for fire, chemical weapons, and vehicle weapons instead.

Unarmed Group:

Unarmed attacks need you to be near your target and make contact. Training with any Unarmed skill makes you resistant to Melee Weapon and Unarmed attacks (you take 1 less damage). Training with any Melee Weapon skill and any Unarmed skill stacks (you take 2 less damage), but multiple Melee Weapon skills do not stack. You do not need a free hand to make Unarmed attacks, and can do so even if you are already using both hands.

- **Unarmed (Brawling)**: Rough Blow {T}, Grapple+ {T}, Challenge {T&P}, Grit+ {T}
  - Boxing, wrestling, street-fighting. Fighting styles that emphasize toughness.
- **Unarmed (Striking)**: Swift Strike {A}, Shout+ {P}, Throw {T&A}, Disarm+ {A&E}
  - Fighting styles that emphasize fighting armed opponents with speed and intimidation.
- **Unarmed (Yielding)**: Passive Resist {E}, Taunt+ {P}, Pin {T}, Redirect+ {A&P}
  - Fighting styles that emphasize avoiding attacks and frustrating enemies so they relent.

Command Group:

Command attacks need you to be able to communicate visually or verbally with a selected ally and see your target. The selected ally makes the attack using their weapon or an unarmed attack, but uses your skill and stats to determine success instead of their own. Training with any Command skill makes you resistant to any attacks made via a Command skill (you take 2 less damage). Training with any Command skill stacks with any applicable resistances from other Combat skills, but multiple Command skills do not stack. Using a Command skill to attack makes it impossible to use Stealth skills against your target. Weather and noisy conditions can weaken Command attacks.

- **Command (Riot)**: Mob Rule {P}, Incite+ {P}, Vandalize {A/P}, Guerrilla Movement {A}
  - Attack by rousing a group of allies to fight; relies purely on anger and passion.
- **Command (Tactical)**: Battlefront Push {P/E}, Strategy+ {E}, Secure Area {E}, Adapt {A}
  - Attack by pointing allies to holes in enemy defenses; predicts battle scenarios.
- **Command (United)**: Trusting Gambit {P}, Coordinate+ {P}, Detect Loyalty {E&P}, Heroism {P}
  - Attack by using a deep bond with close allies to appear weak and make foes act rashly.
