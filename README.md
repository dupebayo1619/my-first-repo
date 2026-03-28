# My First Repo: System Utilities

This repository contains a collection of Bash scripts designed to automate Ubuntu system administration tasks.

## 🛠️ Scripts Included

### 1. `mytest.txt` (System Audit Tool)
A smart installation and auditing script that:
* **Checks** if `shellcheck` and `net-tools` are installed.
* **Automates** the installation process if they are missing.
* **Audits** the system by displaying the current version of each tool.

## 🚀 How to Run
To run the audit script, use the following commands:
```bash
chmod +x mytest.txt
./mytest.txt


3.  **Save and Exit:** `Ctrl+O`, `Enter`, `Ctrl+X`.

---

### 🟢 Why the README is your "Resume"
When an instructor or a future employer looks at your GitHub, the README is the first thing they see. 
* It shows you **write documentation**, not just code.
* It explains **why** the script exists.
* It provides **instructions** (like `chmod +x`) so they don't have to guess how to run it.



---

### 🏁 Final Git Push
Now, sync both your script and your new documentation to GitHub:

```bash
cd ~/my-first-repo
git add README.md mytest.txt
git commit -m "docs: update README with script usage and features"
git push origin main
