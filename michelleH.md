# Writing in Markdown

Below you'll find several sections with instructions. Inbetween the two comment tags marked "Start of Section #" and "End of Section #" complete the instructions for that section.

Check off each step as you complete it and [refer back to the reading](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) often to assist!

---

#### Section 1 Instructions
- [x] Add a level 2 heading called "Collaborative Programming"
- [x] Add a link to the collaborative programming reading, the link should say "What is pair programming?" 
- [x] Add a JavaScript code block that contains a jsdoc comment. Take one from a previous replit, use the one from the reading, or create a new one. 
- [x] Add a level 3 heading called "Pair Programming at Pursuit"
- [x] Make an ordered list of the reasons Pursuit wants you to pair program. This list should be bold.

---

<!-- Start of Section 1 -->

## Collaborative Programming


[What is pair programming?](https://github.com/9-5-pursuit/unit-fundamentals/tree/main/collaborative-programming#what-is-pair-programming)


```js
 /**
 * created header with 2 #
 * created a link for the words what is pair programming 
 * adding the url and the name displayed as a link 
 */
 ```




### Pair Programming at Pursuit


**Reasons Pursuit Wants You To Pair Program:**

1. **Knowledge retention and sharing. It is inevitable that at some point another student will know more than you about a particular topic, and vice versa. Pairing gives you multiple opportunities to gain knowledge from other Fellows, or share that knowledge.**

2. **Focus. When you're working with another person, it's difficult to get sidetracked. Working with other Fellows will help both of you stay on task so that you can efficiently complete your assignments.**

3. **Expediency. When you're working with a pair, it's less likely that you will get stuck on frustrating problems like syntax errors. This is because you will have someone else looking on who will be able to spot your small mistakes. Instead, you'll get stuck on the larger, more difficult problems. And that's good! You want to spend your time working through misunderstandings, not spellchecking your variables.**

4. **Community. The students you work with could be your future coworkers, so it's important to have many chances to work with them. While pairing, you'll be developing your interpersonal and teamwork skills which are critical for your future roles.**


<!-- End of Section 1 -->

---

#### Section 2 Instructions
- [x] Add a level 2 heading called "Intro to the Command Line"
- [x] Add a link to the intro to command line reading, the link should say "What is the terminal?" 
- [x] Add a level 3 heading called "Keywords"
- [x] Re-create the list of keywords from the intro to command line reading, making sure to mark all code keywords as the reading did.
- [x] Add a level 3 heading called "Examples"
- [ ] Create a bash code block containing the following examples, each example should have a code comment above it describing what it's doing:
    - Check your current file path
    - List the files and folders in your current directory
    - Make a directory
    - Navigate to that directory
    - Create a file within that directory
    - Move up one directory
    - Open a directory in Visual Studio Code
    - Open a directory in Finder
- [x] Add a level 3 heading called "Tips"
- [x] Recreate the tips section from the intro to command line reading
---

<!-- Start of Section 2 -->

## Intro to the Command Line

[What is the terminal?](https://github.com/9-5-pursuit/unit-fundamentals/tree/main/intro-to-command-line#what-is-the-terminal)



### Keywords


- Operating System (OS)
- Graphical User Interface (GUI)
- Command Line Interface (CLI)
- Terminal
- Shell
- Folder = Directory
- `pwd` - print working directory
- `cd ..` - go to parent directory (aka up)
- `cd [folder]` - go into folder
- `~` - represents your home folder
- `ls` - list files and subfolders in current folder
- `touch [filename]` - creates a new file
- `mkdir [directory name]` - make a new directory
- `code [filename]` - open VSCode editor



### Examples

```bash 
# Check your current file path
pwd
# List the files and folders in your current directory
ls
# Make a directory
mkdir [directory name]
# Navigate to that directory
cd [directory name]
# Create a file within that directory
touch [filename]
# Move up one directory
cd ..
# Open a directory in Visual Studio Code
code [directory name]
# Open a directory in Finder
open [directory name]

```


### **Tips**
---

- Use tab to autocomplete. for example, if the current folder has subfolders titled `games`, `photos` and `photography`, typing `pho` and pressing the tab key will result in displaying `photo` and `photography`. If we then type the letter `g` to get `photog`,and press the tab key - the command will be autocomplete to `photography`.

- You can also use the up and down arrow keys to cycle through all the commands you've typed.

<!-- End of Section 2 -->

---

#### Section 3 Instructions
- [x] Add a level 2 heading called "Git"
- [x] Add a link to the git presentation that we covered in class, the link should say "Git, what is it good for?" 
- [x] Create a bash code block showing how to do the following:
    - Make a directory
    - Navigate to that directory
    - Initialize a Git Repo
    - Create a readme.md file
    - Check the status of the repo
    - Stage the readme.md file
- [x] Put together instructions, utilizing code blocks when necessary, describing the following steps:
    - Open the directory you created previously in Visual Studio Code
    - Update the readme.md file
    - Compare the differences between the staged and unstaged readme.md files
    - Stage the changes to the readme.md file
    - Commit the changes
---

<!-- Start of Section 3 -->

## Git


[Git, what is it good for?](https://docs.google.com/presentation/d/1KSqHQw8DxaZTtGQn5VKjP_Ljv4H_zc2hfE1CEVH8M8o/edit#slide=id.g420132f636_0_109)

### Examples

```bash 
# Make a directory
mkdir [directory name]
# Navigate to that directory
cd [directory name]
# Initialize a Git Repo
git init
# Create a readme.md file
touch readme.md
# Check the status of the repo
git status
# Stage the readme.md file
git add .
```

### Try it yourself:
1. Open the directory you created previously in Visual Studio Code
- in your terminal: `code .`

2. Update the readme.md file
- edit file in VSCode
- save changes

3. Compare the differences between the staged and unstaged readme.md files
- go back to your terminal: `git diff`

4. Stage the changes to the readme.md file: 
`git add .`

5. Commit the changes: 
`git commit -m "A message about your changes"`



<!-- End of Section 3 -->

---

#### Section 4 Instructions
- [x] Add a level 2 heading called "GitHub (YourGithubUsername)"
- [x] Add a link to the GitHub reading, the link should say "GitHub, Let's build from here"
- [x] Create a level 3 heading called "Connecting Local to Remote"
- [x] Create a level 4 heading called "Local vs. Remote"
- [x] Describe, in your own words, what the difference between a local repo and remote repo is. 
- [x] Create a level 4 heading called "Getting ready on your local machine"
- [x] Copy the above section from the GitHub reading and highlight the code snippets where necessary.
- [x] Create a level 4 heading called "Creating a new repository"
- [x] Create a list detailing how to create a repository on GitHub (use the GitHub reading)
- [x] Create a level 3 heading called "Push your code"
- [x] Copy the "Push Your Code" section from the GitHub reading and format it the same way.
- [x] Create a level 3 heading called "Collaborating with GitHub"
- [x] Create a step by step task list for the collaboration process. Include the following:
    - Forking
    - Cloning
    - Making Changes
    - Pull Requests

---

<!-- Start of Section 4 -->

## GitHub (chellxh)


[GitHub, Let's Build From Here](https://github.com/9-5-pursuit/unit-fundamentals/tree/main/github/reading)



### **Connecting Local To Remote**

#### **Local vs. Remote**


The difference between a Local Repositiory and a Remote Repositiory is:

**Local Repository** is the repository that is stored on your *local* machine. You are the only person that has access to this repository. Any edits or changes to this contents in this repo is seen only by you.

**Remote Repository** is a repository that is stored somewhere else (in this case **GitHub**). All changes and edits can be seen on this repository by anyone with permission. This repository can be downloaded onto your local machine also.


#### **Getting Ready on Your Local Machine**


Before creating a remote repository on GitHub, you'll need a local repository with at least a single commit. That means you'll need to:

- Create a new directory with at least one file.  

- Initialize that directory as a git repository with `git init`.  

- Stage and commit files, with `git add` and `git commit`.  

You can always check if your directory is a git repository and has a single commit by running `git log`.


#### **Creating A New Repository**

You can create a new repository on [GitHub](https://github.com/) by clicking the green button on the left side of the website.
![Picture of GitHub Green Button Circled](/greenbutton.png)


You can also create a new repository by clicking the plus sign on the top right corner of the GitHub website.
![Picture of Plus Sign Circled On GitHub Website](/plusrepo.png)


You should give your repository the same name as the folder that contains your repository on your local machine.

At the bottom of the screen, it gives you the option to initialize your repository with some files. You will have already initialized your repository on your local machine, so you do not need to check these boxes.

After clicking the "Create repository" button, you will be brought to a new page that includes a number of code blocks.
![Picture of code blocks to do after creating a new repository](/afterCreateRepo.png)


### **Push Your Code**

There are three commands that are run to connect your local repository to your remote repository. Typically, you can copy and paste these commands directly into your terminal. However, it's important to generally understand what each command is doing.

`git remote add origin <url>`

When you run this command inside of your local git repository, this command connects your local repository with your remote repository.

As you can see by reading the command, a new "remote" is added at the given URL. The name "origin" is just that -- a name for the remote. This name *could* be whatever you want, but you can just leave it as origin.

`git branch -M main`

This command sets the name of the main "branch" to be called `main`. You will learn more about branches later on. For now, know that the `main` branch is where your commit history will live. Your local repository also has a `main` branch -- these two branches will be connected.

`git push -u origin main`

The `git push` command moves all of the commits from your local repository to your remote repository. This is the command that gets the two synchronized.

The `-u` flag sets the "upstream" default for this branch to always be the remote with a name of "origin" and the branch with the name of "main."

Because of the `-u` flag, moving forward you can just write `git push` from your local `main` branch and git will know that you want to push to the main branch of the remote repository by the name of "origin".


### **Collaborating with GitHub**


GitHub is designed to work particularly well for sharing code and collaborating with others. GitHub has useful features when working on group projects.


#### **Forking**  


Forking a repository mean to make a duplicate of it on your own GitHbu *account*. The "forked" repository maintains a connection to the original repository.

Anyone can fork a public repository. To Fork a repository, you can click the Fork button at the top of any repository you have access to. After a brief moment, you'll be brought to a new page which is *your* version of the forked repository.

You should see your account name as the owner of the repository, which will have the same name. You should also see that your repository is forked from the original repository.

Now you have a forked version of the code which means you can update and change it as you like.


#### **Cloning**


Cloning is the process of taking a remote repository from GitHub and creating a synchronized version of it on your computer.

Before cloning, you should do the following on your local machine:

1. Navigate to a directory that is not a git repository.

2. Navigate to a directory that is the parent directory of where you want this repository to live.

3. Make sure that there is not already a folder inside the directory that has the same name as the repository.

Once you've confirmed the above, you will click on the green "Code" button and then copy the URL that is there.


On the command line, you will then run the following command, replacing `<url>` with the URL you just copied.


`git clone <url>`


This will start a process of downloading all of the files associated with your forked repository. All of those files will go into a new folder with the same name as the repository.

You now have a local version of your remote repository. Your local repository:

- Already has its remote set to be your forked repository.

- Has the same history as the remote repository.

- Is yours, which means you can add your own commits!


#### **Making Changes**

You can now work on your forked repository in the same way you would work on any local repository. Make changes, stage those changes, and make new commits. You can also push your changes from your local repository to the forked repository in the same way.

### **Pull Requests**


Once you've added at least one new commit, you can create a pull request. Pull requests are a way to suggest changes to a repository without forcefully changing that repository. In a real development workflow, someone would be tasked with reviewing that pull request and determining whether or not your code should be accepted.


#### **Creating Pull Request**


To create a pull request, click on the "Contribute" dropdown and then click the green "Open pull request" button. 

After you click the "Create pull request" button, you'll see an area what you can add more details about your pull request.

You can find your pull request by returning to the original repository and then clicking the Pull Requests tab. There you will see all of the pull requests for this repository.

<!-- End of Section 4 -->

---

#### Section 5 Instructions
- [x] Add a level 2 heading called "My Time at Pursuit"
- [x] Add an image that represents your time in the program so far.
- [x] Add a list with the following 3 things:
    - One thing you need to work on
    - One thing you feel you understand well
    - One thing you are looking forward to learning
- [x] Create a to-do list for your long weekend
- [x] Add a quote that keeps you motivated to keep pushing.
- [x] Add a paragraph of bold text describing who you're doing this program for and why.
---

<!-- Start of Section 5 -->
## **My Time At Pursuit**

![Naruto and Sasuke Fighting - An Even Match Up](https://media.tenor.com/_J_gjB8wifoAAAAd/naruto-vs-sasuke-anime.gif)

#### **Overview**

1. One thing I need to work on:
    - Time Management
2. One thing I feel I understand well:
    - Git
3. One thing I am looking forward to learning:
    - HTML


#### **To-Do List**
---
- practice, practice, practice
- expand comprehension of newer topics
- sleep .

#### **Motivation**

> You are very special!
> 
> — Mikey

**My motivation is my family. My wonderful husband who works so hard for our family and supported every decision I've made, whether it was to be a stay-at-home Mom or to join a bootcamp to make more opportunities for us as a family. My son Mikey who is the smartest, kindest, funniest, and intuitive 7 year old ever and my daughter Emma who is the spiciest, sweetest, boldest, and adventure filled 4 year old ever. My family is the motivation pumping through my veins. I want to set the example that my children can live by. Failure is not an option for me.**

<!-- End of Section 5 -->

---

## Done?
- Rename your markdown file using your first name and first initial of your last name (for example, mine would be anthonyp.md)
- Create a pull request