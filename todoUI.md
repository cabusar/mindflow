# Améliorations UI/UX — Mindmap React Flow

> **Statut : Tout le P0-P2 est terminé ✅** — Restent les bonus P3.

---

## ✅ Terminé

### P0 — Urgences UX
- ✅ Dark mode (toggle, `prefers-color-scheme`, persistance, Material icons ☀️/🌙)
- ✅ Panel responsive mobile (bottom-sheet, slide, backdrop, close button)
- ✅ Status bar (nœuds, liaisons, zoom, mode stockage)

### P1 — Améliorations perceptibles
- ✅ Hints auto-hide (5s) + bouton rappel + persistance
- ✅ Micro-interactions (pulse sélection, hover scale, flash suppression)
- ✅ Indicateur chargement (spinner + overlay)

### P2 — Raffinements
- ✅ Sélection nœud améliorée (triple glow, pulse 400ms, indicateur ✏️)
- ✅ Compteurs nœuds/liaisons dans toolbar et panel
- ✅ Accessibilité (`aria-live`, `aria-label`, focus trap mobile)
- ✅ Export PNG avec watermark toggle et feedback visuel

### Hors-plan (analyse de code)
- ✅ Pas de flash au chargement (overlay jusqu'au load async)
- ✅ `meta theme-color` dynamique
- ✅ `touch-action: manipulation`
- ✅ `prefers-reduced-motion`
- ✅ Sélection multiple (`selectionMode: partial`)
- ✅ Copier-coller (Ctrl+C/V)
- ✅ Snap grille configurable (5/10/20/40px)
- ✅ Material Design Icons (Google Material Symbols)
- ✅ Mini-map custom (bordures, couleurs)
- ✅ i18n FR/EN
- ✅ Explorateur de projets (drawer, CRUD, migration)

---

## ⏸️ Reste à faire (P3 — Fun / Bonus)

### Thèmes personnalisés
- Presets supplémentaires au-delà des CANVAS_BG_PRESETS existants
- Sélecteur de thème avancé

### Animations canvas
- Fond animé subtil (points mobiles)
- Particules création/suppression nœuds

---

## Contraintes

- **Mono-fichier** : tout reste dans `index.html`
- **Pas de build** : CSS inline, JS inline
- **CDN** : dépendances via import map `esm.sh`
- **Licence** : MIT
