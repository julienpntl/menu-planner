# Menu Planner - Installation sur téléphone

## 📱 Méthode simple : Déployer sur Netlify (gratuit)

### Étape 1 : Créer un compte Netlify
1. Va sur https://www.netlify.com
2. Clique sur "Sign up" et crée un compte (avec GitHub ou email)

### Étape 2 : Déployer l'application
1. Une fois connecté, tu verras "Sites"
2. **Glisse-dépose le dossier `menu-pwa`** directement sur la page
3. Netlify va créer automatiquement un site avec une URL comme : `random-name.netlify.app`

### Étape 3 : Installer sur ton Samsung
1. Ouvre **Chrome** sur ton téléphone
2. Va sur l'URL de ton site Netlify
3. Appuie sur le menu ⋮ (3 points en haut à droite)
4. Sélectionne **"Ajouter à l'écran d'accueil"**
5. Confirme le nom "Menu Planner"
6. L'app apparaît maintenant sur ton écran d'accueil ! 🎉

---

## 🔧 Alternative : Autres services gratuits

### GitHub Pages
1. Crée un repo GitHub
2. Upload les fichiers
3. Active GitHub Pages dans Settings
4. URL : `username.github.io/repo-name`

### Vercel
1. Va sur https://vercel.com
2. Connecte-toi avec GitHub
3. Import le projet
4. URL automatique fournie

---

## 📁 Fichiers inclus

```
menu-pwa/
├── index.html      # Application complète
├── manifest.json   # Config PWA (nom, icône, couleurs)
├── sw.js          # Service Worker (fonctionne hors-ligne)
└── icon-192.svg   # Icône de l'app
```

## ✨ Fonctionnalités

- ✅ Fonctionne hors-ligne
- ✅ S'installe comme une vraie app
- ✅ Sauvegarde locale (tes plats et préférences sont conservés)
- ✅ Interface optimisée mobile
