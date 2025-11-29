# Development Process

This document explains how the calculator project was built step by step.

## Steps Followed

1. **Project Setup**
   - Created a new folder `calculator-project` and opened it in Visual Studio Code.
   - Added the main file `calculator.py` with the calculator code.

2. **Git Initialization**
   - Initialized a Git repository using:
     ```bash
     git init
     ```
   - Configured Git username and email (first-time setup).

3. **Writing Code**
   - Implemented basic arithmetic functions: addition, subtraction, multiplication, division.
   - Added error handling for division by zero.
   - Tested the program in VS Code terminal using:
     ```bash
     python calculator.py
     ```

4. **Version Control**
   - Staged changes with:
     ```bash
     git add .
     ```
   - Committed changes with descriptive messages:
     ```bash
     git commit -m "Initial commit: Added calculator code"
     ```

5. **Repository Hosting**
   - Created a new repository on GitHub.
   - Linked local repo to GitHub using:
     ```bash
     git remote add origin https://github.com/your-username/calculator-project.git
     ```
   - Pushed changes with:
     ```bash
     git push origin main
     ```

6. **Documentation**
   - Added `.gitignore` to exclude unnecessary files.
   - Created `README.md` with project details, usage instructions, and screenshots.
   - Added `docs/` folder with `overview.md`, `development.md`, and `future.md`.

7. **Commit History**
   - Ensured at least 5 meaningful commits:
     - Added calculator code
     - Added README
     - Added .gitignore
     - Added docs folder
     - Updated calculator with error handling

---

## Tools Used
- **Visual Studio Code** → for writing and testing code
- **Git** → for version control
- **GitHub** → for hosting the repository

---

## Outcome
A fully functional calculator project hosted on GitHub with:
- Clean repository structure
- Proper documentation
- Multiple commits showing development progress
