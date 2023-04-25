# Subjects

- Markdown ( review )
- Git ( review )
- Github
- Connecting to GitHub with SSH
- Creating a repository on Github
- Branches ( review )
- Merging Pull Requests

## Markdown

What is Markdown?

Markdown is a lightweight markup language (simple or humane markup language) for creating formatted text.

Markdown Guide: https://www.markdownguide.org/

Why I should use Markdown?

- documentation

- web pages

## Git

![image info](https://media.tproger.ru/uploads/2020/12/git_guide_for_beginners-cover-icon-original.png)


What is Git?

![](https://cdn.movavi.io/pages/0013/24/2448dd0f445a993039a57f67714a8a0a921994c8.webp)


- specific open-source version control system.


- the entire codebase and history is available on every developer&#xb4;s computer.


- allows for easy branching and merging.


## Github

![](https://i.ytimg.com/vi/OEGm7LXAN_c/maxresdefault.jpg)

What do you know about Github?


GitHub is a website and cloud-based service that helps developers store and manage their code.


Vs Code: https://github.com/microsoft/vscode

There is another website called Gitlab, which is similar to Github. But Github is more popular and has more features.


Why I shoud use Github?


- It is a great platform to backup your project if something get wrong with laptop.


- It is a great way to share your code with others and collaborate on projects.


- It is a great way to learn from others and improve your skills.


How does git and Github working together?

![](https://public.crtil.com/images/s0FGke5TM.png)



## Connecting to GitHub with SSH


You can connect to GitHub using the Secure Shell Protocol (SSH), which provides a secure channel over an unsecured network.


1. Generating a new SSH: https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent


2. Go to your GitHub account settings.


3. Click on SSH and GPG keys.


4. Click on New SSH key.


5. Give a title to your SSH key.


6. Copy the SSH key from your computer and click Add SSH key button.



## Creating a repository on Github


- In your Github account, under Repositories tab In the upper-right corner of any page, use the new button, to create New repository.


- To create a new repository, use the Owner drop-down list, and choose the account you want to own the repository.


- Type a name for your repository and an optional description. 


- Choose a repository visibility, in in my case public and click Create Repository button.


- Follow the instructions to push an existing repository from the command line.


## Branches


branches represent features or bug fixes.


**git branch** command lets you create, list, rename, and delete branches.

```sh
git branch
```


**git checkout** command lets you navigate between the branches.

**git checkout -b** command lets you create a new branch and navigate to it.

```sh
git checkout -b fix-readme
```


```sh
git branch
```


**git status** command lets you check the status of your repository.

```sh
git status
```


**git add .** command lets you add all the files to the staging area.

```sh
git add .
```


**git commit -m** command lets you commit your changes to the current branch.

```sh
git commit -m "Fix readme"
```


**git push --set-upstream origin** command lets you push your branch to the remote repository(Github).

```sh
git push --set-upstream origin fix-readme
```



## Merging Pull Requests


pull request referred to a merge request 

---

### Resources

- [What Is GitHub? A Beginner Introduction to GitHub](https://kinsta.com/knowledgebase/what-is-github/)
- [Generating a new SSH key and adding it to the ssh-agent](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent?platform=linux)
- [Creating a new repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository)
- [What is a difference between local and remote repository?](https://www.bettercoder.io/job-interview-questions/532/what-is-a-difference-between-local-and-remote-repository)
- [The Ultimate Github Collaboration Guide](https://medium.com/@jonathanmines/the-ultimate-github-collaboration-guide-df816e98fb67)