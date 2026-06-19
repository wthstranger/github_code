# 🚀 GitHub Setup Guide

## 📌 Initialize Git Repository

```bash
git init
git add .
git commit -m "Initial Commit"
git branch -M main
git remote add origin https://github.com/USERNAME/REPOSITORY_NAME.git
git push -u origin main
```

---

## 🔄 Change Existing Remote Repository

### Check Current Remote

```bash
git remote -v
```

### Remove Old Repository

```bash
git remote remove origin
```

### Add New Repository

```bash
git remote add origin https://github.com/NEW_USERNAME/REPO_NAME.git
```

### Push Project to GitHub

```bash
git branch -M main
git push -u origin main
```

---

## ✅ Rename Branch to Main

If your branch is named `master`, rename it to `main`:

```bash
git branch -M main
git push -u origin main
```

---

## 📥 Clone Repository

```bash
git clone https://github.com/USERNAME/REPOSITORY_NAME.git
cd REPOSITORY_NAME
```

---

## 📤 Push Future Changes

```bash
git add .
git commit -m "Update project"
git push origin main
```
