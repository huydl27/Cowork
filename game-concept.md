# Game Concept: Flapster — A Flappy Bird-Inspired Mobile Game

**Genre:** Casual Arcade
**Platform:** Mobile (iOS & Android)
**Target Audience:** Casual gamers, ages 8 and up
**Session Length:** 1–3 minutes per run

---

## Overview

**Flapster** is a casual endless runner inspired by the classic Flappy Bird formula — simple one-touch controls, pixel-perfect timing, and addictive replayability. The game retains the familiar side-scrolling bird-and-pipe aesthetic but introduces a **power-up system** that adds strategic depth and variety to each run, keeping players engaged beyond pure muscle memory.

---

## Core Gameplay Loop

1. **Tap to flap** — The player taps the screen to keep the bird airborne against gravity.
2. **Navigate pipe gaps** — Horizontally scrolling pipe pairs generate at varied heights; the player must thread through the gaps.
3. **Collect coins** — Small coins float between pipes, rewarding skillful navigation.
4. **Activate power-ups** — Certain coins are replaced by glowing orbs that grant temporary abilities.
5. **Score & repeat** — Upon collision, the run ends, a score is displayed, and the player is prompted to try again.

---

## Power-Up System

Power-ups are the key differentiator of Flapster. They spawn randomly among pipes (roughly every 5–10 gaps) and are collected by flying through them. Only one power-up can be active at a time.

| Power-Up | Icon | Duration | Effect |
|---|---|---|---|
| **Shield** | 🛡️ | 1 hit | Absorbs a single pipe collision; the bird flashes briefly then continues |
| **Slow-Mo** | ⏱️ | 5 seconds | Reduces scroll speed by 50%, giving the player breathing room |
| **Magnet** | 🧲 | 8 seconds | Automatically attracts nearby coins to the bird |
| **Ghost** | 👻 | 3 seconds | Bird becomes semi-transparent and passes through one set of pipes |
| **Double Score** | ⭐ | 10 seconds | All points earned are multiplied by 2 |

Power-up orbs are visually distinct from coins — they pulse with a glow effect and emit a short particle burst when collected. A small icon and countdown timer display in the top corner while a power-up is active.

---

## Controls

| Action | Input |
|---|---|
| Flap | Single tap anywhere on screen |
| Pause | Tap the pause icon (top-right corner) |

Controls are intentionally minimal — the entire game is playable with one thumb.

---

## Progression & Scoring

- **Score** is based on the number of pipe pairs successfully passed.
- **Coins** add a secondary currency score tracked separately.
- **Milestones** unlock cosmetic rewards at scores of 10, 25, 50, and 100.
- **Daily Best** and **All-Time Best** are stored locally and optionally synced to a leaderboard.

### Difficulty Scaling
The game gradually ramps up as the player's score increases:

| Score Range | Scroll Speed | Gap Size | Power-Up Frequency |
|---|---|---|---|
| 0–9 | Slow | Wide | Common |
| 10–24 | Medium | Medium | Moderate |
| 25–49 | Fast | Narrow | Rare |
| 50+ | Very Fast | Narrow | Very Rare |

---

## Visual Style

Flapster sticks close to the original Flappy Bird aesthetic:

- **Art Style:** Retro pixel art, warm color palette (greens, blues, earth tones)
- **Character:** A small round bird with expressive eyes, slightly animated wing flap cycle
- **Pipes:** Classic green pipe design with subtle shadow/depth
- **Backgrounds:** Parallax-scrolling sky with drifting clouds; sky color shifts subtly at score milestones (dawn → day → dusk → night)
- **UI:** Clean, minimal HUD — score counter at top-center, power-up icon at top-left, pause button at top-right

---

## Audio Design

- **Background Music:** Upbeat, looping chiptune track — energetic but not distracting
- **SFX:**
  - Wing flap — soft flutter sound on each tap
  - Coin collect — classic 8-bit "ding"
  - Power-up collect — distinct chime per power-up type
  - Pipe hit / death — short impact sound + brief screen shake
  - New high score — celebratory fanfare

---

## Monetization (Optional Layer)

Since this is a casual mobile game, the following light monetization hooks can be considered:

- **Cosmetic Bird Skins** — Purchasable or earnable through milestones; purely visual, no gameplay impact
- **Continue Token** — After a death, the player may watch a short ad to resume once from their last position
- **Coin Doubler** — Optional IAP that permanently doubles coins earned per run

*No pay-to-win mechanics. All power-ups remain earned through gameplay only.*

---

## Unique Selling Points

1. **Familiar yet fresh** — Instantly recognizable Flappy Bird feel, but power-ups add "just one more run" moments.
2. **One-thumb accessibility** — Zero learning curve; anyone can pick it up in seconds.
3. **Replayability** — Random power-up spawns and difficulty scaling ensure no two runs feel identical.
4. **Cosmetic depth** — Bird skins give players a reason to keep playing without affecting fairness.

---

## Competitive Landscape

| Title | Differentiator vs. Flapster |
|---|---|
| Flappy Bird (original) | No power-ups, no progression hooks |
| Flappy Golf | Different control scheme; golf theme |
| Swing Copters | Pendulum mechanic; steeper difficulty |
| Jetpack Joyride | More complex; deeper systems; longer sessions |

Flapster occupies the sweet spot: **pure simplicity with just enough variety** to keep sessions lasting and players returning.

---

## Next Steps for Development

- [ ] Prototype core flap-and-pipe mechanic in Unity / Godot
- [ ] Design and test all 5 power-up feel and balance
- [ ] Create pixel art asset set (bird, pipes, backgrounds, UI)
- [ ] Implement difficulty scaling curve and playtest
- [ ] Soft launch on TestFlight / Google Play Internal Testing

---

*Document version: 1.0 — March 2026*
*Game Designer: Huy Dinh*
