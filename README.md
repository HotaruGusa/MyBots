# CLion with GitHub
* Click the green "Clone or download" button and copy the HTTPS link.
* You may need to install Git on your machine.
* CLion -> (VCS ->) Checkout from Version Control -> Git
* Paste the link from GitHub.
* You may be prompted to enter your GitHub username and password.

# Create a new branch
* VCS -> Git -> Branches…
* Create your own branch
* Naming convention: First and last initial + dash + purpose (e.g. LD-style)
* Push the branch to the repository: 
    * VCS -> Git -> Push
    * Click Push

# Mantra
* Work on the project. Add/modify files.
* When you finish a task, commit it and push it to the repository:
    * VCS -> Git -> Commit
    * Choose all files added/changed
    * Write commit message
    * Commit and Push (click the arrow in the "Commit" button)
    * Push
    * Wait for confirmation to appear

# Style main.cpp
* Read through main.cpp and figure out what the class and program are intended to do.
    * When there is something in the code that you don't understand, ask the instructor/TA.
* Receive style assignment from the instructor. State your style here:
    * Braces: hanging
    * Case: snake
    * Comments: top of file
    * Variables: no prefixes
* Modify main.cpp to reflect that style.
    * Use the directions in the Mantra above to change the GitHub repository.
    * You can make commits / pushes as frequently as you want.
* Split the code into:
    * a header file with the class declaration;
    * a corresponding .cpp file with the class method definitions; and
    * main.cpp with the functioning program, including at least one global function.
* Commit and push the changes to the repository.

# Grading
This lab will be graded based on the last commit to your branch before the start of class on Tuesday, January 21st.

### Rubric
One point for each of the following:
- [ ] Create a branch with the correct naming convention.
- [ ] Fill out the assigned style rules in the README.
- [ ] Correct and consistent braces.
- [ ] Correct and consistent cases.
- [ ] Correct and consistent comments.
- [ ] Correct and consistent variables.
- [ ] All other style choices are correct and consistent.
- [ ] Create header file with appropriate code.
- [ ] Create corresponding .cpp file with appropriate code.
- [ ] Create a global function in main with consistent style.

# Extra Credit
You can earn up to three bonus points for fixing the bugs in the code.