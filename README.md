GitBasics
=========

# Git basics

## Comiting
Ass and commit all changes with one command
	git commit -am "descriptive text etc"

## Branches
Delete Remote Branch
	git push origin --delete <branchName>p

Delete Lokal branch
	git branch -D <branchName>

Reset to Remote Branch
	git fetch origin master
	git reset --hard FETCH_HEAD
	git clean -df

Force a merge
Prefere own stuff
	git merge branch -X ours
Prefere other stuff
	git merge -X theirs <branchB>

## Tagging
Tag with note
	git tag -a <tag name> -m "comment etc."
push all tags
	git push origin --tags


## LINKS:
Some sshagent magic, useful to avoid multiple typing Passwords during each Session. http://stackoverflow.com/questions/17846529/could-not-open-a-connection-to-your-authentication-agent


