# spotter-assets

Assets statiques publics pour l'application **Spotter**.

Servis via [GitHub Pages](https://karmadibsa.github.io/spotter-assets/).

## Structure

```
/
├── index.html                        → Politique de confidentialité
└── bundles/
    ├── exercises-full_gym.json       → Bundle salle complète (~870 exercices)
    ├── exercises-home_gym.json       → Bundle home gym (~710 exercices)
    └── exercises-bodyweight.json     → Bundle poids de corps (~360 exercices)
```

## URLs de production

| Fichier | URL |
|---------|-----|
| Privacy Policy | `https://karmadibsa.github.io/spotter-assets/` |
| Bundle full gym | `https://karmadibsa.github.io/spotter-assets/bundles/exercises-full_gym.json` |
| Bundle home gym | `https://karmadibsa.github.io/spotter-assets/bundles/exercises-home_gym.json` |
| Bundle bodyweight | `https://karmadibsa.github.io/spotter-assets/bundles/exercises-bodyweight.json` |

## Ajouter / mettre à jour les bundles

1. Placer les fichiers JSON dans `bundles/`
2. `git add bundles/ && git commit -m "chore: update exercise bundles" && git push`
3. GitHub Pages se met à jour automatiquement en ~1 min.
