# Guide d'Hébergement Gratuit et d'Intégration sur Google Sites
## LIGHT ÉLEC ENGINEERING

Ce guide complet vous explique comment héberger votre site web professionnel gratuitement sur les plateformes les plus performantes (Netlify, GitHub Pages, Vercel) tout en conservant le **libre contrôle** total sur **Google Sites**.

En hébergeant gratuitement le code source de ce projet (le fichier `index.html` et les images optimisées dans `assets/images/`), vous obtenez des liens URL publics permanents pour vos images et vos widgets dynamiques (le calculateur de devis, les animations). Vous pouvez ensuite les intégrer et les piloter directement depuis votre tableau de bord **Google Sites**.

---

### Étape 1 : Héberger le site gratuitement (3 Méthodes simples)

Choisissez l'une de ces trois plateformes gratuites pour mettre votre code et vos images en ligne en moins de 2 minutes :

#### Option A : Netlify (La plus simple, par Glisser-Déposer)
1. Allez sur [Netlify Drop](https://app.netlify.com/drop).
2. Glissez-déposez le dossier de ce projet contenant :
   - Le fichier `index.html`
   - Le dossier `assets/` (contenant le dossier `images/` et toutes les images du projet)
3. Netlify va déployer instantanément votre site et vous fournir une URL publique sécurisée (ex: `https://light-elec-engineering.netlify.app`).
4. Dans les paramètres de Netlify, vous pouvez changer ce nom de sous-domaine gratuitement ou y lier votre propre nom de domaine.

#### Option B : GitHub Pages (Hébergement automatique et permanent)
1. Créez un dépôt gratuit sur [GitHub](https://github.com/).
2. Importez-y les fichiers de ce projet (`index.html` et le dossier `assets`).
3. Allez dans les **Settings** (Paramètres) de votre dépôt GitHub.
4. Dans le menu latéral, cliquez sur **Pages**.
5. Sous "Build and deployment", choisissez la branche `main` ou `master` comme source, puis cliquez sur **Save**.
6. Votre site sera disponible publiquement sous l'URL `https://<votre-nom-dutilisateur>.github.io/<nom-du-depot>/`.

#### Option C : Vercel (Déploiement rapide de production)
1. Allez sur [Vercel](https://vercel.com/) et connectez-vous avec votre compte GitHub ou Google.
2. Importez votre dépôt GitHub en un clic.
3. Cliquez sur **Deploy**. Votre site est en ligne avec un certificat SSL gratuit (ex: `https://light-elec-engineering.vercel.app`).

---

### Étape 2 : Intégrer et Contrôler le projet sur Google Sites

Une fois votre site hébergé gratuitement via l'une des options ci-dessus, vous disposez d'un contrôle absolu depuis **Google Sites**.

#### Méthode 1 : Intégration par URL (La plus propre)
Cette méthode charge l'intégralité du site hébergé (avec le calculateur interactif, les filtres de services, etc.) dans votre Google Sites.
1. Ouvrez votre projet sur [Google Sites](https://sites.google.com/).
2. Dans le panneau de droite, cliquez sur **Insérer** > **Intégrer** (icône `< >`).
3. Sélectionnez l'onglet **Par URL**.
4. Saisissez l'URL publique de votre site hébergé (ex: `https://light-elec-engineering.netlify.app`).
5. Cliquez sur **Insérer**.
6. Étirez les bordures du cadre d'intégration sur Google Sites pour qu'il prenne toute la largeur et la hauteur de votre page sans barres de défilement.

#### Méthode 2 : Intégration par Code (Idéal pour des sections spécifiques)
Si vous préférez utiliser l'éditeur visuel natif de Google Sites pour le texte mais souhaitez intégrer notre calculateur de devis dynamique :
1. Sur Google Sites, cliquez sur **Insérer** > **Intégrer** > **Intégrer le code**.
2. Copiez uniquement la section du calculateur ou du formulaire de contact de notre fichier `index.html` et collez-la.
3. Les images hébergées sur votre hébergeur gratuit s'afficheront instantanément en utilisant leur lien absolu (ex: `https://light-elec-engineering.netlify.app/assets/images/logo.png`).

---

### Étape 3 : Associer votre nom de domaine personnalisé

Pour un rendu 100% professionnel (par exemple : `www.lightelecengineering.com`) :
1. Allez sur les paramètres de votre **Google Sites** (icône de roue crantée).
2. Cliquez sur **Domaines personnalisés** > **Commencer la configuration**.
3. Saisissez votre nom de domaine.
4. Suivez les étapes de configuration DNS indiquées par Google pour valider la propriété de votre nom de domaine auprès de votre registraire de domaine (ex: GoDaddy, Namecheap, LWS).
5. Publiez ! Votre site professionnel sur Google Sites est désormais en ligne avec une URL unique de marque.
