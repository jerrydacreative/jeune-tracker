# 🌿 Tracker de Jeûne - Application Web

Une application web progressive pour suivre vos jeûnes intermittents avec un système de badges motivant et des informations physiologiques détaillées.

## ✨ Fonctionnalités

### 📊 Suivi en temps réel
- **Timer principal** : Affichage heures:minutes:secondes
- **Temps restant** : Countdown jusqu'à l'objectif avec couleurs progressives
- **Barre de progression** : Pourcentage visuel de completion

### 🏆 Système de badges (19 niveaux)
- **30min à 72h** : Progression motivante avec paliers rapprochés
- **Détails physiologiques** : Ce qui se passe dans votre corps
- **Astuces pratiques** : Comment tenir bon à chaque étape
- **Cliquable** : Modal détaillé pour chaque badge débloqué

### 💾 Sauvegarde automatique
- **localStorage** : Progression conservée même après fermeture
- **Restauration intelligente** : Reprend exactement où vous étiez
- **Expiration 7 jours** : Nettoyage automatique des anciennes données

### 📱 Compatible mobile
- **Progressive Web App** : Installable sur iOS/Android
- **Interface responsive** : Optimisée pour tous les écrans
- **Touch-friendly** : Interactions tactiles fluides

## 🚀 Utilisation

### Sur ordinateur
1. Ouvrez `index.html` dans votre navigateur
2. Entrez la date/heure de début et durée cible
3. Cliquez "Commencer le Jeûne"

### Sur iPhone/iPad
1. Ouvrez dans Safari
2. Appuyez sur "Partager" → "Ajouter à l'écran d'accueil"
3. L'app apparaît comme une application native

## 🎯 Badges disponibles

| Durée | Badge | Nom | Physiologie |
|-------|-------|-----|-------------|
| 30min | 🌤️ | Première Demi-heure | Début de baisse d'insuline |
| 1h | 💧 | Hydratation Active | Digestion ralentit |
| 2h | 🌿 | Digestion Complète | Insuline basale |
| 4h | 🌱 | Débutant | Transition métabolique |
| 6h | 🔋 | Mode Économie | Pic de difficultés |
| 8h | 🔥 | Initié | Glycogène épuisé |
| 10h | 💪 | Force Mentale | Corps cétoniques |
| 12h | ⚡ | Persévérant | Entrée en cétose |
| 14h | 🧘 | Zen Attitude | Clarté mentale |
| 16h | ✨ | Guerrier | Autophagie démarre |
| 18h | 🦸 | Super Héros | Hormone de croissance |
| 20h | 💫 | Étoile Montante | Excellence métabolique |
| 24h | 🎯 | Champion | Autophagie active |
| 30h | 🔮 | Visionnaire | Neurogenèse |
| 36h | 💎 | Maître | Régénération profonde |
| 42h | 🌸 | Sage | Renaissance cellulaire |
| 48h | 👑 | Légende | Pic d'autophagie |
| 60h | 🏔️ | Titan | Force ultime |
| 72h | 🌟 | Mythique | Maîtrise totale |

## 🔧 Fonctionnalités techniques

### Sauvegarde locale
- Données stockées dans `localStorage`
- Sauvegarde automatique toutes les 10 secondes
- Restauration au rechargement de page
- Bouton de suppression des données

### Interface avancée
- Pause/reprise du jeûne
- Fermeture modal par clic extérieur
- Animations fluides des badges
- Messages motivationnels rotatifs

### Compatibilité
- **Navigateurs** : Chrome, Safari, Firefox, Edge
- **Mobile** : iOS Safari, Android Chrome
- **Hors ligne** : Fonctionne sans internet une fois chargé

## 📋 Installation locale

```bash
# Cloner ou télécharger
git clone https://github.com/votre-nom/fasting-tracker.git

# Ouvrir le fichier
open index.html
# ou double-clic sur le fichier
```

## 🌐 Déploiement web

### GitHub Pages
1. Créer un repo GitHub public
2. Upload `index.html`
3. Settings → Pages → Deploy from main branch
4. URL : `https://votre-nom.github.io/repo-name`

### Netlify (drag & drop)
1. Aller sur netlify.com
2. Glisser-déposer le fichier HTML
3. URL automatique générée

## ⚠️ Avertissements

- **Usage médical** : Cette app est à des fins informatives uniquement
- **Jeûnes longs** : Consultez un professionnel de santé pour jeûnes >24h
- **Conditions médicales** : Demandez un avis médical si problèmes de santé

## 🛠️ Développement

### Structure
```
fasting-tracker/
├── index.html          # Application complète
├── README.md           # Documentation
└── manifest.json       # PWA configuration
```

### Technologies
- **HTML5** : Structure et sémantique
- **CSS3** : Glassmorphism, animations, responsive
- **JavaScript ES6+** : LocalStorage, timers, modals
- **PWA** : Service worker, manifest, offline

## 📄 Licence

Usage libre pour projets personnels et éducatifs.

## 🤝 Contribution

Les suggestions d'amélioration sont les bienvenues via les issues GitHub.

---

**Developed with ❤️ for the fasting community**