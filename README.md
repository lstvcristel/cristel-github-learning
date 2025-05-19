# My GitHub Learning Journey

Hi there! I'm Cristel, and I have been exploring GitHub to learn more about version control. Here's a summary of what I have learned so far.

## GitHub Basic

I started with the basics:

* Setting up a Repository:

<<<<<<< HEAD
  1.  First, Created a public repository named `cristel-github-learning`
  2.  Then, created a folder named `cristel-github-learning` on my local machine.
  3.  I opened this folder in VS Code.
  4.  In VS Code, I opened the terminal and initialize a Git Repository by running this commands:
=======
  1. First, Created a public repository named `cristel-github-learning`
  2. Then, created a folder named `cristel-github-learning` on my local machine.
  3. I opened this folder in VS Code.
  4. In VS Code, I opened the terminal and initialize a Git Repository by running this commands:
>>>>>>> 69a8635045df73c6abe5f5f8598207c84cd5532c
     * `git init`
     * `git remote add origin https://github.com/lstvcristel/cristel-github-learning.git`
     * `git branch -M main`
     * `touch README.md`
     * `git status`
     * `git add .`
     * `git commit -m "Initial commit"`
     * `git push -u origin main`

* Branching:

  1. Create a new branch: `git branch develop`
  2. Push and set upstream: `git push --set-upstream origin develop`
  3. Switch to new branch: `git checkout develop`
  4. Create and switch branch: `git checkout -b develop`
  5. List all branch: `git branch`
  6. Push a branch: `git push origin develop`
  7. Delete branch from remote repo: `git branch --delete develop`

* Merging:

