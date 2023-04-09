
<div class="header">
    <div class="logo"><img src="Logo.png"/></div>
</div>
<div class="Container">
<h1>Module One: What Git is & Setting Git Up</h1>
<p>Git is a Version Control System (VCS) that allows computer file to be tracked for changes, this allows clients to work within a grouped project folder and contribute changes to that project on single branches that are separate to the main/master branch.</p>
<p>Git was created in 2005 by Linus Torvalds, who also created Linux and the Linux kernel, git does not have any specific coding language so very coder friendly.</p>

<h2>Installation Requirement</h2>
<p>In this module you will be required to setup a working environment that entails installation of git and git bash, a github account and logged in to that account along with a text editor of your choice.</p>

<h2>Module Brief</h2>
<p>You are required to create a repository and push a folder and a file to this repository with changes made to that file. This will include at least two commits and a readme file that explains your steps. </p>

<h2>Steps</h2>
    <p>Once all components are installed please follow these step.</p>
    <p>1. Create a folder by typing mkdir in to git bash and then cd in to that folder.</p>
    <p>2. Create a file by typing echo hello > filename.txt.</p>
    <p>3. Now type <samp style="color: #cc0">"git config --global user.name "yourname" "</samp> this is setting the workspace/folder with a git user name.</p>
    <p>4. Now type "git config --global user.email "youremail@gmail.com" " this is setting the workspace/folder with a git user email.</p>
    <p>5. Type "git init" and your folder's name: The git init command initializes a new git repository.</p> 
    <p>6. Type "git add" and your file's name: The git add command adds a change in the working directory and to the staging area.</p>
    <p>7. Type "git commit -m "your comment based on this task.":</p>
    <p>8. Type "git push -u origin master" This will push any commits from the local to the master Branch.</p>

<h2>Conclusion</h2>
    <p>Onnce all step have been carried out I had my first repository with a folder and a file within that folder. Through carrying out these step a number of times there where little code hits that are very handy to know if anything goes wrong, one of the most important lines that help me a lot was "git status(obviously), git remote -v" and remembering that if I don’t "git commit -m "Comment" then nothing will be pushed. This is an easy task but for someone that is not normalised to git it can take some time to visuilize the proccess.</p>

<h1>Module Two: Workflow & Staging</h1>
    <h2>Workflow</h2>
        <p>A Git workflow is a suggestion/recipe for how a team will use Git to achieve working on a project in a consistent way with a with more functionality and productivity.</p>
        <p>With the option of creating single branches for individuals to work on the main project and then discus gives any project that is carried out in git is instantly given an error checking and development area before any merges to the master project.</p>
    <h2>Staging</h2>
        <p>The main command to stage a file is "git add filename" this will place the file and any changes in to the staging area.</p><p>Once the files are in the staging area you can then commit them for every change you make with a comment but it is advised to try and keep your commits to every five change.</p>
        <h3>Extra Staging Commands</h3>
            <p>git add --all this will add all files within the directory to the staging area.</p>
            <p>git remote add takes two arguments, your remote repos name and the url of the github repository that you are adding it to.</p>
            <p>git add "directory path": this will stage a specific directory or file, you need to have a file within the folder as git will not allow an empty folder to be push without a file, for tracking logs.<p>
            <p>git rm filename is used to remove files or changes that are in the staging area.</p>
            <p>git rm --chached filename will remove the file from the staging area only, this may need -r after rm for folders.</p>
        <h3>The Four Stages of git(Creation, Modification, Refactoring & Deletion)</h3>
            <p>The creation stage is the first and can be seen as the untracked work directory.
            <p>The modification stage is next and can be seen as the tracked work directory.</p>
            <p>The refactoring is the staging area within git and can be seen as the discussion stage.<p>The deletion stage is after all project files and git branches are up-to-date and merged you can then delete the sub branch with no data loss.</p>

            
            
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
        <h2>The Four Stages within git</h2>
            <p>Creation, Modification, Refactoring, and Deletion</p>+ 
        <h2>The Four Stages of git</h2>
            <p>The creation stage is the first and can be seen as the untracked work directory.</p>


        
            
            
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
        <p>This problem accords mainly when an text editor is used to commit and the a command line is used to push or pull, the switch between the compiler/text editor to the command line seems to cause a history lag and then a committing error.</p>
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
   <p> Assessment Completion Link:</p>

<h1>Module Eight:  Open Source Edit Assessment</h1>
    <h2>Assessment Brief</h2>
    <p>For this assessment you are required to setup a local folder with a git repo in it. 
    You are the asked to find a git project that you like and pull that project through the command line in
    to your folder and edit one of its file. 
    You are then asked to create a repo on github and push the changed project to your repo. 
   </p>
   <p> Assessment Completion Link:</p>
 

   
   <h2>Commands: Helper</h2>
        <p>1. git config --global core.editor "code --wait" = </p>
        <p>git config --global -e = this will open gitconfig.</p>
        <p>End of length = </p>
        <p>System = all users</p>
        <p>Global = all repositories of the user</p>
        <p>Local =  The current repository’s</p>
        <p>git reflog = short logs</p>
        <p>create a new repository on the command line
            echo "# Repo" >> README.md
            git init
            git add README.md
            git commit -m "first commit"
            git branch -M main
            git remote add origin https://github.com/Alexander-Milligan/Repo.git
            git push -u origin main
        </p>
        <p>…or push an existing repository from the command line
            git remote add origin https://github.com/Alexander-Milligan/Repo.git
            git branch -M main
            git push -u origin main</p>

</div>


