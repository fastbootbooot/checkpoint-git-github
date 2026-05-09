# 🚀 Git & GitHub Fundamentals Checkpoint

Welcome to my Git practice repository! This project serves as a practical log of essential Git operations, demonstrating proficiency in repository initialization, staging, committing, and configuration management.

---

## 💻 Practice Log

### 1. Repository Initialization
> Setting up the working environment and initializing version control.

**Step 1: Create a folder called `learn_git`**
![Terminal Output](image.png)

**Step 2: Navigate into the `learn_git` folder**
![Terminal Output](image-1.png)

**Step 3: Create a file called `third.txt`**
```bash
touch third.txt
```
![Terminal Output](image-2.png)

**Step 4: Initialize an empty Git repository**
```bash
git init
```
![Terminal Output](image-3.png)

---

### 2. File Staging & Committing
> Tracking changes and saving snapshots of the project.

**Step 5: Add `third.txt` to the staging area**
```bash
git add third.txt
```
![Terminal Output](image-4.png)

**Step 6: Commit the file with a descriptive message**
```bash
git commit -m "adding third.txt"
```
![Terminal Output](image-5.png)

**Step 7: Verify the commit history**
```bash
git log
```
![Terminal Output](image-6.png)

**Step 8: Create another file called `fourth.txt`**
```bash
touch fourth.txt
```
![Terminal Output](image-7.png)

**Step 9: Add `fourth.txt` to the staging area**
```bash
git add fourth.txt
```
![Terminal Output](image-8.png)

**Step 10: Commit the new file**
```bash
git commit -m "adding fourth.txt"
```
![Terminal Output](image-9.png)

---

### 3. Modifying & Removing Files
> Handling file deletions and updating the repository state.

**Step 11: Remove the `third.txt` file**
```bash
git rm third.txt
```
![Terminal Output](image-10.png)

**Step 12: Stage all current changes**
```bash
git add .
```
![Terminal Output](image-11.png)

**Step 13: Commit the removal**
```bash
git commit -m "removing third.txt"
```
![Terminal Output](image-12.png)

**Step 14: Check the updated commit history**
```bash
git log
```
![Terminal Output](image-13.png)

---

### 4. Git Configuration
> Customizing the global Git environment.

**Step 15: Change global settings to use `cat` for paging**
```bash
git config --global core.pager cat
```
![Terminal Output](image-14.png)

**Step 16: List all global configurations**
```bash
git config --global --list
```
![Terminal Output](image-15.png)

---

<div align="center">
  <i>Practiced and documented by <b>Wael Kahlfi</b></i>
</div>
