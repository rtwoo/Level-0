# Level 0 - Git Basics Exercise

## Introduction to Git

Git is a distributed version control system that helps you manage your project's history, collaborate with others, and keep track of changes over time. A fundamental concept in Git is the "commit."

## What Are Commits?

A commit is like a snapshot of your project at a specific point in time. It captures the changes you've made to your files. Each commit has a unique identifier (hash) and a commit message that describes the changes you've made. Commits help you understand the history of your project and enable you to switch between different versions.

## Exercise: Creating Commits

In this exercise, you will practice creating commits in an existing Git repository. The goal is to create three files, not including this README, and make a commit for each file. Follow these steps:

### Step 1: Clone the Repository

1. Open your terminal or command prompt.

2. Clone the Git repository to your local machine:

```bash
git clone <repository_url>
cd git-basics-exercise
```


### Step 2: Creating and Committing Files 
1. Create a new text file (e.g., `file1.txt`) with some content. You can use any text editor or command line tools to create the file. 
2. Check the status of your repository to see which files are not yet committed:

```bash
git status
``` 
3. Add the new file to the staging area:

```bash
git add file1.txt
``` 
4. Create your first commit:

```bash
git commit -m "Add file1.txt"
``` 
5. Repeat the process to create two more files (`file2.txt`, `file3.txt`). For each file, add and commit it with meaningful commit messages. 
6. After creating and committing all four files, use the following command to view the commit history:

```bash
git log
```



You'll see a list of commits, including their commit hashes, messages, authors, and dates.
### Step 3: Conclusion

Congratulations! You've completed the exercise and practiced creating commits in a Git repository. Commits are an essential part of Git and help you track your project's history. You can continue exploring Git by branching, merging, and collaborating with others. Happy coding!
