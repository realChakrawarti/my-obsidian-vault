
Hello everyone, today I will show you how to setup Obsidian on Windows & Android, also sync the Vault using GitHub.

Pre-requisite:
1. Basic knowledge of Git and GitHub
2. GitHub Access Token, which will be used to login and setup Obsidian Git plugin on Android

#### On Windows Platform
1. Create a GitHub repository using your account.
2. Create a folder on your system, name it anything.
3. Initialize git using Command Prompt or Git Bash, `git init`
4. Now add link your folder with GitHub remote repo, `git remote add origin <repo_link>`
5. Open Obsidian application on your system, select the folder you created set it as the Vault location.
6. Install Obsidian Git plugin from Community Plugins
7. <kbd>Ctrl + P</kbd>, opens up the Command palette, commit your changes and push them, you can further customize Obsidian Git plugin to your requirement for that refer: link

#### On Android Platform
1. Install Termux from F-droid
2. Do `pkg install git`
3. Do `termux-setup-storage`, doing this will enable you to access your device storage using terminal
4. Create a folder anywhere, this is will be your Vault location.
5. Now do, `git clone <repo_link>`
6. Open Obsidian app on your Android Device, and select the folder, will show up automatically
7. Install Obsidian Git plugin from Community Plugins
8. Screenshot of setup

https://github.com/dmnemec/copy_file_to_another_repo_action
How to use this [[GitHub Action]] https://github.com/DominiqueMakowski/DominiqueMakowski.github.io/blob/master/.github/workflows/copy_content.yml
