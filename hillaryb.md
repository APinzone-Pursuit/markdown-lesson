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

```bash js 
/**
 * Creates a new car object from the gathered parameters.
 * @param {string} make - The make (or brand) of the car.
 * @param {string} model - The model (or generic name) of the car.
 * @param {number} year - The year the car was built.
 * @returns {Object} An object with `make`, `model`, and `year` keys.
 */
function createCar(make, model, year) {}
```
### Pair Programming at Pursuit 

1. **Knowledge retention and sharing**
2. **Focus**
3. **Expediency**
4. **Community**

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
[What is a terminal?](https://github.com/9-5-pursuit/unit-fundamentals/tree/main/intro-to-command-line)
### Keywords
- Operating System (OS)
- Graphical User Interface (GUI)
- Command Line Interface (CLI)
- Terminal
- Shell
- Folder = directory
- `pwd` - print working directory
- `cd ..` - go to parent directory (aka up)
- `cd [folder]` - go into folder
- `~` - represents your home folder
- `ls` - list files and subfolders in current folder
- `touch [filename]` - create a new file
- `mkdir [directory name]` - make a new directory
- `code [filename]` - open the VSCode editor
### Examples 
```bash js
# Check your current file path 
`pwd` 
# List the files and folders in your current directory
`ls`
# Make a directory
`mkdir [directory name]`
# Navigate to that directory
`cd [folder]`
# Create a file within that directory
`touch [file name]`
# Move up one directory
`cd ..`
# Open a directory in Visual Studio Code
`code .`
# Open a directory in Finder
`open [folder name]`
```
### Tips
- Use tab to autocomplete. for example, if the current folder has subfolders titled 'games', 'photos' and 'photography', typing 'pho' and pressing the tab key will result in displaying 'photo' and 'photography'. If we then type the letter 'g' to get 'photog',and press the tab key - the command will be autocomplete to 'photography'.

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
[Git, what is it good for?](https://github.com/9-5-pursuit/unit-fundamentals/tree/main/git)
```bash
# Make a directory
`mkdir [directory name]`
# Navigate to that directory
`cd [directory name]`
# Initialize a Git Repo
`git init` 
# Create a readme.md file
`touch readme.md`
# Check the status of the repo
`git status`
# Stage the readme.md file
`git add readme.me`
```
```bash
# Open the directory you created previously in Visual Studio Code
`code [directory name]` 
# Update the readme.md file
Make changes within VS code 
# Compare the differences between the staged and unstaged readme.md files
`git status`
# Stage the changes to the readme.md file
`git add readme.md`
# Commit the changes
`git commit -m "Message"`
```

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
- [ ] Create a step by step task list for the collaboration process. Include the following:
    - Forking
    - Cloning
    - Making Changes
    - Pull Requests

---

<!-- Start of Section 4 -->
## GitHub (YourGitHubUsername)
[GitHub, Let's build from here](https://github.com/9-5-pursuit/unit-fundamentals/blob/main/github/reading/readme.md)
### Connecting Local to Remote
#### Local vs. Remote 
A local repository is the repository that lives in your machine that is accessed through the terminal using git init

A remote repository is usually hosted on GitHub that requires you to gain access  through a git clone command. Allows you to see documentated changes and review them before accepting them.
#### Getting ready on your local machine
Before creating a remote repository on GitHub, you'll need a local repository with at least a single commit. That means you'll need to:

- Create a new directory with at least one file.

- Initialize that directory as a git repository with `git init`.
- Stage and commit files, with `git add` and `git commit`.

You can always check if your directory is a git repository and has a single commit by running `git log`.
#### Creating a new repository 
1. Click the green New button to start the process or click the "+" button in the top right corner of any GitHub page. You will then be brought to a page to name new Repo 
2. Give your Repo a name that is meaningful , typically the same name as the folder that contains repo on local machine  
3.Click create repo 
### Push your code
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
- Forking means to make a duplicate of it to your own GitHub account. The forked repository maintains a connection with the original repository 
    1. Click the Fork button at the top of any repository you have access to. 

    2. Should see account name as the owner of the repo which will have the same name. Should also see that your repo is forked from the original repository 

    3. Now you have a forked version of the code which means you can update and change as you like 

- Cloning is the process of taking a remote repository from GitHub and creating a synchronized version of it on your computer.

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


- Making Changes
   -  You can now work on your forked repository in the same way you would work on any local repository. Make changes, stage those changes, and make new commits. You can also push your changes from your local repository to the forked repository in the same way.
- Pull Requests
Once you've added at least one new commit, you can create a pull request. 

Pull requests are a way to suggest changes to a repository without forcefully changing that repository. 

In a real development workflow, someone would be tasked with reviewing that pull request and determining whether or not your code should be accepted.

At Pursuit, you will begin by using pull requests to submit your work. Your instructors can then add feedback to your pull requests, as if it were a code review.

Creating a pull request
- To create a pull request, click on the "Contribute" dropdown and then click the green "Open pull request" button.

Anatomy of a pull request
The page you will be brought to has a number of important parts.

After clicking the "Open pull request" button on your forked repository, you'll find you are now on the original repository. This is because you are making a pull request that will be compared to the original repository.

This allows you to choose what you're going to compare. You can typically leave this alone for now.

All of the commits you are sharing will be listed here.

Whatever changes you've made are listed here. In red are the lines that you deleted while in green are the lines you've added.

You'll click this green button to actually create the pull request.

You can switch between a "Unified" or "Split" view when comparing changes.

Completing your pull request
After you click the "Create pull request" button, you'll see an area what you can add more details about your pull request.

As a developer, this is where you might describe what changes you're suggesting. If you're using a pull request to submit an assignment for Pursuit, you can just press the "Create pull request" button.

You can find your pull request by returning to the original repository and then clicking the Pull Requests tab. There you will see all of the pull requests for this repository.



You can click on the link to your specific pull request to get back to the page that shows you the details of your pull request.


The URL on this page is a direct URL to your pull request. Keep this in mind, as you will need to submit a link to your pull request URL on some assignments.
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
![Woman slowly losing it](https://media.istockphoto.com/id/675278540/photo/different-faces-of-a-woman.jpg?s=612x612&w=0&k=20&c=X38qqjl0n7Jt9dm7KD_Fi7wO7uxQVHuIQ9IHNzpeBvk=)
#### Progress Check
1. Nested For Loops
2. Navigating terminals 
3. CSS
#### To Do list for Long Weekend 
1. Finish in class assignment
2. Finish lab 
3. Catch up on my reading notes 
4. Get a facial to destress 
5. Play Dungeons and Dragon with friends 
#### Motivational Quote
 “So Matilda’s strong young mind continued to grow, nurtured by the voices of all those authors who had sent their books out into the world like ships on the sea. These books gave Matilda a hopeful and comforting message: You are not alone.” 
#### Who's it for
**I havent always been the healthiest. My partner has supported me in so much in my life, and recently his health isnt the best. So I want to get through this to be financially stable enough for him to quit his job and focus on his health. He took care of me and its my turn to do the same.**
<!-- End of Section 5 -->

---

## Done?
- Rename your markdown file using your first name and first initial of your last name (for example, mine would be anthonyp.md)
- Create a pull request