# git-practice-with-victor

# 🧭 Contribution Guidelines

## 🔸 Branch Workflow

We use a **Git branching strategy** to keep our main codebase stable and production-ready.

### **Main Branch (`main`)**
- The `main` branch represents the **production-ready** version of the project.  
- **Do not push directly** to `main` under any circumstance.  
- All changes must go through a **Pull Request (PR)** and be **merged into `main` only from the `dev` branch** after review.

### **Development Branch (`dev`)**
- The `dev` branch is our **integration branch** where all new features are tested before release.  
- Always create new branches from `dev`.  
- When your feature or fix is complete, open a **Pull Request to merge into `dev`**, not `main`.

### **Feature Branches**
- Name your feature branches clearly using the following format:  

**Examples:**
- `feature/login-screen`
- `feature/add-payment-api`
- `fix/typo-in-readme`
