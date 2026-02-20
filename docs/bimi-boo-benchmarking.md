# Project 1: Cultural Toddler Puzzle — Bimi Boo Analysis & Visual Mockup Plan

## 1. Bimi Boo UX Benchmarks
Based on [Bimi Boo's Kids Puzzles](https://bimiboo.net/apps/kids-puzzles/), these are the "North Star" requirements for our MVP:

*   **Tactile Feedback:** Pieces must have "bouncy" physics when dragged and a satisfying "click" or "snap" when dropped correctly.
*   **Visual Reward:** High-quality particle effects (confetti, sparkles) and a celebratory animation from a central character upon level completion.
*   **Audio cues:** Professional voiceover for the landmark name (e.g., "Taj Mahal!") and festive music.
*   **Zero-UI Design:** No text in the main gameplay; all actions must be intuitive via large, high-contrast shapes.

## 2. Technical Strategy (Senior Dev Approach)
- **Engine:** Unity 2D (Standard)
- **Asset Handling:** Addressable Assets for dynamic landmark loading (minimizes app size).
- **Architecture:** ScriptableObjects for landmark metadata (easy for us to add more landmarks without code changes).
- **UI:** Unity UI (uGUI) with custom "Squash and Stretch" tweens.

## 3. Visual Mockup Generation (Prompting Strategy)
I am generating a high-fidelity visual concept with these specifications:
- **Scene:** Hawa Mahal (Pink Palace) as the puzzle.
- **Style:** Flat, vibrant, 2D vector art (Bimi Boo style).
- **UI:** Shadow outlines of 3-5 pieces on one side, colorful pieces on the other.
- **Atmosphere:** Cheerful, kid-friendly, high contrast.
