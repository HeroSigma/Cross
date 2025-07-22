# Region Progression Plan

This document outlines the proposed structure for progressing through Hoenn, Kanto and Johto in **Pokémon Crossroads**. The goal is to maintain a stable codebase while offering a clear narrative flow.

## 1. Solve Technical & Script Glitches
- Remove multi-region intro support to prevent crashes and softlocks.
- Maintain a single clean intro sequence with Professor Birch in Hoenn.
- Treat Kanto and Johto as fully scripted post‑game zones to avoid early branching complications.

## 2. Provide Natural, Linear Progression
- Players earn entry to each region by defeating that region's Pokémon League.
- Each region functions like a new "season" with higher difficulty.
- Focus the player on one objective at a time to reduce open‑world fatigue.

## 3. Support Hardcore Difficulty Scaling
- Hoenn: levels 5–70
- Kanto: levels 70–90
- Johto: levels 90–100
- No region reset in difficulty; each area builds on the previous one.

## 4. Integrate All Major Rivals
- May/Brendan, Red, Blue, Green, Gold, Silver and Lyra appear with dialogue and personality.
- Rival battles are staggered across regions for better pacing.
- Use rivals for ambushes, tournaments and story beats.

## 5. Make Starters Feel Special
- Pikachu or Eevee starters are exclusive to the player and cannot evolve.
- Red and Gold keep their classic starters for canonical consistency.
- Consider unique moves, ribbons or events tied to the player's starter.

## 6. Increase Player Investment
- Each region acknowledges the player's prior victories.
- A new starter from a new professor acts as a reward and adds lore depth.

## 7. Build a Narrative Arc Across Generations
- **Hoenn**: the player's origin.
- **Kanto**: the legacy of Red, Blue and Green.
- **Johto**: the future represented by Gold, Silver and Lyra.
- Culminate in a final encounter featuring all rivals or a multi‑region champion challenge.

## 8. Allow Post‑League Unlocks Instead of HMs
- New regions unlock after League victories, not by obscure NPCs or HM usage.
- Enables precise control over story triggers.

## 9. Keep a Cleaner Codebase
- Use region entry flags such as `FLAG_BEAT_HOENN_LEAGUE`.
- Simplifies testing and prevents overlapping event trees.

## 10. Create an Epic Three‑Part Game
- **Hoenn** as the beginning.
- **Kanto** as the legacy chapter.
- **Johto** as the culmination of the adventure.
- Combines the feel of three games into one coherent experience.

