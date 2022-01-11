# Resources-for-Bootcamp-Students
Extra resources for coding bootcamp students. 


## Git 

Git is an open source command line tool that allows software developers to perform version control and collaborate with other developers. Think Google Docs for software developers. You'll need a basic understanding of how your file systems is organized (directories and files) and basic navigation on your terminal. 

Using git at first will seem foreign, but with repeated practice it will become more natural and you'll see the benefits of it. The more you use it, the better you'll get at it. While you are learning, run the command ```git status``` after every git command to see the state of your repository. The messages back generally will point you in the direction of what you need to do next. 

<details><summary><b>Installing Git on MacOs</b></summary>
      
Mac computers often come with git pre-installed. 

To check if that's the case, open the Terminal application and run the command: ```git --version```. 

If you have it installed, it will respond with the version number you have. Otherwise, it will say something to the effect of, “command not found”.

If you need to install it, follow the installation instructions here: https://git-scm.com/download/mac

I recommend using the homebrew package manager to install git. Take a few minutes and follow the link to read about homebrew and get it installed if you don’t have it already. 

</details>

<details><summary><b>Installing Git on Windows</b></summary>
Windows typically doesn not have git preinstalled. You can follow the Windows installation instructions here: https://git-scm.com/download/win
Note that during the installation process you will be prompted to answer a series of configuration questions. If you aren't sure what the options are, it's generally safe to accept the default settings. They can be changed later if needed. 
</details>

<details><summary><b>Git quick reference</b></summary>
  
  
Use these commands as a reference when you are first connecting a git repository on your local computer to a remote repository on your Github.com account

```console echo "# github-cheatsheet" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/blentz100/github-cheatsheet.git

git push -u origin main
```

Once your local repository is connected to the remote repository, you can use the commands below as a framework for saving your changes at regular intervals.  

```console 

git add .

git commit -m "second commit"

git push
```
</details>

<details><summary><b>Common problems when first using github</b></summary>
  
  
You try to push your code to your Github repo but you get this error:

```console
src refspec master does not match any
```

If you see this error, it's possible your local branch is named master and the remote is named main. You can run ```git status``` to see what your local branch name is. After you first iniatilize your local git repo, it's a good idea to change the branch name to main by typing ```git branch -M main```.

It's also a really good idea to change your default git configuration to always use ```main``` as the default branch name so you don't have to change it every time you make a new repo. You can do that by running ```$ git config --global init.defaultBranch main```. If that doesn't work for you, read this [article](https://www.seancdavis.com/blog/git-set-default-branch/)
</details>

<details><summary><b>Additional Git Resources</b></summary>

[MIT Missing Semester Lecture on Version Control](https://missing.csail.mit.edu/2020/version-control)
  
[Learn Git Branching](https://learngitbranching.js.org)
  
[Pro Git Book](https://git-scm.com/book/en/v2)

</details>

## Github

Github is a popular platform for developers to host software projects and adds a ton of additional functionality on top of git. 

The [Github Hello World Tutorial](https://docs.github.com/en/get-started/quickstart/hello-world) is a good first exercise to help you get familiar with GitHub. 

[Awesome Github Profiles](https://github.com/abhisheknaiidu/awesome-github-profile-readme) for inspiration when customizing your own profile

[Contribute To Open Source](https://github.com/danthareja/contribute-to-open-source) Try contributing to this practice project to get a better sense for what Github is all about.

[GitHub Learning Lab](https://lab.github.com/)

[Github Markdown Preview Tool](https://markdown-it.github.io/)

## Interview Preparation

[Interview Questions](https://github.com/blentz100/Interview-Questions)

[Questions to Ask During an Interview](https://github.com/blentz100/Questions-to-Ask-During-an-Interview)

## Coding Challenges

Codewars has good beginner level challenges for Javascript. 

Freecode camp has good basic level mini tutorials for Front End Development concepts. 

Leetcode has some more advanced level coding challenges. 
