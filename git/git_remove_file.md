# Three commands
git rm
git commit
git push


# Land to the folder where the file exists

Example: PS C:\CBC\DSAI\04-NOSQL\MyNotes\test-mongodb> cd git

# look for the file

Eample: PS C:\CBC\DSAI\04-NOSQL\MyNotes\test-mongodb\git> dir


    Directory: C:\CBC\DSAI\04-NOSQL\MyNotes\test-mongodb\git


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        2026-04-21   2:42 PM                images
-a----        2026-04-20   1:07 PM          47690 git-cheat.docx
-a----        2026-04-20   1:05 PM           1089 git-cheat.md
-a----        2026-04-21   2:43 PM           1089 git-cheat.md.txt
-a----        2026-04-21   2:43 PM            805 git-init-workflow.md

# run git rm git-cheat.md.txt

Example: PS C:\CBC\DSAI\04-NOSQL\MyNotes\test-mongodb\git> git rm git-cheat.md.txt
rm 'git/git-cheat.md.txt'

# run  commit -m "remove git
Exaple: PS C:\CBC\DSAI\04-NOSQL\MyNotes\test-mongodb\git> git commit -m "remove git-cheat.md.txt file"
[main 1377d1a] remove git-cheat.md.txt file
 1 file changed, 51 deletions(-)
 delete mode 100644 git/git-cheat.md.txt

 # run git push
Example: PS C:\CBC\DSAI\04-NOSQL\MyNotes\test-mongodb\git> git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 296 bytes | 296.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
 