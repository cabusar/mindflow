# 📋 Todo — React Flow Mindmap

> **Statut : Fondations terminées ✅** — Reste l'IA et le tooling contributeur.

---

## ✅ Terminé

### P0 — Quick wins
- Constantes nommées, lazy init, validation imports, persistance centralisée, a11y HTML5

### P1 — Refactor mono-fichier
- Composants extraits en interne, sections documentées, distribution mono-fichier préservée

### P2 — Modèle métier
- Reducer applicatif, historique action-based, séparation document/UI, structural sharing

### P2bis — Robustesse
- Pas de flash au chargement, `React.StrictMode`, `meta theme-color` dynamique, indicateur stockage IndexedDB/localStorage

### P4 — UX avancée
- Dark mode (toggle, auto-détection, persistance)
- Layout responsive (panel bottom-sheet mobile)
- `prefers-reduced-motion` respecté
- Sélection multiple (`selectionMode: partial`)
- Snap grille configurable (5/10/20/40px)
- Copier-coller (Ctrl+C/V)
- `touch-action: manipulation`
- `NodeResizer`, `onEdgeUpdate`, `isValidConnection`
- Type Bézier, `connectionRadius`

### UI — Toutes priorités
- Panel responsive mobile + focus trap
- Status Bar avec mode stockage
- Hints auto-hide + bouton rappel
- Micro-interactions (pulse, hover, flash)
- Indicateur chargement + export PNG
- Sélection visuelle améliorée
- Compteurs nœuds/liaisons
- Watermark PNG toggle
- Material Design Icons (Google Fonts)
- Mini-map custom (bordures, couleurs)
- i18n FR/EN complet
- Explorateur de projets multi-documents (drawer, CRUD, migration legacy)

### Code Quality
- Plus de `console.log` (sauf erreurs légitimes)
- `useEffect` standardisé, refs sync consolidés
- Constantes extraites (`DEFAULT_STROKE`, `DUPLICATE_OFFSET_PX`, etc.)
- `shapeClass` en lookup object
- `historyRef` initialisé dans `useEffect`
- Import inutilisé (`getViewportForBounds`) retiré
- Code mort retiré
- CSS redondant nettoyé
- Variables CSS manquantes corrigées
- En-tête open-source (MIT)
- CSP meta tag

---

## ⏸️ Reste à faire

### Assistant IA (P4.16)
- Format de patch, validation, application atomique
- Endpoint/modèle/config sans secret hardcodé
- Limites : contexte, taille patch, tokens

### Tooling contributeur (P3.11)
- ESLint / Prettier / Vitest / Playwright
- CI minimale vérifiant le mono-fichier

### Tests avancés (P3.13)
- Migrer `?test=1` vers Vitest
- Tests unitaires, e2e, a11y

### Sécurité (P3.12)
- Audit CSP complet
- SRI pour dépendances CDN
- Valeurs CSS arbitraires dans imports

### Fun / Bonus (UI P3)
- Thèmes personnalisés supplémentaires
- Animations canvas (fond animé, particules)
