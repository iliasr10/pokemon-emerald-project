# Design Decisions and Open Questions

> Working record of discussions. **Confirmed direction** means the overall intent is agreed; details may still require design and testing. This file is not a substitute for reviewed GDD sections.

## Confirmed directions

| ID | Topic | Decision |
| --- | --- | --- |
| D01 | Identity | Expanded and reimagined Emerald, preserving its recognizable foundation. |
| D02 | Audience | Pokémon players of all experience levels who engage with game mechanics; more challenging than vanilla, not Kaizo. |
| D03 | Player experience | A cohesive, satisfying, definitive-feeling Gen 3 adventure; references include Polished Crystal and Emerald Legacy. |
| D04 | Completeness | Develop underused characters and make the intended Pokédex obtainable within one game without trading or version exclusives. |
| D05 | Narrative | Expand the existing Emerald story rather than fundamentally rewrite its major sequence. |
| D06 | Rivals | Wally grows into the endgame rival; Norman and Brendan/May mentor him, with Brendan/May's mentorship initially concealed. Wally need not become Champion before the player. |
| D07 | Brendan/May | Pursue Battle Frontier mastery and eventually succeed Spenser as Frontier Brain of the redesigned Battle Palace; remain relevant after Gold Symbol completion. Specific events are subject to further design. |
| D08 | Frontier philosophy | Much harder than the main story, but more approachable and less time-consuming than vanilla; prioritize strategy over long RNG-heavy streaks. |
| D09 | Frontier rewards | Gold Symbols unlock Frontier Brain contact/rematches. The Frontier remains optional for the main story and Pokédex; no legendary is locked behind it. |
| D10 | Frontier battles | Introductory Silver Symbol battles, shorter challenges toward Gold, indefinitely replayable facilities; facility battles use smaller teams, external rematches use full six-Pokémon teams. |
| D11 | Trainer rematches | VS. Seeker offers guaranteed on-demand overworld rematches; Match Call remains for Gym Leaders, important trainers, and its existing overworld uses. Both share trainer progression. |
| D12 | Rematch tiers | Global story checkpoints unlock tiers; each trainer uses their strongest defined team at or below the unlocked tier. Trainers may skip tiers; no prerequisite rematch chain. |
| D13 | Pokémon balance | Improve underused Pokémon for meaningful roles without equalizing species; exceptionally powerful legendaries should remain a distinct higher power tier. |

## Battle Frontier: working detail

- Brendan/May is the redesigned facility's Frontier Brain for **both** Silver and Gold Symbol battles.
- Spenser appears twice in connection with facility progress: an introductory evaluation during the facility's transition, and another evaluation before the final Gold Symbol challenge.
- Spenser's encounters unlock his contact information; the precise timing is still to be defined.
- The new facility replaces the RNG-heavy Battle Palace, but its battle gimmick has not been chosen.
- Gold Symbol rewards may include repeatable external Frontier Brain battles and access to a convenience-oriented postgame shop.

## Rematches: working detail

- VS. Seeker recharge is intended to be very short (approximately 0–10 steps), not yet finalized.
- VS. Seeker acceptance should be guaranteed for eligible trainers.
- Trainer team changes are triggered by story checkpoints, **not** the number of rematches completed.
- A trainer with Tier 1 and Tier 4 teams keeps Tier 1 when global Tier 2 or 3 unlocks, then switches directly to Tier 4 when that milestone is reached.

## Open questions and tentative ideas

| Topic | Open question / proposal |
| --- | --- |
| Battle Frontier facility | What replaces the Battle Palace's battle mechanic? |
| Frontier pacing | Exact battle counts, consecutive-win requirements, and per-facility formats. |
| Spenser | Exact sequence of evaluations and when his repeatable rematch unlocks. |
| Frontier rewards | Possible unlimited Master Ball shop, Rare Candies, evolutionary items, and remaining TMs; exact prices and unlock conditions. |
| TMs | Reusable TMs from the beginning are under consideration; not yet finalized. |
| Legend Ball | Possible specialized legendary-catching ball; currently considered probably unnecessary. |
| VS. Seeker | Final recharge amount and any trainer-specific exceptions. |
| Rematch checkpoints | Which story events unlock the global team tiers? Four tiers are a working model. |
| Story | Specific scenes, rival encounters, dialogue, and character arcs beyond the established directions. |
| Legendary encounters | Encounter difficulty, catch rates, and individual events remain to be designed. |

## Documentation convention

- **Confirmed:** Intent explicitly agreed in discussion.
- **Proposed:** Plausible design not yet approved.
- **Open:** Requires a decision or investigation.
- **Implementation verified:** Reserve this label for behavior actually checked in the codebase or game.
