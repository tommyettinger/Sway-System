# Sway System
A small setting-adaptive tabletop role-playing game system by Tommy Ettinger.

## The Basics

There is one Narrator at the table, and one or more players. The Narrator lays out a setting and describes the actions of Non-Player Characters (NPCs), while each Player controls one Player Character (PC) directly. Players create the mechanical details for their PCs fairly quickly in this system, and before play starts, the focus should be mostly on the interactions between PCs and how they know each other. NPCs follow similar rules to PCs, and may be friends, foes, or just neutral observers.

The success or failure of actions are determined by dice. Unlike many other role-playing games, in combat players know the values of their dice at the start of each round, before they decide to take actions. The dice rolled at the start of the round also determine the order in which characters, both PCs and NPCs, will act. Outside of combat, situations involve a mix of dice rolled for everyone at the start of the encounter, and dice rolled additionally over time.

Dice rolls are normally done by rolling and adding up 4 six-sided dice at the start of the round, then adding any relevant modifiers at the time an action occurs. The lowest dice rolls go first in a round, and when those characters act, their actions are the least likely to succeed, if they are difficult or challenged activities like attacks. The highest dice rolls go last in a round, and are the most likely to succeed. A character can choose to delay their turn until after any another character's turn, or after a declared event happens. If the declared event doesn't ever happen, that character's turn is wasted. Some actions may involve rolling a few different dice when you choose an action; these are always six-sided dice, and they do not change your dice for the round.

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

## Skills

Skills are used in both combat and non-combat situations, but some Skills are classified as Combat Skills and others Non-Combat Skills. A PC starts with 3 trained Non-Combat Skills and 1 trained Combat Skill, plus an additional 2 trained Skills they can choose as they please. From the Skills a PC has training in, they also select two Skills to specialize in. Being specialized in a skill allows you to effectively attempt skill usages with a `+` next to them; without a specialty, you are not considered trained when attempting specialized usages. Skill usages are written as Skill:Usage, such as Acrobatics:Catch or Perception:Sense.

Every skill usage involves one or two Stats. If only one Stat is listed, add that Stat to your dice result. If two Stats are listed with a slash (`/`) between them, you use the better of those two Stats and subtract 1 from the result. If two Stats are listed with an ampersand (`&`) between them, you add both Stats and subtract 2 from the result. Some occasions might use a different Stat than normal, and a Player can always try to convince the Narrator that a different Skill or Stats can apply in a situation. Using a different Skill or Stat always subtracts at least 1 from the result, depending on how well it applies, and requires the Player to justify that it applies using one of their Techniques. Training in a skill gives you +3 on all usages of that skill, and a specialty in a skill gives an additional +2 to all usages of that skill.

Events that need a skill attempt can be classified as easy, difficult, or contested.

An easy skill attempt is something a trained professional does all the time, such as a swimming a short distance without a heavy load using Athletics:Swim, or fixing a jammed gun without any time pressure using Mechanics:Repair. Easy skill attempts don't require any roll for characters who are trained in that skill. For characters who aren't trained, easy usages require rolling a dice result of 11 or more.

A difficult skill attempt is one where there is a significant risk on a failure, attempting the task is costly/time-consuming, or a task is simply challenging even for an expert. Examples include decoding a secret message using Education:Decipher, determining whether an unknown plant is safe to eat or has medicinal value with Nature:Wild Lore, and escaping a set of handcuffs using Acrobatics:Escape. Difficult skill attempts always require a roll, and the result needed varies on the task, but is usually 15 or more. After a Player knows their attempt has failed, they can choose to roll and spend Favor Dice to change the result.

A contested skill attempt is one where one or more other characters are opposing your skill attempt. Examples include a thief trying to hide from an unaware guard, which contests the thief's Stealth:Sneak against the guard's Perception:Vigilance, or a customer haggling a merchant over a price, which contests the customer's Influence:Bargain against the merchant's Influence:Bargain. Contested skill attempts require a roll, and the higher result wins (after modifiers are applied). After a Player knows their attempt has failed, they can choose to roll and spend Favor Dice to change the result. In the case of a tie between a PC and NPC, a PC wins if their Player can justify how they act with one of their Techniques, or if they spend a Favor Die. Otherwise, the PC loses the tie automatically. In the case of a tie between opposed PCs, they must roll and spend any available Favor Dice until the tie is broken, or they both lose.

### Non-Combat Skills:

- **Acrobatics**: Catch {A}, Escape {T/A}, Maneuver {A}, Tumble+ {A}, Moving Recovery {T&A}
   - Training in Acrobatics also makes you Resistant 1 to Melee Weapon attack rolls.
- **Athletics**: Climb {T}, Endure {T}, Jump {T/A}, Swim {T/A}, Team Play {A&P}
   - Training in Athletics also gives +1 to Melee Weapon Skill rolls.
- **Deception**: Bluff {P}, Disguise {P}, Forgery {E}, Legerdemain {A&P}, Feign Health {T}
   - Training in Deception also makes you Resistant 1 to Command attack rolls.
- **Education**: Decipher {E}, Solve+ {E}, Research {E}, Write {P/E}, Broad Learning {E}
	- Training in Education also gives +1 to Mechanics rolls.
- **Focus**: Calm {P}, Concentrate {T}, Second Wind {T}, Resist Pain {T}, Courage {T/P}
   - Training in Focus also makes you Resistant 1 to Unarmed attack rolls.
- **Healing**: First Aid {T/E}, Pharmacology+ {E}, Surgery+ {A&E}, Therapy {P}, Care {P}
   - Training in Healing also gives +1 to Unarmed Skill rolls.
- **Influence**: Bargain {P}, Befriend {P}, Bribe {P&E}, Intimidate {T/P}, Entertain {P}
   - Training in Influence also gives +1 to Command Skill rolls.
- **Mechanics**: Demolish+ {E}, Fine Tune+ {A&E}, Jury Rig {T/A}, Repair {E}, Gauge {E}
   - Training in Mechanics also gives +1 to Ranged Weapon Skill rolls.
- **Nature**: Handle Animal {P}, Wild Lore {E}, Survival {T}, Track+ {A}, Ride {T/A}
	- Training in Nature also gives +1 to Healing rolls.
- **Perception**: Insight {P}, Search {E}, Sense {A}, Vigilance {T}, Self Awareness {T/P}
   - Training in Perception also gives +1 to Stealth rolls.
- **Stealth**: Camouflage {A}, Bypass+ {A&E}, Sneak {A}, Subtlety {P}, Culture Blend {P}
   - Training in Stealth also makes you Resistant 1 to Ranged Weapon attack rolls.

### Combat Skills:

Melee Weapon Group:

Melee Weapon attacks need you to be near your target and have your weapon ready. Training with any Melee Weapon skill makes you Resistant 1 to Melee Weapon and Unarmed attacks (the attacker takes a -1 penalty to hit you). Training with any Melee Weapon skill and any Unarmed skill stacks (the attacker takes a -2 penalty to hit you), but multiple Melee Weapon skills do not stack.

- **Melee (Large)**: Power Smash {T}, Sweep+ {T}, Maintain {E}, Execution+ {T&P}
  - Two-handed melee weapons, except spears. Axes, hammers, cudgels, big polearms, etc.
  - These are weapons that generally are big enough that dodging them is your best defense.
- **Melee (Balanced)**: Measured Strike {T/A}, Parry+ {A&E}, Maintain {E}, Flourish+ {P}
  - One-handed swords, all spears, fencing weapons, shields.
  - These are weapons that can be used to block an opponent's close-quarters attacks.
- **Melee (Small)**: Aggressive Flurry {A/P}, Close Combat+ {T}, Maintain {E}, Quick Draw+ {A}
  - Concealable melee weapons, knives. Chains, whips, and other tricky, flexible weapons. 
  - These are weapons that might be useful when grabbed or grabbing, and can be drawn quickly.

Ranged Weapon Group:

Ranged Weapon attacks need you to be away from your target and have your weapon ready. Training with any Ranged Weapon skill makes you Resistant 2 to Ranged Weapon attacks (the attacker takes a -2 penalty to hit you). Training with multiple Ranged Weapon skills does not stack. Weather conditions can weaken Ranged Weapon attacks.


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

Unarmed attacks need you to be near your target and make contact. Training with any Unarmed skill makes you Resistant 1 to Melee Weapon and Unarmed attacks (the attacker takes a -1 penalty to hit you). Training with any Melee Weapon skill and any Unarmed skill stacks (the attacker takes a -2 penalty to hit you), but multiple Unarmed skills do not stack. You do not need a free hand to make Unarmed attacks, and can do so even if you are already using both hands.

- **Unarmed (Brawling)**: Rough Blow {T}, Grapple+ {T}, Challenge {T&P}, Grit+ {T}
  - Boxing, wrestling, street-fighting. Fighting styles that emphasize toughness.
- **Unarmed (Striking)**: Swift Strike {A}, Shout+ {P}, Throw {T&A}, Disarm+ {A&E}
  - Fighting styles that emphasize fighting armed opponents with speed and intimidation.
- **Unarmed (Yielding)**: Passive Resist {E}, Taunt+ {P}, Pin {T}, Redirect+ {A&P}
  - Fighting styles that emphasize avoiding attacks and frustrating enemies so they relent.

Command Group:

Command attacks need you to be able to communicate visually or verbally with a selected ally and see your target. The selected ally makes the attack using their weapon or an unarmed attack, but uses your skill and stats to determine success instead of their own. Training with any Command skill makes you Resistant 2 to any attacks made via a Command skill (the attacker takes a -2 penalty to hit you). Training with any Command skill stacks with any applicable resistances from other Combat skills, but multiple Command skills do not stack. Using a Command skill to attack makes it impossible to use Stealth skills against your target. Weather and noisy conditions can weaken Command attacks.

If you use a Technique with a Command attack, it treats the character issuing the command as the attacker. Counterattacks or other responses to an attack apply to the character receiving the command.

- **Command (Riot)**: Mob Rule {P}, Incite+ {P}, Vandalize {A/P}, Guerrilla Movement {A}
  - Attack by rousing a group of allies to fight; relies purely on anger and passion.
- **Command (Tactical)**: Battlefront Push {P/E}, Strategy+ {E}, Secure Area {E}, Adapt {A}
  - Attack by pointing allies to holes in enemy defenses; predicts battle scenarios.
- **Command (United)**: Trusting Gambit {P}, Coordinate+ {P}, Detect Loyalty {E&P}, Heroism {P}
  - Attack by using a deep bond with close allies to appear weak and make foes act rashly.

## Techniques

Techniques are one of the ways a character's personality is defined with mechanics. A character is created knowing three different tiers of progressively stronger Techniques, with two known Technique at each tier. Using a Technique in battle costs Technique Points (TP), which you accrue over combat. At the start of every round, a player accrues 1 TP, plus an additional TP for each of their round dice that had a value of their Expertise or less. This means low round dice results give you TP, as well as make your turn come earlier in the round, but make your actions on that turn less effective. As an example, if a character with 2 Expertise rolls `1, 2, 3, 4` for their round dice, the rolls of 1 and 2 each give +1 TP on top of the 1 TP every character gets, for a total of 3 TP. TP don't need to be spent right away, but any TP left over at the end of a combat are wasted.

Every Technique is applied in combat to a single pair of an attacker and a defender when an attack is declared. Even if an Item allows you to attack multiple opponents at once, your Technique still only applies to one defender. This is always the first defender the attack resolves against, though you can choose which defender is resolved first. A Technique also applies its effects even if the attack misses or is partially resisted. Some Techniques, mostly magical ones, affect all characters in the combat or all characters allied with the attacker or defender.

The three tiers of Technique are simply Tier 1, Tier 2, and Tier 3, which cost 2 TP, 4 TP, and 6 TP respectively. Most techniques affect the Light and Heavy damage an attack does (raising or lowering either or both), and all have an additional affect that usually changes the Offense and Defense tracks in some way. For example, the Tier 2 Technique **Furious** makes an attack deal -4 Light damage, +6 Heavy damage, and raises the attacker's Offense by 2 steps when declared. Another example is the Tier 1 Technique **Deceitful**, which makes an attack deal +4 Light damage, -3 Heavy damage, and if the defender has a Defense penalty when declared, that penalty becomes `---`.

Outside of combat, the Tier of a Technique doesn't matter, and how they are applied uses some creative thinking from the Players. Each Technique lists some cases where it could be used as a benefit, and some cases where it could be used as a handicap (to earn Favor Dice, regardless of the result of the skill). If a technique applies as a benefit, it grants +2 to the skill result. If a technique applies as a handicap, the Player can opt to take -4 to the skill result, and the Player gains a Favor die after the skill resolves. If there isn't a clearly applicable Technique a PC knows for a situation, but their Player has a good idea for how one they do know could apply, they can try to persuade the Narrator that it applies by taking a -1 penalty on the skill result. If the Narrator agrees that it applies, the normal rules apply on top of the -1 penalty for "off-label usage." In the case of the **Furious** Technique mentioned earlier, it can apply as a benefit if the character needs to look intimidating or break something, or apply as a handicap if a task is especially annoying or frustrating. In the case of the **Deceitful** Technique, it can apply as a benefit to any tasks involving lying or trickery, or apply as a handicap if the character's reputation is in question or the character is trying to convince someone they are telling the truth.

Techniques that work using supernatural powers may have special rules regarding out-of-combat uses. A Technique like **Scorching**, which creates and controls fire, is rather versatile and applies as a benefit in a wide variety of situations. Being able to manipulate fire can be intimidating, can be used to destroy objects, can create distractions, can be used to create warmth and light, and so on. As a counterbalance to this, **Scorching** and several other supernatural Techniques can be applied as a handicap at the Narrator's option, rather than when the player chooses. This only can happen if that Technique has been applied a benefit already in that situation. In this case, using fiery magic can start extra fires unintentionally, often at inopportune times. A Technique like **Dazing**, which uses psychic power to affect someone's mind, is also versatile, and can also be applied as a handicap at the Narrator's option after it has applied as a benefit. In this case, the handicap is special, and while it still gives the player a Favor die, it doesn't impose a penalty or grant the Favor die immediately. Using psychic powers alerts nearby supernatural characters, who can impose the handicap when they interact with the psychic character (granting Favor dice to the psychic then).

### Normal Techniques (In-Combat)

Tier 1         | Light | Heavy | Special
---------------- | ------ | ------ | ----------------------------------------------------------------------
Angry            | -4     | +5     | Before: Your Offense improves by 1 step.
Cautious         | +1     | +0     | Before: Your Defense improves by 1 step.
Taxing           | +2     | +3     | After: Your Offense worsens by 1 step.
Reckless         | +0     | +5     | After: Your Defense worsens by 1 step.
Smug             | -2     | +1     | Before: The target's Offense worsens by 1 step.
Probing          | +4     | -3     | Before: The target's Defense worsens by 1 step.
Calm             | -1     | -2     | Before: If you have an Offense penalty, set it to `0`.
Quick            | +2     | -2     | Before: If you have a Defense penalty, set it to `0`.
Fierce           | -3     | +1     | Before: If you have an Offense penalty, flip it to a bonus.
Steadfast        | -2     | +0     | Before: If you have a Defense penalty, flip it to a bonus.
Deceitful        | +4     | -3     | Before: If the target has a Defense penalty, set it to `---`.
Gripping         | +0     | +0     | Before: Set the target's Offense and Defense both to `0`.

