# 🚀 COMPLETE GIT + GITHUB + PYTHON + JUPYTER GUIDE

## (Beginner → Advanced | Full Workflow)

---

# 🟢 1. FIRST TIME SETUP (NEW SYSTEM)

## ✅ Python install

- Python 3.11 install karo
- ✔ Add to PATH

Check:

```
python --version
pip --version
```

---

## ✅ Git install

Download: https://git-scm.com/downloads

Check:

```
git --version
```

---

## ✅ Git setup (one time)

```
git config --global user.name "Ankitjaiz06"
git config --global user.email "ankitjaiswal0274508@gmail.com"
```

---

# 🟢 2. NEW PROJECT CREATE

```
cd Desktop
mkdir MyProject
cd MyProject
```

---

## ✅ Virtual environment

```
python -m venv venv
venv\Scripts\activate
```

---

## ✅ Jupyter install

```
pip install notebook ipykernel
python -m ipykernel install --user --name=venv --display-name "Python (venv)"
```

---

## ✅ Run project

```
jupyter notebook
```

---

# 🟢 3. GIT START (IMPORTANT)

```
git init
```

---

# 🟢 4. .gitignore (VERY IMPORTANT)

Create file:

```
notepad .gitignore
```

Add:

```
venv/
__pycache__/
.ipynb_checkpoints/
*.pyc
```

---

# 🟢 5. FIRST COMMIT

```
git add .
git commit -m "first commit"
```

---

# 🟢 6. GITHUB SETUP

## 👉 Step:

1. https://github.com
2. New repository
3. Name: MyProject
4. Create

---

## 👉 Connect repo

```
git remote add origin https://github.com/your-username/MyProject.git
git branch -M main
git push -u origin main
```

---

# 🔁 7. DAILY WORKFLOW

## ▶ Start work:

```
cd MyProject
venv\Scripts\activate
jupyter notebook
```

---

## 💾 Save work:

```
git add .
git commit -m "update"
git push
```

---

# 💻 8. NEW LAPTOP SETUP

```
git clone https://github.com/your-username/MyProject.git
cd MyProject
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

---

# 🟢 9. REQUIREMENTS FILE

Create:

```
pip freeze > requirements.txt
```

Install:

```
pip install -r requirements.txt
```

---

# 🗑️ 10. DELETE / CLEAN PROJECT

## ❌ Delete unwanted files:

```
del "filename"
rm -r foldername
```

---

## ❌ Delete repo (GitHub):

- Repo → Settings → Danger Zone → Delete

---

# 🧠 11. CONCEPT CLEAR

| Tool    | Use             |
| ------- | --------------- |
| Python  | Coding          |
| venv    | Environment     |
| pip     | Install libs    |
| Jupyter | Notebook        |
| Git     | Version control |
| GitHub  | Online backup   |

---

# ⚠️ IMPORTANT RULES

❌ Never upload:

```
venv/
```

✔ Always upload:

- code
- notebook
- requirements.txt
- README.md

---

# 🔥 COMPLETE FLOW

## Laptop 1:

```
Code → git add → commit → push
```

## Laptop 2:

```
clone → venv → install → continue
```

---

# 🎯 FINAL

✔ Multi system ready
✔ No data loss
✔ Clean workflow
✔ Professional setup

---

# 🚀 YOU ARE NOW

👉 Beginner ❌
👉 Developer ✔
👉 Future Ready ✔

---
