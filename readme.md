Microsoft Windows [Version 10.0.16299.309]
(c) 2017 Microsoft Corporation. All rights reserved.

C:\Users\INDUS INFOTEK-2>sites
'sites' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\INDUS INFOTEK-2>d:

D:\>cd server

D:\server>cd xampp

D:\server\xampp>cd htdocs

D:\server\xampp\htdocs>cd sites

D:\server\xampp\htdocs\sites>mkdir Giting_Started

D:\server\xampp\htdocs\sites>cd Giting_Started

D:\server\xampp\htdocs\sites\Giting_Started>ls
'ls' is not recognized as an internal or external command,
operable program or batch file.

D:\server\xampp\htdocs\sites\Giting_Started>dir
 Volume in drive D is New Volume
 Volume Serial Number is E872-FEAF

 Directory of D:\server\xampp\htdocs\sites\Giting_Started

18-Apr-18  12:15 PM    <DIR>          .
18-Apr-18  12:15 PM    <DIR>          ..
18-Apr-18  12:15 PM                 0 readme.md
               1 File(s)              0 bytes
               2 Dir(s)  156,928,352,256 bytes free

D:\server\xampp\htdocs\sites\Giting_Started>git init
Initialized empty Git repository in D:/server/xampp/htdocs/sites/Giting_Started/.git/

D:\server\xampp\htdocs\sites\Giting_Started>git status
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        readme.md

nothing added to commit but untracked files present (use "git add" to track)

D:\server\xampp\htdocs\sites\Giting_Started>subl readme.md
'subl' is not recognized as an internal or external command,
operable program or batch file.

D:\server\xampp\htdocs\sites\Giting_Started>git add readme.md

D:\server\xampp\htdocs\sites\Giting_Started>git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   readme.md


D:\server\xampp\htdocs\sites\Giting_Started>git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   readme.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        second.txt


D:\server\xampp\htdocs\sites\Giting_Started>git add second.txt

D:\server\xampp\htdocs\sites\Giting_Started>git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   readme.md
        new file:   second.txt


D:\server\xampp\htdocs\sites\Giting_Started>git commit -m "Initial commit added read me file from us"
[master (root-commit) 7630c09] Initial commit added read me file from us
 2 files changed, 58 insertions(+)
 create mode 100644 readme.md
 create mode 100644 second.txt

D:\server\xampp\htdocs\sites\Giting_Started>git status
On branch master
nothing to commit, working tree clean

D:\server\xampp\htdocs\sites\Giting_Started>

18-Apr-18  03:02 PM    <DIR>          .
18-Apr-18  03:02 PM    <DIR>          ..
18-Apr-18  03:03 PM                32 .gitignore
18-Apr-18  03:02 PM                 0 file.txt
18-Apr-18  12:43 PM             2,930 readme.md
18-Apr-18  12:43 PM                30 second.txt
               4 File(s)          2,992 bytes
               2 Dir(s)  156,884,156,416 bytes free

$ ssh-keygen -t rsa -b 4096 -C "umashankarsh1@yahoo.com"
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/INDUS INFOTEK-2/.ssh/id_rsa):
Created directory '/c/Users/INDUS INFOTEK-2/.ssh'.
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/INDUS INFOTEK-2/.ssh/id_rsa.
Your public key has been saved in /c/Users/INDUS INFOTEK-2/.ssh/id_rsa.pub.
The key fingerprint is:
SHA256:38FWwGRSy4GQ1ZN4HB2HU3Y2SKwjIFHgfhKHnKO+tB0 umashankarsh1@yahoo.com
The key's randomart image is:
+---[RSA 4096]----+
|     o+..+oOX=o=*|
|    o.o.. o+B*++o|
|     B...  .+... |
|    o +  . + .   |
|   . o .S . =    |
|  .   o  . o .   |
|   o E    . .    |
|  . + .          |
|   o .           |
+----[SHA256]-----+
