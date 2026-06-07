# 🏆 Special Super League WC26 — 8 Player Edition

A real-time fantasy league for **8 players** following the FIFA World Cup 2026.
**48 teams · 104 matches · USA · Canada · Mexico**

---

## 🎲 The Draw

### Group Stage
- 12 groups of 4 teams = 48 teams total
- Each player is assigned **6 teams** from **6 different groups** (one team per group)
- Every group has exactly **4 players** assigned (one per team)
- 8 players × 6 teams = 48 teams — every team is owned by someone

### Knockout Draw
A fresh draw before R32, R16 and QF. SF/3rd place/Final carry over from QF.

| Round | Teams per player | Total |
|-------|-----------------|-------|
| Round of 32 | 4 | 32 ✓ |
| Round of 16 | 2 | 16 ✓ |
| Quarter-Finals | 1 | 8 ✓ |
| Semi-Finals | — | carry from QF |
| 3rd Place & Final | — | carry from QF |

**Draw rules for KO rounds:**
- All 8 players participate in R32, R16 and QF draws
- No player can receive two teams that play each other in the same round
- SF/3rd/Final: whoever owns the QF team that advanced keeps them — no new draw

---

## ⚽ Scoring

### Group Stage
| Result | Points |
|--------|--------|
| Win | 3 |
| Draw | 1 |
| Loss | 0 |

Tiebreaker: Goal Difference → Goals For

### Knockout Rounds
| Result | Points |
|--------|--------|
| Win (Full Time) | 3 |
| Loss | 0 |
| Win (Penalties) | 3 |
| Loss (Penalties) | 0 |

> Penalties: FT score counts for GD. Pen winner gets 3pts. No draws in KO rounds.

---

## 📊 League Table

All 8 players ranked by total points across all rounds (group stage + all KO). No elimination from the table — everyone accumulates points throughout the tournament.

---

## 🏅 Best 3rd-Placed Teams

Top 2 from each group qualify automatically. The **8 best 3rd-placed teams** also advance to R32, ranked by pts/GD/GF. The **Groups** tab shows live 3rd-place standings.

---

## 📱 App Features

| Tab | Description |
|-----|-------------|
| 🏆 Table | Full 8-player standings |
| 📊 Groups | Live group standings A–L + best 3rd-place ranking |
| 🔗 Bracket | Full KO bracket R32 → Final |
| 🎲 Draw | Group and KO draws (R32/R16/QF only) |
| ⚽ Matches | Enter scores · 📅 calendar view |
| 👤 Players | Names, simulate, reset |

### Real-Time Sync
Firebase Firestore — all changes sync instantly to all devices.

### Lock 🔒
Tap the lock button (appears on any tap, bottom-right) to password-protect editing. When locked, simulate and reset are hidden. Admin PIN required to lock/unlock.

### Simulate (admin only)
Step-by-step simulation for testing:
1. Assign teams to players (group draw)
2. Simulate group phase
3. Per KO round: **Assign** draw → **Simulate** results → **Clear** if needed

---

## 🗓️ Tournament

| | |
|-|-|
| Kick-off | 11 June 2026 |
| Final | 19 July 2026 |
| Hosts | 🇺🇸 USA · 🇨🇦 Canada · 🇲🇽 Mexico |
| Teams | 48 |
| Matches | 104 |

---

*Special Super League WC26 · Built with vanilla JS + Firebase · GitHub Pages*
