# Setting up a project on GitHub
* Find two teammates to work with (so you are a group of three).
* Make sure you all have a GitHub account.
* One of you will be responsible for managing files (should have created a new GitHub repository during the previous session), one for managing issues and the third for managing the project. Decide who does what.

## Team member 1: files
* Invite the other team members to your repository: open your repository in a browser -> go to "settings" (top bar, rightmost option) -> go to "Manage access" -> "add people".
* Navigate to the repository's folder on your local machine and create two additional text files with the file names "analysis" and "visualization". You should now have at least the files "analysis", "visualization" and "README" in your repository.
* Add the new files to your repository, commit them and push them to the remote repository (use either GitKraken or the command line interface).

## Team member 2: issues
* Create a new issue: open the repository in a browser -> go to "issues" (top bar, second option to the left) -> "new issue".
* Write some text in the issue, create a list of interactive checkboxes (write "- [ ]" to create a checkbox) and submit the issue.
* Make new project labels: Go back to the "issues" page -> click on "labels" -> make three new labels "analysis", "visualization" and "documentation" and select a distinctive color for each label (you can specify colors by their hexadecimal name and pick colors for example [here](https://www.w3schools.com/colors/colors_picker.asp) or choose from default colors.
* Delete all labels you don't want anymore.
* Assign one or more labels to the issue you just created.
* Assign yourself to the issue.

## Team member 3: project
* Create a new project: navigate to "projects" (top bar, middle) -> "new project"
* Add a column "to do" to the board, using the "To do" preset and selecting "newly added".
* Add a column "in progress" to the board, using the "in progress" preset and selecting "Reopened".
* Add a column "Done" to the board, using the "Done" preset, selecting "Closed".


## All team members
* Pull the new version of the repository to your local machine (use GitKraken or the command line interface). Each of you should now also have the files "analysis", "visualization" and README on your local machines.
* Create a new issue that mentions a file (see below for which file) in the repository (just navigate to the file and copy the URL from your browser). Write some text in the issue description asking for a modification to the file (can be dummy tasks) and create some interactive checkboxes, breaking down the required modifications into smaller steps (your "issues" team mate knows how to do that). Assign another team mate to the issue (make sure each team mate gets one issue) and a label to the issue.
	* Team member 1: "README", assign to team member 2 with label "documentation".
	* Team member 2: "analysis", assign to team member 3 with label "analysis".
	* Team member 3: "visualization", assign to team member 1 with label "visualization".
* Check if the issues have been added to the Project board (should appear in the "To do" column). If not, add them there manually.
* Check out the issue that has been assigned to you and add some text to the file that is mentioned in the issue on your local machine.
* Commit the file and push it to the remote repository. If Git doesn't let you push to the remote repository, you might need to pull changes from other team members to your local machine before you are able to push.
* Navigate to the remote repository in your browser and find the commit number of the change you just pushed: Click on the file you changed in the repository, the commit number is a long string of letters and numbers on the top right. Copy the commit number.
* Go back to the issue you were assigned to. Check all the boxes in the issue description. Write a comment describing what you did, paste the commit number there and "close the issue with comment".
* Check the project board and confirm that all issues have moved to the "Done" column.