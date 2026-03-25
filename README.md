# Denis · Site — Guide de lancement

## Fichiers inclus

| Fichier | Description |
|---|---|
| `index.html` | Page principale — module 0 + liste des jeux |
| `sources_bibliotheques.html` | Plateforme unifiée ta bibli + expertisées |
| `sciences.html` | Hub sciences/maths (physique/maths = coming soon) |
| `monde_enfant.html` | Curiosité intégrée — minimaliste |
| `denis_cbip.html` | Médecine · CBIP pharmacologie |
| `diagnostic_medical.html` | Aide au diagnostic |
| `pico.html` | PICO · aide au traitement EBM |
| `denis_chimie_generale.html` | Chimie générale |

## Fichiers à ajouter (existants, non modifiés)

- `denis_francais.html`
- `denis_espagnol.html`

## Changements appliqués

### index.html
- Module 0 affiché en premier (plein écran dark) avec bouton "passer"
- Neurochirurgie supprimée de médecine
- Python, crypto, Qiskit → coming soon
- Maths → coming soon
- Lien unifié "sources & bibliothèques" en bas (plus de séparation ma bibli / expertisées)
- Retour vers page précédente sur toutes les pages

### sources_bibliotheques.html (nouveau)
- "Ta bibliothèque" mise en avant — hero dark en haut
- Ajout de sources URL/DOI directement
- Chat IA contrôlée (répond sur tes sources)
- Bibliothèques expertisées en liste simple (source + date cliquable)
- Filtres par domaine
- Napoléon en petit strip "passe le bac"
- Enrichissement des expertisées via URL/QR
- Section "qui contrôle ton IA ?" avec liens protocole

### sciences.html
- Maths → coming soon
- Bottom strip sources & bibliothèques unifié

### monde_enfant.html
- Contenu condensé, ton adulte
- Exemples enfantins supprimés
- Présentation liste dépliable, plus aérée

## Clé API

Pour activer l'IA, stocker ta clé Anthropic dans le localStorage :
```js
localStorage.setItem('denis_api_key', 'sk-ant-...')
```

## Lancement

Ouvrir `index.html` dans un navigateur. Aucun serveur requis pour la navigation de base.
Pour les appels API (chat IA), un serveur local ou une connexion internet est nécessaire.
