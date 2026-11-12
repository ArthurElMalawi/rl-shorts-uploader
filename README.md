# RL Shorts Uploader

Site public de l'application **RL Shorts Uploader**, qui publie les Shorts Rocket League de la chaîne Azuzti sur YouTube, Instagram et TikTok via leurs API officielles.

Le site sert à la fois de vitrine et de dossier de conformité. Les plateformes (TikTok Login Kit et Content Posting API en particulier) exigent une page d'accueil décrivant l'application, une politique de confidentialité, des conditions d'utilisation et une URL de retour OAuth.

Le pipeline de montage et de publication lui-même vit dans un dépôt privé (`rl-shorts`).

## Contenu

| Fichier | Rôle |
|---|---|
| `index.html` | Présentation de l'application : fonctionnement en 4 étapes (montage, contrôle qualité, file quotidienne, publication), intégration TikTok (scopes demandés, stockage local du jeton, révocation), FAQ |
| `privacy.html` | Politique de confidentialité |
| `terms.html` | Conditions d'utilisation |
| `callback.html` | Page de retour OAuth TikTok |
| `tiktok*.txt` | Fichier de vérification du domaine pour TikTok |
| `style.css`, `img/`, icônes | Styles, visuels, favicon et icône Apple |

## Stack

HTML et CSS statiques, sans framework ni build. Hébergé sur GitHub Pages (`.nojekyll`).

## Lancer en local

```bash
npx serve .   # ou n'importe quel serveur statique
```

## Auteur

[Arthur El Malawi](https://github.com/ArthurElMalawi)
