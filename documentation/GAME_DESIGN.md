# Game Design Document

> **Project:** Pokémon Emerald — Expanded and Reimagined (working description)  
> **Status:** Living design document  
> **Foundation:** `pokeemerald-expansion`

## 1. Project Vision

### 1.1 Overview

This project is an expanded and reimagined version of **Pokémon Emerald**, developed using the `pokeemerald-expansion` decompilation project.

Its primary objective is to deliver a complete, cohesive, and satisfying Generation 3 Pokémon experience while preserving the identity, atmosphere, and charm of the original Hoenn adventure.

Inspired by projects such as **Pokémon Polished Crystal** and **Pokémon Emerald Legacy**, the game aims to realize the potential of the original experience through expanded storytelling, improved gameplay systems, greater Pokémon availability, and purposeful Pokémon improvements that preserve meaningful differences in power and role.

Rather than replacing Pokémon Emerald with an entirely different game, the project seeks to build upon its existing foundations and create an experience that feels like a natural evolution of the original.

### 1.2 Design Philosophy

The project follows five guiding principles.

#### Preserve Emerald's Identity

Hoenn's geography, characters, major story events, and overall progression should remain recognizable.

Changes should primarily expand, refine, or improve existing elements rather than replace them without a compelling reason.

#### Deliver a More Complete Adventure

The original game introduces numerous characters, locations, and gameplay possibilities that could benefit from further development.

The project aims to explore this untapped potential through additional character interactions, meaningful battles, expanded progression, and rewarding postgame activities.

#### Make More Pokémon Worth Using Without Equalizing Their Power

Pokémon that are frequently overlooked because of weak statistics, limited movepools, or restrictive mechanics should receive carefully considered improvements.

The objective is **not** to make every Pokémon equally powerful. Different species should retain distinct strengths, weaknesses, and roles. Pokémon such as Ledian or Pidgeot need not rival Salamence in raw power to become more enjoyable or useful choices. 

Here's an example of power balancing:
I was always frustrated that Fearow is so much better than Pidgeot stat wise while being a 2 stage evolution evolving at level 20 while Pidgeot has to wait until level 36 to reach its final stage. That doesn't mean nerf Fearow, but buffing Pidgeot to a reasonable degree. Also Fearow will be way stronger than Pidgeotto in this example, but weaker than Pidgeot.

Legendary Pokémon should feel exceptional. Particularly powerful legendary Pokémon—including Rayquaza, Kyogre, Groudon, Mewtwo, Lugia, and Ho-Oh—are intended to occupy a higher power tier than ordinary Pokémon. Preserving that distinction is a deliberate design choice, not a balancing failure.

#### Encourage Strategic Gameplay

Battles should reward understanding type matchups, building balanced teams, and adapting strategies.

The game should offer a greater challenge than vanilla Emerald without requiring competitive Pokémon expertise or relying on excessive difficulty.

#### Respect the Player's Time

Unnecessary grinding, excessive randomness, and inconvenient mechanics should be reduced where possible.

Quality-of-life improvements should make the experience more enjoyable without eliminating meaningful challenges or undermining progression.

### 1.3 Target Audience

The project is intended for Pokémon players of all experience levels, from newcomers to long-time veterans.

While the original Pokémon Emerald can often be completed through straightforward strategies, including relying heavily on a single overlevelled Pokémon, this project aims to encourage greater engagement with the battle system.

Players should be willing to learn and apply the game's mechanics, but should not need extensive prior knowledge, competitive training experience, or highly optimized teams to complete the main adventure.

Optional endgame challenges may demand significantly greater mastery of the battle system.

### 1.4 Intended Player Experience

The ultimate goal is to create a version of Pokémon Emerald that feels like the ideal Generation 3 adventure: familiar enough to evoke the original experience, yet expanded and polished enough to feel substantially more complete.

Players should experience a richer Hoenn region, encounter characters whose journeys continue beyond their original roles, discover more opportunities to use their favorite Pokémon, and find meaningful challenges throughout the adventure.

The project prioritizes cohesion over sheer content volume. Additional features should contribute positively to the overall experience rather than exist solely for the sake of adding more content.

Upon completing the adventure, players should feel that they have experienced a definitive interpretation of Pokémon Emerald and the Hoenn region.

---

# Story and Characters

> **Document status:** Living design document. Narrative directions marked **Confirmed** have been agreed in design discussion; **Proposed** elements are working ideas; **Undecided** details require later review.
>
> **Integration:** This is a standalone companion to `GAME_DESIGN.md`. It does not replace existing project files or supersede local edits.

## 2.1 Overall Story Direction

The project retains the original Pokémon Emerald storyline as its foundation, expanding existing events and character arcs rather than replacing the narrative with an entirely new adventure.

The player's journey through Hoenn, the Gym Challenge, the conflict between Team Magma and Team Aqua, and the pursuit of becoming Champion remain central to the experience.

### Narrative Expansion

The original story introduces several characters with significant potential for further development. The project aims to give these characters more meaningful roles, additional interactions, and clearer personal motivations.

Characters should have their own ambitions, relationships, and development beyond their encounters with the player. Their stories should progress naturally alongside the player's journey.

Additional dialogue, encounters, and battles should reinforce this development without unnecessarily interrupting gameplay.

### Continuity and Progression

The major events and general sequence of the original Pokémon Emerald storyline should remain recognizable.

New events may be introduced, and existing events may be expanded or adjusted where doing so improves narrative consistency, character development, or gameplay progression.

Changes should feel like natural extensions of the original adventure rather than disconnected additions.

### Character Roles and Narrative Flexibility

While the original storyline provides the foundation for the project, established character roles, relationships, and responsibilities may be adjusted when doing so creates a more cohesive and satisfying narrative.

Such changes should be supported by appropriate character development and in-game events, ensuring that new roles feel earned rather than arbitrary.

Preserving the spirit of Pokémon Emerald takes precedence over reproducing every detail of its original narrative structure.

### A Living World

Hoenn should feel like a region whose inhabitants continue to grow and pursue their own goals.

Rivals, Gym Leaders, Champions, and other important characters should not become irrelevant simply because the player has completed their original storyline.

Where appropriate, characters may return through new encounters, rematches, dialogue, or postgame activities that reflect their continued development.

### Storytelling Philosophy

The project prioritizes meaningful character development over excessive dialogue or unnecessary exposition.

Narrative additions should enrich the player's understanding of Hoenn and its inhabitants while preserving the exploration-focused pacing of Pokémon Emerald.

## 2.2 Brendan/May and Wally — Agreed Narrative Direction

Brendan/May and Wally serve as the player's two principal rivals, each following a distinct path of personal development. Their stories gradually become interconnected, but each retains independent motivations and goals.

### Brendan/May — Rival and Mentor

Brendan/May initially serves as the player's primary friendly rival. As the adventure progresses, Brendan/May also helps Wally improve as a Trainer, alongside Norman. This mentorship is initially hidden from the player.

Brendan/May's development continues beyond the main adventure, with a more extensive Battle Frontier role to be documented separately under postgame design.

### Wally — From Inexperienced Trainer to Champion Aspirant

Wally initially wants to become a capable Pokémon Trainer. His early motivation is to improve his skills, gain confidence, and learn what he can accomplish.

As he recognizes his limitations, Wally seeks guidance. His mentorship under Norman and Brendan/May supports his growth but does not replace his own determination and effort.

Only after developing as a Trainer and recognizing his potential does Wally set his sights on becoming Pokémon Champion. This ambition emerges from his journey rather than motivating it from the beginning.

Wally eventually becomes the player's most significant rival near the end of the main adventure, culminating in an important confrontation near the Pokémon League. **He does not become Champion before the player.** His personality should remain recognizably kind and respectful as his confidence grows.

### The Hidden Mentorship — Confirmed Structure

1. **Established connection:** Norman's original assistance with Wally's first Pokémon and their proximity in Petalburg make him an obvious possible mentor, but ongoing mentorship is not explicitly confirmed.
2. **Two mentors:** Wally mentions receiving guidance from *two* mentors, without identifying either. Players may suspect Norman while wondering about the second person.
3. **Subtle clue:** The player encounters Wally interacting with Brendan/May in a way that suggests a training relationship, without explicit confirmation.
4. **Revelation:** The identities of both mentors are eventually confirmed. Brendan/May has been helping Wally grow as a Trainer, and later supports his ambition to become Champion.

Brendan/May knows about Wally's Champion ambition **before the player learns of it**, reflecting their close relationship and regular interactions. The player's discovery is not the moment Wally decides on his goal.

**Undecided:** Exact event locations, dialogue, reveal timing, and whether Wally's participation in the Gym Challenge is explicitly shown or stated. His Champion ambition implies appropriate League qualification, but this need not be spelled out immediately.

## 2.3 Norman and Professor Birch — Limited Expanded Roles

Neither Norman nor Professor Birch requires a major new character arc. Their established personalities and responsibilities should be preserved, with selected postgame interactions where they contribute meaningfully.

### Norman — Wally's Mentor and Eon Ticket Intermediary

**Confirmed narrative direction:** Norman's continuing mentorship of Wally can remain implicit until the mentorship revelation. Additional early exposition is unnecessary.

After the player becomes Champion, Norman delivers the **Eon Ticket** on Latios's behalf. This is strictly a **postgame** event, granting access to Southern Island and a challenging Latios encounter. The reason Latios extends this invitation is developed in the Eon Pokémon storyline below.

**Undecided:** How Latios contacts Norman, the presentation of the ticket handoff, and any additional postgame prerequisites.

### Professor Birch — Johto Starter Rewards

**Proposed reward progression (not finalized):**

| Milestone | Birch's reward |
| --- | --- |
| First Pokémon League victory and National Pokédex unlock | Player chooses one of Chikorita, Cyndaquil, or Totodile |
| Completion of the first postgame Gym Leader rematch cycle | Player chooses one of the two remaining Johto starters |
| Victory over the postgame Elite Four and Champion | Player receives the final remaining Johto starter |

This provides all three Johto starters in one save without trading, while allowing the player to choose their acquisition order.

**Open consideration:** The Johto starters could alternatively or additionally appear as wild encounters in suitable postgame areas. However, this could reduce the significance of Birch's rewards; Birch-exclusive acquisition is currently a plausible preference, not a final decision.

### Other Starter Pokémon — Early Ideas

- **Hoenn:** The player receives the usual starting Pokémon. Brendan/May might later provide an Egg of their starter, and Birch might provide the last starter needed to complete the trio. Exact timing and rival-starter assignment require design.
- **Kanto:** A distinct acquisition storyline or progression may be created for the three Kanto starters.

These ideas belong primarily in Pokémon availability/progression documentation and are **not confirmed**.

## 2.4 The Eon Pokémon — Latias and Latios

> **Status:** Core narrative direction agreed; precise event implementation and several mechanics remain undecided. This storyline is placed here provisionally and may later move into a dedicated Legendary Pokémon section.

### Timing and Premise

The original roaming encounters for Latias and Latios are replaced by scripted events.

The major Latias event occurs **before the Mossdeep Gym**, preferably between **Fortree and Lilycove**, or alternatively between **Lilycove and Mossdeep**. It should occur before Team Magma and Team Aqua have moved into their Groudon/Kyogre encounter sequences.

### Act 1 — The Teams' Pursuit

Team Magma targets **Latias** and Team Aqua targets **Latios**, seeking their assistance in acquiring Groudon and Kyogre respectively.

Team Magma succeeds in capturing Latias. Latios, portrayed as stronger than Latias within this storyline, overpowers Team Aqua's forces and rushes to rescue Latias.

### Act 2 — Latias's Rescue

The player intervenes against Team Magma, rescues Latias, and earns her deep trust. Latias willingly joins the player and becomes obtainable during the main adventure.

Latias's bond with the player is a **narrative relationship**, not something dependent on keeping her in the active battle party.

### Act 3 — Latios's Misunderstanding

Latios arrives to find Latias with the player and mistakenly assumes the player has captured or exploited her. Enraged, Latios prepares to attack.

A sudden seismic disturbance interrupts the confrontation, startling Latios and causing it to withdraw. The disturbance could foreshadow Groudon, Kyogre, or Rayquaza awakening; **its cause is undecided**.

### Act 4 — Trust and Recognition

Latios's misunderstanding resolves **off-screen**. Through observing Latias's trust in the player, possibly supplemented by telepathic communication, Latios comes to accept that Latias is with the player willingly. Latios does **not** need to explicitly learn every detail of her rescue.

The player's eventual rise to Champion reinforces Latios's respect but is **not the sole reason** for its change of heart.

After the player becomes Champion, Latios reaches out to Norman and arranges for delivery of the Eon Ticket. Receiving the ticket is the player's **first indication** that Latios has changed its opinion. Southern Island hosts the culminating, more challenging postgame Latios encounter.

### Potential Battle Ability — Eon Soul

**Proposed, not confirmed:** Latias and Latios could share an ability named **Eon Soul**, providing a synergistic benefit when both are on the same side of a Double Battle, conceptually similar to Plus/Minus.

The effect, magnitude, activation rules, and whether it replaces Levitate are undecided. Losing Levitate would remove their Ground immunity and must be considered alongside their already substantial power.

### Open Story Questions

- Exact map locations and cutscene staging
- How the teams intend to exploit each Eon Pokémon
- The nature of Latias's capture and voluntary joining
- The seismic disturbance's cause
- How Latios contacts Norman and how the ticket is presented
- Southern Island encounter design and Latios's level/strength

## Gameplay Note — HMs and Latias-Assisted Fly

> **Status: Proposed; not a finalized system.** This note should eventually move to the gameplay/quality-of-life documentation.

Traditional **HMs remain available as HMs**. The project may also provide alternative tools or Pokémon-assisted field abilities so players are not forced to dedicate a party slot or move slot to an unwanted field move.

One proposed alternative is **Latias-assisted Fly**, unlocked through the player's relationship with Latias after her rescue. It would function as ordinary Fly for travel purposes, **including the existing destination restrictions**: a location such as Sootopolis cannot be selected before it has been visited/unlocked through normal progression.

Latias would **not need to be in the active party** for this assistance.

**Undecided:** Whether every HM receives an alternative, when the Fly alternative unlocks, exact controls/presentation, and whether other field tools are items, Pokémon abilities, or separate mechanics.

---

## Review and Integration Notes

- **Approved:** Section 2.1, including narrative flexibility regarding character roles.
- **Agreed direction:** Wally's gradual ambition, the two-mentor mystery, Brendan/May knowing his ambition early, and the Latias/Latios relationship and postgame Latios resolution.
- **Proposed:** Birch's starter milestone rewards, other starter acquisition ideas, Eon Soul, HM alternatives, and Latias-assisted Fly.
- **To review later:** Steven/Wallace/Juan roles, Team Magma/Aqua details beyond the Eon storyline, Battle Frontier character arcs, exact story scripting, and implementation feasibility.

## 3. Pokémon and Gameplay

*To be drafted and reviewed. Topics include Pokédex availability without trading, alternative evolution methods, selective species improvements, legendary power tiers, and battle mechanics.*

## 4. Progression and Rematches

*To be drafted and reviewed. Topics include Gym Leader rematches, VS. Seeker and Match Call coexistence, and story-gated trainer team tiers.*

## 5. Postgame and Battle Frontier

*To be drafted and reviewed. Topics include a redesigned Battle Palace, Brendan/May as Frontier Brain, Spenser's role, shorter Gold Symbol requirements, repeatable rematches, and optional completion rewards.*
