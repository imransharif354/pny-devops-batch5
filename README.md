task 

**Steps:**

1. Clone the repository (if you haven't already):
    
    ```bash
    git clone https://github.com/username/repository.git
    cd repository
    ```
    
2. Create a new branch and switch to it:
    
    ```bash
    git checkout -b feature-branch
    ```
    
3. Edit a shared file (e.g., `README.md`). Add some new text.
4. Stage and commit your changes:
    
    ```bash
    git add README.md
    git commit -m "Updated README on feature-branch"
    ```
    
5. Switch to `main` and make different changes to the same file:
    
    ```bash
    git checkout main
    ```
    
6. Edit `README.md` again in a different way.
7. Commit the changes:
    
    ```bash
    git add README.md
    git commit -m "Updated README on main"
    ```
    
8. Merge your `feature-branch` into `main`:
    
    ```bash
    git merge feature-branch
    ```
    
9. **Git will show a merge conflict!** Open the file and manually resolve the conflict by choosing which changes to keep.
10. After resolving the conflict, commit the merge:
    
    ```bash
    git add README.md
    git commit -m "Resolved merge conflict in README.md"
    ```
    
11. Push the changes:
    
    ```bash
    git push origin main
    ```
    


# pny-devops-batch5
get started with git


# pny-devops-batch5
get started with git
Imran Shairf Here
