1. GitHub Repository Creation:
- Log in to your GitHub account.
- Create a new repository on GitHub
- Initialize it with a README file. (optional)

2. Local Folder Setup:
 - Create a new folder on your local machine
- Open a terminal or git bash and navigate to the created folder.

3. Git Initialization:
  - Initialize a new Git repository in your local folder.
    ```
      git init
    ```


4. Connecting to GitHub:

  - Link your local repository to the GitHub repository you created in Task 1.

   ```

git remote add origin <repository-url>

   ```

5. Create a File:
- Inside your local folder, create a new text file
- Add a simple text/code and save.
- use touch command and text editor of choice e.g vim

6. Committing Changes:

  - Stage the changes.

   ```bash

   git add hello.txt  or git add .

   ```

  - Commit the changes.

   ```bash

   git commit -m "your commit message"

   ```
7. Pushing to GitHub:

  - Push the committed changes to your GitHub repository.

   ```bash

   git push -u origin main

   ```
8. Verify on GitHub:

  - Visit your GitHub repository in a web browser and confirm that your file(s) and commit message are visible.

