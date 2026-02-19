# Convert to Jekyll Recipes Collection (GitHub Pages)

## What this adds
- `_recipes/` collection (drop new recipes here)
- Automatic recipe cards on `/` and `/recipes/`
- Optional `image`, `serves`, `time` fields
- Print button + print styles

## Install
1. Copy these files/folders into the ROOT of your repo.
2. IMPORTANT: If your repo has a file named `.nojekyll`, DELETE it (GitHub Pages must run Jekyll).
3. Commit and push. GitHub Pages will rebuild automatically.

## Add a new recipe
Create `_recipes/chili.md`:

---
title: Chili
serves: "6"
image: /images/recipes/chili.jpg
---

## Ingredients
- ...

## Directions
1. ...

Images go in `images/recipes/`.
