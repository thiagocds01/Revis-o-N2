Thiago Silva@NotCastThiSilva MINGW64 ~/Documents/thiago/4 periodo/1
$ git clone https://github.com/thiagocds01/Revis-o-N2.git
Cloning into 'Revis-o-N2'...
warning: You appear to have cloned an empty repository.

Thiago Silva@NotCastThiSilva MINGW64 ~/Documents/thiago/4 periodo/1
$ ls
Revis-o-N2/

Thiago Silva@NotCastThiSilva MINGW64 ~/Documents/thiago/4 periodo/1
$ cd Revis-o-N2/

Thiago Silva@NotCastThiSilva MINGW64 ~/Documents/thiago/4 periodo/1/Revis-o-N2 (main)
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.index

nothing added to commit but untracked files present (use "git add" to track)

Thiago Silva@NotCastThiSilva MINGW64 ~/Documents/thiago/4 periodo/1/Revis-o-N2 (main)
$ git add .

Thiago Silva@NotCastThiSilva MINGW64 ~/Documents/thiago/4 periodo/1/Revis-o-N2 (main)
$ git commit -m 'criação de index da pagina'
[main (root-commit) 107079c] criação de index da pagina
 1 file changed, 19 insertions(+)
 create mode 100644 index.index

Thiago Silva@NotCastThiSilva MINGW64 ~/Documents/thiago/4 periodo/1/Revis-o-N2 (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 364 bytes | 364.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/thiagocds01/Revis-o-N2.git
 * [new branch]      main -> main

Thiago Silva@NotCastThiSilva MINGW64 ~/Documents/thiago/4 periodo/1/Revis-o-N2 (main)
$ code .

Thiago Silva@NotCastThiSilva MINGW64 ~/Documents/thiago/4 periodo/1/Revis-o-N2 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    index.index

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        imagem/
        index.html

no changes added to commit (use "git add" and/or "git commit -a")

Thiago Silva@NotCastThiSilva MINGW64 ~/Documents/thiago/4 periodo/1/Revis-o-N2 (main)
$ git add .

Thiago Silva@NotCastThiSilva MINGW64 ~/Documents/thiago/4 periodo/1/Revis-o-N2 (main)
$ git commit -m 'inserindo foto do gato'
[main 85a399a] inserindo foto do gato
 3 files changed, 23 insertions(+), 19 deletions(-)
 create mode 100644 imagem/gato.jpg
 create mode 100644 index.html
 delete mode 100644 index.index

Thiago Silva@NotCastThiSilva MINGW64 ~/Documents/thiago/4 periodo/1/Revis-o-N2 (main)
$ git push origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 3.41 MiB | 1.72 MiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/thiagocds01/Revis-o-N2.git
   107079c..85a399a  main -> main

Thiago Silva@NotCastThiSilva MINGW64 ~/Documents/thiago/4 periodo/1/Revis-o-N2 (main)
$
