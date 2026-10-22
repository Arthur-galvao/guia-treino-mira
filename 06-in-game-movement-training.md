---
title: In-Game Movement Training
---

[English](06-in-game-movement-training.html) | [Português](06-treino-in-game-movimentacao.html)

# In-Game Movement and Mechanics Training, by KoreyVAL

This plan focuses on integrating fine mouse control with in-game movement inside Valorant, establishing clean peek mechanics, counter-strafing, and crisp crosshair snappiness.

## General Guidelines

Perform this routine either after your ranked matches or several hours before. Never use this routine as a rushed pre-game warm-up. Always select Jett in The Range to enable rightward Dash repositioning during the 50-elimination drill. Expected duration: 15 to 20 minutes daily.

Remain at least 3 days on each level before advancing. Avoid autopiloting: actively deliberate on your technique throughout each exercise and Deathmatch. Do not use a metronome during regular training; employ it solely at the conclusion of a block to evaluate benchmark readiness for the next tier.

## Level 0: Foundation Building (Optional Prerequisites)

Before tackling the progression tiers below, aim to meet these baseline indicators: Gold or higher in Valorant, 100% accurate 2-shot bursts against the wall at approximately 75 BPM, solid raw aim (e.g. Voltaic Gold or Viscose Benchmarks v1 Mammoth in KovaaK's), and consolidated basic counter-strafing.

## Level 1.0 (Recommended for Platinum+)

- **Perfect Movement Accuracy Drill (The Range, 3 minutes):** Exclusively 2-shot bursts. Start slowly and accelerate tempo as comfort solidifies. Initially aim for 100% accuracy; once fluidity is mastered, sustain 80%+.
- **50 Elims in The Range (2 sets):** Use Jett's Dash to the right and apply the identical 2-shot burst technique across bots.
- **2 Natural Deathmatches:** Play focusing on how your movement dynamics stabilize your aim, without forcing artificial overaim technique.
- **Advancement Criteria to Level 1.5:** Comfortably executing the Range drill at ~75 BPM under metronome verification, minimal misses attributable to movement inaccuracy, and observable movement synergy aiding crosshair placement in Deathmatch.

## Level 1.5 (Recommended for Platinum+)

- **Perfect Movement Accuracy Drill (The Range, 2 minutes):** 2-shot bursts, emphasizing fluidity and maintaining 80%+ accuracy.
- **Snappiness Drill with 2-Shot Bursts (The Range, 1 minute):** Mentally visualize "slicing the pie." Move in the same direction on several eliminations to simulate clearing angles, and alternate directions on others to practice sudden stops. As soon as your crosshair touches the bot's head, execute the counter-strafe, come to a complete stop, and fire at your own cadence.
- **50 Elims in The Range (2 sets):** Dash right, 2-shot bursts with precision movement technique.
- **2 Natural Deathmatches:** As comfort allows, incorporate snappiness into initial bursts. If the initial burst does not secure the elimination, immediately transition into continuous evasive movement.
- **Advancement Criteria to Level 2.0:** Executing the Range drill at ~88 BPM under metronome testing, nearly zero movement errors, with initial bursts feeling instant, firm, and snappy.

## Level 2.0 (Recommended for Ascendant+)

- **Snappiness Drill with 2-Shot Bursts (The Range, 2 minutes):** Slice angles, counter-strafe precisely when crosshair contacts target head, and fire the burst.
- **50 Elims in The Range (2 sets):** Dash right, apply rapid snappiness mechanics to each bot.
- **Visual Error Practice / Shadowing (The Range, 30 seconds):** Spend this final segment visualizing contingency transitions when the first burst misses, instantly reverting into active movement.
- **1 Deathmatch with angle-clearing prefire (initial 1-2 days of tier):** Focus entirely on tactile hand feeling and kinetic movement, rather than whether the prefire connects with opponents.
- **1-2 Deathmatches with high-intention stopping windows:** Apply deliberate stopping windows while clearing angles. Each time you stop, actively visualize the weapon discharging.
- **Advancement Criteria to Level 2.5:** Consistent feeling that the majority of initial DM bursts are snappy and identical to Range execution.

## Level 2.5 (Recommended for Immortal+)

- **Tap Snappiness Drill (The Range, 1 minute):** Single-bullet taps at an accelerated tempo, sustaining 80%+ accuracy. If a tap misses, remain locked on the same target until eliminated; do not abandon the target.
- **50 Elims in The Range, Tapping Technique (3 sets):** Dash right, apply single taps with snappy mechanics and angle-clearing visualization.
- **Visual Error Practice / Shadowing (The Range, 30 seconds):** Rehearse transition to active evasive repositioning if the initial tap fails.
- **2 Deathmatches with stopping windows and tapping:** Apply stopping windows clearing angles with full deliberate intent.
- **Advancement Criteria to Level 3.0:** Fluid, natural first-bullet snappiness and effortless comfort with tapping execution.

## Level 3.0 (Recommended for Immortal+)

- **Range Freestyle with Practice Bots Center (3 minutes):** Fluidly alternate between tapping, crouch-tapping, and snappiness, exploring total mechanical freedom.
- **50 Elims in The Range, Evasive Mode (2 sets):** Dash right, maximize evasive maneuvers, utilizing micro-movements and incorporating crouch-taps.
- **50 Elims in The Range, Natural Movement (2 sets):** Reduce conscious deliberation. Shoot as in authentic high-stakes matches, assuming the bot returns fire, and let muscle memory drive execution. Target ~90% first-shot accuracy.
- **2 High-Intention Deathmatches:** Integrate tapping and micro-crouches seamlessly into initial shot snappiness, minimizing transition latency into follow-up bursts if choosing an initial tap over a burst.

---

## Netcode Foundations, Peeker's Advantage, and Duel Geometry

### 1. Biological Reaction Time vs. The Mathematics of Peeker's Advantage

- **Simple Reaction Time (SRT):** While the average adult exhibits a visual SRT between **200 and 250 ms**, professional FPS players operate within **150 to 180 ms** (median **165 ms**). Auditory stimuli are processed by the cortex **40 to 50 ms faster** than visual stimuli—which is why footstep audio cues dramatically accelerate pre-fire timing.
- **Peeker's Advantage:** Due to client-server-client network latency and entity interpolation buffers:
  - Even under ideal, symmetric low-ping conditions, an attacker swinging an angle at full velocity holds a structural **63 to 68 ms** advantage before rendering on a stationary defender's screen.
  - In real online matches (CS2 / Valorant), compound peeker's advantage ranges between **39 and 218 ms**, and can reach **229 to 270 ms** under severe ping asymmetry—exceeding human biological reaction time itself.

### 2. Crosshair Placement and Wide-Swing Offset

By Fitts's Law ($MT = a + b \log_2(2A/W)$), optimal *Crosshair Placement* reduces distance $A$ toward zero, eliminating the need for a wide ballistic flick. However, because *Peeker's Advantage* (~65 ms+) stacks with your own biological reaction time (~165 ms), **never passively hold a common angle with your crosshair glued tightly to the wall edge**:

- **Wide-Swing Offset:** When holding an angle against an opponent likely to swing at full speed (*wide swing*), offset your reticle horizontally from the corner by the distance an enemy model travels during `SRT + Peeker's Advantage` (~220 ms). The opponent will run directly into your crosshair at the exact millisecond your finger clicks.
- **Tight Placement:** Only hold your crosshair tight against the wall corner when anticipating a shallow information *jiggle peek*, or when you are the one actively *slicing the pie*.
- **Defensive Tactical Mitigation:** To neutralize the attacker's *Peeker's Advantage*, hold *off-angles* (positions outside the attacker's standard pre-aim path) or perform periodic defensive *jiggle peeks* behind cover, making yourself the peeker in the server's timeline.

### 3. Movement Geometry: Mirroring vs. Anti-Mirroring

During mid-to-long-range duels or extended exchanges in *Tracking* / *Dynamic Clicking* scenarios:

- **Mirroring:** You strafe in the **same world direction** as your opponent (e.g., as they move to your right, you press `D`). Relative angular velocity cancels out almost completely, making the target appear nearly stationary on your screen. This vastly simplifies your shot, **but equally simplifies the enemy's shot against you**. Use *Mirroring* when you hold a health/weapon advantage or have already landed the opening tag.
- **Anti-Mirroring:** You strafe in the **opposite direction** of your opponent. This multiplies relative angular velocity between models, demanding rapid aim correction while making your character model much harder to track. Use *Anti-Mirroring* when at a disadvantage or immediately after missing your opening burst (the *shadowing* transition drilled in Levels 1.5–2.5).

---

[← Back to Index](./index.html)
