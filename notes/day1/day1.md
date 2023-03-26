# Day 1

### Useful git commands 

- To clone 
`git clone <url>` -> Use ssh url to clone, so no personal tokens are required 

- To check git status 
`git status`

- To checkout to new branch
`git checkout master -b <new_branch_name>`

- To add file to staged area
`git add .` -> . means it add all the files and folder 

- To add particular file 
`git add <file_name_with_full_path>` 

- To commit with  message and signature
`git commit -m <message> -s .` -> . means it commits all the files 

- To commit only particular file 
`git commit -m <message> -s <file_name_with_full_paht>`

- To print local branch 
`git branch`

- To print all the branch (local and origin)
`git branch -a`

- To check the difference before commit 
`git diff`

- To check the commit message 
`git log` -> This prints all the commit messages 

- To check the commit message of last 1 commit 
`git log -1` -> This prints last one commit message 

- To avoid printing all the message
`git log -1 --oneline` -> This print only one line of the last commit

- To push the code 
`git push` 

- If branch is not present in the origin then 
`git push --set-upstream origin <locally_created_branch_name>`


## Helpful link for markdown
[markdown official site](https://www.markdownguide.org/basic-syntax/)\
[Github](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

