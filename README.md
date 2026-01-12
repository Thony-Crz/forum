# Forum Topics Grid

Une application web simple pour gérer des sujets de forum dans une grille personnalisable avec un chronomètre intégré.

## 🎯 Fonctionnalités

- **Grille personnalisable** : Ajustez le nombre de lignes et de colonnes (par exemple, 6x3, 5x2, etc.)
- **Saisie de sujets** : Cliquez sur n'importe quelle cellule pour ajouter ou modifier un sujet de forum
- **Chronomètre 30 minutes** : Timer intégré avec boutons démarrer/pause/réinitialiser
- **Persistance locale** : Vos données sont automatiquement sauvegardées dans le navigateur (localStorage)
- **Interface intuitive** : Design moderne et responsive

## 🚀 Utilisation

### En ligne
Accédez à l'application via GitHub Pages : [https://thony-crz.github.io/forum/](https://thony-crz.github.io/forum/)

### En local
1. Clonez le dépôt :
   ```bash
   git clone https://github.com/Thony-Crz/forum.git
   cd forum
   ```

2. Ouvrez `index.html` dans votre navigateur web

## 📝 Comment utiliser

1. **Ajuster la grille** : Modifiez le nombre de lignes et de colonnes puis cliquez sur "Mettre à jour la grille"
2. **Ajouter des sujets** : Cliquez dans une cellule et tapez votre sujet de forum
3. **Utiliser le chronomètre** : 
   - Cliquez sur ▶️ pour démarrer le timer de 30 minutes
   - Cliquez sur ⏸️ pour mettre en pause
   - Cliquez sur 🔄 pour réinitialiser
4. **Effacer une cellule** : Survolez une cellule et cliquez sur le bouton ✖
5. **Effacer tout** : Utilisez le bouton "Effacer tout" pour réinitialiser la grille complète

## 💾 Persistance

Les données sont automatiquement sauvegardées dans le localStorage de votre navigateur. Vos sujets et la configuration de la grille seront conservés même après fermeture du navigateur.

## 🛠️ Technologies

- HTML5
- CSS3 (Grid Layout, Flexbox, Animations)
- JavaScript vanilla (ES6+)
- localStorage pour la persistance
- GitHub Actions pour le déploiement automatique

## 📄 Licence

MIT