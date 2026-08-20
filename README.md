# Digital Snake and Ladder Game (EEE 4308)

A hardware and simulation implementation of a 2-player Snake & Ladder game built on a $4 \times 4$ LED grid (positions 0–15) using discrete digital logic components.

## Features & Modules
- **Dice Module:** 2-bit pseudo-random generator (1–3) using a high-frequency 555 timer and counter.
- **Board Grid:** $4 \times 4$ array displaying Player 1 (Red), Player 2 (Blue), Snake (Yellow), and Ladder (Green) locations.
- **Snake & Ladder Logic:** Evaluates positions, subtracts for snake encounters (12 $\to$ 2), and adds for ladders (3 $\to$ 8).
- **Memory Module:** D-type flip-flop registers storing real-time 4-bit positions for each player.
- **Winner Detection:** 4-bit magnitude comparison for position 15 (`1111`) triggering an active buzzer and LED.

## Tools & Components
- **Simulation:** Proteus Design Suite
- **Key ICs:** 555 Timer, 4-to-16 Decoders, 4-bit Adders/Subtractors, D Flip-Flops, Logic Gates.
