# Prism_Proj.demo
Repository for the tasks given by the projects domain of prism club

# Task 1(Git + Markdown)

Well , wow , i uhh , just used git clone and opened by git bash , this is crazyyyy.
All right , so lets discuss what this Git is and what github is and the basic syntax of markdown files.

## What is Git?
Okay So now , What is Git ?

Git is called a version control system. In laymans terms we can explain what git is by telling that is like a 
"Save your history " for your work.

Well in our academic life , like making projects , or reports,docs , etc. we must have had many circumstances where we wished , oh the last one i typed was better than this current , but no , the file is gone or (we used to make multiple files for the same doc hehe)

Well thats basically what git does , it store multiple version of the history of the code , document , (your work basically).

In our computer , the git store stores this changes in the directory /.gitconfig.
We tell git who we are by entering our user name and the email & we only do this once .

## What is Github ?
So now what is github , now that we have a basic understanding of what git does?

Github is like a remote repository(Repository - a fancy word for Folders that remembers your changes) to store our files. 

Github is a Online website where we can store our files (push our files)
We have other websites as well similar to Github for example BitBucket/Gitlab, but github is a public website that can be used by the public

Now that we have got to know what github is lets know the basic command we need to know to push , remove files to your git and github.

Oh yeah before we introduce the commands , we type this commands in **git bash** or **cmd**, or **powershell**.

## Basic Git Commands

### Setting Up
```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

### Starting a Repository
```bash
git init        # turns any folder into a git repo
git clone <url> # download a repo from GitHub like i have done with this one
```

### The BIG 3 
```bash
git add .               # tell your changes (tell git what to save)
git commit -m "message" # Description to let others or yourself know what u have changed and used to save the changes 
git push origin main    # Upload your changes to GitHub
```

### Other Useful Commands
```bash
git status   # See what files have changed
git pull     # Download latest changes from GitHub
git log      # See the history of commits
```
Well we have learnt what do to for github, The same commands are also used to store the commits on the local machine. we just wont have the cloning thing .

Until and unless we push github doesnt have any idea of what happens to the files

In git , we have three stages :
1. Well the first stage is the working directory . This the where we edit our codes and uhh make changes to the files. the thing is git doesnt track these changes yet.
2. The second stage is The stagin area 
  when you run 
```bash
  git add .
```
 this command tells git to include these changes in the next upcoming commit or save.
3. The third stage is the repo . This is going to get done when we run the command 
```bash
git commit
``` 
basically what this does is , it save s the changes that you have done util you have run git add. to the local .git folder permanently .



## What is Markdown?

- Well markdown is used to make our text into nicely formatted text.
 The  '#' is used for Headings
 the symbols '##,###,####,' are also used for headings.

### Style of Letters
 '**Bold**'- This is is used for bold text
 '_Italic_'- This is used to italisese the letter.
 '~~Strikethrough~~' is used to stike out the letters 

### Code Blocks
For a code block , what we do is we use backticks along with the language name, as following:
```markdown
# Helloooo
**NExt is Python**
```

```python
print("Hello Peasants")
print("Summ of 12 and 34",12+34)
```

```java
System.out.println("I dont know java")
```

**Unordered list** (bullet points):
```markdown
- Item one
- Item two
  - Nested item
```

**Ordered list** (numbered):
```markdown
1. First 
2. Second 
3. Third 
```
### Links
[Just click here ](https://www.youtube.com/watch?v=QDia3e12czc)

### Images
![no image in here](image-url.png)


### Blockquotes
> This is a quote(greater thn symbol)

### Tables
| Name  | Age |
|-------|-----|
| Vivek | 13  |
