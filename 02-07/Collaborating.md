# BDL - Versioning - 04: Collaborating

> Learning goals

**TODAY**
- Markdown (recap)

- Collaborating with GitHub:
- Review branching and merging
- Pull requests and Code review
- Conflicts
<!-- - Open source, forking in GitHub -->

# Working as a Collaborator on GitHub
1. Accept Collaboration Invite
2. Clone the Repository
 with this command
 ```bash
 git clone https://github.com/username/repository-name.git

 ```

3. Create a Personal Branch
```bash
git branch name
or 

git checkout -b your-username

or 

git switch -c name

```

4. Make Changes
5. Commit Changes
```bash

   git add .
   git commit -m "Describe the changes made"

```
6. Push Changes to GitHub
```bash
git push origin your-username

```   

7. Create a Pull Request
   - On GitHub, navigate to the repository.
   - Click on 'Pull requests' > 'New pull request'.
   - Set base: main and compare: your-username.
   - Click 'Create pull request', add details about your changes, and submit for review




## Resolving Conflicts in GitHub
1. Ensure your local main branch is up-to-date with the remote repository
   
```bash 
   git checkout main
   git pull origin main

 ```

2. Switch to Your Feature Branch
```bash
git checkout hiba

```

3. Merge the Main Branch into Your Feature Branch
```bash

git merge main
git rebase main

```