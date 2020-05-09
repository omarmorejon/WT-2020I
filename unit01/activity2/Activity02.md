# Activity: GIT Repositories

![](https://marine.rutgers.edu/~cfree/wp-content/uploads/git-and-github-workflows-12-638.jpg)

## Part 1: Individual part

The purpose of this part is to get acquainted with [Git](https://git-scm.com) and [GitHub](www.github.com)

- Create an account / Log in to [GitHub](www.github.com).

- Create a new repository in GitHub
  + Repository name: `my_repo`

- Clone the repository locally (in you computer)

  ```
    git clone https://github.com/<username>/my_repo.git
  ```
  It will create a new directory called `my_repo`


- Create a text file `my_first_git_file.txt` inside the directory `my_repo`
  - Add some text to the file and save it.

- Save your local changes using the below commands:
	- `git add [file]`
	- `git commit -m “[descriptive message]”`

- Publish your local changes onto the remote repository
	- `git push`



## Part 2 (Group activity):

The purpose of this part is to work in a collaborative fashion.
Members of a repository (`shared_repo`) will contribute and perform actions like add, commit, push and pull.

- Create a repository (one per group) in [GitHub](www.github.com)
  + Repository name: `shared_repo`

- Invite your classmates as collaborators in this repository

- Clone the repository locally (to your computer)
  ```
  git clone https://github.com/<username>/my_repo.git
  ```
- Only one participant should copy the file `collaborative_work.md` in his/her local directory `shared_repo`.
  - Add, commit and push the file so that other participants can `git pull` the file.

- After the previous point is done, all the others participants must pull the changes of the repository and work on the file `collaborative_work.md`.

- All participants must add content to the file in the corresponting sections.
  - Save changes and commit as you work (at least one commit for each subsection)

- Pull and Push, so you get any update from your mates and they get your changes.

- Practice the commands:
  - `git add [file]`
  - `git commit -m “[descriptive message]”`
  - `git push` Transmit local branch commits to the remote repository branch
  - `git pull` Fetch and merge any commits from the tracking remote branch

## Deliverable

- A PDF document that includes a screenshot of the `shared_repo` contributors. You can find the contributors information in the Github's tab `Insights / Contributors`


## Software requirements

- [Git](https://git-scm.com)
- [GUI for Git - Github desktop](https://desktop.github.com) *(optional)*
- [Text editor Atom](https://atom.io) *(optional)*


## Extra info

- [Git cheatsheet](https://education.github.com/git-cheat-sheet-education.pdf)
- [Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
