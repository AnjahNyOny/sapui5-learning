# SAPUI5 / Fiori — Learning Repo

Ce dépôt contient :
- `walkthrough-notes/` : notes par step (Markdown)
- `projects/` : mini-projets UI5 (un dossier par thème)
- `snippets/` : extraits réutilisables (XML/JS)
- `assets/` : captures d’écran

# --------------------------------------------------------------------------------------------------------------------------------------- #


# walkthrough-notes

# Step X : Title
_ Date : 16 September 
_ Goal : 
_ What I did : 
            _ 

_ What I learned : 
            _


# --------------------------------------------------------------------------------------------------------------------------------------- #

# Routine : 

# Travailler la nouvelle étape
git checkout -b learn/step-02
# ... modifications ...
git add .
git commit -m "feat(step-02): <résumé>"
git push -u origin learn/step-02

# PR sur GitHub → Merge pull request (merge commit recommandé)

# Synchroniser localement, tagger, nettoyer
git checkout main
git pull origin main
git tag -a v0.02-step-02 -m "Walkthrough step 02 complete"
git push --tags
git branch -d learn/step-02
git push origin --delete learn/step-02  # optionnel

# --------------------------------------------------------------------------------------------------------------------------------------- #