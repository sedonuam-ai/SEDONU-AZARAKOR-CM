╔══════════════════════════════════════════════════════════════╗
║        SEDONU AZARAKOR — Installation via GitHub Pages       ║
╚══════════════════════════════════════════════════════════════╝

CONTENU DU DOSSIER
──────────────────
  index.html          → Application complète (React embarqué)
  manifest.json       → Configuration PWA
  sw.js               → Service Worker (hors-connexion)
  icons/
    icon-192x192.png  → Logo écran d'accueil Android
    icon-512x512.png  → Logo haute résolution
    apple-touch-icon  → Logo iOS
    favicon-32x32.png → Favicon navigateur
  README.txt          → Ce fichier


ÉTAPES D'INSTALLATION SUR GITHUB PAGES
════════════════════════════════════════

ÉTAPE 1 — Créer un dépôt GitHub
  1. Ouvrez https://github.com
  2. Cliquez sur le bouton vert "New" (nouveau dépôt)
  3. Nom du dépôt : sedonu-azarakor
  4. Visibilité : Public  ← OBLIGATOIRE pour GitHub Pages gratuit
  5. Cliquez "Create repository"

ÉTAPE 2 — Uploader les fichiers
  1. Dans votre nouveau dépôt, cliquez "uploading an existing file"
     (ou le bouton "Add file" → "Upload files")
  2. Glissez-déposez TOUS les fichiers :
       • index.html
       • manifest.json
       • sw.js
       • Le dossier icons/ (avec tous les PNG à l'intérieur)
  3. En bas, cliquez "Commit changes"

ÉTAPE 3 — Activer GitHub Pages
  1. Allez dans l'onglet "Settings" de votre dépôt
  2. Dans le menu gauche, cliquez "Pages"
  3. Sous "Source", sélectionnez :
       Branch : main  |  Folder : / (root)
  4. Cliquez "Save"
  5. Attendez 1-2 minutes
  6. Votre URL sera :
       https://VOTRE-PSEUDO.github.io/sedonu-azarakor/

ÉTAPE 4 — Installer sur Android (Chrome)
  1. Ouvrez Chrome sur votre téléphone
  2. Allez sur : https://VOTRE-PSEUDO.github.io/sedonu-azarakor/
  3. Un bandeau doré apparaît en bas :
       "⬇ Installer SEDONU AZARAKOR"
  4. Appuyez "⬇ Installer"
  5. Le logo ◆ apparaît sur l'écran d'accueil !

  Si le bandeau n'apparaît pas :
  → Menu Chrome (⋮) → "Ajouter à l'écran d'accueil"


UTILISATION HORS-CONNEXION
───────────────────────────
  Une fois installée, l'application fonctionne
  ENTIÈREMENT sans Internet.
  Toutes les données sont embarquées localement.


VOTRE LOGO
──────────
  Le logo est un diamant or ◆ sur fond noir avec la lettre "S"
  Il s'affiche proprement sur l'écran d'accueil Android
  (pas le logo Google Chrome)


RÉSUMÉ DES FONCTIONNALITÉS
───────────────────────────
  • 9 boutons Modulo (120 grilles chacun)
  • Saisie du tirage officiel (5 numéros)
  • Témoin rouge clignotant sur les boutons concernés
  • Vérification automatique des gains
  • Cumul des gains par tirage
  • Barème : 5 bons=10 / 4=6 / 3=3 / 2=1
  • Affichage des 120 grilles avec numéros surlignés
