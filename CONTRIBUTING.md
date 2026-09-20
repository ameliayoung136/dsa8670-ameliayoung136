# Contributing Guidelines – DSA 8670

This repository is your practice space for **Week 5** of the course.  
You will use it to learn GitHub basics: Issues, commits, branches, and Pull Requests.

---

## 📌 General Workflow
1. **Find or create an Issue**  
   - Every change should be connected to an Issue on your Project board.
   - If no Issue exists, create one before you start working.

2. **Make the change locally**  
   - Clone the repo with GitHub Desktop.
   - Edit the relevant file (e.g., `README.md`, `docs/about.md`, `src/hello.py`).

3. **Commit your change**  
   - Write a clear commit message.  
   - Always reference the Issue number so GitHub can link them.  
     - Example:  
       ```
       Fixes #2 – Added my name to docs/team.md
       ```

4. **Push to GitHub**  
   - Push your commit(s) from GitHub Desktop to the remote repo.
   - Check your Project board for automation (Issues can move or close).

5. **Open a Pull Request**  
   - Push your branch, then open a PR from that branch into `main` **in your own repository**.
   - Link it to the Issue using the syntax:  
     ```
     Closes #3
     ```
   - Add a short description of what changed.

---

## ✍️ Commit Message Examples
- `Fixes #1 – Updated README with project description`
- `Closes #4 – Modified hello.py to print my name`
- `Fixes #3 – Added fun fact to team.md`

---

## 📋 Project Board Use
- **Backlog:** Tasks not yet started.  
- **In Progress:** Tasks you are currently working on.  
- **Review:** Tasks waiting on Pull Request review.  
- **Done:** Completed tasks.  

Always drag your Issue cards to the correct column as you work.

---

## ✅ Expectations
- One Issue per distinct task.  
- One clear commit (or set of commits) per Issue.  
- PRs should be descriptive and linked to an Issue.  
- Update `CHANGELOG.md` with a brief note for any change you make.  

---

## 🚫 What *not* to do
- Don’t commit unrelated changes together (e.g., “fixed everything”).
- Don’t skip creating Issues — the workflow depends on them.
- Don’t push IDE/system files (`.DS_Store`, `__pycache__`) — they are ignored via `.gitignore`.

---

Following these steps will help you practice the same workflow we'll use in the Week 7 group project, where your team will share one repository.
