## Assignment: Branching and Contribution with Git - The Internship Repository

**Objective:** This assignment will give you hands-on experience with forking a repository, creating a branch, adding content, and contributing back through a pull request. You will be interacting with a simulated "internship" project.

**Repo to Contribute to:** `[Replace with the actual GitHub repo URL]`/internship

**Steps:**

1. **Star the Repository:**
    * Navigate to the  `[Replace with the actual GitHub repo URL]`/internship repository on GitHub.
    * Click the "Star" button at the top right of the page.  This helps us track engagement!

2. **Fork the Repository:**
    * On the same GitHub page, click the "Fork" button (also located at the top right).
    * Choose your personal GitHub account as the destination for the fork.  This creates a copy of the repository under your own account.

3. **Clone the Repository:**
    * Go to *your* forked repository (e.g., `github.com/your-username/internship`).
    * Click the green "Code" button, then copy the URL (either HTTPS or SSH).
    * Open your terminal or command prompt.
    * Navigate to the directory where you want to store the project files (e.g., `cd Documents/GitHub`).
    * Run the following command, replacing `[YOUR_REPOSITORY_URL]` with the URL you copied:

        ```bash
        git clone [YOUR_REPOSITORY_URL]
        ```

4. **Create a New Branch:**
    * Navigate into the cloned repository directory: `cd internship`
    * Create a new branch named `add_your_name`:

        ```bash
        git checkout -b add_your_name
        ```

    * This command does two things:  it creates a new branch named `add_your_name` and switches to that branch.

5. **Add Your File:**
    * Inside the `internship` directory, create a new text file named `your_name.txt` (replace `your_name` with your actual name, e.g., `theri.txt`).
    * Open the file in a text editor.
    * Add your favorite quote to the file.  Make sure the quote is on the first line. Optionally, you can add your name on the second line.  For example:

        ```
        "The only way to do great work is to love what you do." - Steve Jobs
        Theri
        ```

    * Save the file.

6. **Commit and Push Your Changes:**
    * Add your new file to the staging area:

        ```bash
        git add your_name.txt
        ```

    * Commit your changes with a descriptive message:

        ```bash
        git commit -m "Add your_name.txt with favorite quote"
        ```

    * Push your branch to your forked repository on GitHub:

        ```bash
        git push origin add_your_name
        ```

7. **Create a Pull Request:**
    * Go to *your* forked repository on GitHub (e.g., `github.com/your-username/internship`).
    * You should see a banner saying "Your branch `add_your_name` has recently been pushed."  Click the "Compare & pull request" button on that banner. If you don't see the banner, select the `add_your_name` branch in the branch selector, and click "Contribute".
    * Verify that the base repository is the original `[Replace with the actual GitHub repo URL]`/internship repository and the base branch is `main`.
    * Write a clear and concise title and description for your pull request.  For example:
        * **Title:** Add [Your Name].txt file
        * **Description:**  Adds my file containing my favorite quote.
    * Click the "Create pull request" button.

8. **Submit your Assignment**
    * Submit the URL of your Pull Request to the assignment link where you found these instructions.

**Grading Criteria:**

* Successfully forking the repository.
* Successfully cloning the repository to your local machine.
* Creating and using a new branch.
* Adding a file named correctly and containing the required content.
* Committing changes with a meaningful commit message.
* Pushing the branch to your forked repository.
* Creating a pull request against the original repository.

**Key Concepts Reinforced:**

* **Forking:** Creating a personal copy of a repository.
* **Cloning:** Downloading a repository to your local machine.
* **Branching:** Isolating changes to avoid disrupting the main codebase.
* **Committing:** Saving changes with a descriptive message.
* **Pushing:** Uploading local changes to a remote repository.
* **Pull Requests:** Proposing changes to a repository for review and merging.

Good luck!
