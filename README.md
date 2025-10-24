# Tutorial 4 – Git & GitHub Collaboration

**Author:** Jasanie Austin  
**Collaborator:** Jemar Foster  

---

## Purpose
This repository was created as part of **Tutorial 4** to demonstrate how to use Git and GitHub for version control and collaboration.  
It showcases the creation of branches, commits, pull requests, and approvals between two collaborators.

---

## Steps Taken
mkdir tutorial4 && cd tutorial4
git init
git remote add origin https://github.com/J-A-Austin/tutorial4-Jasanie-Austin.git
git checkout -b feat/add-name-file
print("Jasanie Austin")
# updated branch version
git add name.py
git commit -m "Added sample file for tutorial"
# Opened Pull Request
On GitHub, a Pull Request was created to merge the feat/add-name-file branch into the main branch.
The collaborator Jemar Foster was assigned as the Reviewer.
# Approval and Merge
Once Jemar Foster reviewed and approved the PR, it was merged into the main branch, completing the collaboration process.


