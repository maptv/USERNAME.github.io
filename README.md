# Blog and presentation setup instructions

0\. Go to the repo I prepared: <https://github.com/maptv/USERNAME.github.io>

1\. Copy “USERNAME.github.io”

2\. Click “Use this template” and then “Create new repository”

3\. Paste “USERNAME.github.io” in as the repository name

4\. Copy your GitHub username and paste it in place of “USERNAME” in “USERNAME.github.io”

<img width="447" height="395" alt="image" src="https://github.com/user-attachments/assets/3d8f177d-69c3-46c6-9f63-770b64fcab0d" />

5\. Click “Create repository”

6\. Copy the web address (url)

7\. Go to [https://posit.cloud](https://posit.cloud/)

8\. Click “New Project” and then “New Project from Git Repository”

9\. Paste the repo url you copied in Step 3 and click “OK”

10\. In the Files tab of the bottom right pane, select git.R

11\. Edit the user.name and user.email values in git.R and click the diskette icon to save

12\. When you see a yellow banner above git.R, click "Install" and wait for installation to complete in the background

13\. Click “Source” in the upper right corner of the upper left pane (the one that is displaying git.R)

14\. If you already have a Personal Access Token (PAT), close the new browser tab that opened. Otherwise, enter a note, click “Generate Token”, and click the copy button.

### Updating

15\. Make at least one change to at least one file, such as the edits to git.R above

16\. Click the "Git" tab in the top right pane of Posit Cloud

17\. Click the [check box](https://en.wikipedia.org/wiki/Checkbox#:~:text=a%20graphical%20widget%20that%20allows%20the%20user%20to%20make%20a%20binary%20choice) next to the file you changed

18\. Click "Commit" to open a popup window ([modal](https://en.wikipedia.org/wiki/Modal_window#:~:text=a%20graphical%20control%20element%20subordinate%20to%20an%20application%27s%20main%20window))

19\. Enter a commit message in the upper right corner of the modal and click "Commit"

20\. Close all modals and click the green up arrow labeled "Push" to push your commit to GitHub

**Publishing**

21\. Push at least one commit to your repo using the instructions above so that the credentials manager has your username and PAT

22\. Copy the command below, paste it into the terminal tab in the lower left pane, and press Enter or Return

```         
quarto publish gh-pages
```
