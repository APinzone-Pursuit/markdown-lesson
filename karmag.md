# Writing in Markdown

Below you'll find several sections with instructions. Inbetween the two comment tags marked "Start of Section #" and "End of Section #" complete the instructions for that section.

Check off each step as you complete it and [refer back to the reading](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) often to assist!

---

#### Section 1 Instructions
- [x ] Add a level 2 heading called "Collaborative Programming"
- [x] Add a link to the collaborative programming reading, the link should say "What is pair programming?" 
- [x] Add a JavaScript code block that contains a jsdoc comment. Take one from a previous replit, use the one from the reading, or create a new one. 
- [x] Add a level 3 heading called "Pair Programming at Pursuit"
- [x] Make an ordered list of the reasons Pursuit wants you to pair program. This list should be bold.

---

<!-- Start of Section 1 -->
## Collaborative Programming
[What is pair programming](https://github.com/KarmaG-7/karma-markdown-practice)
    
    function add(a,b){
        let total;
        total = a + b
        return total
    };
### Pair Programming at Pursuit
1. **Better Understanding**
2. **Help another student**
3. **Getting to know each other's idea**
  

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
[what is terminal](https://www.computerhope.com/jargon/t/terminal.htm)
### Keywords
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
### Examples
```bash
#Check your current file path
`pwd`
#Make a directory
`mkdir directory_name`
#Navigate to that directory
`cd directory_name`
#Create a file within that directory
`touch file.txt`
#Move up one directory
`cd ..`
#Open a directory in Visual Studio Code
`code .`
#Open a directory in Finder
`open .`
```
### Tips
* Use tab to autocomplete. for example, if the current folder has subfolders titled `games`, `photos` and `photography`, typing `pho` and pressing the tab key will result in displaying `photo` and `photography`. If we then type the letter `g` to get `photog`,and press the tab key - the command will be autocomplete to `photography`.

* You can also use the up and down arrow keys to cycle through all the commands you've typed.

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
["Git, what is it good for?"](https://github.com/9-5-pursuit/unit-fundamentals/tree/main/git) 

```bash
mkdir directory_name
cd directory_name
git init
touch readme.md
git status
git add readme.md
```
```
mkdir directory_name
cd directory_name
code .
```
Adding text or whatever necessary on the readme.md file
staged is a state when you add the changes you made to the readme.md file to the git repo and unstaged is when you made the changes but did not add to git repo.

`git add readme.md`

`git commit -m " Added couple sentences"`
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
## GitHub (KarmaG-7)
["GitHub, Let's build from here"](https://github.com/9-5-pursuit/unit-fundamentals/tree/main/github)
### Connecting Local to Remote
#### Local vs. Remote
Local repo is the forked git that you have in your machine but the remote repo is the one that is available in a server to all the team members .

#### Getting ready on your local machine
Before creating a remote repository on GitHub, you'll need a local repository with at least a single commit. That means you'll need to:

* Create a new directory with at least one file.

* Initialize that directory as a git repository with `git init`.

* Stage and commit files, with `git add` and `git commit`.

You can always check if your directory is a git repository and has a single commit by running `git log`.
#### Creating a new repository
* You can create a new repository from the [GitHub.com](github.com) homepage. Click the green New button to get the process started.
!["First step"](https://github.com/9-5-pursuit/unit-fundamentals/blob/main/github/assets/reading/new-repository.png)

* Alternatively, you can click the "+" button in the top-right corner of any GitHub page. You will then be brought to a page where you can name your repository.
!["Alternative way to create a repo"](https://github.com/9-5-pursuit/unit-fundamentals/blob/main/github/assets/reading/new-repo-settings.png)

* You should give your repository a name that is meaningful as opposed to the nonsense names GitHub typically suggests, like "curly-rotary-phone." It's also typical to give your repository the same name as the folder that contains your repository on your local machine. 
At the bottom of the screen, it gives you the option to initialize your repository with some files. You will have already initialized your repository on your local machine, so you do not need to check these boxes.After clicking the "Create repository" button, you will be brought to a new page that includes a number of code blocks.
!["Page after clicking create repository "](https://github.com/9-5-pursuit/unit-fundamentals/blob/main/github/assets/reading/repository-setup.png)

### Push your code
There are three commands that are run to connect your local repository to your remote repository. Typically, you can copy and paste these commands directly into your terminal. However, it's important to generally understand what each command is doing.

`git remote add origin <url>`

When you run this command inside of your local git repository, this command connects your local repository with your remote repository.

As you can see by reading the command, a new "remote" is added at the given URL. The name "origin" is just that -- a name for the remote. This name could be whatever you want, but you can just leave it as origin.

`git branch -M main`

This command sets the name of the `main` "branch" to be called `main`. You will learn more about branches later on. For now, know that the main branch is where your commit history will live. Your local repository also has a `main` branch -- these two branches will be connected.

`git push -u origin main`

The `git push` command moves all of the commits from your local repository to your remote repository. This is the command that gets the two synchronized.

The `-u` flag sets the "upstream" default for this branch to always be the remote with a name of "origin" and the branch with the name of "main."

Because of the `-u` flag, moving forward you can just write `git push` from your local `main` branch and git will know that you want to push to the main branch of the remote repository by the name of "origin".
### Collaborating with GitHub
**Forking**

* Forking a repository means to make a duplicate of it to your own GitHub account. The "forked" repository maintains a connection to the original repository.
 Anyone can fork a public repository, which makes it a great way for developers to work together on open-source projects without having to manage permissions for a repository.

 * To Fork a repository, you can click the Fork button at the top of any repository you have access to. After a brief moment, you'll be brought to a new page which is your version of the forked repository.

 * You should see your account name as the owner of the repository, which will have the same name. You should also see that your repository is forked from the original repository.

**Cloning**

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
* Already has its remote set to be your forked repository.

* Has the same history as the remote repository.

* Is yours, which means you can add your own commits!

**Making changes**

You can now work on your forked repository in the same way you would work on any local repository. Make changes, stage those changes, and make new commits. You can also push your changes from your local repository to the forked repository in the same way.

**Pull requests**

Once you've added at least one new commit, you can create a pull request. Pull requests are a way to suggest changes to a repository without forcefully changing that repository. In a real development workflow, someone would be tasked with reviewing that pull request and determining whether or not your code should be accepted.

At Pursuit, you will begin by using pull requests to submit your work. Your instructors can then add feedback to your pull requests, as if it were a code review.

**Creating a pull request**

To create a pull request, click on the "Contribute" dropdown and then click the green "Open pull request" button.

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
!["I got this!"](https://upload.wikimedia.org/wikipedia/en/f/ff/SuccessKid.jpg)
* Better understanding of Github
* github collaboration
* HTML/CSS

#### My long weekend plans:
- [ ] Revise the github reading
- [ ] Watch a movie
- [ ] Cook a new dish

"Work hard play hard"

**I am doing this program for my better future**




<!-- End of Section 5 -->

---

## Done?
- Rename your markdown file using your first name and first initial of your last name (for example, mine would be anthonyp.md)
- Create a pull request