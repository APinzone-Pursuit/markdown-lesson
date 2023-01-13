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
 * Creates a new car object from the gathered parameters.
 * @param {string} make - The make (or brand) of the car.
 * @param {string} model - The model (or generic name) of the car.
 * @param {number} year - The year the car was built.
 * @returns {Object} An object with `make`, `model`, and `year` keys.
 */
```
### Pair Programming at Pursuit
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
```bash
# check your current file path

pwd

# List the files and folders in your current directory

ls

# Make a directory

mkdir

# Navigate to that directory

cd [folder]

# Create a file within that directory

touch [filename]

# Move up one directory

cd ../

# Open a directory in Visual Studio Code

code .

# Open a directory in finder

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
[Git, what is it good for?](https://docs.google.com/presentation/d/1KSqHQw8DxaZTtGQn5VKjP_Ljv4H_zc2hfE1CEVH8M8o/edit#slide=id.g420132f636_0_109)
```bash
# Make a directory

mkdir

# Navigate to that directory

cd [folder]

# Initialize a Git Repo

git init

# Create a readme.md file

touch readme.md

# Check the status of the repo

git status

# Stage the readme.md file

git add readme.md
```

### Updating and committing
```bash
# Opening the directory in Visual Studio Code

code .
```
*Update the readme.md file in Visual Studio Code and save (cmd + s)*

```bash
# Use git diff to compare changes

git diff

# Stage the changes to the readme.md file

git add readme.md

# Commit the changes

git commit -m "updated readme.md"
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
- [x] Create a step by step task list for the collaboration process. Include the following:
    - Forking
    - Cloning
    - Making Changes
    - Pull Requests

---

<!-- Start of Section 4 -->
## GitHub jeremytjimenez
[GitHub, Let's build from here](https://github.com/9-5-pursuit/unit-fundamentals/blob/main/github/reading/readme.md)
### Connecting Local to Remote
#### Local vs. Remote
A local repo is a git repository created on your computer/laptop, hence it being "local". A remote repo is a git repository on some cloud base like GitHub, not on your personal machine. 
#### Getting ready on your local machine
Before creating a remote repository on GitHub, you'll need a local repository with at least a single commit. That means you'll need to:

- Create a new directory with at least one file.

- Initialize that directory as a git repository with `git init`.

- Stage and commit files, with `git add` and `git commit`.

You can always check if your directory is a git repository and has a single commit by running `git log`.
#### Creating a new repository
- Click the "+" button in the top right corner of your GitHub page. Name your repository something meaningful. You can choose to initialize it with some files, but since you are connecting it to your local, that should be ignored.

- After clicking "Create repository", you will be brought to a page with code blocks. Only pay attention to the code under the heading "... or push an existing repository from the command line".
### Push your code
There are three commands that are run to connect your local repository to your remote repository. Typically, you can copy and paste these commands directly into your terminal. However, it's important to generally understand what each command is doing.

**`git remote add origin <url>`**

When you run this command inside of your local git repository, this command connects your local repository with your remote repository.

As you can see by reading the command, a new "remote" is added at the given URL. The name "origin" is just that -- a name for the remote. This name _could_ be whatever you want, but you can just leave it as origin.

**`git branch -M main`**

This command sets the name of the main "branch" to be called `main`. You will learn more about branches later on. For now, know that the `main` branch is where your commit history will live. Your local repository also has a `main` branch -- these two branches will be connected.

**`git push -u origin main`**

The `git push` command moves all of the commits from your local repository to your remote repository. This is the command that gets the two synchronized.

The `-u` flag sets the "upstream" default for this branch to always be the remote with a name of "origin" and the branch with the name of "main."

Because of the `-u` flag, moving forward you can just write `git push` from your local `main` branch and git will know that you want to push to the `main` branch of the remote repository by the name of "origin".
### Collaborating with GitHub
1. **Forking**: click the fork button on someone else's repository in order to create a duplicate of it in your account. This duplicate is connected to the original
2. **Cloning**: First, make sure your terminal is navigated to a directory that *isn't* a git repository, is the parent directory of where you want this repo to live and that there is not a folder inside that directory with the same name as the repo. Then, click the green "Code" button on the GitHub page with the forked repo, copy the url and then run the following command, replacing url with the url you copied.
```bash
git clone <url>
```
3. **Making changes**: You can work in this repo now as you would any other local repo, making changes, staging those changes and making new commits. You can push these changes the same way as you would your personal repos.
4. **Pull requests**: Once you've added at least 1 commit and pushed it, click the "Contribute" button on your forked repo page and click the "Open pull request" button. You will be brought to a new page where you can see the details of the pull request along with whatever changes you've made and the differences between yours and the original repo. Click the green button to actually create the pull request. You'll then be brought to a new page where you can describe the changes you made. Once you do that (or don't do that), you can just click the "Create pull request" button. If you want to see your pull request after you've made it, just go to the original repo and click the pull requests tab.
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
![How I'm feeling](https://akhilviz.files.wordpress.com/2016/08/smiley-face-clip-art-thumbs-up-free-clipart-images-2.png)
- One thing I need to work on: The terminal is confusing and I don't think I fully understand what Git is actually doing (lol). But I can do it. Also, some of the problem solving aspects can be daunting when approaching something in code, but I'm exercising that muscle.
- One thing I feel I understand well: The syntax and logic of what's going on, at least in regards to the JS concepts we've learned. I feel very comfortable with understanding what specifically is going on with the loops, conditionals, and all that stuff.
- One thing I am looking forward to learning: Well, I'm not sure about specfically, but I am excited to put these concepts into practice to actually create something interesting. Especially being a creative person, there are lots of ideas I have in regards to artistic applications of code.
### To-Do List
- Read my code simplicity book
- Do more JS practice
- Do more markdown practice
- Make and push a few more repos
- Sleep
- Play Tekken

*"My life fell like dew*

*Disappears like dew*

*All of this world*

*Is dream after dream"*

*-Toyotomi Hideyoshi*

**I am doing this program for my parents. They've worked so hard for me my entire life and I feel like I haven't contributed very much to their struggle. I want to be able to be that person for them. A person to rely on. Also, for my niece as well (actually my first cousin once removed). My cousin just had a little girl and he was always like a big brother to me, so I want to be as much of a role model as I can for that child.**

<!-- End of Section 5 -->

---

## Done?
- Rename your markdown file using your first name and first initial of your last name (for example, mine would be anthonyp.md)
- Create a pull request