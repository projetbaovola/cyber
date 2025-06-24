# 📘 TUTO GIT : Collaboration par branche

## 🎯 Objectif

Chaque membre travaille sur **sa propre branche** pour éviter les conflits.

---

## ✅ Prérequis

- Git installé
- Compte GitHub
- Accès au dépôt : [cyber](https://github.com/projetbaovola/cyber)

---

## 🚀 Étapes

### 1️⃣ Cloner le projet (une seule fois)

```bash
git clone https://github.com/projetbaovola/cyber.git
cd cyber
```

### 2️⃣ Créer ta branche

```bash
git checkout -b ton-prenom
```

### 3️⃣ Travailler sur tes fichiers

```bash
git add .
git commit -m "Ton message"
```

### 4️⃣ Pousser ta branche

```bash
git push -u origin ton-prenom
```

### 5️⃣ Reprendre le travail plus tard

```bash
cd cyber
git checkout ton-prenom
```

## 📋 Commandes essentielles

| Action             | Commande                                               |
| ------------------ | ------------------------------------------------------ |
| Cloner             | `git clone https://github.com/projetbaovola/cyber.git` |
| Créer branche      | `git checkout -b ton-prenom`                           |
| Ajouter fichiers   | `git add .`                                            |
| Committer          | `git commit -m "Message"`                              |
| Pousser            | `git push -u origin ton-prenom`                        |
| Changer de branche | `git checkout nom-branche`                             |
| Mettre à jour      | `git merge main`                                       |

---

**💡 Conseil :** Remplace `ton-prenom` par ton nom ou pseudo !
