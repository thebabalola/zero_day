# This file is mandatory in projects

## Installing Git

1. **Install Git:**
   - To begin, you need to have Git installed on your local computer. If Git is not already installed, you can download it from the official website [here](https://git-scm.com/downloads).

2. **Verify Installation:**
   - After installation, open your terminal or command prompt and verify that Git is installed correctly by running the following command:
        ```bash
	     git --version
	          ```

## Working with Git Locally

3. **Create a Local Directory:**
   - Open your terminal or command prompt and navigate to the location where you want to create your local project directory.
      - Create a directory named "Zero day":
           ```bash
	        mkdir Zero\ day
		     cd Zero\ day
		          ```

4. **Initialize Git Locally:**
   - Initialize a Git repository in your local directory:
        ```bash
	     git init
	          `
5. **Commit Your Changes:**
    - Stage your changes and commit them:
          ```bash
	        git add .
		      git commit -m "Initial commit"
		            ```
6. **Push to GitHub:**
    - Push your local repository to GitHub:
          ```bash
	        git push -u origin master
		      ```

7. **Verify on GitHub:**
    - Go to your GitHub repository's page in your web browser to see your committed changes.
