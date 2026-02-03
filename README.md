# aplankas
Susikuriame katalogą, tada GitHube susikuriame repozitoriją.

git init
git branch -M main
git remote add origin https://github.com/Ausra123/aplankas.git
git push -u origin main (pirmą kartą, antrą kartą pakanka git push)


Komandų eiliškumas:

ausra@DESKTOP-FNT4MCG MINGW64 ~/Desktop/aplankas (master)
$ git branch -M main

ausra@DESKTOP-FNT4MCG MINGW64 ~/Desktop/aplankas (main)
$ echo "# aplankas" >> README.md

ausra@DESKTOP-FNT4MCG MINGW64 ~/Desktop/aplankas (main)
$ git init
Reinitialized existing Git repository in C:/Users/ausra/Desktop/aplankas/.git/

ausra@DESKTOP-FNT4MCG MINGW64 ~/Desktop/aplankas (main)
$ git add README.md
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it

ausra@DESKTOP-FNT4MCG MINGW64 ~/Desktop/aplankas (main)
$ git commit -m "first commit"
[main (root-commit) 7f21d08] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

ausra@DESKTOP-FNT4MCG MINGW64 ~/Desktop/aplankas (main)
$ git branch -M main

ausra@DESKTOP-FNT4MCG MINGW64 ~/Desktop/aplankas (main)
$ git remote add origin https://github.com/Ausra123/aplankas.git

ausra@DESKTOP-FNT4MCG MINGW64 ~/Desktop/aplankas (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 219 bytes | 54.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Ausra123/aplankas.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

ausra@DESKTOP-FNT4MCG MINGW64 ~/Desktop/aplankas (main)
$ git add .
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it

ausra@DESKTOP-FNT4MCG MINGW64 ~/Desktop/aplankas (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md
        new file:   index.html


ausra@DESKTOP-FNT4MCG MINGW64 ~/Desktop/aplankas (main)
$ git commit -m "pridėtas naujas failas index.html"
[main 197621e] pridėtas naujas failas index.html
 2 files changed, 17 insertions(+)
 create mode 100644 index.html

ausra@DESKTOP-FNT4MCG MINGW64 ~/Desktop/aplankas (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

ausra@DESKTOP-FNT4MCG MINGW64 ~/Desktop/aplankas (main)
$ git push -u origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 606 bytes | 202.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Ausra123/aplankas.git
   7f21d08..197621e  main -> main
branch 'main' set up to track 'origin/main'.

Pagrindinės komandos atnaujinimui:
ausra@DESKTOP-FNT4MCG MINGW64 ~/Desktop/aplankas (main)
$ git add .
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it

ausra@DESKTOP-FNT4MCG MINGW64 ~/Desktop/aplankas (main)
$ git commit -m "atnaujintas Readme"
[main 6d91b20] atnaujintas Readme
 1 file changed, 84 insertions(+), 1 deletion(-)

ausra@DESKTOP-FNT4MCG MINGW64 ~/Desktop/aplankas (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.

Jeigu reikia autentifikuoti save reikia pridėti savo vardą ir pašto adresą.

git config --global user.name GitHubo vardas
git config --globas user.email pasto.adresas@gmail.com (gitHubo paštas)

usra@DESKTOP-FNT4MCG MINGW64 ~/Desktop/aplankas (main)
$ git log --oneline (parodo versijas)
db5c69a (HEAD -> main, origin/main) atnaujinatas failas konfiguravimo komandomis
6d91b20 atnaujintas Readme
197621e pridėtas naujas failas index.html
7f21d08 first commit
 pereiti į kitą versją 
 git checkout 197621e 
 