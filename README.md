# Linux + Git Cheat Sheet (IS601 Homework 1)

This repository is my cheat sheet for 15 basic Linux and Git commands.  
I created and edited this file entirely from the terminal using **vi** in WSL,  
and practiced branching, merging, and pushing to GitHub via SSH.

---

## Linux Commands

1. **ls** – List directory contents  
   Example: `ls -lah`

2. **cd** – Change directory  
   Example: `cd /home/user`

3. **pwd** – Print working directory  
   Example: `pwd`

4. **mkdir** – Make a new directory  
   Example: `mkdir new_folder`

5. **touch** – Create an empty file  
   Example: `touch notes.txt`

6. **cp** – Copy files or directories  
   Example: `cp file.txt backup.txt`

7. **mv** – Move or rename files  
   Example: `mv file.txt archive/`

8. **rm** – Remove files or directories  
   Example: `rm -r old_folder`

9. **grep** – Search for text in files  
   Example: `grep -rin "pattern" .`

10. **find** – Search for files  
    Example: `find . -name "*.py"`

11. **chmod** – Change file permissions  
    Example: `chmod +x script.sh`

---

## Git Commands

12. **git status** – Show changes and branch info  
    Example: `git status`

13. **git add & git commit** – Stage and commit changes  
    Example:  
    ```bash
    git add README.md
    git commit -m "Added initial content"
    ```

14. **git branch / git switch** – Create or switch branches  
    Example: `git branch feature1` and `git switch feature1`

15. **git merge** – Merge a branch into main  
    Example:  
    ```bash
    git switch main
    git merge feature1
    ```

---




