# Git Practice Ground

This repository is for practicing basic Git workflows, including branching, committing, pushing, and creating pull requests.

## Training Goal

Simulate a collaborative development workflow. Each member will practice the following steps:

1.  Create a new branch from `main`.
2.  Make changes to the repository.
3.  Push the changes to the remote repository.
4.  Open a Pull Request (PR) to merge the changes back into `main`.

## Instructions

1.  **Clone the repository:**

    ```bash
    git clone <repository-url>
    cd <repository-name>
    ```

2.  **Create your branch:**
    Create a new branch with a descriptive name, for example: `feat/add-your-name`.

    ```bash
    git checkout -b feat/your-name
    ```

3.  **Add your name:**
    Edit this `README.md` file and add your name to the "Team Members" list below.

4.  **Modify the Python file:**

    - Open `src/app.py`.
    - Add a print statement with your name inside the `greet()` function.

5.  **Commit and push your changes:**

    ```bash
    git add .
    git commit -m "feat: Add [Your Name] and update app.py"
    git push origin feat/your-name
    ```

6.  **Open a Pull Request:**
    - Go to the repository on GitHub.
    - You will see a prompt to create a Pull Request from your new branch.
    - Create the PR and wait for it to be reviewed and merged.

## Team Members

- Huynh Viet Thinh
- Anh Khoa
- Le Vu
- Bao Trang
- Pham Van Tuan
- Truong Thi Minh Loan
