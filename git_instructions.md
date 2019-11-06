# How to contribute using Git and GitHub

## Step 0: Be a member of the SOAR GitHub Team
If you are not a member already message Madison Kozee or Ian Sanders on Slack.

## Step 1: Download Git
Go [here](https://www.git-scm.com/downloads) and download the version for your OS. If on Linux use your distros package manager.

## Step 2: Open your terminal

* **Windows** - Open *Git Bash*
* **MacOS/Linux** - Open *Terminal*

## Step 3: Configure Git

Run both of these commands and substitute `<username>` and `<email>` with your GitHub username and email. The brackets are replaced as well so it will just be your username in parentheses.
``` 
git config --global user.name "<username>"
git config --global user.email "<email>"
```

## Step 4: Navigate to where files will be stored

If you want the main directory **irec-avionics-payload-pcb** to be in **Documents** then run `cd Documents`


## Step 5: Clone the project

```
git clone https://github.com/usfsoar/irec-avionics-payload-pcb.git
```

## Step 6: Navigate into the cloned directory

```
cd irec-avionics-payload-pcb
```

## Step 7: Create a new branch for your feature

Replace `<name_of_branch>` with a short but discriptive name of the feature you are working on. Note, you will be prompted for your GitHub password and username at this step.

```
git pull
git checkout -b <name_of_branch>
git push origin <name_of_branch>
```

## Step 8: Edit the files for your feature/change

Make all of the edits to the project here before you go to the next step

## Step 9: Commiting changes

Replace `<git_commit_message>` with a discription of what changes you made so it is clear what the changes to the project are

```
git add .
git commit -m "<git_commit_message>"
```

## Step 10: Push branch to GitHub

Push your branch to GitHub, make sure to keep the branch name consistant by replcing the `<name_of_branch>` with the same name of the branch from earlier

```
git push -u origin <name_of_branch>
```

## Step 11: Pull Request

Now go to the GitHub project pull request page [here](https://github.com/usfsoar/irec-avionics-payload-pcb/pulls) and make a pull request saying what you changed and why it should be part of the project.
