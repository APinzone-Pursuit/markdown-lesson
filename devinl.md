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
[What is pair programming?](https://github.com/9-5-pursuit/unit-fundamentals/tree/main/collaborative-programming)
```js
/**
 * Returns the first name in the array.
 * @param {string[]} line - An array of names.
 * @returns {string} The name of the first person in line.
 */
```
### Pair Programming at Pursuit
1. **Keep track of changes made by other developers** 
2. **Pair programming is very common in the workplace**
3. **Ability to make changes and not have them "live" until approved"**
4. **Ability to organize work done on a project**
<!-- End of Section 1 -->

---

#### Section 2 Instructions
- [x] Add a level 2 heading called "Intro to the Command Line"
- [x] Add a link to the intro to command line reading, the link should say "What is the terminal?" 
- [x] Add a level 3 heading called "Keywords"
- [x] Re-create the list of keywords from the intro to command line reading, making sure to mark all code keywords as the reading did.
- [x] Add a level 3 heading called "Examples"
- [x] Create a bash code block containing the following examples, each example should have a code comment above it describing what it's doing:
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
[What is the terminal?](https://github.com/9-5-pursuit/unit-fundamentals/tree/main/intro-to-command-line)
### Keywords
* Operating System (OS)
* Graphical User Interface (GUI)
* Command Line Interface (CLI)
* Terminal
* Shell
* Folder = directory
* `pwd` - print working directory
* `cd ..` - go to parent directory (aka up)
* `cd [folder]` - go into folder
* `~` - represents your home folder
* `ls` - list files and subfolders in current folder
* `touch [filename]` - create a new file
* `mkdir [directory name]` - make a new directory
* `code [filename]` - open the VSCode editor
### Examples
```bash
   <!-- Check your current file path  -->
    pwd
   <!-- List the files and folders in your current directory  -->
    ls
   <!-- Make a directory  -->
    mkdir new-directory
   <!-- Navigate to that directory  -->
    cd new-directory
   <!-- Create a file within that directory  -->
    touch newtext.txt
   <!-- Move up one directory  -->
    cd ..
   <!-- Open a directory in Visual Studio Code  -->
    code .
   <!-- Open a directory in Finder  -->
    open .
```
### Tips
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
[Git, what is it good for?](https://docs.google.com/presentation/d/1KSqHQw8DxaZTtGQn5VKjP_Ljv4H_zc2hfE1CEVH8M8o/edit?usp=sharing)
```bash
    #Make a directory
    mkdir new-git-directory
    #Navigate to that directory
    cd new-git-directory
    #Initialize a Git Repo
    git init
    #Create a readme.md file
    touch readme.md
    #Check the status of the repo
    git status
    #Stage the readme.md file
    git add readme.md
```
1. Open the directory you created previously in Visual Studio Code `cd new-get-directory`
2. Update the readme.md file, this command will open the directory into visual studio where you can proceed to edit the readme.md file `code .`
3. Compare the differences between the staged and unstaged readme.md files `git diff`
4. Stage the changes to the readme.md file `git add readme.md`
5. Commit the changes `git commmit -m "Updated readme.md"`
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
## GitHub (devinjlewis)
[GitHub, Let's build from here](https://github.com/9-5-pursuit/unit-fundamentals/tree/main/github)
### Connecting Local to Remote
#### Local vs. Remote
A local repo is directory that is git initiated on your computer. A remote repo is a repo that is created on github.com.
#### Getting ready on your local machine
Before creating a remote repository on GitHub, you'll need a local repository with at least a single commit. That means you'll need to:

* Create a new directory with at least one file.

* Initialize that directory as a git repository with `git init`.

* Stage and commit files, with `git add` and `git commit`.

You can always check if your directory is a git repository and has a single commit by running `git log`.
#### Creating a new repository
1. To create a repository on GitHub you will need to first go to github.com
2. Click the green New button to get the process started.
    - Alternatively, you can click the "+" button in the top-right corner of any GitHub page. You will then be brought to a page where you can name your repository.
3. Give your repository a name that is meaningful as opposed to the nonsense names GitHub typically suggests, like "curly-rotary-phone."
    - At the bottom of the screen, it gives you the option to initialize your repository with some files. You will have already initialized your repository on your local machine, so you do not need to check these boxes.
4. After clicking the "Create repository" button, you will be brought to a new page that includes a number of code blocks.
    - If you have already created a repository, you'll be following the instructions under the heading "...or push an existing repository from the command line."
### Push Your Code
There are three commands that are run to connect your local repository to your remote repository. Typically, you can copy and paste these commands directly into your terminal. However, it's important to generally understand what each command is doing.

`git remote add origin <url>`

When you run this command inside of your local git repository, this command connects your local repository with your remote repository.

As you can see by reading the command, a new "remote" is added at the given URL. The name "origin" is just that -- a name for the remote. This name could be whatever you want, but you can just leave it as origin.

`git branch -M main`

This command sets the name of the main "branch" to be called `main`. You will learn more about branches later on. For now, know that the `main` branch is where your commit history will live. Your local repository also has a `main` branch -- these two branches will be connected.

`git push -u origin main`

The `git push` command moves all of the commits from your local repository to your remote repository. This is the command that gets the two synchronized.

The `-u` flag sets the "upstream" default for this branch to always be the remote with a name of "origin" and the branch with the name of "main."

Because of the `-u` flag, moving forward you can just write `git push` from your local `main` branch and git will know that you want to push to the `main` branch of the remote repository by the name of "origin".
### Collaborating with GitHub
1. To collaborate with someone GitHub, you will need their link to their GitHub repository.
2. From that link, it will have you make a copy of their repository for your own editing purposes. You will need to make a name for it.
3. After name it, you will need to click on the Code button and it will give you a url for your repository.
4. Open a terminal and `cd` into the folder that you will like to have your repository saved. It is best practice to not create the folder in a folder that is already intialized via `git init`.
5. Run the command `git clone <url>`. This will download all of the files in your repository onto your computer.
6. While inside of the folder you can use `code .` to open the folder into Visual Studio Code. Proceed to make any changes that you will like to your code. 
7. Upon make changes, after saving the changes you will want to commit the changes. It is a two step process to commit your changes. You will want to stage your changes first by running `git add .` and then you will need to run `git commit -m "(Message pertaining to changes)"`
8. After the changes are made locally and commited you will need to push them to the GitHub repository. To do so you will run `git push`.
9. Go to your GitHub repository and you can then create a Pull request for the original creator of the repository to update their repo with your changes.

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
## My Time at Pursuit
![This has been my pursuit :laughing:](https://images.squarespace-cdn.com/content/v1/5ea906bfb2891a7f00d30604/1591593368495-WTN6Z0NU1GKJ9N2PO90B/Pursuit%2BLogo%2BBlack.png)
* Reading the readme files THROUGHLY, I understand the task but I sometimes bypass important details.
* Programming and command line
* More programming languages
## To-Do list
* Read upcoming reading for next class.
## Motivation
"Dare to be different today, to be extraordinary tomorrow"
**I am doing this program for myself, my wife, and our future. I have a history in the programming field but I've been longing to get back into and this opportunity presented its self at a time in my life where I actually have time to fully commit to it. My pursuit path has been a rollercoaster but through the support of my friends, my wife, and my class mates its getting there!**

<!-- End of Section 5 -->

---

## Done?
- Rename your markdown file using your first name and first initial of your last name (for example, mine would be anthonyp.md)
- Create a pull request