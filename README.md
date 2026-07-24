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

## Livré (v0.1)
`valide_requis`, `valide_longueur`, `valide_plage`, `valid_fusion`, `valid_ok` — erreurs structurées (`ErreurValidation { champ, message }`).

## Feuille de route
- Validation de JSON, paramètres d'URL, fichiers téléversés
- Règles : email, motif/regex, énumérations, imbrication, schémas déclaratifs
