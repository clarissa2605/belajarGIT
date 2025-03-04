Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject

Daftar perintah GiT

ASUS@DESKTOP-PTBT1OP MINGW64 ~ (master)
$ cd Documents

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents (master)
$ git clone https://github.com/clarissa2605/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents (master)
$ cd belajarGIT

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-git

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ notepad Tugas-git.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan Tugas-git.txt"
[Tugas-git a3e8165] Menambahkan Tugas-git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-git
Updating 4a3207d..a3e8165
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 305 bytes | 305.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/clarissa2605/belajarGIT.git
   4a3207d..a3e8165  main -> main

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-html

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ notepad Tugas-html.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan Tugas-html.txt"
[Tugas-html 2f2f733] Menambahkan Tugas-html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-html
Updating a3e8165..2f2f733
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 338 bytes | 338.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/clarissa2605/belajarGIT.git
   a3e8165..2f2f733  main -> main

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-css

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ notepad Tugas-css.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan Tugas-css.txt"
[Tugas-css 69efb7d] Menambahkan Tugas-css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-css
Updating 2f2f733..69efb7d
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 364 bytes | 364.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/clarissa2605/belajarGIT.git
   2f2f733..69efb7d  main -> main

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-js

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ notepad Tugas-js.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan Tugas-js.txt"
[Tugas-js 26cb686] Menambahkan Tugas-js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-js
Updating 69efb7d..26cb686
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 296 bytes | 296.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/clarissa2605/belajarGIT.git
   69efb7d..26cb686  main -> main

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-midProject

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ notepad Tugas-midProject.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan Tugas-midProject.txt"
[Tugas-midProject dc5e087] Menambahkan Tugas-midProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-midProject
Updating 26cb686..dc5e087
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 323 bytes | 323.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/clarissa2605/belajarGIT.git
   26cb686..dc5e087  main -> main

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-php

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ notepad Tugas-php.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan Tugas-php.txt"
[Tugas-php 976913b] Menambahkan Tugas-php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-php
Updating dc5e087..976913b
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 298 bytes | 298.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/clarissa2605/belajarGIT.git
   dc5e087..976913b  main -> main

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-finalProject

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ notepad Tugas-finalProject.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan Tugas-finalProject.txt"
[Tugas-finalProject b1f6a88] Menambahkan Tugas-finalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 976913b..b1f6a88
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

ASUS@DESKTOP-PTBT1OP MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 318 bytes | 318.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/clarissa2605/belajarGIT.git
   976913b..b1f6a88  main -> main

