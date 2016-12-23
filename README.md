# Senior Project Document

The documents file is used to give the guidance for the documentation and git usage

[Guide to markdown in md format](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

## List of content

1. [Guide to git usage](#guide-to-git)
2. [Kanban board](#kanban-board)
3. [Project Proposal](https://github.com/TinkersStudio/SeniorProjectDocument/tree/master/Project%20Proposal)

### Guide to git

The "correct order" to push the code is:

```
git commit
git pull
git push
```

#### Check the change in the folder

```
git status
```

#### Clone a repository

```
TODO: Write the instruction on how to clone a repo. Setup the correct upstream
```

#### Update a repo

It is recommend to update whenever a new file is created in the repo. We have to add the file into the tracking system

```
git add <filenames>
```

or add all files by

```
git add .
```

To commit the changes that you make(making a save of your work)

```
git commit -m "Message provide information about the changes"
```

or (recommended)

```
git commit -am "Message provide information about the changes"
```

To push the changes to github

```
git push origin <name of the branch>
```

Ex:

```
git push origin master
```
### Kanban Board

The project is managed use the kanban board for project management. Access the board using the "[Board Tab](https://github.com/TinkersStudio/SeniorProjectDocument#boards?repos=76986294)" in the github.

The task is assigned by using tag. If you see the name, it is assigned to you. There is 3 columns:
- TODO is for the task need to do
- In Progress for work is working on
- Done is used for the work has been completed and ready to check.

Only put the issues to the "Closed column" if there is the closing statement in the issue. A developer confirmed that the implementation has been completed
The UI allows user to arrange the issues by drag and drop to proper column
