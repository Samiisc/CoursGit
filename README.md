# 📘 Cours Git & GitHub

Bienvenue dans ce cours Git et GitHub conçu pour les débutants, les développeurs ou les équipes souhaitant apprendre à versionner, collaborer et gérer efficacement leur code.

## 📚 Contenu du cours

Ce dépôt contient les fichiers suivants :

| Fichier | Description |
|--------|-------------|
| `INTRODUCTION.md` | Introduction à Git, son historique et ses concepts de base |
| `COMMANDES_DE_BASE.md` | Commandes Git essentielles (init, clone, commit, push, pull…) |
| `TRAVAIL_EQUIPE.md` | Branches, merge, pull request (PR), bonne gestion collaborative |
| `AVANCE.md` | Rebase, cherry-pick, stash, tags, hooks, workflows GitHub |
| `CONFLIT.md` | Comprendre et résoudre les conflits Git |
| `README.md` | Ce fichier d’accueil du cours |

---

## 🧰 Prérequis

- Avoir **Git installé** sur votre machine ([télécharger ici](https://git-scm.com/)).
- Installer **Git Bash** (inclus dans Git for Windows).
- Avoir un compte [GitHub](https://github.com/).

---

## ⚙️ Installation de Git Bash (Windows)

1. Télécharger l’installateur depuis : [https://git-scm.com/download/win](https://git-scm.com/download/win)
2. Lancer le fichier `.exe`
3. Choisir les options par défaut sauf :
   - **Terminal** : Choisir “Use Git Bash only”
4. Ouvrir `Git Bash` depuis le menu démarrer.

---

## 🏁 Démarrer avec Git

```bash
# Configurer Git
git config --global user.name "Votre Nom"
git config --global user.email "vous@example.com"

# Initialiser un dépôt
git init

# Ajouter et valider des fichiers
git add .
git commit -m "Premier commit"

# Partager les fichiers locals en Ligne
git push
git push "Nom du repository"

cours-github/
├── README.md                # Présentation du cours
├── INSTALLATION.md          # Guide d’installation Git & Bash
├── INTRODUCTION.md          # Introduction à Git & GitHub
├── COMMANDES_DE_BASE.md     # Les commandes Git essentielles
├── TRAVAIL_EQUIPE.md        # Branches, PR, collaboration
├── AVANCE.md                # Concepts avancés
├── TP/
│   ├── TP1.md
│   └── TP2.md
└── ressources/
    ├── cheatsheet.pdf
    └── logo-github.png
