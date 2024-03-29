# Oyster-Data-Checks

PROJECT DESCRIPTION:  
This project is intended to house code for performing data checks on FWRI oyster data. This is the final step in our data flow and involves using R to inspect data for errors. RMarkdown scripts exist for each trip type and lab location. This allows for customization in the error detection process. Data managers are currently the only FWRI staff who will be able to execute these scripts.

PROJECT STATUS:  
This project is currently active. These scripts are being used to fulfill the Project Description. Code may still be revised as needs arise. 

GETTING STARTED:  
You will need:
1. Microsoft SQL Server Management Studio (SSMS) 
2. R/RStudio
3. Git 
4. (Optional) GitHub Desktop or other GUI git tool

SUGGESTED WORKFLOW:
1. If you need to make changes, "Create an Issue" in GitHub describing what changes, additions, or issues need to be addressed.
2. Pull a current copy of this repo to your local machine.
3. Create a new branch to address the issue. Please use format: issue-#-Example when naming a new branch where # is the issue number and Example briefly describes the issue. Alternatively, on GitHub, on the Issues page: Development > Create a branch. 
4. Work on the issue in your local branch.
5. Commit changes to save your work.
6. If more time or contributions from others is needed, publish your branch back to the GitHub repo.
7. When the issue is resolved, issue a pull request to have the changes merged into the main branch and close the outstanding issue.
8. Once a branch is merged, delete that branch.

FILE STRUCTURE:  
/code - RMarkdown scripts  
/code/archive - scripts to check data uploaded prior to ODIN 
