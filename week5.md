# Week 5 — GitHub Foundations

This week is your introduction to using GitHub.  
You will practice cloning a repository, making commits, creating branches, opening pull requests, creating Issues, and linking them to your work.  
Expect this to take about **6–8 hours** in total.  

---

## 📖 Readings

From *GitHub for Dummies (2nd Edition)*:  

- **Chapter 1 – Understanding the Git in GitHub**  
  - Introducing GitHub  
  - Understanding Version Control  
  - Git Version Control  
  - Git’s Place on GitHub  
  - Signing Up for GitHub.com  
  - Personalizing Your GitHub.com Account (skim: Accounts, Passwords, Notifications)  
  - Discovering Helpful Resources  

- **Chapter 2 – Setting Up Your Collaborative Coding Environment**  
  - Exploring GitHub.com  
  - Understanding Your Profile  
  - Getting to Know GitHub Desktop  
  - Setting Up GitHub Desktop  

- **Chapter 3 – Introducing GitHub Repositories**  
  - Setting Up a Repository  
  - Exploring Your Repository  
  - Modifying README.md  
  - Merging a Pull Request  
  - Using Issues (⚠️ skip the Project Boards part — we’ll cover Kanban in Week 6)  

From **GitHub Docs** (short references):  
- [Hello World Tutorial](https://docs.github.com/en/get-started/start-your-journey/hello-world)  
- [GitHub Desktop Basics](https://docs.github.com/en/desktop/overview/getting-started-with-github-desktop)  

---

## 🛠️ Activities

You will complete the following tasks in your own repository, `dsa8670-<yourusername>`,
which you created from the course template in Setup Assignment 3.

### Part 1 – Setup & Exploration (≈1 hr)
1. Open **GitHub Desktop**, sign in if needed, and choose **File → Clone repository**.
   - On the **GitHub.com** tab, select your `dsa8670-<yourusername>` repository.
   - Pick a folder on your computer and click **Clone**.
2. Explore the files:
   - `README.md` – overview of the repository
   - `week5.md` – these instructions
   - `intro.txt` – placeholder text you will edit
   - `.github/workflows/autograde.yaml` – the automated self-check; don't edit this
3. In GitHub Desktop, look at the **History** tab to see the commits so far.

> **About the self-check.** Every time you push, GitHub runs a check and reports which
> parts of this assignment it can see in your repository. It is there to help you catch
> a missing file before you submit. It never fails, and it is not your grade.

---

### Part 2 – Commit Practice (≈1.5–2 hrs)
1. Open `intro.txt` in a text editor (Notepad, VS Code, etc.).  
2. Replace `[STUDENT NAME]` with your full name.  
3. In GitHub Desktop:  
   - The change will appear in the **Changes** tab.  
   - Enter a commit message: `Added my name to intro.txt`  
   - Click **Commit to main**.  
4. Make **three additional edits**, each committed separately:  
   - Add your major/program.  
   - Add your favorite dataset or industry interest.  
   - Add one reason you are studying analytics.  
5. After each edit: save → commit with a clear message → push origin.  

✅ Checkpoint: You should now see at least **4 commits** in the **History** tab.  

---

### Part 3 – Branching & Pull Request (≈2 hrs)
1. In GitHub Desktop, click **Current Branch → New Branch**, name it `update-bio`.  
2. On this branch, edit `README.md` and add a short paragraph (3–5 sentences):  
   - Why version control matters for analytics.  
   - At least one connection to this week’s readings.  
3. Save → commit in GitHub Desktop → push origin.  
4. On **GitHub.com**, open your repo.  
   - You’ll see a prompt to open a Pull Request for `update-bio`.  
   - Click **Compare & pull request**.  
   - Add a comment explaining what you changed.  
   - Submit the PR.  
5. Merge the PR into `main`.  

---

### Part 4 – Reflection File (≈1 hr)
1. Back in **main**, create a new file called `reflection.md`.  
2. Write 2–3 paragraphs:  
   - One thing you learned from the readings.  
   - One challenge you faced in GitHub and how you solved it.  
   - One way you see GitHub helping future team projects.  
3. Commit and push the file.  

---

### Part 5 – Advanced Practice: Issues & Pseudocode (≈1–1.5 hrs)
1. In GitHub Desktop, create another branch called `analysis-draft`.  
2. Create a new file called `pseudocode.md`.  
3. Write **pseudo-code** (descriptive steps, not actual code) for analyzing a dataset:  
   - Step 1: Load the dataset  
   - Step 2: Clean the data (explain how)  
   - Step 3: Calculate summary statistics  
   - Step 4: Create a visualization  
   - Step 5: Interpret results  
4. Commit and push this file to `analysis-draft`.  
5. On GitHub.com, open a new **Issue** titled *Draft pseudocode for analysis*.  
6. Open a Pull Request to merge `analysis-draft` → `main`.  
   - In the PR description, type `Closes #<issue-number>` to link it to the Issue.  
7. Merge the PR into `main`.  

---

## 📤 Deliverables (Submit in Canvas)
- Link to your repository  
- Commit history showing ≥6 commits  
- Evidence of at least 2 merged PRs (`update-bio` and `analysis-draft`)  
- Screenshot of the linked Issue + PR  
- `reflection.md` file with your paragraphs  
- `pseudocode.md` file with descriptive analysis steps  

---

## 📊 Grading Rubric (100 pts)

**Repository evidence (70 pts):**  
- 20 pts – `intro.txt` edited with name + 3 details  
- 20 pts – Commit history shows ≥6 commits  
- 15 pts – `update-bio` branch + PR merged  
- 15 pts – `analysis-draft` branch + PR merged with `pseudocode.md`  

**Written work (30 pts):**  
- 10 pts – Commit messages are meaningful  
- 10 pts – `reflection.md` connects to readings  
- 10 pts – PR comments & Issue show workflow understanding  

---

💡 **Tips for Success**  
- Use **GitHub Desktop** for local commits/branches.  
- Use **GitHub.com** for PRs and Issues.  
- Don’t try to memorize — check the readings or Docs when stuck.  
