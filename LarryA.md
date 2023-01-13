# Writing in Markdown

Below you'll find several sections with instructions. In between the two comment tags marked "Start of Section #" and "End of Section #" complete the instructions for that section.

Check off each step as you complete it and [refer back to the reading](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) often to assist!

---

#### Section 1 Instructions
- [ ] Add a level 2 heading called "Collaborative Programming"
- [ ] Add a link to the collaborative programming reading, the link should say "What is pair programming?" 
- [ ] Add a JavaScript code block that contains a jsdoc comment. Take one from a previous replit, use the one from the reading, or create a new one. 
- [ ] Add a level 3 heading called "Pair Programming at Pursuit"
- [ ] Make an ordered list of the reasons Pursuit wants you to pair program. This list should be bold.

---

<!-- Start of Section 1 -->
## "Collaborative Programming" 

[What is pair programming] (https://github.com/9-5-pursuit/unit-fundamentals/tree/main/collaborative-programming)

```js
/**
 * This function does something. See example below:
 * 
 * var x = foo('test'); // it will show test message
 * 
 * @param {string} str - string argument that will be shown in message
 */
function foo(str) {
    alert(str);
}

```

### "Pair Programming at Pursuit"


1. ***Knowledge retention and sharing. It is inevitable that at some point another student will know more than you about a particular topic, and vice versa. Pairing gives you multiple opportunities to gain knowledge from other Fellows, or share that knowledge.***

2. ***Focus. When you're working with another person, it's difficult to get sidetracked. Working with other Fellows will help both of you stay on task so that you can efficiently complete your assignments.***

3. ***Expediency. When you're working with a pair, it's less likely that you will get stuck on frustrating problems like syntax errors. This is because you will have someone else looking on who will be able to spot your small mistakes. Instead, you'll get stuck on the larger, more difficult problems. And that's good! You want to spend your time working through misunderstandings, not spellchecking your variables.***

4. ***Community. The students you work with could be your future coworkers, so it's important to have many chances to work with them. While pairing, you'll be developing your interpersonal and teamwork skills which are critical for your future roles.***
<!-- End of Section 1 -->

---

#### Section 2 Instructions
- [ ] Add a level 2 heading called "Intro to the Command Line"
- [ ] Add a link to the intro to command line reading, the link should say "What is the terminal?" 
- [ ] Add a level 3 heading called "Keywords"
- [ ] Re-create the list of keywords from the intro to command line reading, making sure to mark all code keywords as the reading did.
- [ ] Add a level 3 heading called "Examples"
- [ ] Create a bash code block containing the following examples, each example should have a code comment above it describing what it's doing:
    - Check your current file path
    - List the files and folders in your current directory
    - Make a directory
    - Navigate to that directory
    - Create a file within that directory
    - Move up one directory
    - Open a directory in Visual Studio Code
    - Open a directory in Finder
- [ ] Add a level 3 heading called "Tips"
- [ ] Recreate the tips section from the intro to command line reading
---

<!-- Start of Section 2 -->
## "Intro to the Command Line" 

[What is the terminal] (https://github.com/9-5-pursuit/unit-fundamentals/blob/main/intro-to-command-line/readme.md)

### "Keywords" 

* Operating System (OS)
* Graphical User Interface (GUI)
* Command Line Interface (CLI)
* Terminal
* Shell
* Folder = directory
* pwd - print working directory
* cd .. - go to parent directory (aka up)
* cd [folder] - go into folder
* ~ - represents your home folder
* ls - list files and subfolders in current folder
* touch [filename] - create a new file
* mkdir [directory name] - make a new directory
* code [filename] - open the VSCode editor

### "Examples" 

```bash

# Check your current file path
pwd

# List the files and folders in your current directory
ls -la

# Make a directory
mkdir my_new_directory

# Navigate to that directory
cd my_new_directory

# Create a file within that directory
touch my_new_file.txt

# Move up one directory
cd ..

# Open a directory in Visual Studio Code
code .

# Open a directory in Finder
open .

```

### "Tips" 

* Use tab to autocomplete. for example, if the current folder has subfolders titled games, photos and photography, typing pho and pressing the tab key will result in displaying photo and photography. If we then type the letter g to get photog,and press the tab key - the command will be autocomplete to photography.

* You can also use the up and down arrow keys to cycle through all the commands you've typed.


<!-- End of Section 2 -->

---

#### Section 3 Instructions
- [ ] Add a level 2 heading called "Git"
- [ ] Add a link to the git presentation that we covered in class, the link should say "Git, what is it good for?" 
- [ ] Create a bash code block showing how to do the following:
    - Make a directory
    - Navigate to that directory
    - Initialize a Git Repo
    - Create a readme.md file
    - Check the status of the repo
    - Stage the readme.md file
- [ ] Put together instructions, utilizing code blocks when necessary, describing the following steps:
    - Open the directory you created previously in Visual Studio Code
    - Update the readme.md file
    - Compare the differences between the staged and unstaged readme.md files
    - Stage the changes to the readme.md file
    - Commit the changes
---

<!-- Start of Section 3 -->
## "Git" 

[Git, What is it good for?] (https://github.com/9-5-pursuit/unit-fundamentals/blob/main/git/readme.md)

```bash

# Make a new directory
mkdir myproject

# Navigate to the directory
cd myproject

# Initialize a Git Repo
git init

# Create a readme.md file
touch readme.md

# Check the status of the repo
git status

# Stage the readme.md file
git add readme.md

```

## Instructions 

1. Open the directory you created previously in Visual Studio Code by running the following command in the terminal:

- code myproject


2. Update the readme.md file using Visual Studio Code's built-in text editor.

3. Compare the differences between the staged and unstaged readme.md files by running the following command in the terminal:

- git diff
- Stage the changes to the readme.md file by running the following command in the terminal:
- Copy code
- git add readme.md
- Commit the changes by running the following command in the terminal:
- Copy code
- git commit -m "Updated the readme file"

<!-- End of Section 3 -->

---

#### Section 4 Instructions
- [ ] Add a level 2 heading called "GitHub (YourGithubUsername)"
- [ ] Add a link to the GitHub reading, the link should say "GitHub, Let's build from here"
- [ ] Create a level 3 heading called "Connecting Local to Remote"
- [ ] Create a level 4 heading called "Local vs. Remote"
- [ ] Describe, in your own words, what the difference between a local repo and remote repo is. 
- [ ] Create a level 4 heading called "Getting ready on your local machine"
- [ ] Copy the above section from the GitHub reading and highlight the code snippets where necessary.
- [ ] Create a level 4 heading called "Creating a new repository"
- [ ] Create a list detailing how to create a repository on GitHub (use the GitHub reading)
- [ ] Create a level 3 heading called "Push your code"
- [ ] Copy the "Push Your Code" section from the GitHub reading and format it the same way.
- [ ] Create a level 3 heading called "Collaborating with GitHub"
- [ ] Create a step by step task list for the collaboration process. Include the following:
    - Forking
    - Cloning
    - Making Changes
    - Pull Requests

---

<!-- Start of Section 4 -->
## "LarryPursuit" 
[GitHub, Let's build from here!] (https://github.com/9-5-pursuit/unit-fundamentals/blob/main/github/readme.md)
### Connecting Local to remote 
#### Local vs. Remote 

Git has two types of repositories: local and remote.

A local repository, as described in [1] and [2], is one that resides on the individual's computer and is only used by them. It is created using the command git init and any changes made to it are only stored on the local machine.

A remote repository, on the other hand, as described in [1], [2], and [3], is typically hosted on a server and is accessible to all members of a team. It is used to store the "centralized" version of a project, and changes made to it are synced with the local repository through the use of git pull and git push commands.

In summary, a local repository is a personal copy of the project that is only stored on an individual's machine, while a remote repository is a centralized version of the project that is accessible to all members of a team, typically stored on a server.

#### Getting ready on your local machine

```js
The git program is different than GitHub, the online service. One of the easiest ways to differentiate the two is to think of where each one "lives."

The git program "lives" on your computer. You can use the git program without having to be connected to the internet.

GitHub is an online service. The majority of GitHub-specific features can only be done on the website.

Note: There are some ways to perform git actions on the web and access GitHub features from your computer. However, in general, this distinction holds.

On its own, git is a powerful tool for managing versions of your own programs. GitHub allows that version control to go global. By sharing your code on GitHub, you can work with other developers around the world. GitHub also has a few specific features that can help for managing projects, even if you're working on your own.

```
#### Creating a new repository

1. Log into your GitHub account.
2. In the upper-right corner of any page, use the drop-down menu, and select "New repository".
3. Fill in the "Repository name" field.
3. Optionally, to create a repository with the directory structure and files of an existing repository, use the "Choose a template" drop-down and select a template repository.
4. Click on "Create repository" button.

Alternatively, you can create a repository using the command line:

1. In the command line, navigate to the directory where you would like to create a local clone of your new project.
2. To create a repository for your project, use the gh repo create subcommand.
3. When prompted, select "Create a new repository on GitHub from scratch" and enter the name of your new project.
4. If you want your project to belong to an organization instead of to your personal account, specify the organization name.

### Push your code

There are three commands that are run to connect your local repository to your remote repository. Typically, you can copy and paste these commands directly into your terminal. However, it's important to generally understand what each command is doing.

`git remote add origin <url>`

When you run this command inside of your local git repository, this command connects your local repository with your remote repository.

As you can see by reading the command, a new "remote" is added at the given URL. The name "origin" is just that -- a name for the remote. This name could be whatever you want, but you can just leave it as origin.

`git branch -M main`

This command sets the name of the main "branch" to be called `main`. You will learn more about branches later on. For now, know that the main branch is where your commit history will live. Your local repository also has a `main` branch -- these two branches will be connected.

`git push -u origin main`

The `git push` command moves all of the commits from your local repository to your remote repository. This is the command that gets the two synchronized.

The `-u` flag sets the "upstream" default for this branch to always be the remote with a name of "origin" and the branch with the name of "main."

Because of the `-u` flag, moving forward you can just write `git push` from your local `main` branch and git will know that you want to push to the `main` branch of the remote repository by the name of "origin".


### Collaborating With GitHub

Creating a psychologically safe environment: Encourage the group to share constructive criticism and praise respectfully. Each individual's experience and talents play into their unique perspective to tackle problems and tasks. 

1. Forking: Create a fork of the main repository, this creates a copy of the main repository under your account. This allows you to make changes and commit them to your own repository without affecting the original repository. 



2. Cloning: Clone the forked repository to your local machine. This creates a local copy of the repository on your machine, which you can use to make changes. 

- `git clone`: Clone the forked repository

3. Making Changes: Make the necessary changes to the local copy of the repository. This can include adding, modifying, or deleting files. 

- `git add`: Add, `git commit -m " "`: commit

4. Pull Requests: Once the changes are made, create a pull request. This is a request for the main repository to accept the changes you made to the forked repository. The owner of the main repository will review the changes and decide whether to merge them or not. 

- `git pull`: pull the changes









<!-- End of Section 4 -->

---

#### Section 5 Instructions
- [ ] Add a level 2 heading called "My Time at Pursuit"
- [ ] Add an image that represents your time in the program so far.
- [ ] Add a list with the following 3 things:
    - One thing you need to work on
    - One thing you feel you understand well
    - One thing you are looking forward to learning
- [ ] Create a to-do list for your long weekend
- [ ] Add a quote that keeps you motivated to keep pushing.
- [ ] Add a paragraph of bold text describing who you're doing this program for and why.
---

<!-- Start of Section 5 -->

## My Time at Pursuit

![My mental state] (https://industrywired.b-cdn.net/wp-content/uploads/2022/04/Top-10-Animes-that-Encourage-to-Coding-Skills.jpg)

### The Journey so far

1. Paying better attention when reading the instructions.

2. Git commmands and using the terminal.

3. HTML and CSS.

### To-Do list

1. Beat God of war ragnarok.
2. Catch up on anime.
3. Make an anime themed readme for my github repository


> “We are all like fireworks: We climb, we shine and always go our separate ways and become further apart. But even when that time comes, let’s not disappear like a firework and continue to shine… forever.” — Hitsugaya Toshiro


Well, I'm doing this program for future me. I didn't want to settle for working in the food industry knowing that video games and art is a huge part of my life. If I didn't at least try strive for my passions what was the point y'know. Plus having a background in photography and photoshop is great for getting into UX/UI


<!-- End of Section 5 -->

---

## Done?
- Rename your markdown file using your first name and first initial of your last name (for example, mine would be anthonyp.md)
- Create a pull request