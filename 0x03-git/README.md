# Solutions for Git task

## Setting up

- Setup your local git identity
  - `git config --global user.name "your-name"`
  - `git config --global user.email "your-email@example.com"`
- Ensure your token or SSH keys have been generated and properly configured

## Initializing Repo

- First, create a folder for the repo. `mkdir <direcrtory-name>`
- Change directory. `cd <directory-name>`
- Initialize an empty repo. `git init`

## Clone or set the remote source to track

- Clone: `git clone <url>` **OR**
- Set remote: `git remote add <remote-name> <remote-url>`

## Pushing for the first time

After you are done and ready to push your changes, use the command `git push -u <remote-name> <branch>` <br />
Example: `git push -u origin main` <br />

Subsequent pushes can be accomplished with just `git push`. This remains true until there's an edge case, like pushing to a new branch.<br/>
This case also uses the format `git push -u <remote-name> <branch>` **for the first time.**
