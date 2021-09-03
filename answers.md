Answer 1.  git version 2.17.1
Answer 2. user.name=gobkinknoblin
user.email=cloverdecadence@gmail.com
Answer 3. GIT-ADD(1)                        Git Manual                        GIT-ADD(1)

NAME
       git-add - Add file contents to the index

SYNOPSIS
       git add [--verbose | -v] [--dry-run | -n] [--force | -f] [--interactive | -i] [--patch | -p]
                 [--edit | -e] [--[no-]all | --[no-]ignore-removal | [--update | -u]]
                 [--intent-to-add | -N] [--refresh] [--ignore-errors] [--ignore-missing] [--renormalize]
                 [--chmod=(+|-)x] [--] [<pathspec>...]

DESCRIPTION
       This command updates the index using the current content found in the
       working tree, to prepare the content staged for the next commit. It
       typically adds the current content of existing paths as a whole, but
       with some options it can also be used to add content with only part of
       the changes made to the working tree files applied, or remove paths
       that do not exist in the working tree anymore.

5. On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	answers.md

6. On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md
	new file:   answers.md

7. [master (root-commit) 73356f3] Initial commit
 2 files changed, 25 insertions(+)
 create mode 100644 README.md
 create mode 100644 answers.md

8. commit 73356f30cbc02d566fe9f5fcf3cd46d77bd212e8 (HEAD -> master)
Author: gobkinknoblin <cloverdecadence@gmail.com>
Date:   Fri Sep 3 16:41:59 2021 -0400

    Initial commit

9. On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")

10. no

11. Username for 'https://github.com': gobkinknoblin   
Password for 'https://gobkinknoblin@github.com': 
To https://github.com/gobkinknoblin/git-lab.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/gobkinknoblin/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

12. the lines I added online were added to my local file

13. .  ..  .git  .gitignore  README.md


