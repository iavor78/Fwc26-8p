# 🏆 Special Team League WC26 — 8 Player Edition

A real-time fantasy league tracker for **8 players** following the FIFA World Cup 2026 (USA · Canada · Mexico).

---

## 🎲 The Draw

### Group Stage Draw
There are 12 groups (A–L) with 4 teams each — all 48 WC teams. Each player is assigned **1 team from 6 different groups**, giving every player **6 teams total**.

- 8 players × 6 teams = 48 teams (every team is owned)
- Each group has exactly **4 players** assigned (one per team)
- No player can have more than one team from the same group

### Knockout Draw
A **fresh draw is held before each KO round** — group stage ownership does not carry over. Only the **top 4 players** from the group stage qualify for the KO rounds.

| Round | Teams per qualifying player |
|-------|---------------------------|
| Round of 32 | 8 |
| Round of 16 | 4 |
| Quarter-Finals | 2 |
| Semi-Finals | 1 |
| 3rd Place & Final | 1 each |

**Draw rules:**
- Only the top 4 group-stage players participate in KO draws
- The same team cannot be assigned to two different players in the same round
- A player cannot be assigned two teams that **play each other** in the same round
- Final and 3rd Place are paired — a player assigned a team in one cannot be assigned in the other

---

## ⚽ Scoring

### Group Stage
| Result | Points |
|--------|--------|
| Win | 3 |
| Draw | 1 |
| Loss | 0 |

Goal Difference and Goals For are tracked as tiebreakers.

### Knockout Rounds
| Result | Points |
|--------|--------|
| Win (Full Time) | 3 |
| Loss (Full Time) | 0 |
| Win (Penalties) | 3 |
| Loss (Penalties) | 0 |

> **Penalties:** Full Time score used for Goal Difference. Pen winner gets 3pts. No draws in KO.

---

## 📊 League Table & KO Qualification

The **Table** tab shows all 8 players ranked by total points. After the group stage, the **top 4 players** advance to the knockout rounds. A qualification line separates them from the bottom 4.

Tiebreakers (in order): Points → Goal Difference → Goals For

---

## 🏅 Best 3rd-Placed Teams

In WC2026, the top 2 teams per group qualify automatically. The **8 best 3rd-placed teams** also qualify for the R32. The **Groups** tab shows live standings and which 3rd-placed teams are currently in the top 8.

---

## 📱 App Features

| Tab | Description |
|-----|-------------|
| 🏆 Table | Overall standings for all 8 players with KO qualification line |
| 📊 Groups | Live group standings A–L + best 3rd-place ranking |
| 🔗 Bracket | Full KO bracket from R32 to Final |
| 🎲 Draw | Group and KO team assignments per player |
| ⚽ Matches | Enter match scores (group stage + all KO rounds) |
| 👤 Players | Edit player names, simulate, reset data |

### Real-Time Sync
All data syncs instantly via Firebase. Everyone connected sees the same live state.

### Lock 🔒
The admin can lock the app to prevent editing. When locked, the simulate and reset functions are hidden and password-protected. Tap the lock button (bottom right) to lock/unlock.

### Simulate
The Players tab (admin only) includes step-by-step simulation:

**Group stage:**
1. Assign teams to players
2. Simulate group phase results

**KO rounds (R32 → Final) — per round:**
- **Assign** — distributes teams to top 4 players (no same-match conflicts)
- **Simulate** — fills in random results and advances the bracket
- **Clear** — resets that round and all subsequent rounds

---

## 🗓️ Tournament

- **Kick-off:** 11 June 2026
- **Final:** 19 July 2026
- **Host nations:** 🇺🇸 USA · 🇨🇦 Canada · 🇲🇽 Mexico
- **Teams:** 48 nations across 12 groups
- **Matches:** 104 total

---

*Built with vanilla JS + Firebase Firestore · Deployed on GitHub Pages*
