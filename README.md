Setting up new Git repository and create development branch for 'new-project':

Setting up new Git repository and create development branch for 'new-project'

Task completion steps:

1. Create new public GitHub repository, e.g. "my-repo".

Navigate to https://github.com/ and login into youe account.
Then, in the page's upper right corner click the "+" button.
Enter "my-repo" in "Repository name" field, then ensure that "Public" radiobutton is checked and "Add a README file" checkbox is unchecked.
Click "Create repository" button below.


2. In your local environment, create a new directory named "new-project".

mkdir new-project


3. Change to the "new-project" directory.

cd new-project


4. Initialize a new public git repository inside the "new-project" directory:

git init

git remote add origin https://github.com/<your_github_username>/my-repo.git

git branch -M main


5. Create a new file named "README.md" and add the initial text into it.

echo -e "Setting up new Git repository and create development branch for 'new-project':\n" >> README.md

6. To prepare "README.md" file to commit, run the following in the terminal:

git add README.md


7. Commit changes to the repo with "init" commit message.

git commit -m "init"

git push -u origin main


8. Create new "development" branch and switch into it.

git checkout -b development


9. Add instructions to "README.md" file, and prepare it to commit:

git add README.md


10. Commit the changes in "development" branch with commit message.

git commit -m "Add step-by-step instructions"

git push


11. Merge changes from "development" branch into "main" branch.

git checkout main

git merge development


12. Check the status to ensure everything is up-to-date.

git status


13. Commit your changes.

git commit -m "Merge changes from development branch"

git push



