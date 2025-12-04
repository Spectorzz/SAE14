# SAE14 - Se présenter sur Internet

## 🌐 Accès au projet
### [https://spectorzz.github.io/SAE14/](https://spectorzz.github.io/SAE14/)

---

## 📝 Présentation du projet
Ce projet a été réalisé dans le cadre de la SAÉ14. Il s'agit d'un site web multipages en HTML et CSS, respectant les standards du web et les critères d'accessibilité.

Le thème choisi est les aurores boréales, permettant de présenter des informations sur ce sujet et de mettre en valeur du contenu visuel et textuel.

## 🎯 Objectifs du projet

Ce projet répond point par point aux exigences du cahier des charges de la SAÉ14 :

### Structure et contenu
* ✅ **Site multipages** : 3 pages HTML distinctes (Accueil, Aurores Boréales, À propos)
* ✅ **Page d'accueil visuelle** : Présentation immersive du thème avec effet glassmorphism
* ✅ **Page dédiée au sujet** : Contenu riche sur les aurores boréales avec sections structurées
* ✅ **Page à propos** : Présentation de l'auteur et du contexte de réalisation

### Design et mise en page
* ✅ **Charte graphique cohérente** : Palette de couleurs unifiée, typographie harmonieuse
* ✅ **Flexbox** : Navigation, centrage des éléments, mise en page flexible
* ✅ **CSS Grid** : Grilles 2 et 3 colonnes pour organisation du contenu
* ✅ **Responsive Design** : Adaptation fluide sur mobile (480px), tablette (768px) et desktop (1024px)

### Animations et interactivité
* ✅ **Animations CSS** : 
  - Animation d'apparition au chargement (@keyframes zoomFade)
  - Effets au survol sur les cartes et la navigation
  - Transitions fluides sur tous les éléments interactifs

### Standards et qualité
* ✅ **Validation W3C HTML** : Code sémantique respectant les standards HTML5
* ✅ **Validation W3C CSS** : Styles conformes aux normes CSS3
* ✅ **Accessibilité WCAG 2.0 AA** : 
  - Contrastes de couleurs vérifiés
  - Navigation au clavier fonctionnelle
  - Structure sémantique appropriée

### Versioning et déploiement
* ✅ **Repository GitHub** : Code source versionné et accessible
* ✅ **Commits** : Messages porteurs de sens 
* ✅ **GitHub Pages** : Site déployé et accessible en ligne
* ✅ **README.md détaillé** : Documentation complète du projet avec technologies utilisées et liens d'hébergement

---

## 📂 Structure du site

1.  **Page d'accueil (`index.html`) :**
    * Présentation visuelle et immersive avec effet glassmorphism
    * Animation d'apparition au chargement (zoomFade)
    * Mise en avant du thème des aurores boréales
    
2.  **Page Aurores Boréales (`aurores.html`) :**
    * Explications détaillées sur le phénomène scientifique
    * Sections structurées : Qu'est-ce qu'une aurore, Où observer, Quand observer
    * Galerie d'images avec effets au survol
    * Cards d'information avec backdrop-filter
    
3.  **Page À propos (`a_propos.html`) :**
    * Présentation de l'auteur
    * Contexte de réalisation
    * Informations sur le projet

### Éléments communs à toutes les pages :
- **Navigation fixe** en haut de page (glassmorphism effect)
- **Background image** avec effet parallaxe (background-attachment: fixed)
- **Design cohérent** avec palette de couleurs unifiée
- **Responsive** sur Desktop, tablette et mobile (480px, 768px, 1024px)

---

## 🛠 Technologies et Outils

| Technologie | Usage |
| :--- | :--- |
| **HTML5** | Structure (body, nav, main, section) |
| **CSS3** | Mise en forme, Flexbox, Animations, Backdrop-filter |
| **CSS Animations** | Keyframes (@keyframes zoomFade), Transitions, Transform |
| **CSS Effects** | Backdrop-filter (effet de flou), Box-shadow, Gradients |
| **Responsive Design** | Media queries (480px, 768px, 1024px) |
| **Git / GitHub** | Versioning et hébergement (GitHub Pages) |

### Techniques CSS utilisées :
- **Flexbox** : Navigation, centrage des éléments
- **CSS Grid** : Grilles responsive 2 et 3 colonnes avec gap
- **Positioning** : Navigation fixe (fixed), centrage absolu
- **Pseudo-classes** : :hover, :focus pour l'interactivité
- **Vendor prefixes** : -webkit-backdrop-filter pour compatibilité Safari
- **RGBA** : Transparences et effets de verre (glassmorphism)

---

## ✔️ Validations

### W3C HTML
![alt text](<images/Screenshot 2025-11-30 222752.png>)
### W3C CSS
![alt text](<images/Screenshot 2025-11-30 222817.png>)
### conformité WCAG.0 AA
![alt text](<images/Screenshot 2025-11-30 222836.png>)