PS C:\SANU's DATA\VS Code\LocalRepo> git init
Reinitialized existing Git repository in C:/SANU's DATA/VS Code/LocalRepo/.git/

PS C:\SANU's DATA\VS Code\LocalRepo> git remote add origin https://github.com/Sanu2002-bit/Local-Repo.git

PS C:\SANU's DATA\VS Code\LocalRepo> git remote -v
origin  https://github.com/Sanu2002-bit/Local-Repo.git (fetch)
origin  https://github.com/Sanu2002-bit/Local-Repo.git (push)

PS C:\SANU's DATA\VS Code\LocalRepo> git branch   
* master

PS C:\SANU's DATA\VS Code\LocalRepo> git branch -M main

PS C:\SANU's DATA\VS Code\LocalRepo> git branch        
* main

PS C:\SANU's DATA\VS Code\LocalRepo> git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 14 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 232 bytes | 232.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Sanu2002-bit/Local-Repo.git
 * [new branch]      main -> main

PS C:\SANU's DATA\VS Code\LocalRepo> git push -u origin main
branch 'main' set up to track 'origin/main'.
Everything up-to-date

PS C:\SANU's DATA\VS Code\LocalRepo>    

this 1 is sanuk commit
sss
PS C:\SANU's DATA\VS Code\LocalRepo> git branch
* main
PS C:\SANU's DATA\VS Code\LocalRepo> git checkout -b sanubranch  
Switched to a new branch 'sanubranch'
PS C:\SANU's DATA\VS Code\LocalRepo> git branch
  main
* sanubranch
PS C:\SANU's DATA\VS Code\LocalRepo> git checkout sanubranch
Already on 'sanubranch'
PS C:\SANU's DATA\VS Code\LocalRepo> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\SANU's DATA\VS Code\LocalRepo> git branch             
* main
  sanubranch
PS C:\SANU's DATA\VS Code\LocalRepo> git branch -d sanubranch
Deleted branch sanubranch (was cc555eb).
PS C:\SANU's DATA\VS Code\LocalRepo> 

-- I am on sanuk branch and i want to commit this

