# nol.validation

Validation déclarative avec erreurs structurées en pur [Nolc](https://github.com/Noliae-France/nolc), sans dépendance lourde.

> **État : fondation (v0.1).** Les primitives ci-dessous sont implémentées et testées. La feuille de route liste la suite. Construit lot par lot, chaque étape avec CI verte.

## Installation

```toml
[dependances]
"nol-validation" = { git = "https://github.com/Noliae-France/nol-validation" }
```

## Licence

MIT © 2026 Bastien LANGUEDOC.

## Livré (v0.2)
Erreurs structurées (`ErreurValidation { champ, message }`), agrégeables via `valid_fusion` / `valid_ok`.
- `valide_requis`, `valide_longueur(min,max)`, `valide_plage(min,max)`
- `valide_email`, `valide_numerique`, `valide_dans(ensemble)`

## Feuille de route
- Validation de JSON (via nol.serde), paramètres d'URL, fichiers téléversés
- Règles : motif/regex, imbrication, schémas déclaratifs
