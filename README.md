Microsoft Windows [Version 10.0.19045.6466]
(c) Microsoft Corporation. All rights reserved.

C:\Users\tridi\OneDrive\Desktop\Resumes\GITHUB ACTIONS DOCUMENT SHARED BY PIU>git init
Reinitialized existing Git repository in C:/Users/tridi/OneDrive/Desktop/Resumes/GITHUB ACTIONS DOCUMENT SHARED BY PIU/.git/

C:\Users\tridi\OneDrive\Desktop\Resumes\GITHUB ACTIONS DOCUMENT SHARED BY PIU>git remote add origin https://github.com/tridib98/testRepository98.git
error: remote origin already exists.

C:\Users\tridi\OneDrive\Desktop\Resumes\GITHUB ACTIONS DOCUMENT SHARED BY PIU>git add .

C:\Users\tridi\OneDrive\Desktop\Resumes\GITHUB ACTIONS DOCUMENT SHARED BY PIU>git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Development Workflow and Resources (Out of date).pdf
        new file:   GIT_Initial Setup - Only once and before the first time you deploy.pdf
        new file:   Helpful terminal commands.pdf
        new file:   Overview-Git process used for collaborative development,.pdf


C:\Users\tridi\OneDrive\Desktop\Resumes\GITHUB ACTIONS DOCUMENT SHARED BY PIU>git commit -m "Adding all documents and syllabus"
[master cdf96cf] Adding all documents and syllabus
 4 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Development Workflow and Resources (Out of date).pdf
 create mode 100644 GIT_Initial Setup - Only once and before the first time you deploy.pdf
 create mode 100644 Helpful terminal commands.pdf
 create mode 100644 Overview-Git process used for collaborative development,.pdf

C:\Users\tridi\OneDrive\Desktop\Resumes\GITHUB ACTIONS DOCUMENT SHARED BY PIU>git branch -M main

C:\Users\tridi\OneDrive\Desktop\Resumes\GITHUB ACTIONS DOCUMENT SHARED BY PIU>git push -u origin main
remote: Invalid username or token. Password authentication is not supported for Git operations.
fatal: Authentication failed for 'https://github.com/tridib98/testRepository98.git/'

C:\Users\tridi\OneDrive\Desktop\Resumes\GITHUB ACTIONS DOCUMENT SHARED BY PIU>git push -u origin main --force
info: please complete authentication in your browser...
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 4 threads
Compressing objects: 100% (9/9), done.
Writing objects: 100% (9/9), 151.80 KiB | 7.23 MiB/s, done.
Total 9 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/tridib98/testRepository98.git
 + 7433ad2...cdf96cf main -> main (forced update)
branch 'main' set up to track 'origin/main'.

C:\Users\tridi\OneDrive\Desktop\Resumes\GITHUB ACTIONS DOCUMENT SHARED BY PIU>
