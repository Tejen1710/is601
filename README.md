
i# Linux + Git Cheat Sheet (IS601 Homework 1)

This repository is my cheat sheet for 15 basic Linux and Git commands.  
I created and edited this file entirely from the terminal using **vi** in WSL,  
and practiced branching, merging, and pushing to GitHub via SSH.

---

## Linux Commands

1. **ls** – List directory contents  
   Example: `ls -lah`
- Tip: ls -ltr sorts by time, newest last; ls -lhS sorts by size.
2. **cd** – Change directory  
   Example: `cd /home/user`
- Tip: cd - jumps to the previous directory; cd ~ goes to home.
3. **pwd** – Print working directory  
   Example: `pwd`
- Tip: pwd -P shows physical path, pwd -L shows logical path.
4. **mkdir** – Make a new directory  
   Example: `mkdir new_folder`
- Tip: mkdir -p a/b/c creates nested dirs; mkdir -m 755 sets permissions.
5. **touch** – Create an empty file  
   Example: `touch notes.txt`
- Tip: touch -t 202501011200 file sets a custom timestamp.
6. **cp** – Copy files or directories  
   Example: `cp file.txt backup.txt`
- Tip: cp -r copies directories; cp -u copies only if newer.
7. **mv** – Move or rename files  
   Example: `mv file.txt archive/`
- Tip: mv -i prompts before overwrite; mv *.log logs/ moves all logs.
8. **rm** – Remove files or directories  
   Example: `rm -r old_folder`
- Tip: rm -i asks before delete; rm -r dir/ removes folder tree.
9. **grep** – Search for text in files  
   Example: `grep -rin "pattern" .`
- Tip: grep -rni pattern . does recursive search with line numbers.
10. **find** – Search for files  
    Example: `find . -name "*.py"`
- Tip: find . -type f -name "*.py" -size +1M filters by size.
11. **chmod** – Change file permissions  
    Example: `chmod +x script.sh`
- Tip: chmod 755 file makes it executable; chmod u+x adds exec to owner.
---

## Git Commands

12. **git status** – Show changes and branch info  
    Example: `git status`
- Tip: git status -s shows a short summary; --ignored shows ignored files.
13. **git add & git commit** – Stage and commit changes  
    Example:  
    ```bash
    git add README.md
    git commit -m "Added initial content"
    ```
- Tip: git add -p stages hunks interactively; git commit -am updates tracked files.
14. **git branch / git switch** – Create or switch branches  
    Example: `git branch feature1` and `git switch feature1`
- Tip: git switch -c branchname creates and switches; git branch -d deletes.
15. **git merge** – Merge a branch into main  
    Example:  
    ```bash
    git switch main
    git merge feature1
    ```
- Tip: git merge --no-ff keeps a merge commit; git merge --abort cancels.
---




