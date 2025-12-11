
C:\Users\Koushik\OneDrive\Desktop\FSD>git config --global user.name:"Koushik"
error: invalid key: user.name:Koushik

C:\Users\Koushik\OneDrive\Desktop\FSD>git config --global user.name "Koushik"

C:\Users\Koushik\OneDrive\Desktop\FSD>git config --global user.emial "2400030691@kluniversity.in"

C:\Users\Koushik\OneDrive\Desktop\FSD>git add Hello.java

C:\Users\Koushik\OneDrive\Desktop\FSD>git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   Hello.java


C:\Users\Koushik\OneDrive\Desktop\FSD>git commit -m "Initial commit : added Hello.java"
[master (root-commit) 20b0127] Initial commit : added Hello.java
 1 file changed, 5 insertions(+)
 create mode 100644 Hello.java

C:\Users\Koushik\OneDrive\Desktop\FSD>git status
On branch master
nothing to commit, working tree clean

C:\Users\Koushik\OneDrive\Desktop\FSD>git remote add origin https://github.com/Kl2400030691/s22_gitdemo

C:\Users\Koushik\OneDrive\Desktop\FSD>git branch -M main

C:\Users\Koushik\OneDrive\Desktop\FSD>git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 329 bytes | 65.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Kl2400030691/s22_gitdemo
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

C:\Users\Koushik\OneDrive\Desktop\FSD>git pull --rebase origin main
From https://github.com/Kl2400030691/s22_gitdemo
 * branch            main       -> FETCH_HEAD
Already up to date.

C:\Users\Koushik\OneDrive\Desktop\FSD>git log
commit 20b0127558cc9cc5de879731199eb48964454868 (HEAD -> main, origin/main)
Author: Koushik <2400030691@kluniversity.in>
Date:   Thu Dec 11 14:49:28 2025 +0530

    Initial commit : added Hello.java

C:\Users\Koushik\OneDrive\Desktop\FSD>
