# github-commands

#### Description
This repo contains all the github commands that I use regulary.


#### Create repository
Go to github and create a new repository with a README.md

#### Clone repository
1. Go to github and copy the name of the repository
2. Open the terminal
3. ``` git clone hereEnterTheNameOfTheRepo ```

#### Code new changes on your machine
This is the step where you code your stuff

#### Create a new branch
1. Open the terminal
2. Look at the current branch in use with the command ``` git branch ```
3. Create a new branch ``` git checkout -b hereIsTheNewBranchName ```
4. Look at the current branch in use with the command ``` git branch ```

#### Add, commit and push the changes to the new branch
1. Open the terminal
2. Look at the changes you made with the command  ``` git status ```
3. Add the changes with the command ``` git add . ```
4. Commit the changes with the command ``` git commit -m "enterTheCommitMessageOfYourChange" ```
5. Push the changes with the command ``` git push origin hereIsTheNewBranchName ```

#### Create a pull request
1. Go to github
2. Go in the pull request tab
3. Create a new pull request
4. Assign someone

#### Merge a pull request
1. Once the pull request is ok, it can be merged otherwise do the appropriate changes
2. Delete the branch (only keep master)
3. Open terminal
4. Look at the current branch in use with the command ``` git branch ```
5. Switch to the master branch with this command ``` git checkout master ```
6. Pull recent changes of the master branch from github ``` git pull ```

#### Pull recent changes
In case that the current code that you are working on is not the latest version, do this command on your machine : ``` git pull ```


