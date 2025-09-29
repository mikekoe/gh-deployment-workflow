# Github deployment workflow

This is a simple Github Actions Workflow to deploy static website to Github pages

**URL:** `https://mikekoe.github.io/gh-deployment-workflow/`

Requirements
* Bash shell (MacOS, Windows, Linux)
* git commands


## Steps
- The workflow triggers on git pushes to `main` **ONLY IF `index.html` changes**- This then uploads the repository's content as a Pages artifact and deploys it with `actions/deploy-pages`


## Stretch
Replace `index.html` with your personal portfolio and you now have an auto-deployed site


## Usage
``` 
bash
git clone https://github.com/<username>/gh-deployment-workflow.git

cd gh-deployment-workflow

# edit index.html

git add .

git commit -m "Update files"

git push origin main
```

  
Project URL: https://roadmap.sh/projects/github-actions-deployment-workflow 


