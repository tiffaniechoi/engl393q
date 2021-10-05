# Setup
To get git setup on your local environment, follow the steps below.

## SSH Key
> ** Note:** Follow the steps in the link below to generate a ssh key, and adding it to the ssh-agent

Link: https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

## How to get started
The steps below will only work once your ssh key is added.

### Clone repository 
1. Go to your git repository site
1. Under code, click the code button and copy the ssh link provided
1. In your local terminal, go to your desired directory
1. Enter this command `git clone <ssh link>` with the ssh link being the one you copied in step 2

Great! Now the repository is cloned onto your local machine!

## Features
This goes over how to work on software development locally, and merging your local work to the remote master branch. 

### Create a branch
In your cloned repository, enter these commands:
1. `git branch <enter branch name here>`
1. `git checkout <branch name>`

### Saving the changes
Now you have switched over to your own branch!
Once you have made the desired changes, enter these commands below to create a PR:

1. `git add .`
1. `git commit`
1. `git push --set-upstream origin <branch name>`

You can now view the branch on online, and click the `compare & pull request` button. 
Once a code owner reviews your work, your branch will be merged to master!
