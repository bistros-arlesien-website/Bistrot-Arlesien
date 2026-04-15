# 📖 Guide du Gérant - Bistrot Arlésien

## 🎯 Accès à l'interface d'administration

1. **Allez sur votre site** : `https://VOTRE_USERNAME.github.io/bistrot-arlesien/`

2. **Cliquez sur le symbole ©** en bas de page (dans le footer)

3. **Entrez le code secret** : `13200bistrotarlésiensite`

4. **Vous êtes dans l'admin !** ✅

---

## 🔧 Configuration GitHub (À FAIRE UNE SEULE FOIS)

### Étape 1 : Créer un Token GitHub

1. Allez sur GitHub : https://github.com
2. Cliquez sur votre **photo de profil** en haut à droite → **Settings**
3. Descendez tout en bas → **Developer settings** (dernier menu)
4. Cliquez sur **Personal access tokens** → **Tokens (classic)**
5. Cliquez sur **Generate new token** → **Generate new token (classic)**
6. Donnez un nom : `Bistrot Admin`
7. **Cochez uniquement : `repo`** (accès complet aux repositories)
8. Cliquez sur **Generate token** en bas
9. **COPIEZ LE TOKEN IMMÉDIATEMENT** (vous ne le reverrez plus !)
   - Il ressemble à : `ghp_xxxxxxxxxxxxxxxxxxxxxxxxxxxx`

### Étape 2 : Configurer dans l'interface admin

1. Ouvrez l'interface admin (© → code secret)
2. Remplissez :
   - **Nom d'utilisateur GitHub** : Votre username (ex: `jeandurand`)
   - **Nom du repository** : Le nom de votre repo (ex: `bistrot-arlesien`)
   - **Token GitHub** : Collez le token que vous venez de copier
3. Cliquez sur **Sauvegarder la configuration**

**✅ C'est fait ! Vous n'aurez plus jamais à refaire cette étape.**

---

## ✏️ Modifier la carte du restaurant

### Onglet "La Carte"

Vous pouvez modifier :
- **Noms des plats**
- **Prix**
- **Descriptions** (pour burgers et pizzas)

**Exemple :**
```
Nom : Magret de Canard
Prix : 21,00€

→ Changez en :

Nom : Magret de Canard Sauce Miel
Prix : 22,50€
```

### Onglet "Textes"

Modifiez les textes de présentation :
- Sous-titre de la page d'accueil
- 3 paragraphes de la section "Notre Histoire"

### Onglet "Galerie"

Changez les photos des plats :
- Collez l'URL de la nouvelle image
- Modifiez le label (nom de l'image)

**Où trouver des URLs d'images ?**
- Uploadez votre photo sur https://imgur.com
- Copiez le lien direct de l'image

---

## 🚀 Publier vos modifications

### Option 1 : Enregistrer localement (prévisualisation)

1. Cliquez sur **💾 Enregistrer localement**
2. Vos modifications s'affichent immédiatement sur la page
3. ⚠️ **ATTENTION** : Seul VOUS voyez ces modifications (dans votre navigateur)
4. Les clients ne les voient PAS encore

### Option 2 : Publier sur le site (pour tout le monde)

1. Faites vos modifications
2. Cliquez sur **🚀 Publier sur GitHub**
3. Attendez 2-5 minutes
4. **Rafraîchissez votre site** → Les modifications sont en ligne !
5. ✅ **Tous les clients voient maintenant les nouveaux prix**

---

## 📱 Workflow recommandé

### Pour changer un prix rapidement :

1. © → Code secret → Onglet "La Carte"
2. Changez le prix (ex: `19,00€` → `21,00€`)
3. Cliquez **💾 Enregistrer localement** (pour voir le résultat)
4. Vérifiez que ça vous plaît
5. Cliquez **🚀 Publier sur GitHub**
6. Attendez 3 minutes
7. ✅ C'est en ligne !

---

## ❓ Questions fréquentes

### Q : J'ai modifié les prix mais les clients ne voient rien
**R :** Avez-vous cliqué sur **🚀 Publier sur GitHub** ? Sans ça, les modifications restent uniquement sur votre navigateur.

### Q : Le bouton "Publier sur GitHub" ne marche pas
**R :** Vérifiez que vous avez bien configuré GitHub (Token + nom d'utilisateur + repo). Revenez à la section "Configuration GitHub".

### Q : J'ai perdu mon Token GitHub
**R :** Pas de panique ! Retournez sur GitHub → Developer settings → Créez un nouveau token → Reconfigurez dans l'admin.

### Q : Je veux annuler mes modifications
**R :** Rafraîchissez la page SANS cliquer sur "Publier". Les modifications locales disparaîtront.

### Q : Combien de temps pour que le site soit mis à jour ?
**R :** GitHub Pages met à jour le site en **2 à 5 minutes** après publication.

---

## 🆘 Support

Si vous avez un problème :
1. Rafraîchissez la page (Ctrl + F5)
2. Essayez dans un nouvel onglet
3. Vérifiez votre connexion Internet
4. Contactez votre développeur avec une capture d'écran

---

## 🔒 Sécurité

- **NE PARTAGEZ JAMAIS** le code secret `13200bistrotarlésiensite`
- **NE PARTAGEZ JAMAIS** votre Token GitHub
- Déconnectez-vous en fermant simplement l'interface admin (X en haut à droite)

---

**✅ Vous êtes prêt ! Bonne gestion du Bistrot Arlésien ! 🍽️**
