# ai-startup-website
This is my first repository as a DevOp Engineer
```
In this project, I developed a startup website as part of my practical learning exercise. During the process, I also created and worked with two separate branches to simulate a real-world collaborative development workflow. This involved running and practicing several basic Git commands to manage version control effectively.

To provide clarity on the steps I carried out, I have included snapshots of each command executed in the terminal, demonstrating how the branches were created, switched, updated, and eventually merged back into the project workflow.
```
## mkdir 
At this stage, I created a new repository directory by using the mkdir command in the terminal. This command established a dedicated folder that will serve as the storage space for all the files and resources related to my project.

Once the folder was created, I then used the cd (change directory) command to navigate into the newly created repository directory. This ensured that all subsequent commands would be executed within the correct project location.

After navigating into the directory, I proceeded to initialize the repository by running the git init command. This step set up the necessary Git structure within the folder, enabling version control and allowing me to begin tracking changes, creating branches, and managing the project effectively.

![](./img/1.mkdir.png)

## git clone command
In this step, I cloned the repository from my GitHub account using the git clone command. This action created a local copy of the remote repository on my system, ensuring that all files, version history, and configurations from GitHub were successfully downloaded and stored within my local environment.

Once the repository was cloned, I then used the cd (change directory) command to navigate into the cloned repository folder. This placed me inside the working directory of the project, allowing me to perform further Git operations such as creating branches, committing changes, and pushing updates back to GitHub.
![](./img/2.git-clone.png)

## touch
In this step, I used the touch command to create a new file named index.html inside the main repository. This file will serve as the foundation for my HTML documentation and the starting point for developing the structure of the project website.

After creating the file, I executed the code . command, which opened the entire repository folder in Visual Studio Code (VS Code). From there, I was able to begin editing and documenting content directly within the index.html file in a structured and user-friendly environment.

Additionally, I used the git status command to check the current state of the repository. This allowed me to verify that the newly created index.html file was recognized by Git as an untracked file, ensuring that I could keep track of its changes and prepare it for staging and committing in the next steps.

![](./img/3.index.html.main.png)

## git add command
In this step, I used the git add command to stage the index.html file, preparing it to be saved in the repository. After that, I ran the git status command to confirm that the file was staged successfully. Finally, I used the git commit -m command to save the changes with a message, making the update part of the project’s history.

![](./img/4.git-commit-main.png)

## git push command
In this step, I used the git push command to upload the updated changes from my local repository to the main repository on GitHub. 

![](./img/5.git-push-main.png)

## git checkout -b command
 I used the git checkout -b command to create a new branch and switch into it right away.

![](./img/6.git-branch-update.png)

## echo & git add command
I used the echo command to write a simple HTML structure into the index.html file. After that, I used the git add command to stage the file.

![](./img/7.Tom's-html.png)

## git commit -m command
I used the git commit -m command to save my changes with a message in the repository.

![](./img/8.Tom's-commit.png)

## git push origin command
I used the git push origin command to upload my committed changes from the local repository to the remote repository.

![](./img/9.Tom's-push.png)

## git pull command
I used the git pull command to download the latest changes from the remote repository to my computer.

![](./img/10.git-pull.png)

## 