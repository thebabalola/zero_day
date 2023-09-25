# Setting Up Git and Creating a Repository on GitHub

## Installing Git

1. **Install Git:**
   - To begin, you need to have Git installed on your local computer. If Git is not already installed, you can download it from the official website [here](https://git-scm.com/downloads).

2. **Verify Installation:**
   - After installation, open your terminal or command prompt and verify that Git is installed correctly by running the following command:
        ```bash
	     git --version
	          ```

## Creating a Repository on GitHub

3. **Create a GitHub Account:**
   - If you don't have a GitHub account, sign up for one at [GitHub](https://github.com/).

4. **Log In:**
   - Log in to your GitHub account.

5. **Create a New Repository:**
   - Click on the "New" button in the upper right corner of your GitHub profile to create a new repository.
      - Fill in the repository details:
           - Repository name: `zero_day`
	        - Description: This is my first repository as a full-stack engineer
		     - Choose the visibility (Public or Private).
		          - Do not select "Initialize this repository with a README," ".gitignore," or "License" for now.
			     - Click the "Create repository" button.

## Working with Git Locally

6. **Create a Local Directory:**
   - Open your terminal or command prompt and navigate to the location where you want to create your local project directory.
      - Create a directory named "Zero day":
           ```bash
	        mkdir Zero\ day
		     cd Zero\ day
		          ```

7. **Initialize Git Locally:**
   - Initialize a Git repository in your local directory:
        ```bash
	     git init
	          ```

8. **Add a Remote Origin:**
   - Add your GitHub repository as the remote origin. Replace `<your_username>` with your GitHub username:
        ```bash
	     git remote add origin https://github.com/<your_username>/zero_day.git
	          ```

9. **Create Files and Make Changes:**
   - Create and edit files in your local "Zero day" directory as needed.

10. **Commit Your Changes:**
    - Stage your changes and commit them:
          ```bash
	        git add .
		      git commit -m "Initial commit"
		            ```

11. **Push to GitHub:**
    - Push your local repository to GitHub:
          ```bash
	        git push -u origin master
		      ```

12. **Verify on GitHub:**
    - Go to your GitHub repository's page in your web browser to see your committed changes.

Now you have successfully set up Git, created a repository on GitHub, created a local directory, initialized Git, added a remote origin, committed your changes, and pushed them to GitHub.
