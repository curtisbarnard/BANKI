# Contributing to BANKI

Please take a moment to review this document in order to make the contribution process easy and effective for everyone involved.

## Pull requests
1. [Fork](https://help.github.com/articles/fork-a-repo) the project, clone your fork, and configure the remotes:

   ```bash
   # Clone your fork of the repo into the current directory
   git clone https://github.com/<your-username>/BANKI.git
   # Navigate to the newly cloned directory
   cd BANKI
   # Assign the original repo to a remote called "upstream"
   git remote add upstream https://github.com/curtisbarnard/BANKI.git
   ```
2. If you cloned a while ago, get the latest changes from upstream:

   ```bash
   git checkout main
   git pull upstream main
   ```
3. Create a new topic branch (off the main project development branch) to contain your feature, change, or fix:

   ```bash
   git checkout -b <topic-branch-name>
   ```
4. Locally merge (or rebase) the upstream development branch into your topic branch:

   ```bash
   git pull [--rebase] upstream main
   ```
5. Push your topic branch up to your fork:

   ```bash
   git push origin <topic-branch-name>
   ```
6. [Open a Pull Request](https://help.github.com/articles/using-pull-requests/) with a clear title and description.