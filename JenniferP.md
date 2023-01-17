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
## **Collaborative Programming**
[What is Pair Programming?](https://github.com/9-5-pursuit/unit-fundamentals/tree/main/collaborative-programming)
```
// this function adds 10 to a number. //

function addTen(number) {
    return number + 10;
  
}
console.log(addTen(15))

```
### **Pair Programming at Pursuit**

During the Fellowship, Pursuit wants you to pair program for the following reasons:

1. Knowledge retention and sharing. It is inevitable that at some point another student will know more than you about a particular topic, and vice versa. Pairing gives you multiple opportunities to gain knowledge from other Fellows, or share that knowledge.

2. Focus. When you're working with another person, it's difficult to get sidetracked. Working with other Fellows will help both of you stay on task so that you can efficiently complete your assignments.

3. Expediency. When you're working with a pair, it's less likely that you will get stuck on frustrating problems like syntax errors. This is because you will have someone else looking on who will be able to spot your small mistakes. Instead, you'll get stuck on the larger, more difficult problems. And that's good! You want to spend your time working through misunderstandings, not spellchecking your variables.

4. Community. The students you work with could be your future coworkers, so it's important to have many chances to work with them. While pairing, you'll be developing your interpersonal and teamwork skills which are critical for your future roles.
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
- [ ] Recreate the tips section from the intro to command line reading
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
* pwd - print working directory
* cd .. - go to parent directory (aka up)
* cd [folder] - go into folder
* ~ - represents your home folder
* ls - list files and subfolders in current folder
* touch [filename] - create a new file
* mkdir [directory name] - make a new directory
* code [filename] - open the VSCode editor

### Examples
``` bash
 # Check your current file path
 pwd
 # List the files and folders in your current directory
 ls
# Make a directory
mkdir
# Navigate to that directory
cd [folderName]
# Create a file within that directory
touch [fileName]
# Move up one directory
cd ..
# Open a directory in Visual Studio Code
code .
# Open a directory in Finder
open .
```
### **Tips**
- Use tab to autocomplete. for example, if the current folder has subfolders titled games, photos and photography, typing pho and pressing the tab key will result in displaying photo and photography. If we then type the letter g to get photog,and press the tab key - the command will be autocomplete to photography.

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
- [ ] Put together instructions, utilizing code blocks when necessary, describing the following steps:
    - Open the directory you created previously in Visual Studio Code
    - Update the readme.md file
    - Compare the differences between the staged and unstaged readme.md files
    - Stage the changes to the readme.md file
    - Commit the changes
---

<!-- Start of Section 3 -->
## **Git**
[Git, what is it good for?](https://docs.google.com/presentation/d/1KSqHQw8DxaZTtGQn5VKjP_Ljv4H_zc2hfE1CEVH8M8o/edit#slide=id.g420132f636_0_109)
```bash
# Make a directory
mkdir [fileName]
#Navigate to that directory
cd fileName
# Initialize a Git Repo
git init
# Create a readme.md file
touch readme.md
# Check the status of the repo
git status OR gst
# Stage the readme.md file
git add readme.md OR git add .
```
1. To open the directory you created in VS Code, run the command `code[directoryName]` or while in that directory run `code .`
2. While the directory is open in VS Code, open the `readme.md` file, add some text to it and save the file.
3. In your terminal, run `git diff` to compare the differences between the staged and unstaged `readme.md` files
4. To stage the changes made in the `readme.md` file, run `git add readme.md`
5. To commit the changes made run `git commit -m "Add text" (**A message describing the changes made**)
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
## GitHub (YourGithubUsername)
[GitHub, Let's build from here](https://github.com/9-5-pursuit/unit-fundamentals/tree/main/git)
### Connecting Local to Remote
#### Local vs. Remote
    Local repositories reside on the computers of team members. On the other hand, remote repositories are hosted on a server that is accessible for all team members - most likely on the internet or on a local network.
#### Getting ready on your local machine
Before creating a remote repository on GitHub, you'll need a local repository with at least a single commit. That means you'll need to:

Create a new directory with at least one file.

Initialize that directory as a git repository with `git init`.

Stage and commit files, with `git add` and `git commit`.

You can always check if your directory is a git repository and has a single commit by running `git log`.

#### **Creating a new repository**
1. You can create a new repository from the [GitHub.com](Github.com) homepage.

2. Click the green `New` button to get the process started.
- Alternatively, you can click the `+` button in the top-right corner of any GitHub page. 

3. You will then be brought to a page where you can name your repository.
- You should give your repository a name that is meaningful as opposed to the nonsense names GitHub typically suggests, like "curly-rotary-phone." 
- It's also typical to give your repository the same name as the folder that contains your repository on your local machine.
 
4. At the bottom of the screen, it gives you the option to initialize your repository with some files. 
- **If you have already initialized your repository on your local machine, you will not need to check these boxes.**

5. After clicking the `Create repository` button, you will be brought to a new page that includes a number of code blocks.

### Push your code

There are three commands that are run to connect your local repository to your remote repository. Typically, you can copy and paste these commands directly into your terminal. However, it's important to generally understand what each command is doing.

`git remote add origin <url>`

When you run this command inside of your local git repository, this command connects your local repository with your remote repository.

As you can see by reading the command, a new "remote" is added at the given URL. The name "origin" is just that -- a name for the remote. This name could be whatever you want, but you can just leave it as origin.

`git branch -M main`

This command sets the name of the `main` "branch" to be called main. You will learn more about branches later on. For now, know that the main branch is where your commit history will live. Your local repository also has a `main` branch -- these two branches will be connected.

`git push -u origin main`

The `git push` command moves all of the commits from your local repository to your remote repository. This is the command that gets the two synchronized.

The `-u` flag sets the "upstream" default for this branch to always be the remote with a name of "origin" and the branch with the name of "main."

Because of the `-u` flag, moving forward you can just write `git push` from your local main branch and git will know that you want to push to the `main` branch of the remote repository by the name of "origin".

### Collaborating with GitHub
 **Forking**

- [ ] To Fork a repository, you can click the `Fork` button at the top of any repository you have access to. 
- [ ] You'll be brought to a new page which is your version of the forked repository. Click `Create Fork`.

**Cloning**
- [ ] Before we can clone our new repo, we need to get the link. Click the green `Code` button and copy the link.
- [ ] In the Terminal, navigate to the directory that you want the repo to go and run `git clone <url> (**paste the url link that we copied**)
- [ ] Run `ls` to ensure that your file was successfully downloaded. **(the new folder will be listed)**
- [ ] Open a new folder in VS Code by navigating to it using the command `cd [new directory name]` and then run the code command `code .`

**Making Changes**
- [ ]  With the folder open in the VS Code, add a text to the file and be sure to save the file/
-[ ] Return to the Terminal and run `git status` **to check if there is an untracked change that you have just made.**
- [ ] Run the command `git add .` **to add all of your changes to staging.**
- [ ] Commit your changes in the Terminal by running `git commit -m "**A message describing the changes that you made.**"

**Pull Requests**
- [ ] Open your github page again and refresh it. **You should see the changes you just made.**
- [ ] Open a pull request by clicking the `Contribute` dropdown and next the click `New pull request` button.
- [ ] Add a title (**this may already be filled**) and you can add any additiional comments.
- [ ] Click the `Create pull request` button.



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
![This is me at Pursuit so far](https://i.kym-cdn.com/entries/icons/original/000/021/464/14608107_1180665285312703_1558693314_n.jpg)

### **What I need to work on**
- [ ] **Time management**- I spend so much time on my labs in CONFUSION that i neglect to get to the readings the night before class

- [ ] I understand the purpose of git and gitHub

- [ ] I need to work on understand functions, arrays and loops. **Probably many more things as well**

Weekened To-Do list
- [ ] Complete and practice the [Javascript on Your Machine Reading](https://github.com/9-5-pursuit/unit-fundamentals/tree/main/javascript-on-your-machine)
- [ ] Practice using VS code to further understand how to use git and GitHub
- [ ] Continue reviewing functions, arrays, loops and other materials I am still confused about by reading, watching YouTube videos, and practice writing codes. **ASK FOR HELP WHEN STUCK**
> “Do what you can, with what you have, where you are.” ―Theodore Roosevelt.

**I am doing this program for myself and for my daughter. For years I have been feeling unsure about what I want to do and feeling stuck at where I am in life. As challenging as this new chapter in my life is, not only do I want to stick to it and give it my all but i want to actually be succesfull. I want to understand as much as I can so that I can utilize that knowledge in my life as a future developer. There are days where I feel like I am not smart enough and like I do not have what it takes but I am trying my best to keep such thoughts from even entering my mind. IMPOSTER SYNDROME IS REAL OUT HERE!!**
<!-- End of Section 5 -->

---

## Done?
- Rename your markdown file using your first name and first initial of your last name (for example, mine would be anthonyp.md)
- Create a pull request