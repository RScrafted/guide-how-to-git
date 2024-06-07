# How to Git - Using Visual Studio Code or Git commands

Hey! I am Rachit. I first learned about it from [Reynald Adolphe](https://www.youtube.com/watch?v=i_23KUAEtUM&t=237s), who succinctly covered the fundamentals in under 7 minutes on.

If you prefer following a step-by-step guide, you're in luck. I've crafted four straightforward steps based on my learning experience.

 I personally use both methods to keep my skills sharp, though I find Git integrated with Visual Studio Code to be more intuitive. Ultimately, the choice between methods boils down to personal preference, and either option is perfectly fine!

#### Technical Information

- Visual Studio Code Version: 1.90.0 | [Download](https://code.visualstudio.com/download)
- `git --version`: git version 2.39.3 (Apple Git-146)


---

## Step 1: Initialize Git Repository

1. Open Visual Studio Code.
2. Open your project folder.
   - Alternatively, you can navigate to your project folder in the terminal and use the command `code .` to open it in Visual Studio Code.
3. Click on the Source Control icon in the Activity Bar on the side (or press `Ctrl + Shift + G`).
4. Select "Initialize Repository".
   - Alternatively, in the terminal, you can navigate to your project folder and use the command `git init` to initialize the repository.


---

## Step 2: Add and Commit Changes

1. Make changes to your files in the project folder.
2. In the Source Control panel, you'll see a list of changes. Click the `+` button next to each file you want to include in the commit to stage them.
   - Alternatively, in the terminal, you can use the command `git add .` to stage all changes.
3. Enter a commit message in the text box at the top of the Source Control panel.
4. Click the checkmark icon to commit the changes.
   - Alternatively, in the terminal, you can use the command `git commit -m "Your commit message"` to commit the changes.

---

## Step 3: Connect to GitHub

1. Click on "Publish Branch" icon (it looks like a cloud with an up arrow).
2. You'll see options to select either "Public" or "Private" for your repository. Select your preferece. (This steps actually creates a blank repository to your GitHub Account)
   - Alternatively, in the terminal, you can use the command `git remote add origin <repository-url>` to add a remote repository.
   - If prompted, sign in to your GitHub account.
   - Fill in the repository name, description, and other settings as desired.
3. Pubishing Brach is completed here.
   - Alternatively, in the terminal, you can use the command `git push -u origin master` to push the code to GitHub.


---

## Step 4: Verify on GitHub

1. Click `Open on GitHub` notification prompt from left bottom of your screen. On your web browser and navigate to GitHub.
2. Sign in to your GitHub account.
3. Navigate to your repository.
4. You should see your project files and commit history in the repository.

---

## Bonus Tip

If you wish to `Uninitialize the repository`, follow below:
1. Open the folder you wish to, in the Visual Studio Code
2. Open `bash` terminal
   - selecting `bash` is important
3. Run `git status`
4. Run `rm -rf .git`

---

# Happy Gitting! :)

---