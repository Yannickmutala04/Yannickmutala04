# Guide d'Intégration et de Publication sur Google Sites
## LIGHT ÉLEC ENGINEERING

Ce document détaille, étape par étape, comment déployer et publier le site web professionnel créé pour **LIGHT ÉLEC ENGINEERING** sur la plateforme de création web gratuite **Google Sites**.

Comme Google Sites est un éditeur de site entièrement visuel et hébergé par Google Workspace, vous pouvez importer ce design professionnel et interactif extrêmement facilement.

---

### Méthode 1 : Intégration complète du code HTML/JS (Méthode Recommandée)

Cette méthode vous permet de conserver l'intégralité du design premium, des polices modernes, de la réactivité mobile, des animations, du calculateur de devis interactif et du filtrage dynamique des services.

1. **Ouvrez Google Sites :**
   - Allez sur [Google Sites](https://sites.google.com/) et connectez-vous avec votre compte Google.
   - Cliquez sur le bouton **"+"** (Vide) pour créer un nouveau site.

2. **Supprimez le header par défaut :**
   - Survolez la bannière de titre par défaut en haut de la page blanche et cliquez sur l'icône de poubelle pour la supprimer afin d'avoir une page 100% vierge.

3. **Intégrez le code HTML :**
   - Dans le panneau latéral droit, sélectionnez l'onglet **Insérer**.
   - Cliquez sur **Intégrer** (icône `< >`).
   - Sélectionnez l'onglet **Intégrer le code**.
   - Ouvrez le fichier `index.html` créé dans ce projet, copiez l'intégralité de son contenu, et collez-le dans la zone de saisie.
   - Cliquez sur **Suivant**, puis sur **Insérer**.

4. **Redimensionnez le bloc intégré :**
   - Google Sites va insérer le site web dans un cadre.
   - Cliquez sur les poignées bleues sur les bords du cadre et étirez-les au maximum vers le bas et sur les côtés afin de couvrir toute la largeur et la hauteur de la page sans barres de défilement internes.

---

### Méthode 2 : Hébergement des Images et Reconstruction Visuelle

Pour que Google Sites affiche correctement vos logos et bannières personnalisés extraits de l'affiche publicitaire :

1. **Hébergez vos images personnalisées :**
   - Créez un dossier public dans votre **Google Drive** ou utilisez un hébergeur d'images gratuit.
   - Téléversez les images optimisées générées dans le dossier `assets/images/` de ce projet :
     - `logo.png` (Logo officiel de l'entreprise)
     - `banner_full.jpg` (Bannière grand format de fond d'écran)
     - `partner_presentation.jpg` (Affiche de présentation de droite)
     - `top_banner.jpg` (Bannière du haut contenant le slogan)
     - `service_solaire.jpg`, `service_tableaux.jpg`, `service_cctv.jpg`, `service_reseaux.jpg` (Images de service d'illustration de la grille)

2. **Configurez les liens d'images :**
   - Si vous utilisez la **Méthode 1**, remplacez simplement les chemins relatifs d'images (ex: `assets/images/logo.png`) par les URLs directes de vos images hébergées en ligne.

3. **Reconstruction via l'éditeur visuel Google Sites (Alternative) :**
   - Si vous préférez utiliser l'éditeur "Glisser-Déposer" natif de Google Sites :
     - Utilisez l'onglet **Thèmes** pour choisir une palette de couleurs bleu royal et jaune.
     - Utilisez l'outil **Zone de texte** et **Images** pour importer le texte structuré de l'affiche et les images découpées.
     - Pour l'outil interactif de **Calculateur de devis**, insérez un bloc d'intégration de code (`< >`) avec uniquement le formulaire et le script JavaScript du calculateur présent dans notre `index.html`.

---

### Configuration Finale & Publication

1. **Associer un Domaine Personnalisé :**
   - Dans le coin supérieur droit de Google Sites, cliquez sur l'icône de **Roue crantée** (Paramètres).
   - Allez sur **Domaines personnalisés** > **Commencer la configuration**.
   - Entrez votre domaine d'entreprise officiel : `www.lightelecengineering.com` (en suivant les instructions de validation de propriété Google Search Console).

2. **Publier le Site :**
   - Cliquez sur le gros bouton bleu **Publier** en haut à droite.
   - Choisissez une adresse web sous la forme `https://sites.google.com/view/lightelecengineering`.
   - Cliquez sur **Publier**. Votre site professionnel est maintenant en ligne, opérationnel et prêt à propulser vos projets vers l'avenir !
