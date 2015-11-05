Notes for starting git in 2043

Step 1, get an online git account.
Your user name for reference: W3illiam

Step 2, Use a machine that has git installed.

Step 3, go to the command prompt and lets get started.

Big idea: Get to your folder.

use *dir* to find out what is in the directory.
```
C:\Users\LAB>Dir
 Volume in drive C is OS
 Volume Serial Number is 64FB-7BCF

 Directory of C:\Users\LAB

06/21/2012  01:13 PM    <DIR>          .
06/21/2012  01:13 PM    <DIR>          ..
05/14/2015  08:10 AM    <DIR>          Contacts
11/05/2015  08:18 AM    <DIR>          Desktop
05/14/2015  08:10 AM    <DIR>          Documents
05/14/2015  08:10 AM    <DIR>          Downloads
05/14/2015  08:10 AM    <DIR>          Favorites
05/14/2015  08:10 AM    <DIR>          Links
05/14/2015  08:10 AM    <DIR>          Music
05/14/2015  08:10 AM    <DIR>          Pictures
05/14/2015  08:10 AM    <DIR>          Saved Games
05/14/2015  08:10 AM    <DIR>          Searches
05/14/2015  08:10 AM    <DIR>          Videos
               0 File(s)              0 bytes
              13 Dir(s)  410,543,587,328 bytes free
```
Change directories to our folder.
```
C:\Users\LAB>DIR Desktop
```
Look in the directory for our file using *dir*
```
 Volume in drive C is OS
 Volume Serial Number is 64FB-7BCF

 Directory of C:\Users\LAB\Desktop

11/05/2015  08:18 AM    <DIR>          .
11/05/2015  08:18 AM    <DIR>          ..
11/05/2015  08:18 AM               629 2023_git_Practice - Shortcut.lnk
06/21/2012  02:16 PM             1,553 Report Problems-ITS Dept.lnk
               2 File(s)          2,182 bytes
               2 Dir(s)  410,543,587,328 bytes free
```
C:\Users\LAB>
Change 


1. Go to github.com
2. Sign in
3. Create a new repositorty
4. Name the new repository
5. Provide a meaningful description in the repository
THis is 
Who
What
When
Where
Why

Step 6: Do not select the button to initialize the readme
Step 7: Follow the instructions on Github.com for:
…or create a new repository on the command line
echo # 2043_2015_11_05_Practice >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/W3illiam/2043_2015_11_05_Practice.git
git push -u origin master

Now I will show those instructions and their results inside the command prompt.
I will copy and paste them one line at a time.

Below is command prompt activity

1. Make a readme.md file.
``
C:\Users\LAB\Desktop\2023_git_Practice>echo # 2043_2015_11_05_Practice >> README
.md
``

C:\Users\LAB\Desktop\2023_git_Practice>git init
Initialized empty Git repository in C:/Users/LAB/Desktop/2023_git_Practice/.git/


C:\Users\LAB\Desktop\2023_git_Practice>git add README.md

C:\Users\LAB\Desktop\2023_git_Practice>git add .

C:\Users\LAB\Desktop\2023_git_Practice>git commit -m "first commit"

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'LAB@STF126H-PC.(none)')

C:\Users\LAB\Desktop\2023_git_Practice>git config user.name "William McCaslin"

C:\Users\LAB\Desktop\2023_git_Practice>git config user.email "mccaslinw@student.
swosu.edu"

C:\Users\LAB\Desktop\2023_git_Practice>git commit -m "first commit"
[master (root-commit) ac01903] first commit
 2 files changed, 2 insertions(+)
 create mode 100644 README.md
 create mode 100644 Starting_Git_2043.md

C:\Users\LAB\Desktop\2023_git_Practice>git remote add origin https://github.com/
W3illiam/2043_2015_11_05_Practice.git

C:\Users\LAB\Desktop\2023_git_Practice>git push -u origin master
Username for 'https://github.com': W3illiam
Password for 'https://W3illiam@github.com':
Counting objects: 4, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 313 bytes | 0 bytes/s, done.
Total 4 (delta 0), reused 0 (delta 0)
To https://github.com/W3illiam/2043_2015_11_05_Practice.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.

C:\Users\LAB\Desktop\2023_git_Practice>