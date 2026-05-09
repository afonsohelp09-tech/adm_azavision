# Admin ERP — GitHub Pages

Alias : **ADMIN** (même paquet que ce dossier).

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

2. Remplacer **`window.ERP_BOUTIQUE_URL`** par l’URL **HTTPS** de votre dépôt **BOUTIQUE / BOUTIQUE_CLIENT** (souvent `…/index.html`) si la vitrine n’est pas sur le même site. Les fichiers livrés contiennent un exemple `VOTRE-USER` / `VOTRE-REPO-BOUTIQUE` à adapter.

## Activer GitHub Pages

**Settings** → **Pages** → branche `main`, dossier `/ (root)`.
