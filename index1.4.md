Step 1: Install & Verify Git
If you haven't already, download and install Git from the official Git website.

Open your terminal and verify the installation by running:

Bash
git --version
Step 2: Configure Your Git Identity
Before making commits, configure your Git username and email so your commits are associated with you. Run these commands in your terminal:

Bash
git config --global user.name "Your Full Name"
git config --global user.email "your.email@example.com"
Step 3: Initialize the Git Repository
Open your terminal and navigate to your project folder (e.g., web-development-practice):

Bash
cd path/to/web-development-practice
Initialize the repository by running:

Bash
git init
(This creates a hidden .git folder in your project directory).

Step 4: Make 3 Meaningful Commits
To fulfill requirement #7, you will make three separate changes to your HTML file, staging and committing each one individually.

Commit 1: Initial HTML Structure
Create or open your index.html file and add the basic structure:

HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Portfolio</title>
</head>
<body>
    <h1>Welcome to My Website</h1>
</body>
</html>
Stage and commit the file:

Bash
git status
git add index.html
git commit -m "feat: add initial index.html structure"
Commit 2: Add a Description Paragraph
Open index.html and add a paragraph under the heading:

HTML
    <h1>Welcome to My Website</h1>
    <p>This is my first project tracked with Git and GitHub!</p>
Stage and commit the change:

Bash
git add index.html
git commit -m "feat: add introductory paragraph to index.html"
Commit 3: Add a Footer Section
Open index.html and add a footer at the bottom:

HTML
    <h1>Welcome to My Website</h1>
    <p>This is my first project tracked with Git and GitHub!</p>
    <footer>&copy; 2026 Web Dev Student</footer>
</body>
</html>
Stage and commit the final change:

Bash
git add index.html
git commit -m "feat: add footer section with copyright"
Step 5: Verify Your Commit History
To view your three commits in a neat list, run:

Bash
git log --oneline
You should see all three commit messages displayed in chronological order.

Submission Checklist
Take screenshots of the following for your assignment submission:

Repository Folder: A view of your project folder showing the files (and optionally the hidden .git folder if your file explorer shows hidden files).

Commit History: A screenshot of your terminal window showing the output of git log --oneline displaying your three distinct commits.