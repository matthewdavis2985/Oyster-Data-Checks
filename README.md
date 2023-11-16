# Oyster-Data-Checks

PROJECT DESCRIPTION:
This project is intended to house code for performing data checks on FWRI oyster data. This is the final step in our data flow and involves using R to inspect data for errors. RMarkdown scripts exist for each trip type and lab location. This allows for customization in the error detection process. Data managers are currently the only FWRI staff who will be able to execute these scripts.

PROJECT STATUS:
This project is currently under development. Code is still being written and revised. Many RMarkdown scripts still need to be created and refined.

GETTING STARTED:
You will need:
1. Microsoft SQL Server Management Studio (SSMS) 
2. R/RStudio
3. Git 
4. (Optional) GitHub Desktop or other GUI git tool

SUGGESTED WORKFLOW:
1. If you need to make changes, "Create an Issue" in GitHub describing what changes, additions, or issues need to be addressed.
2. Pull a current copy of this repo to your local machine.
3. Create a new branch to address the issue. Please use format: issue-#-Example when naming a new branch where # is the issue number and Example briefly describes the issue.
4. Work on the issue in your local branch.
5. Commit changes to save your work.
6. If more time or contributions from others is needed, publish your branch back to the GitHub repo.
7. When the issue is resolved, issue a pull request to have the changes merged into the main branch and close the outstanding issue.

FILE STRUCTURE:
/code - RMarkdown scripts
/documentation - In depth documentation of RMarkdown scripts
/outputs - The outputs of the RMarkdown scripts