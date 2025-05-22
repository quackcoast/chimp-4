---
layout: default
title: Version History
---

# Chimp Engine Version History & Evolution

This page details the development journey of the Chimp chess engine series, highlighting key advancements with each version.

---

## Navigation
[**Home/Leaderboard**](https://quackcoast.github.io/chimp-4) | [**Version History**](version-history.md) | [**About & Methodology**](about.md)

---

## Version Log (Newest First)

### [Chimp-4-v5](chimp-4-v5.html)
*Released: 2024-03-25*
**Focus:** Advanced search techniques.
* Implemented Aspiration Windows.
* Added SEE (Static Exchange Evaluation) for move ordering and pruning.
* Improved multi-threading performance for SMP.

---

### [Chimp-4-v4](chimp-4-v4.html)
*Released: 2024-01-15*
**Focus:** Time management and endgame improvements.
* Refined time management logic for different game phases.
* Basic endgame knowledge (e.g., K+P vs K).
* Further tuning of evaluation parameters via automated testing.

---

### [Chimp-4-v3](chimp-4-v3.html)
*Released: 2023-11-10*
**Focus:** Significant evaluation function rewrite.
* Rewritten evaluation function with more complex terms (e.g., pawn structure, passed pawns).
* Added basic contempt factor.
* Increased hash table size.

---

### [Chimp-4-v2](chimp-4-v2.html)
*Released: 2023-08-30*
**Focus:** Focus on search depth and stability.
* Implemented Null Move Pruning (NMP).
* Optimized move ordering heuristics.
* Bug fixes for rare tactical oversights.

---

### [Chimp-4-v1](chimp-4-v1.html)
*Released: 2023-06-20*
**Focus:** Enhanced evaluation and search pruning.
* Added Late Move Reductions (LMR).
* Improved king safety evaluation.
* Tuned piece-square tables.

---

### [Chimp-4](chimp-4.html)
*Released: 2023-04-01*
**Focus:** Foundational version.
* Alpha-beta search with PVS.
* Basic mobility and piece-square tables.
* Quiescence search.
* Iterative deepening.
