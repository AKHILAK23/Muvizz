# music--equilizer
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/AKHILAK23/music--equilizer.git
git push -u origin main




1. **Fork this Repository**
Fork this repository by click on fork button on the top right corner of this page. This will create a copy of this repository in your account.

2.**Clone Repository**
Now you are at your forked repository at your profile.
At the right side corner find code button
Now clone this repo to your machine. Click on the code button and then click the copy to clipboard icon.
Now go to location on your computer where you want to store the local copy of this repository, where you will work on it.
After this, open a terminal and run the following git command: -- git clone url-you-copied
For eg: git clone https://github.com/your-github-username/first-contributions.git

where your-github-username is your GitHub username.

3**.Create a branch**
Change to the repository directory on your computer (if you are not already there): cd first-contributions

Now create a branch using the git checkout command: git checkout -b <add-your-full-name>

For example: git checkout -b add-salim-kumar

4.Make necessary changes and commit
Now open Contributors.md file in a text editor. Refer to this cheat sheet which gives information on how to use Markdown which is used to write in GitHub MD files

In this case, add the following line at the end of Contributors.md:

- [Your-name](https://github.com/Your-username)

Make sure there is no space between ]( . Save the file.

Go again to terminal and go to project directory and execute the command git status, you'll see there are changes which are unstage. Add those changes to the branch you just created using the git add command:

git add Contributors.md

Now commit those changes using the git commit command:

git commit -m "Add <your-name> to Contributors list"

For Example: git commit -m "Add Salim Kumar to contributors list"

Caution: Don't forget to add -m it specifies message to commit. If you forget it will take you to vim terminal which is difficult to operate.

5.Push changes to GitHub
Push your changes using the git push command: git push origin <branch-name>

replacing <branch-name> with the name of the branch you created earlier.

6.Submit your changes for review
Now go to your repository on GitHub, you'll see a New pull request button. Click on that button. It will compare your branch with the original repository. Check if the comparing branch is your created branch

Now submit the pull request.

Soon I'll be merging all your changes into the master branch of this project.

Cheers 😁
