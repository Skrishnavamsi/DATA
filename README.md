PS C:\Users\Krish\OneDrive\Desktop\New folder> git clone https://github.com/krishnavamsi-sanisetty/batch-33.git
Cloning into 'batch-33'...
remote: Enumerating objects: 12, done.
remote: Counting objects: 100% (12/12), done.
remote: Compressing objects: 100% (11/11), done.
remote: Total 12 (delta 0), reused 12 (delta 0), pack-reused 0
Receiving objects: 100% (12/12), done.
PS C:\Users\Krish\OneDrive\Desktop\New folder> git status
fatal: not a git repository (or any of the parent directories): .git
PS C:\Users\Krish\OneDrive\Desktop\New folder> cd .\batch-33\
PS C:\Users\Krish\OneDrive\Desktop\New folder\batch-33> git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
PS C:\Users\Krish\OneDrive\Desktop\New folder\batch-33> git checkout -b krishnavamsis
Switched to a new branch 'krishnavamsis'
PS C:\Users\Krish\OneDrive\Desktop\New folder\batch-33> git status
On branch krishnavamsis
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        2-Git/HelloWorld.Java

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\Krish\OneDrive\Desktop\New folder\batch-33> git add .  
PS C:\Users\Krish\OneDrive\Desktop\New folder\batch-33> git status
On branch krishnavamsis
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   2-Git/HelloWorld.Java

PS C:\Users\Krish\OneDrive\Desktop\New folder\batch-33> git commit -m "Krishnvamsis 1st commit"
[krishnavamsis 169c5ba] Krishnvamsis 1st commit
 1 file changed, 5 insertions(+)
 create mode 100644 2-Git/HelloWorld.Java
PS C:\Users\Krish\OneDrive\Desktop\New folder\batch-33> git status 
On branch krishnavamsis
nothing to commit, working tree clean
PS C:\Users\Krish\OneDrive\Desktop\New folder\batch-33> git push origin krishnavamsis
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 531 bytes | 531.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'krishnavamsis' on GitHub by visiting:
remote:      https://github.com/krishnavamsi-sanisetty/batch-33/pull/new/krishnavamsis
remote:
To https://github.com/krishnavamsi-sanisetty/batch-33.git
 * [new branch]      krishnavamsis -> krishnavamsis
PS C:\Users\Krish\OneDrive\Desktop\New folder\batch-33> 
