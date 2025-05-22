---
layout: default
title: About & Methodology
---

# About & Methodology

Information about how ChimpChess engine ratings are determined and a bit about the project.

---

## Navigation
[**Home/Leaderboard**](https://quackcoast.github.io/chimp-4) | [**Version History**](version-history.md) | [**About & Methodology**](about.md)

---

## How ELO is Calculated

The ELO ratings for Chimp engines are determined through extensive self-play matches and matches against a gauntlet of other chess engines under controlled conditions.

*   **Testing Conditions:**
    *   **Time Control:** Typically 60 minutes + 5 seconds increment per game.
    *   **Hardware:** All tests run on consistent hardware (e.g., AMD Ryzen 9 5900X, 32GB RAM).
    *   **Opponent Pool:** Primarily self-play between Chimp versions, with occasional calibration against a fixed set of external engines.
*   **Rating System:** BayesElo is used to calculate ratings and confidence intervals from game results.
*   **Frequency of Updates:** Ratings are updated after each significant batch of games (approximately 500-1000 games per version relative to its peers).

## About the Developer

ChimpChess is developed by [Your Name/Handle], a passionate chess programmer dedicated to exploring and advancing computer chess. This leaderboard serves as a public record of the Chimp engine's progress.

*(Optional: Add contact info or link to your GitHub profile/personal site)*
