
<div class="header">
    <div class="logo"><img src="Logo.png"/></div>
</div>
<div class="container">
<h1>Module One: What Git is & Setting Git Up</h1>
<p>Git is a Version Control System (VCS) that allows computer files to be tracked when changed/developed, git operates on a tree system where the user can create branches of the main branch. This allows clients to work within a grouped project folder and contribute changes to that project on single branches that are separate to the main/master branch.</p>
<p>The staging area (git add) is where git’s power lies as all members of the project can discussed the branch that is to be merges with the main branch beforehand, which adds an extra level of error checking before any merge happens.</p>
<p>Git was created in 2005 by Linus Torvalds and Junio C Hamano, Linus Torvalds also created Linux and the Linux kernel, git does not have any specific coding language so is extremely coder friendly, hens why half the world’s companies are using it to create their projects.</p>


<h2>Installation Requirement</h2>
<p>In this module you will be required to setup a working environment that entails installation of git, git bash and a github account; along with a text editor of your choice.</p>

<h2>Module One Assessment: Course Folder Setup</h2>
<h3>Assessment Brief</h3>
<p>You are required to follow the steps below to create a repository named “IGG-yourname” along with a file named “CourseLayout.md” and copy the following texted in to that file.</p>

<samp><h1>Introduction to Git & Github: Your name here</h1>
<h2>Course Assessment Layout</h2>
<p>This repository is set up to store the assessment results for completing the ICC course.</p>
<samp>1. Module One: What Git is & Setting Git Up</samp> 
<p>By this readme being setup and here stats that the assessment was followed and complered.</p></samp>

<h2>Steps</h2>
    <p>Once all installation requirements have been met please follow these steps. </p>
    <p>1. Create a folder named “IGG-yourname” on your computer. </p>
    <p>2. Open the new folder, right click any white space in the folder and select “git bash here”. </p>
    <p>3. Create the README.md file by typing echo Introduction > READEME.md.</p>
    <p>4. Type "git init": The git init command initializes a new default empty git repository.</p>
    <p>5. Now type "git config --global user.name "yourname" " this is setting the workspace/folder with a git user name.</p> 
    <p>6. Now type "git config --global user.email "youremail@gmail.com" " this is setting the workspace/folder with a git user email.</p>
    <p>7. Now open the README.md in your text editor and paste in the text given in the assessment brief replacing any text n there and save.</p>
    <p>8. Type "git add" and your file's name or git add *: The git add command adds the changes that have been done in the working directory stages them ready for a commit.</p>
    <p>9. Type "git commit -m "Module One Course Folder Set up" will commit all the files that are in the staging area ready to be pushed.</p>
    <p>10. Login to your github account and create a new repository named “IGG-yourname”.</p>
    <p>11. Type git remote add origin URL -of - IGG-yourname Repo</p>
    <p>12. Type git push –u origin master, this will push your repo to the github remote.</p>
    <p>13. Go to your Github account and look for the new repository to ensure everything is uploaded correctly.</p>

<h2>Conclusion</h2>
    <p>Once all steps had been followed the folder and a file where created I then edited the file, I then pushed and merged. Through carrying out these step a number of times there where little coding hits that I found very important, lines that help me a lot was "git status(obviously), git remote -v" and remembering that if I don’t "git commit -m "Comment" then nothing will be pushed from the staging area as it is empty. This is an easy task but for someone that is not normalised to git it can take some time to visualize the process.</p>

<h1>Module Two: Workflow & Staging</h1>
    <h2>Non-linear Workflow</h2>
        <p>A git workflow is a suggestion/recipe for how a team will use Git to achieve working on a project in a consistent way with more functionality and productivity. </p>
        <p>With the option of creating single branches for individuals to work on the main project and then discus gives any project that is carried out in git is instantly given an error checking and development stage before any merges to the master project.</p>
    <h2>Staging</h2>
        <p>The staging area is the where files are placed ready to be committed and allows the developer to keep editing the files staged; this allows freedom of development on two layers, the developers work area and the branch (group discussion development) before the main merge.  </p>
        <p>The main command to stage a file is "git add filename" this will place the file and any changes in to the staging area. Once the files are in the staging area you can then commit them for every change you make with a comment but it is advised to try and keep your commits to every five change.</p>
    <h2>Module Two Assessment: Committed. Modified & Staged</h2>
        <h3>Module Brief:</h3>
        <p>You are required to create a folder named “ModuleTwo” inside your IGG folder with a file named “README.md”. You are then asked to write an essay based on the three states of git within your README.md file in your new ModuleTwo folder.</p>
        <p>Once you are finished your essay please push it to your IGG repository, remember to add, commit and have a good comment on the commit.</p>
        

            
            
<h1>Module Three:  Git Status & Gitignore file</h1>
    <h2>Status</h2>
        <p>The git status command is one of the most used commands as it allows you to view the stage you are at and the file stage, such as Mfile.txt is modified or Dfile.txt means file has been deleted. There are a number of flags for the command that are very helpful, like status -s = status short: this will give a short output within columns and has flags RED and green colour coding such as the M AND D mentioned before.</p>
        <p>Green M = Modified and staged</p>
        <p>Red D = files that have been deleted.</p>
        <p>Green A = files that have just been added.</p>
        <p>If texted is coloured orange then this means that the branch is be hide or in front of the remote and cyan means the branch matches its remote.</p>
    <h2>Gitignore File</h2>
        <p>The gitignore file is used to tell git to ignore certain file types. You can tell git to ignore folders as well as files, where this helps with security throughout the project.</p>
        <p>To create the gitignore file type "echo gitignore > gitignore" with no extension.</p>
        <p>To ignore folders type "foldername" within the gitignore file.</p>
        <p>To ignore files type filename and extension.</p>
        <p>To ignore all file types you can type "*.txt" or the file extension you want to ignore.</p>
        <p>If you place a # before any text in the ignore file it will be seen as a comment within the ignore file. </p>
        <p>In the command line you can type "echo newtext >> filename.txt" and it will append the file, this is due to the >> symbol which means appending.</p>
        <p>The "git mv filename" command is used to move files and can be used to rename files "rm filename.txt newfilename.txt".<p>
    <h2>Module Three Assessment: Create a Gitignore File</h2>
        <h3>Assessment Brief</h3>
            <p>In this assessment you are required to create a file named FileOne.md through the git bash command line, you are then asked to create a gitignore file through the command line as well. You will then type the line you need to ignore the FileOne.md in the gitignore file; after this is complete you will add, commit and then push to the remote main branch.</p>
            <p>You’re commit comments will be used to view completion so make sure to be clear on your comment.</p>

<h1>Module Four: Diff Tools & Viewing History</h1>
    <h2>Diff Tools</h2>
    <p>The git diff tool is used to compare staged files with the remote files to see the changes in a one screen view.</p>
        <p>Typing git config --global diff.tool "your text editor" will set your text editor to open with diff commands.</p>
        <p>git config --global difftool.vscode.cmd = sets the cmd file to open.</p>
        <p>git config --global difftool.vscode.cmd "code --wait" this command will stop git from processing your changes before you are finish editing.</p>
        <p>git config --global difftool.vscode.cmd "code --wait --diff this set git vs code for diff files.</p>
        <p>git config --global difftool.vscode.cmd "code --wait --diff $LOACL $REMOTE" = Placeholders for copies of new files.</p>
    <h2>Viewing History</h2>
        <p>Checking your branch commit history can be very helpful and is used some time to help project to move forward and not double check areas.</p>
        <p>"git log" will show a history of all the commits on that branch.</p>
        <p>"git log --online" will show a history of the repository’s online commits.</p>
        <p>"git show HEAD~1" this is one step back within the commit history.</p>
        <p>Git sometimes uses other terms for objects such as a blob meaning a file and a tree meaning folder also being able to undo your last changes can be carried out by typing "git clean -fd" and this will undo local changes, the f means file and the d means directory.</p>
    <h2>Module Four Assessment: Display your third commit log.</h2>
        <h3>Assessment Brief</h3>
            <p>You are required to create a file named Thirdcommit.md and place the log history from the third commit comment inside it. You are then asked to add it, commit it and then push it to the main branch, make sure you comment on this commit is clear on its purpose.</p>
        <h3>Assessment complete:</h3>
        <p>commit a382fc106f6e8207d41a2f3c4f71253bc2a517aa</p>
        <p>Author: Alexander Milligan <alexander0milligan@gmail.com></p>
        <p>Date:   Sun Apr 9 12:42:12 2023 +0100</p>
        <p>Finished Module Two</p>
        <p>diff --git a/ModuleTwo/ModuleTwo.md b/ModuleTwo/ModuleTwo.md</p>
        <p>index e6a37d3..27cab33 100644</p>
        <p>--- a/ModuleTwo/ModuleTwo.md</p>
        <p> +++ b/ModuleTwo/ModuleTwo.md</p>
        <p> @@ -10,5 +10,7 @@</p>
        <p>git add "directory path": this will stage a specific directory or file, you need to have a file within the folder as git will not allow an empty folder to be push with out a file, for tracking logs.<p>
        <p>git rm filename is used to remove files or changes that are in the staging area.</p>
        <p>git rm --chached filename will remove the file from the staging
        area only, this may need -r after rm for folders.</p>
        


        
            
            
<h1>Module Five: Push, Merge, Pull & Fetch</h1>
    <h2>Push</h2>
        <p>Description: The git push command is used to upload local repository content to a remote repository. The git push command can be seen as a syncing command and a fetch and pull can be seen as a download command.</p>
        <p>The default push command is "git push -u origin main"
        <p>git push -u origin "BranchName": This command will push any changes from the local repository to the remote repository branch.</p>
        <p>git push "remote url" "BranchName": This command will push any changes from the local repository to the remote repository branch.</p>
        <p>git push --all: This command will push any changes from the local repository to the remote repository branch as long as the command comes from the command line within the directory and branch.</p>
        <p>git branch -D branch_name: This will delete a branch on the remote.</p>
    <h2>Pull</h2>
        <p>Description: The git pull command is used to download content from your remote repository and will update your local repository. This command is two commands in one, a fetch and a merge.</p>
        <p>Commands:</p>
        <p>git pull</p>
        <p>git pull remote</p>
        <p>Fetch the specified remotes copy of the current branch and immediately merge it into the local copy</p>
        <p>git pull --no-commit remote </p>
        <p></p>
        <p>git pull --no-commit remote: This will integrate the remote branch with the local</p>    
        <p>git pull --rebase: This is a method of combining your local unpublished changes with the latest published changes</p>
        <p>git switch BranchName</p>
        <p>This will switch branches.</p>
    <h2>Fetch Request</h2>
        <p>Description: Git fetch will download the remote repository.</p>
        <p>Git fetch is a more safer way to get the remote files from a repository than git pull due to the fact that it does not change any of the files in the process.</p>
        <p>git pull = git fetch + git merge.</p> 
        <p>The default command is: "git fetch remote-url" </p> 
    <h2>Merge Request</h2>
        <p>Description: Git merge requests will join all development histories together from one branch to another or the main branch.</p>
        <p>The git merge command can give you the power to merge specific area of the development.</p>
        <p>The default comand: "git merge"</p>
   


<h1>Module Six:  History Error Assessment</h1>
    <h2>Assessment Brief</h2>
        <p>This assessment is based on a git main(default) branch and a master branch, where the master branch has a history of three commits more than the main branch and the main branch has a change that was not committed. You are asked to type out step base on how to render this error and match up the histories.</p>
    <h2>Catalyst :</h2> 
        <p>This problem accords mainly when an text editor is used to commit and then a command line is used to push or pull, the switch between the compiler/text editor to the command line seems to cause a history lag and then a committing error.</p>
    <h2>Rendering Steps</h2>
        <p>The first step to render this error is to check that your remote master is up to date, if not then try pushing your master branch.</p>
        <p>This failed and it was found that pulling the master and replacing it with the local branch would render the error and refresh the history, this would mean taking a copy of the last updated file and restoring the last master branch to the local.</p>
        <p>The last step was to push the updated master branch on the local to the remote master.</p>
        <p>Once this was completed and checked online (remote) merge the main with the master and all commit history errors where rendered</p>
    <h2>Command Path</h2>
        <p>git pull master url</p>
        <p>git merge</p>
        <p>git add *</p>
        <p>git commit - m "comment"</p>
        <p>git push -u origin master</p>
    <h2>Conclusion :</h2>
        <p>This happens due to a syncing error, the pull command on the master branch and merging the local after this syncs the repositories back to equal stats.</p>
 

<h1>Module Seven:  Pull, Edit, Push Assessment</h1>
    <h2>Assessment Brief</h2>
    <p>For this assessment you will need to create a new repository named ModuleSeven, you are then required to pull this repository(https://github.com/Alexander-Milligan/ModuleSevenFolder.git)in to your repository and edit the readme to say Hello Module Seven. Save the file and add, commit and push the folder and file to your repository.</p>
   <p>Assessment Completion Link: https://github.com/Alexander-Milligan/ModuleSeven.git</p>

<h1>Module Eight:  Open Source Edit Assessment</h1>
    <h2>Assessment Brief</h2>
    <p>For this assessment you are required to setup a local folder with a git repo in it named ModuleEightProject. 
    You are then asked to find a git project that you like and pull that project through the command line in
    to your folder and edit one of its file, you are then asked to push the new repository to github. 
   </p>
   <p>Assessment Completion Link: https://github.com/Alexander-Milligan/ModuleEightProject.git</p>

</div>
<div class="header">
    <div class="logo"><img src="IGG-Certificate.png"/></div>
</div>