# Contributing Guidlines
This documentation contains a set of guidelines to help you during the contribution process.
## ⚙Setup Git If You've Never Used Git Before.
* ***If you don't have git on your machine, [install it](https://docs.github.com/en/get-started/quickstart/set-up-git).***
* `git config --global user.name "YourUsername"`
* `git config --global user.email "youremail@example.com"`
## ⭐Contributing
Below you will find the process and workflow used to review and merge your changes.
### Step 0: Find an issue
* Take a look at the existing issue or create your own issues!
* Wait for the Issue to be assigned to you after which you can start working on it.

### Step 1 : Fork the Project

* Fork this Repository. This will create a Local Copy of this Repository on your Github Profile.
Keep a reference to the original project in `upstream` remote.  

* Clone your new fork of the repository
```bash
git clone https://github.com/<your-username>/<repo-name> 
```
* Navigate to the new project directory:
```bash
cd <repo-name>
```
* Set upstream command:
```bash
git remote add upstream https://github.com/<upstream-owner>/<repo-name>  
```  



* If you have already forked the project, update your copy before working.

```bash
git remote update
git checkout <branch-name>
git rebase upstream/<branch-name>
```
### Step 2: Branch
Create a new branch. Use its name to identify the issue you're addressing.
```bash
#It will create a new branch with name Branch_Name
git checkout -b Branch_Name
```
### Step 3: Work on the issue assigned
* Work on the issue(s) assigned to you.
* Add all the files/folders needed.
* After you've made changes or made your contribution to the project, add changes to the branch you've just created by:
```bash
#To add a new file abc.xyz to Branch_Name
git add <abc.xyz>
```
### Step 4: Commit
* To commit, give a descriptive message for the convenience of reviewer by: 
```bash
#This message get associated with all files you have changed
git commit -m "message"
```
### Step 5: Work Remotely
* Now you're ready to push your work to the remote repository.
* When your work is ready and compiles with the project conventions, upload your changes to your fork:
```bash
#To push your work to the remote repository
git push -u origin Bransh_Name
```
* Now your Branch_Name branch will be updated with your commited changes in your forked repo.
### Step 6: Pull Request
* Click on ***contribute*** in the main page of your repo. 
* Click on ***open pull request***.
* Give a title to your PR according to your issue.
* Fill the given PR template to help us review your work.
### All the best! 🥇
## 🛡️Code of Conduct

### Our Pledge

In the interest of fostering an open and welcoming environment, we as
contributors and maintainers pledge to making participation in our project and
our community a harassment-free experience for everyone, regardless of age, body
size, disability, ethnicity, gender identity and expression, level of experience,
nationality, personal appearance, race, religion, or sexual identity and
orientation.

### Our Standards

Examples of behavior that contributes to creating a positive environment
include:

* Using welcoming and inclusive language
* Being respectful of differing viewpoints and experiences
* Gracefully accepting constructive criticism
* Focusing on what is best for the community
* Showing empathy towards other community members

Examples of unacceptable behavior by participants include:

* The use of sexualized language or imagery and unwelcome sexual attention or
advances
* Trolling, insulting/derogatory comments, and personal or political attacks
* Public or private harassment
* Publishing others' private information, such as a physical or electronic
  address, without explicit permission
* Other conduct which could reasonably be considered inappropriate in a
  professional setting

### Our Responsibilities

Project maintainers are responsible for clarifying the standards of acceptable
behavior and are expected to take appropriate and fair corrective action in
response to any instances of unacceptable behavior.

Project maintainers have the right and responsibility to remove, edit, or
reject comments, commits, code, wiki edits, issues, and other contributions
that are not aligned to this Code of Conduct, or to ban temporarily or
permanently any contributor for other behaviors that they deem inappropriate,
threatening, offensive, or harmful.

### Scope

This Code of Conduct applies both within project spaces and in public spaces
when an individual is representing the project or its community. Examples of
representing a project or community include using an official project e-mail
address, posting via an official social media account, or acting as an appointed
representative at an online or offline event. Representation of a project may be
further defined and clarified by project maintainers.

### Enforcement

Instances of abusive, harassing, or otherwise unacceptable behavior may be
reported by contacting the project team at innogeeks@kiet.edu . All
complaints will be reviewed and investigated and will result in a response that
is deemed necessary and appropriate to the circumstances. The project team is
obligated to maintain confidentiality with regard to the reporter of an incident.
Further details of specific enforcement policies may be posted separately.

Project maintainers who do not follow or enforce the Code of Conduct in good
faith may face temporary or permanent repercussions as determined by other
members of the project's leadership.

### Attribution

This Code of Conduct is adapted from the [Contributor Covenant][homepage], version 1.4,
available at [http://contributor-covenant.org/version/1/4][version]

[homepage]: http://contributor-covenant.org
[version]: http://contributor-covenant.org/version/1/4/
