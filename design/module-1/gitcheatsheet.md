---
header: "Lesson Git:1 "
marp: true
theme: default
size: 16:9
paginate: true
color: #111
backgroundColor: #eee
_footer: "@2022 [Ludvig Alvir](https://www.noroff.no/en/contact/staff/) using [Marp](https://marp.app/)"
---

<!-- prettier-ignore -->
# Git

Download for windows https://gitforwindows.org/

---

<!-- prettier-ignore -->
## navigation

- ls

  - Shows files at current location

- cd "path"
  - change directory to specified path
  - cd ".." to go back

---

<!-- prettier-ignore -->
## Create files

- mkdir "new directory name"

  - Creates a new directory with specified name at current path

- touch "filename"
  - creates a file at current path with specified name

---

<!-- prettier-ignore -->
## Cloning

git clone "https://linktoyourgithubrepository"

- Adds the specified repository to your current path

git pull

- updates your local repository with last version on github

---

<!-- prettier-ignore -->
## committing

git add "name of files or directories you want to add, or \* to add all"

- choses what to add

git commit -m"commit message"

- committing the action to do, the message will be in the git Logo

git push origin main/master

- pushes the changes to the main/master repository on github (later we will use branches).
