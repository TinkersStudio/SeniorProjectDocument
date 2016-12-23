# Senior Project Document
Contain the information about the project

## List of content
1. [Guide to git usage](#guide-to-git)
2. Guide to markdown in md format
3. Kanban board
4. Project Proposal

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
It is recommend to update  
Whenever a new file is created in the repo. We have to add the file into the tracking system  
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
