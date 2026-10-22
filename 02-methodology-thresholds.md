---
title: Methodology and Thresholds
---

[English](02-methodology-thresholds.html) | [Português](02-metodologia-thresholds.html)

# Methodology: Weakness Focus and the Threshold Method

## Why Focus on Weaknesses (Viscose Method, by robinwobin)

The Viscose Benchmark was constructed specifically so that every scenario represents the type of training required if you are deficient in that domain. It is not arbitrary.

The benchmark is not intended to be your entire daily routine. The principle is to run all scenarios once to establish a baseline score in each, and subsequently direct your training volume toward the scenarios where you scored the lowest. Systematically eliminating weaknesses is one of the most reliable methods for long-term improvement, regardless of your current skill level.

## The Threshold Method (by Escalate / VT Matty)

Measuring your progression solely by Personal Best (PB) is a fundamental error. PBs are easily skewed by external variables unrelated to true mechanical skill: sleep quality, nutrition, or favorable RNG target clusters in a given run. A PB does not reflect your true raw aim consistency or your ability to transfer that skill into competitive gameplay.

### What is a Threshold?

A Threshold is the score value you can achieve on any given day through concentrated effort and correct technique. It is not your best possible run; it is your reliable, repeatable performance baseline.

### The Weightlifting Analogy

Think of a Threshold like a working set in strength training performed near technical failure with high RPE (Rate of Perceived Exertion).

Banging out reps on autopilot with low resistance is the equivalent of cruising through trivial scores without real stimulation. Ego-lifting excessive weight that compromises your posture merely to say you lifted it is the equivalent of a lucky PB achieved with erratic technique. The Threshold lies precisely in between: the performance boundary where you train at the limit of your capability while maintaining proper biomechanical control and tension management, without letting execution break down.

### Practical Example

Across 5 attempts you record scores of 1000, 970, 890, 900, and 980. Your PB is 1000. Your Threshold is 970, because that is the score requiring focused technique and deliberate effort to match reliably.

### Applying Thresholds to Your Routine

In your playlists, only advance to the next task after hitting its established Threshold. If you are blazing through tasks in less than 15 minutes across the entire playlist, repeat the playlist and elevate your Threshold targets: this indicates the current target is too easy for your current mechanical baseline.

A Threshold increases only when your genuine consistency advances, never as a result of an isolated high-luck run.

---

## Foundations of Visuomotor Psychophysics and Motor Control

### 1. Fitts's Law and the Speed-Accuracy Trade-Off

In human pointing psychophysics (Paul Fitts, 1954), the movement time ($MT$) required to acquire a target is governed by the ratio between target distance ($A$) and target width ($W$):

$$MT = a + b \log_2\left(\frac{2A}{W}\right)$$

The logarithmic term defines the **Index of Difficulty ($ID$)**: smaller or more distant targets require more bits of motor information processed by the central nervous system. To evaluate a player's actual shot dispersion across a training session, Crossman's **Effective Index of Difficulty ($ID_e$)** is used:

$$ID_e = \log_2\left(\frac{A_e}{W_e} + 1\right), \quad \text{where } W_e = 4.133 \times SD_x$$

Here, $W_e$ represents the effective target width derived from the standard deviation ($SD_x$) of impact coordinates, and $ID = \log_2(2d/e)$ quantifies the direct relationship between distance ($d$) and error tolerance ($e$). The Threshold Method works by compressing motor standard deviation ($SD_x$), tightening your click distribution inside the hitbox without sacrificing acquisition time ($MT$).

### 2. Signal-Dependent Noise

Landmark motor neuroscience research (Harris & Wolpert, 1998) demonstrates that neural control signals sent to skeletal muscles are subject to **Signal-Dependent Noise**: motor force variability ($\sigma_v$) scales directly with the magnitude of the control signal added to baseline noise ($\sigma_0$).

- When you violently throw the mouse with uncontrolled force (rushing shots or applying a *death grip*), neuromotor noise spikes, causing the cursor to overshoot the target or jitter during braking.
- The optimal trajectory that minimizes endpoint variance requires **kinematic smoothness** (minimum-jerk trajectory), applying phasic tension only at initial launch and relaxing immediately during deceleration.

### 3. Two-Phase Flick Kinematics and Conservative Hypometria

Every high-level flick consists of two distinct neurophysiological phases:

1. **Phase 1 — Primary Ballistic Impulse (*Open-Loop*):** A high-velocity movement driven by large proximal muscle groups (shoulder/forearm) that transports the cursor into the target's vicinity. Because it unfolds faster than visual feedback latency, it operates without mid-flight visual correction.
2. **Phase 2 — Secondary Micro-Adjustment (*Closed-Loop*):** A fine correction executed by the wrist and fingertips, guided by foveal visual feedback to align the reticle precisely onto the target prior to clicking.

**The Discovery of Conservative Hypometria (*Under-Flicking* vs. *Over-Flicking*):**
Biomechanical studies comparing wide-target tasks (*Gridshot*) against extreme-precision tasks (*Sixshot*) reveal a deliberate strategic shift ($p = 0.88$ consistency in trained players):
- On small targets (*Sixshot* / tactical FPS headshots), elite players adopt a conservative **hypometric (*under-flicking*)** strategy, landing the primary ballistic impulse slightly **short** of the target.
- Chaining the secondary micro-adjustment in the **same direction** as the primary movement saves tens of milliseconds compared to **over-flicking** (which requires overcoming momentum to reach a full stop and reversing antagonist muscle groups in the opposite direction).

### 4. The 3 Stages of Motor Learning and the Myth of Fixed "Muscle Memory"

The popular belief that muscles memorize a fixed physical distance in centimeters—and that changing sensitivity "destroys muscle memory"—is scientifically false (Krakauer et al.). Even at a constant in-game sensitivity, mousepad friction fluctuates daily with ambient humidity, skin temperature, sweat, and PTFE skate wear.

Instead, the brain builds a **Generalized Motor Program (GMP)** capable of rapidly rescaling movement parameters across three stages:

| Stage | Timeframe | Neurocognitive Characteristics |
|---|---|---|
| **1. Cognitive** | Days 1 to 7 | High conscious effort, fragmented sub-movements, large score variance, and heavy reliance on visual monitoring. |
| **2. Associative** | Weeks 2 to 8 | Refined coupling between ballistic impulse and micro-adjustment, marked reduction in parasitic muscle tension, and Threshold stabilization. |
| **3. Autonomous** | Months 2+ | Automated subcortical execution with minimal attentional cost, freeing 100% of working memory for tactical in-game reading. |

---

[← Back to Index](./index.html)
