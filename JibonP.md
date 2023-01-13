# Writing in Markdown

Below you'll find several sections with instructions. Inbetween the two comment tags marked "Start of Section #" and "End of Section #" complete the instructions for that section.

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
## Collaborative Programming

[What is pair programming?](https://github.com/9-5-pursuit/unit-fundamentals/tree/main/collaborative-programming)

/**
 * Creates a new car object from the gathered parameters.
 * @param {string} make - The make (or brand) of the car.
 * @param {string} model - The model (or generic name) of the car.
 * @param {number} year - The year the car was built.
 * @returns {Object} An object with `make`, `model`, and `year` keys.
 */


### Pair Programming at Pursuit

Bold List of reasons for pair programming at Pursuit:

**1. To improve code quality**

**2. To increase knowledge sharing**

**3. To improve team collaboration**

**4. To promote more efficient problem-solving**

**5. To facilitate skill development among team members.**
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
## Intro to the Command Line

[What is the terminal?](https://github.com/9-5-pursuit/unit-fundamentals/tree/main/intro-to-command-line)

### Keywords

`pwd` (print working directory)

`ls` (list files and directories)

`mkdir` (make directory)

`cd` (change directory)

`touch` (create a new file)

`..` (navigate up one directory)

`code` (open a directory in Visual Studio Code)

`open` (open a directory in Finder)

### Examples

``` bash
# Check your current file path
pwd

# List the files and folders in your current directory
ls

# Make a directory
mkdir 

# Navigate to that directory
cd 

# Create a file within that directory
touch 

# Move up one directory
cd ..

# Open a directory in Visual Studio Code
code .

# Open a directory in Finder
open .

```



### Tips

. Always double check your file path before making any changes

. Use tab completion to save time typing out file and directory names

. Use `man` command to view manual pages for any command

. Use `clear` command to clear the terminal screen
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
## Git

[Git, what is it good for?](https://github.com/9-5-pursuit/unit-fundamentals/tree/main/git)

``` bash
# Make a directory
mkdir 

# Navigate to that directory
cd 

# Initialize a Git Repo
git init

# Create a readme.md file
touch readme.md

# Check the status of the repo
git status

# Stage the readme.md file
git add readme.md

```
**Instructions**

Open the directory you created previously in Visual Studio Code

``` bash
code .
```

**Update the readme.md file**

. Make the desired changes to the readme.md file within the Visual Studio Code editor

**Compare the differences between the staged and unstaged readme.md files**

``` bash
git diff

```

**Stage the changes to the readme.md file**

``` bash
git add readme.md

```

**Commit the changes**

``` bash
git commit -m "updated the readme file"

```

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
**GitHub (JibonP)**

[GitHub, Let's build from here](https://github.com/9-5-pursuit/unit-fundamentals/tree/main/github)

### Connecting Local to Remote

### Local vs. Remote

A local repository is a copy of a project that is stored on your local machine. A remote repository is a copy of a project that is stored on a remote server, such as GitHub. The main difference between the two is that a local repository can only be accessed and modified by the person working on the project on their own machine, while a remote repository can be accessed and modified by multiple people from different locations.

#### Getting ready on your local machine

Before you can connect your local repository to a remote repository, you'll need to make sure you have a few things set up on your local machine.

First, you'll need to have Git installed. You can check if you already have it installed by opening a terminal window and running the following command:

``` bash
git --version
```
If you don't have Git installed, you can download it from the [official website.](https://github.com/)

Next, you'll need to set up your Git configuration. This includes your username and email address, which will be associated with your commits. You can set these up by running the following commands:

``` bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```
#### Creating a new repository

To create a new repository on GitHub, you can follow these steps:

**1. Log in to your GitHub account.**

**2. Click the "New repository" button on the dashboard.**

**3. Enter a name and description for your repository.**

**4. Choose whether you want your repository to be public or private.**

**5. Click the "Create repository" button.**

### Push your code

Once you've set up your local repository and your remote repository, you can push your code from your local repository to your remote repository. To do, you can use the git push command.

``` bash
git remote add origin https://github.com/yourusername/yourrepo.git

```
Next, you'll need to push your code to the remote repository. You can do this by running the following command:

``` bash
git push -u origin master

```
The -u flag sets the upstream branch, which allows you to push and pull changes to and from the remote repository. The origin parameter specifies the remote repository to push to, and the master parameter specifies the branch to push.

### Collaborating with GitHub

**Forking**

1. Log in to your GitHub account.

2. Locate the repository you want to fork.

3. Click the "Fork" button in the top-right corner of the repository.

**Cloning**

1. Log in to your GitHub account.

2. Locate the repository you want to clone.

3. Click the "Clone or download" button.

4. Copy the repository's URL.

5. Open a terminal window and navigate to the directory where you want to clone the repository.

6. Run the following command: `git clone URL`

**Making Changes**

1. Open the cloned repository in your local machine.

2. Make the desired changes to the code.

3. Use `git add` command to stage your changes.

4. Use `git commit -m "your message"` command to commit your changes.

**Pull Requests**

1. Push your changes to your forked repository.

2. Go to the original repository.

3. Click on the "Pull Request" button.

4. In the pull request page, ensure that the base repository and base branch is correct.

5. Leave a detailed description of the changes you made and why they were necessary.

6. Click the "Create pull request" button.

7. Wait for the repository maintainer to review and merge your changes.






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

![This is me right now](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.cometchat.com%2Fblog%2Fprogramming-memes-for-developers&psig=AOvVaw1YfyYyLG1uFmKZF9hM6lKt&ust=1673717598061000&source=images&cd=vfe&ved=0CA8QjRxqFwoTCMjqlYyKxfwCFQAAAAAdAAAAABAD)

One thing I need to work on:

    . Improving my algorithm and data structure skills

One thing I feel I understand well:

    . Understanding the basics of JavaScript and its syntax

One thing I am looking forward to learning:

    . Building a full-stack web application and deploy it

## To-Do List for Long Weekend

- [ ] Review algorithms and data structures

- [ ] Practice coding challenges

- [ ] Start building a personal project

- [ ] Review the concepts of web development

- [ ] Take a break and relax

"**Be the change you wish to see in the world**"

I am doing this program for myself, to improve my skills and to achieve my career goals. I want to be a professional software developer, and I believe that with the knowledge and resources provided by the program, I can achieve my goal. I am determined to work hard and make the most of this opportunity to improve myself and reach my full potential. I am doing this program to be the best version of myself and to make a positive impact on the world.

<!-- End of Section 5 -->

---

## Done?
- Rename your markdown file using your first name and first initial of your last name (for example, mine would be anthonyp.md)
- Create a pull request

