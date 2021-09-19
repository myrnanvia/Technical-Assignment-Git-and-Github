<ol>
    <li>What does git clean do?<br>
    answer : git clean is a convenience method for deleting untracked files in a repo's working directory</li>
    <li>What do the -d and -f flags for git clean do?<br>
    answer : Normally, when no <path> is specified, git clean will not recurse into untracked directories to avoid removing too much. Specify -d to have it recurse into such directories as well. -f flag is for delete untracked nested git repositories (directories with a .git subdirectory)</li>
    <li>What git command creates a branch?<br>
    answer : git branch branch-name</li>
    <li>What is the difference between a fast-forward and recursive merge?<br>
    answer : The merge commit continues to have two parents. Note: There is nothing right or wrong of either one of the strategies but with fast forward merge you have a straight line of history and with the recursive merge, it is of multiple lines.</li>
    <li>What git command changes to another branch?<br>
    answer : git checkout branch-name</li>
    <li>How do you remove modified or deleted files from the working directory?<br>
    answer : git rm file-name</li>
    <li>What git command deletes a branch?<br>
    answer : git branch -d branch-name</li>
    <li>What does the git diff command do?<br>
    answer : The git diff command is used when you want to see differences between any two trees</li>
    <li>How do you remove files from the staging area?<br>
    answer : git reset HEAD file-name </li>
    <li>How do merge conflicts happen?<br>
    answer : Merge conflicts can happen when merging a branch, rebasing a branch, or cherry picking a commit.</li>
</ol>