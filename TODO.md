# Session 1 practice: put the Churn Predictor under Git and on GitHub

Use **Git Bash** on Windows, **Terminal** on Mac/Linux. Run everything inside this folder.
The numbers match the steps in the recording.

1. **TODO 1** Tell Git who you are (once per computer):
   `git config --global user.name "Your Name"` and `git config --global user.email "you@example.com"`
2. **TODO 2** Turn this folder into a Git repository: `git init -b main`
3. **TODO 3** Create `.gitignore` with the 3 lines `.venv/`, `data/`, `__pycache__/`.
   Commit it on its own: `git add .gitignore` then `git commit -m "Ignore venv, data and cache"`.
   Then save the project files: `git add .` then `git commit -m "Add churn predictor starter"`
4. **TODO 4** Edit `README.md` (see the comment at the bottom), then commit it.
5. **TODO 5** Create a branch for a new feature: `git switch -c add-report`
6. **TODO 6** Follow the TODO 6 comment in `train.py`, run `python train.py`, commit.
7. **TODO 7** Create an empty repository on github.com called `churn-predictor`, then
   `git remote add origin <your repo URL>`, `git push -u origin main`, `git push -u origin add-report`
8. **TODO 8** On GitHub, open a pull request from `add-report` into `main`, then merge it.
9. **TODO 9** Bring the merged work back to your computer:
   `git switch main` then `git pull`

Done when: your GitHub repo shows **5+ commits** and **1 merged pull request**.
