# Last Light – Vertical Slice

A 12–18 minute vertical slice built to communicate the core thesis of _Last Light_ to publishers and investors.

This build reflects **GDD Demo v2.1 (VC / Publisher Aligned)**.

## Engine & Platform

- Unity 6.3 LTS (6000.3.8f1)
- Platform: PC

## Studio

- Kato.8 Studios

## Getting Started

1. Clone this repository
2. Open the project in Unity Hub using the exact Unity version above
3. Open the `Bootstrap` scene
4. Press Play

## Demo Scope

- Single playable night
- One home base
- One surrounding exploration area
- One escalating horde event

This demo intentionally excludes long-term progression and extended content.  
The focus is on clarity, cause-and-effect, and system readability.

## Core Demo Pillars

- **Shared Ammo = Shared Fate**  
  One ammo supply feeds both player firearms and base defenses.

- **Horde Pressure (Not Waves)**  
  Threat escalates over time and noise, communicated through a readable horde meter.

- **Melee First, Guns Are Risky**  
  Firearms solve short-term problems while creating long-term danger.

- **Home as a Calm Anchor**  
  Early safety contrasts with escalating pressure as the night progresses.

## Project Structure

- `Assets/_Project/` – Game-specific code and assets
- `Docs/` – Design, architecture, and conventions

## Bootstrap & UI

- The project starts from a `Bootstrap` scene
- Global UI is initialized once and persists across scenes
- UI screens are prefab-based and instantiated by code
- Core UI is prewarmed at startup to avoid first-open hitches
- The horde meter is always visible and central to player decision-making

## Git Workflow

- `main` is protected
- Work in feature branches
- Open a PR before merging into `main`

## Repo Rules

- Do not commit `Library/`, `Temp/`, or `Build/`
- Commit `Assets/`, `Packages/`, and `ProjectSettings/`
- Game code and assets belong in `Assets/_Project`
- Do not upgrade the Unity version without team agreement

## Notes

This repository represents a vertical slice built for evaluation and alignment.  
It is not a content-complete or progression-complete version of the game.
