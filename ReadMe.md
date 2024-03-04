# GitHub Code Push Automation Script

This bash script automates the process of pushing code to a GitHub repository. It prompts users for a commit message and a branch name, and if the specified branch does not exist, it creates a new one on the fly.

## Usage

1. **Clone the Repository:**
   Clone the repository containing this bash script to your local machine.

   ```bash
   git clone <repository-url>
2. **Navigate to the directory containing the bash script.**
cd <repository-directory>

3. **Run the bash script by executing the following command:**

  ```bash 
  bash linda.sh 

4. **The script will prompt you to enter a commit message. Provide a descriptive message summarizing your changes.
Next, it will ask for the branch name where you want to push your changes. If the branch already exists, it will proceed with pushing the code to that branch. If not, it will create a new branch and push the code to it.

5. **Once the script completes execution, your code will be successfully pushed to the specified branch on GitHub.**