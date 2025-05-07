## Assignment-3;Branching Strategies & Merge Conflicts
## Objective
work with branches an resolving the merge conflicts usinf github flow

## Tasks Completed

1. Created a new GitHub repository and followed **GitHub Flow**:
   - Work on feature branches.
   - Open pull requests early and frequently.
   - Merge only after review/conflict resolution.

2. Created a simple HTML page (`index.html`).
3. Created a simple file('styles.css)

## Branches Created

- **Branch A**: `feature/update-styling`  
  Modified styles in `styles.css`.

- **Branch B**: `feature/add-content`  
  Modified the padding in 'styles.css'.

## Merge Conflict Simulated

- Both branches modified `styles.css` — different sections, but same file.
- Merged `feature/update-styling` first.
- Encountered a **merge conflict** while merging `feature/add-content`.

##  Conflict Resolution Steps

1. Switched to conflict branch and pulled updates from `main`:
   git checkout feature/add-content
   git pull origin main

2. Conflict appeared in `styles.css`:
   ![Screenshot 2025-05-07 114233](https://github.com/user-attachments/assets/468abcf0-c96d-4165-8d3f-bdcf40d3870e)
3.The conflict araised due to the changes in padding
4. Manually resolved by combining both:

5. Finalized resolution:
   git add styles.css
   git commit 
   git push origin feature/add-content

7. Successfully merged the pull request.
## ✅ GitHub Repository

[🔗 GitHub Repository Link] https://github.com/Madhu678-coder/github-merge

---

## 📸 Merge Conflict & Resolution Screenshots
![Screenshot 2025-05-07 114040](https://github.com/user-attachments/assets/15fc40d9-bb0d-4105-9f5b-fcbf417aca68)
![Screenshot 2025-05-07 114217](https://github.com/user-attachments/assets/9df9a511-dc5b-40f0-a277-312d0c3fb298)
Commiting After resolving conflict
![Screenshot 2025-05-07 114257](https://github.com/user-attachments/assets/32ba4c77-d2f3-475c-a06b-2e5cbf9ee537)
The Branches are merged succesfully
![Screenshot 2025-05-07 114710](https://github.com/user-attachments/assets/c6f36fdd-05fc-4d8a-b9d9-5bd007425ab9)

---
