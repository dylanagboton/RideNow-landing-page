# 🚗 RideNow - Vehicle Rental Landing Page

> **Une landing page moderne et responsive pour un service de location de véhicules, construite avec HTML et Tailwind CSS.**

![RideNow Preview](/preview.jpg)

## ✨ Fonctionnalités

- 🎨 **Design moderne et épuré** avec une palette de couleurs professionnelle
- 📱 **Fully responsive** - Optimisé pour tous les appareils (mobile, tablette, desktop)
- 🚀 **Performance optimisée** - Chargement rapide sans framework lourd
- 🎯 **Sections complètes** :
  - Navigation fixe avec logo et menu
  - Section Hero avec call-to-action
  - Section Avantages avec icônes
  - Galerie de véhicules populaires
  - Témoignages clients
  - FAQ interactive
  - Formulaire de contact
  - Footer avec newsletter et liens utiles
- 🎪 **Animations et interactions** - Effets hover et transitions fluides
- 🔍 **SEO-friendly** - Structure HTML sémantique
- ♿ **Accessible** - Respect des standards d'accessibilité

## 🚀 Instructions d'installation

### Prérequis

- Un navigateur web moderne
- Git (pour cloner le repository)

### Étapes d'installation

1. **Cloner le repository**

   ```bash
   git clone https://github.com/dylanagboton/RideNow-landing-page.git
   cd RideNow-landing-page
   ```

2. **Ouvrir dans un navigateur**

   - Double-cliquez sur le fichier `index.html`
   - Ou ouvrez-le avec votre navigateur préféré
   - Ou utilisez un serveur local :

     ```bash
     # Avec Python
     python -m http.server 8000

     # Avec Node.js (si vous avez http-server installé)
     npx http-server
     ```

3. **Accéder au site**
   - Ouvrez votre navigateur et allez sur `http://localhost:8000`

### ⚡ Note importante

**Tailwind CSS est utilisé via CDN** - Aucune installation supplémentaire n'est requise ! Le site fonctionne immédiatement après le clonage.

## 🧱 Structure des fichiers

```
RideNow-landing-page/
├── 📄 index.html              # Page principale
├── 📁 css/
│   └── index.css              # Styles personnalisés
├── 📁 src/
│   ├── 📁 assets/
│   │   ├── 📁 images/         # Images du projet
│   │   │   ├── 01.jpg         # Image principale
│   │   │   ├── 02.jpg         # Véhicule 1
│   │   │   ├── 03.jpg         # Véhicule 2
│   │   │   ├── 04.jpg         # Véhicule 3
│   │   │   ├── 05.jpg         # Photo client
│   │   │   └── hero-bg.jpg    # Arrière-plan hero
│   │   └── 📁 fonts/          # Polices personnalisées
│   ├── input.css              # Configuration Tailwind
│   └── output.css             # CSS compilé Tailwind
├── 📄 main.js                 # JavaScript (vide pour l'instant)
├── 📄 package.json            # Configuration npm
└── 📄 README.md               # Ce fichier
```

## 🎨 Stack technique utilisée

### Frontend

- **HTML5** - Structure sémantique et moderne
- **Tailwind CSS** - Framework CSS utilitaire (via CDN)
- **Phosphor Icons** - Bibliothèque d'icônes modernes
- **CSS3** - Styles personnalisés et animations

### Outils de développement

- **Git** - Contrôle de version
- **npm** - Gestion des dépendances (optionnel)

### Caractéristiques techniques

- **Responsive Design** - Mobile-first approach
- **Performance** - Optimisé pour le chargement rapide
- **Accessibilité** - Respect des standards WCAG
- **Cross-browser** - Compatible avec tous les navigateurs modernes

## 🧩 Personnalisation possible

### Couleurs

Les couleurs principales sont définies dans les classes Tailwind :

- **Primaire** : `#9964d9` (violet)
- **Secondaire** : `#d5d5d6` (gris clair)
- **Texte** : Noir et gris

### Contenu

- **Images** : Remplacez les fichiers dans `/src/assets/images/`
- **Texte** : Modifiez directement dans `index.html`
- **Liens** : Mettez à jour les href dans la navigation et footer

### Styles

- **CSS personnalisé** : Éditez `css/index.css`
- **Classes Tailwind** : Modifiez directement dans `index.html`
- **Arrière-plans** : Changez `hero-bg.jpg` pour un nouveau design

### Fonctionnalités

- **Formulaire** : Ajoutez la logique de traitement dans `main.js`
- **Animations** : Intégrez des bibliothèques comme AOS ou GSAP
- **Analytics** : Ajoutez Google Analytics ou autres outils

## 📄 Licence

Ce projet est sous licence **ISC**. Voir le fichier `package.json` pour plus de détails.

## 🙋‍♂️ Auteur / Crédits

**Développé avec ❤️ par Dylan Agboton**

- **GitHub** : [@dylanagboton](https://github.com/dylanagboton)
- **Projet** : [RideNow Landing Page](https://github.com/dylanagboton/RideNow-landing-page)

### Remerciements

- **Tailwind CSS** - Pour le framework CSS utilitaire
- **Phosphor Icons** - Pour la bibliothèque d'icônes
- **Communauté open source** - Pour l'inspiration et les ressources

---

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :

1. Fork le projet
2. Créer une branche pour votre fonctionnalité (`git checkout -b feature/AmazingFeature`)
3. Commit vos changements (`git commit -m 'Add some AmazingFeature'`)
4. Push vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrir une Pull Request

## 📞 Support

Si vous avez des questions ou besoin d'aide :

- Ouvrez une [issue](https://github.com/dylanagboton/RideNow-landing-page/issues)
- Contactez l'auteur via GitHub

---

⭐ **N'oubliez pas de donner une étoile au projet si vous l'aimez !**
