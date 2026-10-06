# Information Architecture Deep-Dive & Methodological Guide (`IA_RESEARCH_DEEPDIVE.md`)

## 1. Diegetic Navigation vs. Generic Dashboards

```
DIEGETIC MAP MODEL (Ages 5–9)
┌────────────────────────────────────────────────────────┐
│  [⭐ 120]  [💎 45]                             [⚙️]   │
│                                                        │
│       (Castle: Boss Level 10) 🏰                       │
│                │                                       │
│          (Node 9: Division) 🟢                         │
│                │                                       │
│          (Node 8: Multiplication) 🟡                  │
│                │                                       │
│          [🎁 Daily Chest]                              │
│                │                                       │
│          (Node 7: Addition) 🟢                         │
└────────────────────────────────────────────────────────┘
```

### Diegetic Design Philosophy
In game design and narrative UX, a **diegetic element** exists naturally inside the story world itself. 
- **Non-Diegetic (Traditional Apps):** Floating menus, hamburger bars, pop-up text lists.
- **Diegetic (Our Junior Mode):** The navigation *is* the game world. Users travel along a visual map path. Tapping a treasure chest opens daily rewards; tapping a castle launches a boss math quiz.
- **Why it matters:** Children aged 5–9 think spatially and narratively. Generic administrative menus create cognitive friction. Diegetic maps make navigation feel like playing.

---

## 2. Tree Testing & Label Taxonomy

```
TREE TEST TASK SIMULATION
Task: "Where do you go to claim your free daily gift?"

Option A: Menu -> Account -> Rewards -> Daily Login Bonus (Fail: Too deep, abstract jargon)
Option B: Map -> [🎁 Daily Chest] (Success: 96% completion rate across ages 5-9)
```

### Key Learnings
1. **Child Jargon vs. System Jargon:** Terms like "Login", "Authentication", and "Database" fail. Physical metaphors like "Chest", "Vault", and "Gate" succeed.
2. **The "Parents Gate" Barrier:** To prevent accidental purchases or settings changes by children, the "Parents Gate" requires solving an adult verification problem (`7 × 8 = ?`), ensuring COPPA compliance and safety.

---

## 3. The Max 2-Tap Ergonomic Rule

```
HUB (Home / Map)
 ├── 1-TAP ──> Shop Drawer ──> 2-TAP ──> Buy Item (Done)
 ├── 1-TAP ──> Level Card ──> 2-TAP ──> Start Quiz (Done)
 └── 1-TAP ──> Parents Icon ──> 2-TAP ──> Enter PIN (Done)
```

- **Rule Statement:** No core action or screen should ever be more than 2 taps away from the main hub.
- **Why it matters:** Deeply nested sub-menus (3+ taps) cause navigation disorientation in younger users. The 2-tap boundary keeps the mental model flat and predictable.
