# 📋 ClipShare

Presse-papiers partagé entre appareils — 100% gratuit, P2P, sans serveur.

Copie sur ton iPhone, colle sur ton PC (Ubuntu/Windows) et vice versa.

## 🚀 Déploiement sur GitHub Pages (gratuit)

### 1. Créer le dépôt

```bash
# Créer le dépôt sur GitHub (depuis ton PC Ubuntu ou Windows)
git init clipshare
cd clipshare

# Copie le fichier index.html dans ce dossier

git add .
git commit -m "Initial commit - ClipShare"
git branch -M main
git remote add origin https://github.com/TON-USERNAME/clipshare.git
git push -u origin main
```

### 2. Activer GitHub Pages

1. Va sur **github.com** → ton dépôt `clipshare`
2. **Settings** → **Pages**
3. Source : **Deploy from a branch**
4. Branch : **main** / dossier **/ (root)**
5. Clique **Save**

En 1-2 minutes, ton app sera accessible sur :
```
https://TON-USERNAME.github.io/clipshare/
```

### 3. Utiliser

1. Ouvre l'URL sur ton **iPhone** (Safari)
2. Ouvre la même URL sur ton **PC** (Firefox/Chrome)
3. Note le **code de salle** affiché sur un appareil
4. Entre ce code sur l'autre appareil → **Rejoindre**
5. Colle du texte → **Envoyer** → copie de l'autre côté !

### 📱 Astuce iPhone

Dans Safari, clique **Partager → Sur l'écran d'accueil** pour créer un raccourci comme une app native.

## 🔒 Vie privée

- Connexion **peer-to-peer** (WebRTC) — le texte passe directement entre tes appareils
- Aucun serveur ne stocke tes données
- Le serveur PeerJS Cloud sert uniquement à la mise en relation initiale

## 🛠 Tech

- HTML/CSS/JS pur (fichier unique)
- [PeerJS](https://peerjs.com/) pour le WebRTC
- Hébergé sur GitHub Pages (statique)

---

Fait par [Cypher_IA](https://linkedin.com/in/bienvenu-diatta-58023b267)
