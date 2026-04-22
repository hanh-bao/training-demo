# 🚀 Training Demo - Git Workflow Practice

## 📌 1. Introduction

This repository demonstrates my practice of basic Git workflow, including file management, branching, and merging using Git.

---

## 📂 2. Project Structure

* `hello.js`: Initial JavaScript file
* `feature.js`: File created in a feature branch

---

## 🔄 3. Git Workflow Practice

### Step 1: Navigate to project directory

```bash
cd training-demo
```

### Step 2: Initialize Git repository

```bash
git init
```

### Step 3: Create a JavaScript file

```bash
type nul > hello.js
```

### Step 4: Check status

```bash
git status
```

### Step 5: Stage file

```bash
git add hello.js
```

### Step 6: Commit changes

```bash
git commit -m "add hello.js file"
```

### Step 7: View commit history

```bash
git log --oneline
```

### Step 8: Create and switch to new branch

```bash
git checkout -b new-feature
```

### Step 9: Create new file

```bash
type nul > feature.js
```

### Step 10: Stage & commit new file

```bash
git add feature.js
git commit -m "add feature.js file"
```

### Step 11: Switch back to main branch and check

```bash
git checkout master
git status
```

### Step 12: Merge branch into main

```bash
git merge new-feature
```

---

## 🌿 4. Branching Strategy

* `master`: Main branch
* `new-feature`: Used to implement new feature

---

## 💻 5. How to Run

```bash
node hello.js
```

---

## 🎯 6. Learning Outcomes

* Understand Git workflow from init to merge
* Practice staging, committing, and tracking changes
* Learn how to work with branches
* Understand how merging works

---

## 📎 7. Repository Link

https://github.com/hanh-bao/training-demo

---

## 🙌 8. Acknowledgement

Thank you for reviewing my Git practice!
