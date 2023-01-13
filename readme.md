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

<!-- End of Section 5 -->

---

## Done?
- Rename your markdown file using your first name and first initial of your last name (for example, mine would be anthonyp.md)
- Create a pull request