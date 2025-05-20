# Set Up Vite React and Git Bush

## How to Set Up Vite React 

1. Create Folder in your Desktop
2. Set Up Vite React and Git Bash

## How to Set Up Vite React

1. **Create a Folder on Your Desktop**
   - Navigate to your desktop and create a new folder where you'll set up your React project.

2. **Open Git Bash in the Folder**
   - Right-click inside the folder and select **Git Bash Here** to open Git Bash in that directory.

3. **Run the Vite React Setup Command**
   ```bash
   npm create vite@latest
   ```
   - You will be prompted to name your project and select a framework. Choose:
     - **Framework**: React
     - **Variant**: JavaScript.

4. **Create Folder ReactVite**
   ```bash
   cd cd my-react-vite-app
   ```

5. **Install Dependencies**
   ```bash
   npm install
   ```

6. **Start the Development Server**
   ```bash
   npm run dev
   ```
   - Open the provided URL in your browser to see your React app running.

---

## How to Set Up Git Bash for the Project

1. **Initialize a Git Repository**
   ```bash
    git config --global user.name "Your Name"
   ```

2. **Follow and copy..**
   ```bash
      git config --global user.email "you@youraddress.com"
   ```
   - Next Copy also:
     ```
     git config --global push.default matching
     ```

3. **Stage Your Changes**
   ``` bash
   git config --global alias.co checkout
   ```

4. **Commit Your Changes**
   ``` bash
  git init
   ```

5. **Connect to a Remote Repository**
   go to your git repository and copy the follow.

5. **(1) Check if the file README.md exists in your current directory.**

``` bash
ls
```

5. **(2) Ensure the filename is correct**
``` bash
ls -l
```

6. **Push Your Code**
   ```bash
   git branch -M main
   git push -u origin main

# 🌡️ Git Workflow: Temperature Change Branch

This README explains the steps used to create a new Git branch, commit changes, and push it to a remote repository. The branch in this example is called `temperature-change`.

---

## 🚀 Steps

### 1. Create and switch to a new branch
```bash
git checkout -b temperature-change

git add .

git commit -m "changed temp"

git status

git push origin temperature-change



