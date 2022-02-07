1.Deleting a branch LOCALLY
Git will not let you delete the branch you are currently on so you must make sure to checkout a branch that you are NOT deleting. For example: git checkout main

Delete a branch with git branch -d <branch>.
2.Deleting a branch REMOTELY
Here's the command to delete a branch remotely: git push <remote> --delete <branch>.

3.List Local Git Tags
In order to list Git tags, you have to use the “git tag” command with no arguments.

$ git tag

v1.0
v2.0

4.Delete a local Git tag
In order to delete a local Git tag, use the “git tag” command with the “-d” option.

$ git tag -d <tag_name>

5.Delete a remote Git tag
In order to delete a remote Git tag, use the “git push” command with the “–delete” option and specify the tag name.

$ git push --delete origin tagname

![GitHub](https://1000logos.net/wp-content/uploads/2021/05/GitHub-logo.png)
