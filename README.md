# 🍁 Maple Table — Canadian Meal Planner

A no-shame, nutrition-first meal planner rooted in Canadian food traditions —
wild salmon, bannock, the Three Sisters — adapted to your body, your goals,
and your budget.

**Private repo.** Runs entirely in the browser (single HTML file, no build
step, nothing uploaded).

## Features

- **Personalized macro targets** — Mifflin-St Jeor BMR from your weight, sex,
  age, height, and activity, adjusted to your goal (lose fat + build muscle ·
  cut · bulk · maintain)
- **5 diet types** — traditional omnivore · lactose-free · vegetarian · vegan ·
  northern/budget
- **7-day meal plan** built from Canadian foods, with per-meal protein and
  calories
- **Grocery budget** in CAD (2026 estimates) + a price-ninja link to beat it
- **Calorie counter** — browser-local, resets daily, auto-fills your target
- Auto-flags if the plan's protein falls short of your target

## Design

Inspired by warm, food-forward product design — a light "linen" surface, deep
forest-green primary, clay/terracotta accents, Bricolage Grotesque display type
with Plus Jakarta Sans body text, and generous rounded corners.

## Run it

```bash
# open directly
open index.html

# or serve locally
python3 -m http.server 8000
# → http://localhost:8000
```

## Deploy (optional)

Enable GitHub Pages (Settings → Pages → `main` branch → `/ (root)`) to publish.
Note: GitHub Pages on a **private** repo requires a paid plan; otherwise clone
and open locally.

---

Built on Canada's Food Guide and the Two-Eyed Seeing framework.
