(base) ➜  ~ ls   
Desktop         Downloads       Movies          Pictures        bash_tutorial   science.txt
Documents       Library         Music           Public          neuefische_demo
(base) ➜  ~ cd neuefische_demo                                                               
(base) ➜  neuefische_demo cd ..             
(base) ➜  ~ mkdir neuefische     
(base) ➜  ~ cd neuefische/    
(base) ➜  neuefische git clone https://github.com/trinakohestani/hh-da-24-1-demo.git
Cloning into 'hh-da-24-1-demo'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.
(base) ➜  neuefische ls
hh-da-24-1-demo
(base) ➜  neuefische cd hh-da-24-1-demo/
(base) ➜  hh-da-24-1-demo git:(main) ls
README.md
(base) ➜  hh-da-24-1-demo git:(main) code --add .       
(base) ➜  hh-da-24-1-demo git:(main) code --add .     
(base) ➜  hh-da-24-1-demo git:(main) cd ..              
(base) ➜  neuefische code --add .
(base) ➜  neuefische cd hh-da-24-1-demo 
(base) ➜  hh-da-24-1-demo git:(main) git status                                                     
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
(base) ➜  hh-da-24-1-demo git:(main) git add README.md
(base) ➜  hh-da-24-1-demo git:(main) git status       
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        test.md

nothing added to commit but untracked files present (use "git add" to track)
(base) ➜  hh-da-24-1-demo git:(main) ✗ git add .        
(base) ➜  hh-da-24-1-demo git:(main) ✗ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   test.md

(base) ➜  hh-da-24-1-demo git:(main) ✗ git commit -m "Added test file"                                
[main ed21b8a] Added test file
 Committer: Trina Kohestani <trinakohestani@trinas-air.localdomain>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 test.md
(base) ➜  hh-da-24-1-demo git:(main) git log                        
(base) ➜  hh-da-24-1-demo git:(main) git status                     
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
(base) ➜  hh-da-24-1-demo git:(main) git push  
Missing or invalid credentials.
Error: connect ENOENT /var/folders/8y/rwvh8l2506v7ctg86sx8xq2r0000gn/T/vscode-git-e7376323d2.sock
    at PipeConnectWrap.afterConnect [as oncomplete] (node:net:1495:16) {
  errno: -2,
  code: 'ENOENT',
  syscall: 'connect',
  address: '/var/folders/8y/rwvh8l2506v7ctg86sx8xq2r0000gn/T/vscode-git-e7376323d2.sock'
}
Missing or invalid credentials.
Error: connect ENOENT /var/folders/8y/rwvh8l2506v7ctg86sx8xq2r0000gn/T/vscode-git-e7376323d2.sock
    at PipeConnectWrap.afterConnect [as oncomplete] (node:net:1495:16) {
  errno: -2,
  code: 'ENOENT',
  syscall: 'connect',
  address: '/var/folders/8y/rwvh8l2506v7ctg86sx8xq2r0000gn/T/vscode-git-e7376323d2.sock'
}
remote: No anonymous write access.
fatal: Authentication failed for 'https://github.com/trinakohestani/hh-da-24-1-demo.git/'
(base) ➜  hh-da-24-1-demo git:(main) git remote set-url origin git@github.com:trinakohestani/hh-da-24-1-demo.git
(base) ➜  hh-da-24-1-demo git:(main) git push                                                                   
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 286 bytes | 286.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:trinakohestani/hh-da-24-1-demo.git
   29b5717..ed21b8a  main -> main
(base) ➜  hh-da-24-1-demo git:(main) 
