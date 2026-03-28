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

### 🏁 Final Git Push

```bash
cd ~/my-first-repo
git add README.md mytest.txt
git commit -m "docs: update README with script usage and features"
git push origin main


---

## 🛠️ Htop Auto-Installer (`myscript2.sh`)
This script automates the setup of the `htop` interactive process viewer.

### What it does:
1. Updates your package list.
2. Installs `htop` automatically.
3. Redirects successful installation messages to `package_install_results.log`.
4. Redirects any errors to `package_install_failure.log`.

### Usage:
```bash
chmod +x myscript2.sh
./myscript2.sh


### Step 3: Final Sync to GitHub


1.  **Stage the update:**
    ```bash
    git add README.md
    ```

2.  **Commit:**
    ```bash
    git commit -m "Added htop documentation to main README"
    ```

3.  **Push:**
    ```bash
    git push origin main
    ```


