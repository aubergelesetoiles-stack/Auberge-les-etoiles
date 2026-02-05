# Auberge Les Étoiles - Site Web

Site web présentatif pour Auberge Les Étoiles à Asrarch, Maroc.

## 📋 Contenu du Site

- **Accueil**: Page d'accueil avec bannière élégante
- **À Propos**: Présentation de l'auberge et ses services
- **Galerie**: Section pour vos photos (placeholders à remplacer)
- **Avis**: Lien vers vos avis Google
- **Contact**: Informations de contact, carte Google Maps, et réseaux sociaux

## 🎨 Personnalisation

### 1. Ajouter Votre Logo

Dans le fichier `index.html`, localisez la section navigation (ligne ~14):

```html
<div class="logo-placeholder">
    <!-- Ajoutez votre logo ici -->
    <span>AUBERGE LES ÉTOILES</span>
</div>
```

Remplacez par:
```html
<div class="logo-placeholder">
    <img src="images/logo.png" alt="Auberge Les Étoiles" style="height: 50px;">
</div>
```

### 2. Ajouter Vos Photos

1. Créez un dossier `images` dans le même répertoire que `index.html`
2. Ajoutez vos photos dans ce dossier
3. Dans `index.html`, remplacez les placeholders de la galerie (ligne ~107):

```html
<div class="gallery-item">
    <img src="images/chambre1.jpg" alt="Chambre">
</div>
```

### 3. Style CSS pour les Images

Ajoutez ce CSS dans `styles.css` si vous utilisez de vraies images:

```css
.gallery-item img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
```

## 🚀 Déploiement sur GitHub Pages

### Étape 1: Créer un Repository GitHub

1. Allez sur [GitHub](https://github.com)
2. Cliquez sur "New repository"
3. Nommez-le `auberge-les-etoiles` (ou un autre nom)
4. Cochez "Public"
5. Cliquez "Create repository"

### Étape 2: Uploader les Fichiers

**Option A - Via l'Interface Web:**
1. Dans votre repository, cliquez "Add file" > "Upload files"
2. Glissez-déposez tous les fichiers:
   - index.html
   - styles.css
   - script.js
   - README.md
   - (et votre dossier images/ avec vos photos)
3. Cliquez "Commit changes"

**Option B - Via Git (ligne de commande):**
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/VOTRE-USERNAME/auberge-les-etoiles.git
git push -u origin main
```

### Étape 3: Activer GitHub Pages

1. Dans votre repository, allez dans "Settings"
2. Dans le menu de gauche, cliquez "Pages"
3. Sous "Source", sélectionnez "main" branch
4. Cliquez "Save"
5. Attendez quelques minutes

Votre site sera disponible à: `https://VOTRE-USERNAME.github.io/auberge-les-etoiles/`

## 📱 Fonctionnalités

- ✅ Design responsive (mobile, tablette, desktop)
- ✅ Style art déco élégant (or et noir comme votre carte de visite)
- ✅ Animations au scroll
- ✅ Menu mobile
- ✅ Intégration Google Maps
- ✅ Liens vers réseaux sociaux (Instagram, Facebook, WhatsApp)
- ✅ Boutons d'appel directs

## 🎨 Couleurs Utilisées

- Or: `#D4AF37`
- Or Foncé: `#B8941F`
- Noir: `#1a1a1a`
- Brun Foncé: `#2b2420`
- Crème: `#f5f5dc`

## 📞 Informations de Contact Incluses

- **Téléphones**: +212 622 375 279 & +49 163 1912779
- **Adresse**: 6C9C+23R, Asrarch
- **Instagram**: @auberge_les_etoiles
- **Facebook**: Page officielle
- **Localisation Google Maps**: Intégrée

## 🛠️ Structure des Fichiers

```
auberge-les-etoiles/
│
├── index.html          # Page principale
├── styles.css          # Styles CSS
├── script.js           # JavaScript
├── README.md           # Ce fichier
│
└── images/             # Créez ce dossier pour vos photos
    ├── logo.png
    ├── photo1.jpg
    ├── photo2.jpg
    └── ...
```

## 💡 Conseils

1. **Photos**: Utilisez des images de haute qualité (minimum 1200px de largeur)
2. **Logo**: Format PNG avec fond transparent recommandé
3. **Optimisation**: Compressez vos images avant de les uploader (utilisez TinyPNG)
4. **SEO**: Le site est déjà optimisé avec les balises meta appropriées

## 📝 Support

Pour toute question ou assistance, vous pouvez:
- Modifier les fichiers HTML/CSS selon vos besoins
- Consulter la documentation GitHub Pages
- Contacter un développeur web pour des modifications avancées

## 📄 License

Ce site est créé pour Auberge Les Étoiles. Tous droits réservés © 2026
