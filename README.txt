╔══════════════════════════════════════════════════════════════╗
║        SEDONU AZARAKOR — Installation via GitHub Pages       ║
╚══════════════════════════════════════════════════════════════╝

ÉTAPE 1 — Créer un dépôt GitHub
────────────────────────────────
  1. Allez sur https://github.com  (connectez-vous)
  2. Bouton vert "New"
  3. Repository name : sedonu-azarakor
  4. Visibilité : ● Public   ← OBLIGATOIRE
  5. Cliquez "Create repository"

ÉTAPE 2 — Uploader les fichiers
────────────────────────────────
  1. Dans le dépôt, cliquez "uploading an existing file"
  2. Glissez-déposez TOUT LE CONTENU du dossier gh/ :
       ✓ index.html
       ✓ manifest.json
       ✓ sw.js
       ✓ icons/  (dossier entier avec tous les PNG)
  3. Cliquez "Commit changes"

ÉTAPE 3 — Activer GitHub Pages
────────────────────────────────
  1. Onglet "Settings" du dépôt
  2. Menu gauche → "Pages"
  3. Source : Branch "main" | Folder "/ (root)"
  4. Cliquez "Save"
  5. Attendez 2 minutes
  6. Votre URL :  https://VOTRE-PSEUDO.github.io/sedonu-azarakor/

ÉTAPE 4 — Installation sur Android (sans "Ajouter à l'écran")
───────────────────────────────────────────────────────────────
  1. Ouvrez Chrome sur votre Android
  2. Allez sur votre URL GitHub Pages
  3. Chrome affiche AUTOMATIQUEMENT une boîte en bas :
         ┌─────────────────────────────┐
         │  Ajouter SEDONU à l'accueil │
         │  [Annuler]  [Installer]     │
         └─────────────────────────────┘
  4. Appuyez "Installer"
  5. L'app s'installe comme une vraie application
     avec le logo ◆ or sur fond noir

  ⚠ Si la boîte n'apparaît pas immédiatement :
    → Attendez que GitHub Pages soit actif (2 min)
    → Rechargez la page une fois
    → La boîte apparaît après ~30 secondes sur la page

CONTENU DU DOSSIER
───────────────────
  index.html                   Application complète
  manifest.json                Config PWA (nom, icône, couleur)
  sw.js                        Service Worker (hors-connexion)
  icons/
    icon-192x192.png           Logo standard
    icon-192x192-maskable.png  Logo adaptatif Android
    icon-512x512.png           Logo haute résolution
    icon-512x512-maskable.png  Logo adaptatif HD
    apple-touch-icon.png       Logo iOS
    favicon-32x32.png          Favicon navigateur
