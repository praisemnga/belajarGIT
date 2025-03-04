 Daftar tugas / branch
 1. Tugas-git
 2. Tugas-html
 3. Tugas-css
 4. Tugas-js
 5. Tugas-midProject
 6. Tugas-php
 7. Tugas-finalProject
    
 Daftar perintah GiT

ASUS@preis MINGW64 ~
$ cd Dokumen
bash: cd: Dokumen: No such file or directory

ASUS@preis MINGW64 ~
$ cd Documents

ASUS@preis MINGW64 ~/Documents
$ git clone https://github.com/praisemnga/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 9, done.
remote: Counting objects: 100% (9/9), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 9 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (9/9), done.
Resolving deltas: 100% (1/1), done.

ASUS@preis MINGW64 ~/Documents
$ cd belajarGIT

ASUS@preis MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-git

ASUS@preis MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ notepad Tugas-git.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan Tugas-git.txt"
[Tugas-git 52629a1] Menambahkan Tugas-git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@preis MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-git
Updating 3585c5a..52629a1
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 315 bytes | 315.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/praisemnga/belajarGIT.git
   3585c5a..52629a1  main -> main

ASUS@preis MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-html

ASUS@preis MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ touch Tugas-git.html

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ notepad Tugas-html.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan Tugas-html.txt"
[Tugas-html 15f3ee8] Menambahkan Tugas-html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@preis MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-html
Updating 52629a1..15f3ee8
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 345 bytes | 345.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/praisemnga/belajarGIT.git
   52629a1..15f3ee8  main -> main

ASUS@preis MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-css

ASUS@preis MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ notepad Tugas-css.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan Tugas-css.txt"
[Tugas-css 15bbdea] Menambahkan Tugas-css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@preis MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-css
Updating 15f3ee8..15bbdea
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 376 bytes | 376.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/praisemnga/belajarGIT.git
   15f3ee8..15bbdea  main -> main

ASUS@preis MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-js

ASUS@preis MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ notepad Tugas-js.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git commit -m "menambahkan Tugas-js.txt"
[Tugas-js c713e66] menambahkan Tugas-js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@preis MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-js
Updating 15bbdea..c713e66
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 310 bytes | 310.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/praisemnga/belajarGIT.git
   15bbdea..c713e66  main -> main

ASUS@preis MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-midProject

ASUS@preis MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ notepad Tugas-midProject.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan Tugas-midProject.txt"
[Tugas-midProject 99982dd] Menambahkan Tugas-midProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@preis MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-midProject
Updating c713e66..99982dd
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 327 bytes | 327.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/praisemnga/belajarGIT.git
   c713e66..99982dd  main -> main

ASUS@preis MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-php

ASUS@preis MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ notepad Tugas-php.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan Tugas-php.txt"
[Tugas-php f9ca778] Menambahkan Tugas-php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@preis MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-php
Updating 99982dd..f9ca778
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 311 bytes | 311.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/praisemnga/belajarGIT.git
   99982dd..f9ca778  main -> main

ASUS@preis MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-finalProject

ASUS@preis MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ notepad Tugas-finalProject.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan Tugas-finalProject.txt"
[Tugas-finalProject 2b8bec6] Menambahkan Tugas-finalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@preis MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-finalproject
Updating f9ca778..2b8bec6
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

ASUS@preis MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 319 bytes | 319.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/praisemnga/belajarGIT.git
   f9ca778..2b8bec6  main -> main

ASUS@preis MINGW64 ~/Documents/belajarGIT (main)
$
