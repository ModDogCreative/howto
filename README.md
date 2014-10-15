How To
=====

Github Basics

{{}} indicates a placeholder so {{filename}} would become path/to/file.txt

##Clone the repo locally
Navigate to the directory where you want the repo to go then

```
git clone {{url}}
```
where url is the clone link.

##After making changes

```
git status
```
shows the changes to be applied to the repo

```
git add {{filename}}
```
Stages that file for a commit

```
git add .
```
Stages all unstaged files

```
git rm {{filename}}
```
Removes file from the repo

```
git commit -m "meassage"
```
Commits changes to the local repo and tags them with the message. Keep the message in present tense i.e. "Adds geo locaion functionality", "Removes insecure login script"

```
git push
```
Pushes the repo back up to github.

##Branches

```
git checkout {{branchName}}
```
Starts working on the branch (it must exist in the repo using this command)

```
git checkout -b {{branchName}}
```
Checkout new branch (-b flag indicates the need to create a new branch)

```
git commit -u origin {{branchName}}
```
Commit new branch to the local repo
