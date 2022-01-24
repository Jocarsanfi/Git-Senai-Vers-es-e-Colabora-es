# Git-Senai-Vers-es-e-Colabora-esJosé Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes
$ git init
Initialized empty Git repository in C:/Users/José Carlos/Git - Senai -Versoes Colaboracoes/.git/

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Read me.txt

nothing added to commit but untracked files present (use "git add" to track)

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git add Read me.txt
fatal: pathspec 'Read' did not match any files

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git add .

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   Read me.txt


José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git commit
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'José Carlos@José.(none)')

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git config --global user.name "Jocarsanfi"

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   Read me.txt


José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git commit
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'José Carlos@José.(none)')

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git config --global user.email "jocarsanfi@gmail.com"

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git commit
hint: Waiting for your editor to close the file... unix2dos: converting file C:/Users/José Carlos/Git - Senai -Versoes Colaboracoes/.git/COMMIT_EDITMSG to DOS format...
dos2unix: converting file C:/Users/José Carlos/Git - Senai -Versoes Colaboracoes/.git/COMMIT_EDITMSG to Unix format...
[main (root-commit) 5b518ed] Aprimoramento do arquivo Read me
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Read me.txt

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git status
On branch main
nothing to commit, working tree clean

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git status
On branch main
nothing to commit, working tree clean

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git log
commit 5b518edf87737af62d0ed40c384b74cf8088c816 (HEAD -> main)
Author: Jocarsanfi <jocarsanfi@gmail.com>
Date:   Mon Jan 24 17:24:32 2022 -0300

    Aprimoramento do arquivo Read me

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git log
commit 5b518edf87737af62d0ed40c384b74cf8088c816 (HEAD -> main)
Author: Jocarsanfi <jocarsanfi@gmail.com>
Date:   Mon Jan 24 17:24:32 2022 -0300

    Aprimoramento do arquivo Read me

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git status
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Read me.txt

no changes added to commit (use "git add" and/or "git commit -a")

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git add .

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git commit
hint: Waiting for your editor to close the file... unix2dos: converting file C:/Users/José Carlos/Git - Senai -Versoes Colaboracoes/.git/COMMIT_EDITMSG to DOS format...
dos2unix: converting file C:/Users/José Carlos/Git - Senai -Versoes Colaboracoes/.git/COMMIT_EDITMSG to Unix format...
[main cd7d5e4] Modificação 1 feito no arquivo Read me
 1 file changed, 1 insertion(+)

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git log
commit cd7d5e4b816112b8b8a355c7a5e29da916049376 (HEAD -> main)
Author: Jocarsanfi <jocarsanfi@gmail.com>
Date:   Mon Jan 24 17:39:43 2022 -0300

    Modificação 1 feito no arquivo Read me

commit 5b518edf87737af62d0ed40c384b74cf8088c816
Author: Jocarsanfi <jocarsanfi@gmail.com>
Date:   Mon Jan 24 17:24:32 2022 -0300

    Aprimoramento do arquivo Read me

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git status
On branch main
nothing to commit, working tree clean

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ guit log
bash: guit: command not found

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git log
commit cd7d5e4b816112b8b8a355c7a5e29da916049376 (HEAD -> main)
Author: Jocarsanfi <jocarsanfi@gmail.com>
Date:   Mon Jan 24 17:39:43 2022 -0300

    Modificação 1 feito no arquivo Read me

commit 5b518edf87737af62d0ed40c384b74cf8088c816
Author: Jocarsanfi <jocarsanfi@gmail.com>
Date:   Mon Jan 24 17:24:32 2022 -0300

    Aprimoramento do arquivo Read me

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git reset --hard HEAD~1
HEAD is now at 5b518ed Aprimoramento do arquivo Read me

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git log
commit 5b518edf87737af62d0ed40c384b74cf8088c816 (HEAD -> main)
Author: Jocarsanfi <jocarsanfi@gmail.com>
Date:   Mon Jan 24 17:24:32 2022 -0300

    Aprimoramento do arquivo Read me

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git commit
On branch main
nothing to commit, working tree clean

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git add .

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   Read me.txt


José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git log
commit 5b518edf87737af62d0ed40c384b74cf8088c816 (HEAD -> main)
Author: Jocarsanfi <jocarsanfi@gmail.com>
Date:   Mon Jan 24 17:24:32 2022 -0300

    Aprimoramento do arquivo Read me

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git commit
hint: Waiting for your editor to close the file... unix2dos: converting file C:/Users/José Carlos/Git - Senai -Versoes Colaboracoes/.git/COMMIT_EDITMSG to DOS format...
dos2unix: converting file C:/Users/José Carlos/Git - Senai -Versoes Colaboracoes/.git/COMMIT_EDITMSG to Unix format...
[main 688c560] MOdificação do aqrquino Read me
 1 file changed, 1 insertion(+)

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git log
commit 688c5601df718713df9527950422a6a10a56e72f (HEAD -> main)
Author: Jocarsanfi <jocarsanfi@gmail.com>
Date:   Mon Jan 24 17:55:03 2022 -0300

    MOdificação do aqrquino Read me

commit 5b518edf87737af62d0ed40c384b74cf8088c816
Author: Jocarsanfi <jocarsanfi@gmail.com>
Date:   Mon Jan 24 17:24:32 2022 -0300

    Aprimoramento do arquivo Read me

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git branch develop

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git checkout develop
Switched to branch 'develop'

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (develop)
$ git add .

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (develop)
$ git status
On branch develop
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Outro documento read me.txt


José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (develop)
$ git commit
hint: Waiting for your editor to close the file... unix2dos: converting file C:/Users/José Carlos/Git - Senai -Versoes Colaboracoes/.git/COMMIT_EDITMSG to DOS format...
dos2unix: converting file C:/Users/José Carlos/Git - Senai -Versoes Colaboracoes/.git/COMMIT_EDITMSG to Unix format...
[develop 084b9cb] Criação de outro documento read me
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Outro documento read me.txt

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (develop)
$ git checkout main
Switched to branch 'main'

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git checkout develop
Switched to branch 'develop'

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (develop)
$ git checkout main
Switched to branch 'main'

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git chekout develop
git: 'chekout' is not a git command. See 'git --help'.

The most similar command is
        checkout

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git checkout develop
Switched to branch 'develop'

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (develop)
$ git remote add origin https://github.com/Jocarsanfi/Git-Senai-Vers-es-e-Colabora-es.git

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (develop)
$ git remote -v
origin  https://github.com/Jocarsanfi/Git-Senai-Vers-es-e-Colabora-es.git (fetch)
origin  https://github.com/Jocarsanfi/Git-Senai-Vers-es-e-Colabora-es.git (push)

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (develop)
$ git checkout main
Switched to branch 'main'

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git remote add origin https://github.com/Jocarsanfi/Git-Senai-Vers-es-e-Colabora-es.git
error: remote origin already exists.

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git branch main
fatal: A branch named 'main' already exists.

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git remote
origin

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git remote -v
origin  https://github.com/Jocarsanfi/Git-Senai-Vers-es-e-Colabora-es.git (fetch)
origin  https://github.com/Jocarsanfi/Git-Senai-Vers-es-e-Colabora-es.git (push)

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git branch
  develop
* main

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git push -u origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (6/6), 494 bytes | 247.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Jocarsanfi/Git-Senai-Vers-es-e-Colabora-es.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git add .

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git log
commit 688c5601df718713df9527950422a6a10a56e72f (HEAD -> main, origin/main)
Author: Jocarsanfi <jocarsanfi@gmail.com>
Date:   Mon Jan 24 17:55:03 2022 -0300

    MOdificação do aqrquino Read me

commit 5b518edf87737af62d0ed40c384b74cf8088c816
Author: Jocarsanfi <jocarsanfi@gmail.com>
Date:   Mon Jan 24 17:24:32 2022 -0300

    Aprimoramento do arquivo Read me
...skipping...
commit 688c5601df718713df9527950422a6a10a56e72f (HEAD -> main, origin/main)
Author: Jocarsanfi <jocarsanfi@gmail.com>
Date:   Mon Jan 24 17:55:03 2022 -0300

    MOdificação do aqrquino Read me

commit 5b518edf87737af62d0ed40c384b74cf8088c816
Author: Jocarsanfi <jocarsanfi@gmail.com>
Date:   Mon Jan 24 17:24:32 2022 -0300

    Aprimoramento do arquivo Read me
:...skipping...
commit 688c5601df718713df9527950422a6a10a56e72f (HEAD -> main, origin/main)
Author: Jocarsanfi <jocarsanfi@gmail.com>
Date:   Mon Jan 24 17:55:03 2022 -0300

    MOdificação do aqrquino Read me

commit 5b518edf87737af62d0ed40c384b74cf8088c816
Author: Jocarsanfi <jocarsanfi@gmail.com>
Date:   Mon Jan 24 17:24:32 2022 -0300

    Aprimoramento do arquivo Read me
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git remote add .
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from


José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$  git remote add -m
error: switch `m' requires a value

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git remote add -m
error: switch `m' requires a value

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git remote add .
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from


José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git commit
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git log
commit 688c5601df718713df9527950422a6a10a56e72f (HEAD -> main, origin/main)
Author: Jocarsanfi <jocarsanfi@gmail.com>
Date:   Mon Jan 24 17:55:03 2022 -0300

    MOdificação do aqrquino Read me

commit 5b518edf87737af62d0ed40c384b74cf8088c816
Author: Jocarsanfi <jocarsanfi@gmail.com>
Date:   Mon Jan 24 17:24:32 2022 -0300

    Aprimoramento do arquivo Read me

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git push -u origin main
Everything up-to-date
Branch 'main' set up to track remote branch 'main' from 'origin'.

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git push origin main
Everything up-to-date

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git commit
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git pull origin master
fatal: couldn't find remote ref master

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git pull origin main
From https://github.com/Jocarsanfi/Git-Senai-Vers-es-e-Colabora-es
 * branch            main       -> FETCH_HEAD
Already up to date.

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git commit -m "descrição do commit"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git push origin main
Everything up-to-date

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git add .

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git commit
hint: Waiting for your editor to close the file... unix2dos: converting file C:/Users/José Carlos/Git - Senai -Versoes Colaboracoes/.git/COMMIT_EDITMSG to DOS format...
dos2unix: converting file C:/Users/José Carlos/Git - Senai -Versoes Colaboracoes/.git/COMMIT_EDITMSG to Unix format...
[main 137f1d3] COmandos do GIT
 1 file changed, 108 insertions(+), 1 deletion(-)
 rewrite Read me.txt (100%)

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git log
commit 137f1d3ba3ed29a4c4a0266aec2ad42ef7b2cb38 (HEAD -> main)
Author: Jocarsanfi <jocarsanfi@gmail.com>
Date:   Mon Jan 24 19:24:28 2022 -0300

    COmandos do GIT

commit 688c5601df718713df9527950422a6a10a56e72f (origin/main)
Author: Jocarsanfi <jocarsanfi@gmail.com>
Date:   Mon Jan 24 17:55:03 2022 -0300

    MOdificação do aqrquino Read me

commit 5b518edf87737af62d0ed40c384b74cf8088c816
Author: Jocarsanfi <jocarsanfi@gmail.com>
Date:   Mon Jan 24 17:24:32 2022 -0300

    Aprimoramento do arquivo Read me

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 1.63 KiB | 1.63 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Jocarsanfi/Git-Senai-Vers-es-e-Colabora-es.git
   688c560..137f1d3  main -> main

José Carlos@Jos□ MINGW64 ~/Git - Senai -Versoes Colaboracoes (main)
$
