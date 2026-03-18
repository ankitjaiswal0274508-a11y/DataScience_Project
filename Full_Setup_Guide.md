# 🚀 FULL PYTHON + JUPYTER + GIT + GITHUB SETUP GUIDE

### (Beginner → Advanced | Future Ready)

---

## 🟢 1. SYSTEM SETUP (NEW LAPTOP)

### ✅ Install Python

- Download Python 3.11
- ✔ Add Python to PATH
- ✔ Install for all users

Check:
python --version
pip --version

---

### ✅ Install Git

Download: https://git-scm.com/downloads

Check:
git --version

---

### ✅ Git Setup (One Time)

git config --global user.name "Ankitjaiz06"
git config --global user.email "ankitjaiswal0274508@gmail.com"

---

## 🟢 2. PROJECT DOWNLOAD

git clone https://github.com/your-username/DataScience_Project.git
cd DataScience_Project

---

## 🟢 3. VIRTUAL ENVIRONMENT

python -m venv venv
venv\Scripts\activate

---

## 🟢 4. INSTALL DEPENDENCIES

pip install -r requirements.txt

---

## 🟢 5. JUPYTER SETUP

pip install notebook
pip install ipykernel
python -m ipykernel install --user --name=venv --display-name "Python (venv)"

---

## 🟢 6. RUN PROJECT

jupyter notebook

---

## 🔁 DAILY WORKFLOW

### Start work:

cd DataScience_Project
venv\Scripts\activate
jupyter notebook

---

### Save work:

git add .
git commit -m "update"
git push

---

## 🟢 7. REQUIREMENTS FILE

pip freeze > requirements.txt

---

## 🟢 8. NEW PROJECT

mkdir MyProject
cd MyProject
python -m venv venv
venv\Scripts\activate
pip install notebook

---

## ⚠️ IMPORTANT RULES

Create .gitignore:
venv/
**pycache**/
.ipynb_checkpoints/

---

## 🧠 CONCEPTS

Python = Language
venv = Environment
pip = Package manager
Jupyter = Notebook
Git = Version control
GitHub = Cloud backup

---

## 🔥 FLOW

Laptop 1:
Code → commit → push

Laptop 2:
clone → venv → install → continue

---

## 🚀 YOU ARE NOW

✔ Developer
✔ Multi-device ready
✔ Future proof

---

## 🔥 NEXT

- Pandas
- Machine Learning
- Flask / Django
