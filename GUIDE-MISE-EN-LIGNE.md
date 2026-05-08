# 🚀 Guide de mise en ligne — 2T Film Factory

## Ce que tu vas faire (30 min max)

1. Mettre les fichiers sur GitHub
2. Connecter GitHub à Netlify
3. Activer le système de login admin
4. Accéder à ton back-office

---

## ÉTAPE 1 — Créer le dépôt GitHub (5 min)

1. Va sur **github.com** et connecte-toi
2. Clique sur le bouton vert **"New"** (en haut à gauche)
3. Nomme le dépôt : `2tfilmfactory`
4. Laisse tout par défaut (Public ou Private, peu importe)
5. Clique **"Create repository"**

---

## ÉTAPE 2 — Uploader les fichiers (5 min)

Sur la page de ton dépôt vide, clique **"uploading an existing file"**

Glisse-dépose **tous les fichiers du dossier** que je t'ai fourni :
```
index.html
netlify.toml
admin/
  ├── index.html
  └── config.yml
content/
  ├── general.json
  ├── hero.json
  ├── stats.json
  ├── services.json
  ├── about.json
  └── testimonials/
      ├── sophie-laurent.md
      └── marc-renaud.md
static/
  └── uploads/   (dossier vide)
```

Écris dans le champ en bas : `Premier commit - site 2T Film Factory`
Clique **"Commit changes"**

---

## ÉTAPE 3 — Connecter à Netlify (5 min)

1. Va sur **netlify.com** et connecte-toi
2. Clique **"Add new site"** → **"Import an existing project"**
3. Choisis **GitHub**
4. Autorise Netlify à accéder à GitHub (bouton vert)
5. Sélectionne ton dépôt **2tfilmfactory**
6. Laisse tout par défaut
7. Clique **"Deploy site"**

⏳ Netlify met 1-2 minutes à déployer.
Tu obtiens une URL comme `amazing-name-123.netlify.app`

---

## ÉTAPE 4 — Activer Netlify Identity (login admin) (5 min)

1. Dans ton tableau de bord Netlify → ton site → onglet **"Integrations"**
2. Cherche **"Identity"** → clique **"Enable Identity"**
3. Va dans **Identity** → **"Invite users"**
4. Entre **ton email** → envoie l'invitation
5. Tu reçois un email → clique le lien → crée ton mot de passe

---

## ÉTAPE 5 — Activer Git Gateway (2 min)

1. Dans Netlify → ton site → **Identity** → **"Services"**
2. Clique **"Enable Git Gateway"**

C'est ce qui permet au CMS de sauvegarder les modifications dans GitHub.

---

## ÉTAPE 6 — Accéder à ton back-office ✅

Va sur : `https://TON-SITE.netlify.app/admin`

Tu verras un écran de login → entre ton email + mot de passe.

**Tu as accès à :**
- ⚙️ Réglages (email, téléphone, réseaux)
- 🏠 Hero (titre, sous-titre, photo principale)
- 📊 Chiffres clés
- 🎯 Services (textes, liste de prestations)
- 📸 Portfolio (ajouter/supprimer/réorganiser les photos)
- 💬 Témoignages (ajouter/modifier)
- 👤 À propos (textes + photo)

---

## ÉTAPE 7 — Nom de domaine (optionnel, 10€/an)

1. Achète `2tfilmfactory.fr` sur **ovh.com** ou **namecheap.com**
2. Dans Netlify → **Domain settings** → **"Add custom domain"**
3. Entre ton domaine → suis les instructions (2 lignes DNS à copier)

---

## ⚠️ Important : après chaque modif dans le CMS

Quand tu modifies quelque chose dans le back-office, Netlify redéploie automatiquement le site en **1-2 minutes**. Tu verras le changement en ligne sans rien faire d'autre.

---

## 🆘 Problème ?

Reviens me dire l'étape bloquante, je t'aide à débloquer.
