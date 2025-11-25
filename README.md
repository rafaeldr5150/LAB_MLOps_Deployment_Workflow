# LAB_MLOps_Deployment_Workflow
LAB | MLOps Deployment Workflow (DEV → PRD)
Work in pairs to simulate a real ML engineering workflow:
Developer writes code and proposes it through a Pull Request.
Gatekeeper reviews, tests, and approves changes before they reach production (main).
You will switch roles later, so both students practice each role.
Gatekeeper (first step)
Create a repo on GitHub
Add a README → this creates the main branch
Add your partner as a collaborator
Do NOT write code or run git init. Your job is to own & review, not build.
Developer
Clone the repo (do NOT run git init):
git clone <repo-url>
cd <repo>
Create a branch for your work:
git checkout -b branch-name
Add your code and necessary files
Commit and push your branch only:
git add .
git commit -m "Setup"
git push -u origin branch-name
Open a Pull Request → from your branch into main
Gatekeeper after PR
Review the PR and merge it
Clone the repo
git clone <repo-url>
cd <repo>
Pull the latest code from main :
git pull origin main
Run the project code and test it (If it’s a notebook, you just open it in Jupyter/VS Code and run it)
Gatekeeper Checklist
Does the code run?
 Are required files present?
 Was anything unnecessary committed (env folders, caches, etc.)?
If something is wrong → request changes from Developer.
Then Switch Roles!
Everyone should experience both Developer and Gatekeeper duties.