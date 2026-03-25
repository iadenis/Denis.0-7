# Denis · Site éducatif

## Structure des fichiers

```
denis/
├── index.html                    ← Page d'accueil + module 0 + jeux philo/info
├── sciences.html                 ← Hub sciences · maths · médecine
├── sources_bibliotheques.html    ← Ta bibli + bibliothèques expertisées
├── monde_enfant.html             ← Curiosité intégrée
│
├── denis_chimie_generale.html    ← Chimie · 18 chapitres complets
├── denis_cbip.html               ← Médecine · CBIP pharmacologie
├── diagnostic_medical.html       ← Aide au diagnostic clinique
├── pico.html                     ← PICO · aide au traitement EBM
│
├── denis_francais.html           ← Français robot (placeholder)
├── denis_espagnol.html           ← Español robot (placeholder)
│
└── README.md
```

## Navigation

```
index.html
├── → sciences.html
│     ├── → denis_chimie_generale.html
│     ├── → pico.html
│     ├── → diagnostic_medical.html
│     └── → denis_cbip.html
├── → langues · philo · littérature  (dans index.html)
│     ├── → denis_francais.html
│     └── → denis_espagnol.html
├── → informatique  (dans index.html — coming soon)
├── → monde_enfant.html
└── → sources_bibliotheques.html
      ├── → pico.html
      └── → diagnostic_medical.html
```

## Modules coming soon

- `physique` — overlay coming soon dans sciences.html
- `maths` — overlay coming soon dans sciences.html
- `python_robot`, `crypto_robot`, `quantum/qiskit` — overlay coming soon dans index.html

## Clé API (chat IA)

```js
localStorage.setItem('denis_api_key', 'sk-ant-...')
```

## Lancement

Ouvrir `index.html` dans un navigateur. Aucun serveur requis.

## Palette

| Variable | Valeur | Usage |
|---|---|---|
| `--bg` | `#faf8f4` | Fond principal |
| `--ink` | `#1a1814` | Texte principal |
| `--sage` | `#7a9e87` | Vert · sciences |
| `--sky` | `#8fb4c8` | Bleu · bibliothèques |
| `--amber` | `#c8a870` | Ambre · maths |
| `--lav` | `#a89ec8` | Lavande · philo |
| `--blush` | `#e8a598` | Saumon · médecine |

## Typo

- `DM Mono` — titres, labels, code, UI
- `DM Sans` — corps de texte
