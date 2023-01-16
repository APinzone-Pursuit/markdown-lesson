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
### Pair Programming at Pursuit
**1.** **Knowledge retention and sharing. It is inevitable that at some point another student will know more than you about a particular topic, and vice versa. Pairing gives you multiple opportunities to gain knowledge from other Fellows, or share that knowledge.**
**2.** **Focus. When you're working with another person, it's difficult to get sidetracked. Working with other Fellows will help both of you stay on task so that you can efficiently complete your assignments.**
**3.** **Expediency. When you're working with a pair, it's less likely that you will get stuck on frustrating problems like syntax errors. This is because you will have someone else looking on who will be able to spot your small mistakes. Instead, you'll get stuck on the larger, more difficult problems. And that's good! You want to spend your time working through misunderstandings, not spellchecking your variables.**
**4.** **Community. The students you work with could be your future coworkers, so it's important to have many chances to work with them. While pairing, you'll be developing your interpersonal and teamwork skills which are critical for your future roles.**

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
    - Make a direcctory
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
### Examples
<sub>Check your current file path:</sub>
```
pwd
```
<sub>List the files and folders in your current directory</sub>
```
ls
```
<sub>Make a direcctory</sub>
```
mkdir directory-name
```
<sub>Navigate to that directory</sub>
```
cd directory-name
```
<sub>Create a file within that directory</sub>
```
cd directory-name
touch filename.md
```

<sub>Move up one directory level</sub>
```
..
```

<sub>Open a directory with visual code studio</sub>
```
cd directory-name
code .
```
<sub>Open a directory in finder</sub>
```
cd directory-name
open .
```

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
[Git, what is it good for?](https://docs.google.com/presentation/d/1KSqHQw8DxaZTtGQn5VKjP_Ljv4H_zc2hfE1CEVH8M8o/edit#slide=id.g420132f636_0_109)
```
cd ~
mkdir new-directory
cd new-directory
git init
touch readme.md
git status
git add readme.md
```
**Now we will need to open the directory that we previously created in Visual Studio Code.**
- To do so we will need to open up the directory first.
```
cd~
cd new-directory
code .
```
**Now edit the readme.md file in Visual Studio Code**
- It doesn't matter what you add, just make a change and save it.
**Compare the differences between the staged and unstaged readme.md files**
```
git diff readme.md
```
**Stage the changes to the readme.md file**
```
git add readme.md
```
**Commit the changes**
```
git commit -m "Your message"
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
## GitHub (YourGithubUsername)
[GitHub, Let's build from here](https://github.com/9-5-pursuit/unit-fundamentals/blob/main/github/reading/readme.md)
### Connecting Local to Remote
#### Local vs. Remote
Local repos exist on the individual computer, remote repos are hosted on a server and are either publically or privately accessed by the allowed individuals.
#### Getting ready on your local machine
Before creating a remote repository on GitHub, you'll need a local repository with at least a single commit. That means you'll need to:
- Create a new directory with at least one file.
- Initialize that directory as a git repository with `git init`.
- Stage and commit files, with `git add` and `git commit`.

You can always check if your directory is a git repository and has a single commit by running `git log`.
#### Creating a new repository
You can create a new repository from the GitHub.com homepage. Click the green New button to get the process started.
![Alt text](https://github.com/9-5-pursuit/unit-fundamentals/blob/main/github/assets/reading/new-repository.png)
Alternatively, you can click the "+" button in the top-right corner of any GitHub page. You will then be brought to a page where you can name your repository.
![Alt text](https://github.com/9-5-pursuit/unit-fundamentals/blob/main/github/assets/reading/new-repo-settings.png)
You should give your repository a name that is meaningful as opposed to the nonsense names GitHub typically suggests, like "curly-rotary-phone." It's also typical to give your repository the same name as the folder that contains your repository on your local machine.
At the bottom of the screen, it gives you the option to initialize your repository with some files. You will have already initialized your repository on your local machine, so you do not need to check these boxes.
After clicking the "Create repository" button, you will be brought to a new page that includes a number of code blocks.
![Alt text](https://github.com/9-5-pursuit/unit-fundamentals/blob/main/github/assets/reading/repository-setup.png)
Because you should have already created a repository, you'll be following the instructions under the heading "...or push an existing repository from the command line."
### Push your code
There are three commands that are run to connect your local repository to your remote repository. Typically, you can copy and paste these commands directly into your terminal. However, it's important to generally understand what each command is doing.

##### `git remote add origin <url`

When you run this command inside of your local git repository, this command connects your local repository with your remote repository.

As you can see by reading the command, a new "remote" is added at the given URL. The name "origin" is just that -- a name for the remote. This name *could* be whatever you want, but you can just leave it as origin.

##### `git branch -M main`

This command sets the name of the main "branch" to be called `main`. You will learn more about branches later on. For now, know that the `main` branch is where your commit history will live. Your local repository also has a `main` branch -- these two branches will be connected.

###### `git push -u origin main`

The `git push` command moves all of the commits from your local repository to your remote repository. This is the command that gets the two synchronized.

The `-u` flag sets the "upstream" default for this branch to always be the remote with a name of "origin" and the branch with the name of "main."

Because of the `-u` flag, moving forward you can just write `git push` from your local main branch and git will know that you want to push to the `main` branch of the remote repository by the name of "origin".

### Collaborating with GitHub
##### Forking 
You can fork a repo by hitting the fork button in the top right.

To clone a repo copy the url that's present after hitting the green code button. Now make a directory and cd to that directory. Within that directory use `git clone <url>` to clone your local repo to the cloned remote repo.

Stage your changes to be commited by using `git add <fileame.md>` and then commit them with an appropriate title by using 
`git commit -m "message"` 

Create a pull request to request a merge of your forked commited version of a repo and the remote repo it was copied from by selecting create pull request on the repo page. it will ask if you want to compare two versions of a repo and if so which ones. select your two and hit compare.

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
## "My Time at Pursuit"
![strong calves](data:image/jpeg;base64,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)
##### Things I need to work on:
1. Being intentional about how I spend time getting my work done every day.
2. Set bounadries and live life to the fullest. Nobody can dictate what that is but you.
3. Get up earlier. Go to bed earlier.

##### To Do List for this weekend:
- Get this study guide done
- Do the markdown lab
***"A Wizard is never late. He arrives precisely when he means to."*** - "Gandalf, The Grey"

**I'm doing this for myself. I'm doing it for everyone who's ever supported me and believed in me. I intend to do everything that I've ever set out to do. Sometimes the timeline of things is just not what we want it to be. This feels like where I'm supposed to be right now.**
<!-- End of Section 5 -->

---

## Done?
- Rename your markdown file using your first name and first initial of your last name (for example, mine would be anthonyp.md)
- Create a pull request