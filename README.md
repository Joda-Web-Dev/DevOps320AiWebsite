# README

## Purpose
This repository was created as an assignment to demonstrate an AI-generated website. 

## Steps to Set Up Git and Push Code
1. **Initialize Git:**
   - Ran the command `git init` to initialize a Git repository in the project directory.

2. **Set Git Configuration:**
   - Configured username and email for Git by executing:
     git config --global user.name "My Username"
     git config --global user.email "My email"
     

3. **Stage Files:**
   - Added all files to the staging area with:
     git add .

4. **Commit Changes:**
   - Created the initial commit with:
     git commit -m "Initial commit"

5. **Create Repository on GitHub:**
   - Logged into my GitHub account.
   - Created a new public repository.

6. **Link Remote Repository:**
   - Linked the local repository to the GitHub repository using:
     git remote add origin https://github.com/YourUsername/YourRepositoryName.git


7. **Push Code:**
   - Pushed the code to the master branch:
     git push -u origin master

## Challenges Faced and Resolutions

Thankfully I have done this several times and didn't face any issues this time.

This README serves as a guide to understanding the purpose and development process behind this repository.

UPDATE - Setting up Github Actions

1. I turned off automatic publishing on Github.
2. Created the .github\workflows directory, and the deploy.yml file using the file provided in the assignment
3. Added, committed, and pushed changes
4. Checked workflow on Github and made sure everything worked
5. Checked that the site is live and updated.

Deployment can be triggered by pushing to the master branch, or manually on the github repository. 
For manual deployment, go to github repository, actions, deploy static content to pages and click run workflow.