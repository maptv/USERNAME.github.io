# Blog and presentation setup instructions

## GitHub repo

0\. Go to the repo I prepared: <https://github.com/maptv/USERNAME.github.io>

1\. Copy “USERNAME.github.io”

2\. Click “Use this template” and then “Create new repository”

3\. Paste “USERNAME.github.io” in as the repository name

4\. Copy your GitHub username and paste it in place of “USERNAME” in “USERNAME.github.io”

<img width="442" height="395" alt="image" src="https://github.com/user-attachments/assets/dafe6b6b-0194-4b44-9e97-b9116a039540" />

5\. Click “Create repository”

6\. Copy the web address (url)

## Posit Cloud project

7\. Go to [https://posit.cloud](https://posit.cloud/)

8\. Click “New Project” and then “New Project from Git Repository”

9\. Paste the repo url you copied in Step 3 and click “OK”

<img width="659" height="254" alt="image" src="https://github.com/user-attachments/assets/23a40a7e-d897-4aad-8fd7-234ddb3a3776" />

## Git setup

10\. In the Files tab of the bottom right pane, select git.R

11\. Edit the user.name and user.email values in git.R and click the diskette icon to save

12\. When you see a yellow banner above git.R, click "Install" and wait for installation to complete in the background

<img width="512" height="251" alt="image" src="https://github.com/user-attachments/assets/d9571374-4b31-48ab-9edb-9cd7ff4eaa27" />

13\. Click “Source” in the upper right corner of the upper left pane (the one that is displaying git.R)

14\. If you already have a Personal Access Token (PAT), close the new browser tab that opened. Otherwise, enter a note, click “Generate Token”, and click the copy button.

## Updating

15\. Make at least one change to at least one file, such as the edits to git.R above

16\. Click the "Git" tab in the top right pane of Posit Cloud

17\. Click the [check box](https://en.wikipedia.org/wiki/Checkbox#:~:text=a%20graphical%20widget%20that%20allows%20the%20user%20to%20make%20a%20binary%20choice) next to the file you changed

18\. Click "Commit" to open a popup window ([modal](https://en.wikipedia.org/wiki/Modal_window#:~:text=a%20graphical%20control%20element%20subordinate%20to%20an%20application%27s%20main%20window))

19\. Enter a commit message in the upper right corner of the modal and click "Commit"

20\. Close all modals and click the green up arrow labeled "Push" to push your commit to GitHub

<img width="946" height="343" alt="image" src="https://github.com/user-attachments/assets/92db4bfd-1828-48a7-a0f7-bf74a07ae189" />

## Publishing

21\. Push at least one commit to your repo using the instructions above so that the credentials manager has your username and PAT

22\. Click on the "publi.sh" file in the "File" tab of the bottom right pane, click "Run" in the upper right corner of the upper left pane, then type "y" in the terminal, press Enter or Return

<img width="802" height="205" alt="image" src="https://github.com/user-attachments/assets/32e42f7a-0818-4193-86e4-142221e0b02a" />

