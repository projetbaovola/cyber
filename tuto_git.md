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

---

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

## 🔄 Fusionner ta branche avec main

### 6️⃣ Intégrer ton travail dans main

```bash
# 1. Aller dans ton projet
cd cyber

# 2. Se placer sur main
git checkout main

# 3. Mettre main à jour avec le dépôt distant
git pull origin main

# 4. Fusionner ta branche (ex: sylvio)
git merge sylvio

# 5. Pousser la branche main mise à jour sur GitHub
git push origin main
```

---

**💡 Conseil :** Remplace `ton-prenom` par ton nom ou pseudo !
