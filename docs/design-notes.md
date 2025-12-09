# Design notes

Made out of need and lack for a handy, short but descriptive source of info on a game project. Perfect for planning out jam games and smaller game development projects.

**Note:** This is **NOT** a full Game Design Document (GDD). This is a lightweight, living document meant to track the *current* state of vision for a game. Detailed spreadsheets, script files, and dialogue trees live elsewhere. **Keep it short. Keep it enjoyable to read!**

**Template last updated:** 2025-12-09

---

## 📑 Table of Contents
1. [Working title](#1-working--title)
2. [Overview & Pitch](#2-overview--pitch)
3. [Gameplay](#3-gameplay)
4. [Design & Aesthetics](#4-design--aesthetics)
5. [Narrative & World](#5-narrative--worldbuilding)
6. [Notes & Ideas](#6-notes-andor-random-ideas)
7. [Good Practices](#good-practices)

---

## 1. Working title

## 2. Overview & pitch

### The Pitch

**One Sentence:** [Insert a catchy "elevator pitch" here. e.g., "Mario meets Dark Souls."]

### Summary

A brief description of the game. What is the player doing? What is the goal?

### Target Audience
- **Demographics:** [e.g., Train enthusiasts]
- **Genre/tags:** [e.g., Metroidvania, FPS, Cozy Sim]
- **Comparable titles:** [Game A], [Game B]

## 3. Gameplay

### Core Loop

The cycle the player repeats minute-to-minute.

```mermaid
graph TD
    %% Core Loop Diagram - Update this to match your game!
    A[Start: Level / Mission / Hub] --> B{Challenge}
    B -->|Fail| A
    B -->|Success| C[Reward]
    C --> D[Upgrade / Progression]
    D --> A
```

### Core Systems

  - `Movement`: [e.g., Double jump, dash, wall-climb]
  - `Combat`: [e.g., Turn-based, real-time, projectile logic]
  - `Progression`: [e.g., Skill trees, unlocking levels]

## 4. Design & Aesthetics

### UI / UX

  - **HUD:** [What is on screen? Health bar? Ammo?]
  - **Interfaces:** [Diagetic or not]

### Video / Visuals

  - **Art style:** [e.g., Low-poly, Pixel art 16-bit]
  - **Perspective:** [e.g., Top-down, First-person]

### Audio

  - **Music:** [Genre, adaptive music layers]
  - **SFX:** [Key sound effects needed, ambient nature]

## 5. Narrative & world(building)

### Main Theme

What is the "soul" of the game? (e.g., "Family," "Hopecore")

### Worldbuilding

  - **Setting:** [e.g., Cyberpunk Tokyo, 1920s Noir, Fantasy Forest]
  - **Lore:** [Brief history or rules of the world]
  - **Characters:** [Protagonist motivation, antagonist goal, is there supporting cast?]

## 6. Notes and/or random ideas

*Ideas that are cool but not yet verified or implemented. Keep them here so they don't clutter the main design.*

  - [ ] Maybe add a fishing minigame?
  - [ ] DLC idea: Space levels?
  - [ ] Mechanic idea: Time rewinding (might be too expensive to code)

---

## Good Practices

### Guidelines

  - **Don't get burned out!** Writting a long doc is tiring, sometimes prevents you from the core fun of the game dev!
  - Use Mermaid diagrams, like in [this section](#core-loop), for logic flows.
  - **Kill your darlings:** If a feature isn't fun in the prototype, move it to [here](#6-notes-andor-random-ideas).
  - **Update if you need.** Design might change after every playtest.
