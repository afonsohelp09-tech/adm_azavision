# Admin ERP — GitHub Pages

## Fichiers à la racine du dépôt

Placez **le contenu de ce dossier** à la racine du dépôt GitHub dédié à l’administration.

| Fichier | Description |
|---------|-------------|
| **`index.html`** | **Interface d’administration complète** — fichier principal pour GitHub Pages. |
| `admin_erp.html` | Même application que `index.html` (copie optionnelle). |
| `.nojekyll` | Pour GitHub Pages |
| `.gitignore` | Exclusions Git |

## Avant la mise en ligne obligatoire

1. Dans **`index.html`** (ou `admin_erp.html`), renseigner la même **URL Web App** `/exec` que pour la vitrine (`ERP_API_URL_DEFAULT` / bloc équivalent).  
   `window.ERP_ADMIN_URL` vaut `index.html` pour les liens internes lorsque le site est servi à la racine.

2. Si la **vitrine** est sur un autre dépôt GitHub Pages, définir une URL **HTTPS absolue** (souvent `…/index.html`) :
   - `window.ERP_BOUTIQUE_URL = 'https://VOTRE-USER.github.io/VOTRE-REPO-BOUTIQUE/index.html';`
   - ou la variable documentée en fin de fichier (`BOUTIQUE_STOREFRONT_URL` selon votre version).

## Activer GitHub Pages

**Settings** → **Pages** → branche `main`, dossier `/ (root)`.
