# Bistrot Arlésien - Site Web avec Interface Admin

Site web one-page avec système d'administration intégré pour le restaurant Bistrot Arlésien à Arles.

## 🚀 Déploiement sur GitHub Pages

### 1. Créer le repository GitHub

```bash
# Créer un nouveau repo sur github.com
# Nom suggéré : bistrot-arlesien
# Public

# Puis cloner et pousser
git init
git add index.html GUIDE_GERANT.md
git commit -m "Site Bistrot Arlésien avec interface admin"
git branch -M main
git remote add origin https://github.com/VOTRE_USERNAME/bistrot-arlesien.git
git push -u origin main
```

### 2. Activer GitHub Pages

1. Allez dans **Settings** > **Pages**
2. Source : **Deploy from a branch**
3. Branch : **main** / **(root)**
4. Cliquez sur **Save**

Votre site sera disponible à : `https://VOTRE_USERNAME.github.io/bistrot-arlesien/`

---

## ⚙️ Interface d'Administration

### Accès

1. Allez sur le site
2. Cliquez sur le **©** en bas de page
3. Code secret : `13200bistrotarlésiensite`

### Configuration GitHub (une seule fois)

Le gérant devra configurer ses identifiants GitHub :

1. **Username GitHub**
2. **Nom du repository** (ex: `bistrot-arlesien`)
3. **Token GitHub** (Personal Access Token)

#### Créer un Token GitHub :

1. GitHub > Settings > Developer settings
2. Personal access tokens > Tokens (classic)
3. Generate new token (classic)
4. Nom : `Bistrot Admin`
5. **Cocher : `repo`**
6. Generate token
7. Copier le token (commence par `ghp_`)

### Fonctionnalités

- ✅ **Modifier la carte** (plats, prix, descriptions)
- ✅ **Modifier les textes** (présentation, identité)
- ✅ **Modifier les images** de la galerie
- ✅ **Enregistrer localement** (prévisualisation)
- ✅ **Publier sur GitHub** (automatique, visible par tous)

### Workflow

```
Gérant modifie les prix
    ↓
Enregistre localement (prévisualisation)
    ↓
Publie sur GitHub (bouton 🚀)
    ↓
GitHub Pages se met à jour (2-5 min)
    ↓
Tous les visiteurs voient les modifications
```

---

## 📱 Caractéristiques

- ✅ **100% Responsive** - Mobile & Desktop
- ✅ **Menu Hamburger Mobile**
- ✅ **Animations Scroll** élégantes
- ✅ **SEO Optimisé**
- ✅ **Interface Admin Intégrée**
- ✅ **Publication automatique** via GitHub API
- ✅ **localStorage** pour les modifications locales
- ✅ **Zero dépendances** backend

---

## 🛠️ Technologies

- HTML5
- Tailwind CSS (CDN)
- JavaScript Vanilla
- GitHub API pour publication automatique
- localStorage pour prévisualisation

---

## 📞 Contact Restaurant

**Bistrot Arlésien**
- 📍 5 Place du Forum, 13200 Arles
- ☎️ 04 90 99 51 93
- 👥 [Facebook](https://www.facebook.com/profile.php?id=100063914435983)

---

## 🔒 Sécurité

- Code secret admin : `13200bistrotarlésiensite`
- Token GitHub stocké en localStorage (encodé)
- Accès admin réservé au gérant
- Pas d'exposition de credentials dans le code

---

## 📖 Documentation

Consultez `GUIDE_GERANT.md` pour le guide complet d'utilisation de l'interface admin.

---

## 📄 License

© 2024 Bistrot Arlésien - Tous droits réservés
