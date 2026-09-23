# Food Fighter Arcade

A two-player browser fighting game where the arena backgrounds are real pencil drawings, scanned straight off the paper they were drawn on.

**▶ Play it: https://YOUR-USERNAME.github.io/food-fighter/**
*(replace with your link once GitHub Pages is live)*

---

## The drawings

Viraaj drew four level backgrounds on a sheet of paper and labelled them by level range. Those exact drawings — not redrawn versions — are the four arenas in the game. The photo was deskewed, the paper flattened, and the pencil lifted out; every stroke you see in the background is his.

| Arena | Levels | What's drawn |
|---|---|---|
| **Game Console** | 1–10 | A games console with the crossed-circle button, over rolling hills and grass |
| **Sun Storm** | 11–30 | A grinning sun surrounded by lightning bolts |
| **Volcano Face** | 31–50 | A giant face watching over an erupting volcano and smoke |
| **AARGH Chaos** | 51+ | Screaming, a lit bomb, and lightning everywhere |

In the campaign you get the arena your level number lands in. In 2-player versus, you pick whichever one you want.

## How to play

**1 Player Campaign** — fight through nine levels, earn coins, spend them in the shop on new fighters and weapons. Each level you clear unlocks the next.

**2 Player Versus** — two people, one keyboard. Every fighter, weapon and arena is free to pick.

### Controls

| | Player 1 | Player 2 / CPU |
|---|---|---|
| Move | `A` / `D` | `←` / `→` |
| Jump | `W` | `↑` |
| Punch | `F` | `1` |
| Kick | `G` | `2` |
| Special | `H` | `3` |

Specials need energy — the blue bar under your health. It fills as you fight.

### Weapons

- **Melee** (sword, axe, book, flag, phone, shield) — straight damage multipliers, faster or slower
- **Ranged** (bomb, UFO, portal gun) — your special fires a projectile across the arena
- **Food** (apple, heart, curry stew, potion, hot dog) — hit for less, but heal yourself every 5 seconds

Coins and cleared levels save in your browser, so you can close the tab and come back.

## Running it yourself

One file, no build step, no dependencies, no server:

```
open index.html
```

Double-clicking the file works too. It runs entirely offline — every sprite and background is embedded in the HTML.

## Hosting it

The whole game is `index.html`. Drop it in any static host:

- **GitHub Pages** — upload to a public repo, then Settings → Pages → Deploy from branch → `main` → `/ (root)`
- Or any other static host that serves a folder

Nothing to configure, nothing to pay for.

## Built with

Plain HTML, CSS and JavaScript. Canvas 2D for the fight, no frameworks, no libraries. Backgrounds processed from the original photo with OpenCV and embedded as PNG data URIs.

---

Art by Viraaj. Code with Claude.
