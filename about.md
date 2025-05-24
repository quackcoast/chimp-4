---
layout: default
title: About & Methodology
---

# About & Methodology

Information about how Brainy Baboone's rating and the project are determined.

---

## Navigation
[**Home/Leaderboard**](https://quackcoast.github.io/chimp-4) | [**Version History**](version-history.md) | [**About & Methodology**](about.md)

---

## How ELO is Calculated

The ELO rating for Brainy Baboon is determined through extensive self-play matches and matches against engines with known specific ELO ratings. The engine Brainy Baboon played against the most was one with the strength of ~1616, named shallowblue. I found this model to be the easiest to test with and found its ratings on the official computer chess website.

*   **Testing Conditions:**
    *   **Time Control:** 4 seconds with +0.4 Increment.
    *   **Hardware:** All tests run on consistent hardware: Intel Core Ultra 9 185H, 32GB RAM.
    *   **Opponent Pool:** Primarily self-play between Brainy Baboon versions, with occasional calibration against a fixed set of external engines (mainly Stockfish 8 and ShallowBlue).
*   **Rating System:** BayesElo is used to calculate ratings and confidence intervals from game results.
*   **Frequency of Updates:** Periodically, tests of 2000 or 4000 games will be done to see improvements.

## About the Developer

Brainy Baboon is developed by Tom, a passionate chess programmer dedicated to exploring and advancing computer chess. This leaderboard serves as a public record of the Brainy Baboon engine's progress.

