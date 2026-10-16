# Boutique Stock

Application de suivi de stock en temps réel pour boutique (téléphones, accessoires, écouteurs, powerbanks, clés USB, sacs à dos...).

## Déploiement

### 1. Base de données (Supabase)

1. Créez un compte sur [supabase.com](https://supabase.com) et un nouveau projet.
2. Dans **SQL Editor → New query**, collez le contenu de `setup.sql` et cliquez **Run**.
3. Dans **Project Settings → API**, copiez :
   - **Project URL**
   - **anon public key**
4. Ouvrez `config.js` et remplacez les deux valeurs par les vôtres.

### 2. Hébergement (GitHub Pages)

1. Créez un compte sur [github.com](https://github.com) si vous n'en avez pas.
2. Créez un nouveau dépôt (repository), par exemple `boutique-stock`.
3. Mettez-y les 3 fichiers : `index.html`, `config.js` (avec vos vraies clés), et ce `README.md`.
4. Allez dans **Settings → Pages** du dépôt.
5. Sous "Source", choisissez la branche `main` et le dossier `/ (root)`, puis **Save**.
6. Après 1-2 minutes, votre site est en ligne à l'adresse :
   `https://VOTRE-NOM-GITHUB.github.io/boutique-stock/`

### 3. Accès mobile

Partagez ce lien à votre vendeur par WhatsApp. Sur son téléphone :
- **Android (Chrome)** : menu ⋮ → "Ajouter à l'écran d'accueil"
- **iPhone (Safari)** : icône de partage → "Sur l'écran d'accueil"

Il peut ensuite ouvrir l'app depuis son écran d'accueil comme une application normale.

## Important : sécurité

Cette version n'a **aucun mot de passe** — toute personne connaissant le lien peut voir et modifier le stock. C'est adapté à un usage à deux personnes de confiance (vous et votre vendeur) qui gardent le lien privé. Si vous voulez ajouter une protection par mot de passe plus tard, dites-le-moi.

## Modifier l'app plus tard

Toute modification se fait en éditant `index.html` dans votre dépôt GitHub (directement sur le site github.com, pas besoin d'outil spécial) et le site se met à jour automatiquement en 1-2 minutes.
