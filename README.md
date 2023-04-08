
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
        <p>With the option of creating single branches for indevidules to work on the main project and then discus gives any project that is carried out in git is insently given a error checking and development area before any merges to the master project.</p>
    <h2>Staging</h2>
        <p>The main command to stage a file is "git add filename" this will place the file and any changes in to the staging area.</p><p>Once the files are in the staging area you can then commit them for evey change you make with a coment but it is advised to try and keep your commits to every five change.</p>
        <h3>Extra Staging Commands</h3>
            <p>git add --all this will add all files within the directory to the staging area.</p>
            <p>git remote add takes two arrguments, your remote repos name and the url of the github repository that you are adding it to.</p>
            <p>git add "directory path": this will stage a specific directory or file, you need to have a file within the folder as git will not allow an empty folder to be push with out a file, for tracking logs.<p>
            <p>git rm filename is used to remove files or changes that are in the staging area.</p>
            <p>git rm --chached filename will remove the file from the staging area only, this may need -r after rm for folders.</p>
    <h2>The Four Stages within git</h2>
        <p>Creation, Modification, Refactoring, and Deletion</p>
            
            
<h1>Module Three: gitignore file & Status</h1>
    <h2>Gitignore file</h2>
        <p>To create the file type "echo gitignore > gitignore" with no extension.</p>
        <p>To ignore folders type "foldername"</p>
        <p>To ignore files type filename and extension.</p>
        <p>To ignore all file type *.txt or extension you want to ignore.</p>
        <p># = a comment within the ignore file.</p>
        <p> echo newtext >> filename.txt >> = appending.</p>
        <p>git mv filename = move command and can be used to rename files too = rm filename.txt newfilename.txt <p>
    <h2>Status</h2>
        <p>Status -s =  status short: this will give a short output within columns and has flags RED and green colour coding.</p>
        <p>Green M = Modified and staged</p>
        <p>Green A = add</p>
        <p>git diff --staged = this will show the changes within the files within the staged area.</p>
        <p></p>

<h1>Module Four: Diff Tools & Viewing History</h1>
    <h2>Diff Tools</h2>
        <p>git config --global diff.tool "your text editor"= this will set your text editor to open with diff commands.</p>
        <p>git config --global difftool.vscode.cmd = sets the cmd file to open.</p>
        <p>git config --global difftool.vscode.cmd "code --wait"</p>
        <p>git config --global difftool.vscode.cmd "code --wait --diff = this tell git we want to use it for diff files.</p>
        <p>git config --global difftool.vscode.cmd "code --wait --diff $LOACL $REMOTE" = Placeholders for copies of new files.</p>
    <h2>Viewing History</h2>
        <p>git log = will show a history of commits.</p>
        <p>git log --online = will show a history of the repository’s online commits.</p>
        <p>git show HEAD~1 = This is one step back within the comments.</p>
        <p>A blob = files</p>
        <p>A tree = folders</p>
        <p>git clean -fd = Undo local changes f = files d = directorys.</p> 
            
            
<h1>Module Five: Push, Merge, Pull & Fetch</h1>
    <h2>Push Request</h2>
        <p>Description: The git push command is used to upload local repository content to a remote repository.</p>
        <p></p>
        <p></p>
        <p></p>
        <p></p>
    <h2>Pull Request</h2>
        <p>Description: The git pull command is used to download content from your remote repository and will update your local repository. This command is two commands in one, a fetch and a merge.</p>
        <p>Commands:</p>
    <p><samp>git pull</samp></p>
    <p><samp>git pull remote  </samp></p>
        <p>Fetch the specified remotes copy of the current branch and immediately merge it into the local copy</p>
        
<p><samp>git pull --no-commit remote </samp></p>
        <p></p>

<p><samp>git pull --no-commit remote </samp></p>
        <p>integrate the remote branch with the local</p>
    
<p><samp>git push -u origin master</samp></p>
        <p>This will push your files to the master branch.</p>

<p><samp>git pull --rebase</samp></p>
        <p>This will integrate the remote branch with the local branch.</p>

<p><samp>git switch BranchName</samp></p>
        <p>This will switch branches.</p>

<h2>Fetch Request</h2>
        <p>Description: Git fetch will download the remote repository.</p>
        <p></p>  
<h2>Merge Request</h2>
        <p>Description: Git merge requests merges the branch with the main branch.</p>
        <p></p>


<h1>Module Six:  History Error Assessment</h1>
    <h2>Assessment Brief</h2>
        <p>This assessment is based of a git main(default) branch and a master branch, where the master branch has three comment history’s more than the main branch and the main branch has a change that was not committed.</p>
    <h2>Catalyst :</h2> 
        <p>This problem accords mainly when an editor is used to commit and the a command line is used to push or pull, the switch between the compiler/text editor to the command line seems to coz a history lag and then a commit error.  </p>
    <h2>Rendering and Steps</h2>
        <p>The first step to render this error is to check that your remote master is up to date, if not then try pushing your master branch.</p>
        
<p>If this fails it was found that pulling the master and replacing it with the local branch would render the error and refresh the history, this would mean taking a copy of the last updated file and restoring the last master branch to the local.</p>

<p>The last step was to push the updated master branch on the local to the remote master.</p>
<p>Once this was complete and checked online (remote) merge the main with the master and all commit history errors where rendered</p>
    <h2>Command Path</h2>
        <p>git pull</p>
        <p>git pull master</p>
        <p>git merge</p>
        <p>git add *</p>
        <p>git commit - m "comment"</p>
        <p>git push -u origin master</p>
    <h2>Conclusion:</h2>
    <p>This happens due to a syncing error, the pull command on the master branch and merging the local after this syncs the repositories back up.</p>


<h1>Module Seven:  Pull, Edit, Push Assessment</h1>
    <h2>Assessment Brief</h2>
    <p>For this assessment you are required to setup a remote repository and 
    upload a text file saying hello. You are then required to create a branch named assessment and pull that branch to your local and edit the file to say hello world, then push the file back up to the remote branch and merge the master with the assessment branch.</p>
    <p>Completed: https://github.com/Alexander-Milligan/Assessment-Seven.git</p>

<h1>Module Eight:  Open Source Edit Assessment</h1>
    <h2>Assessment Brief</h2>
    <p>For this assessment you are required to setup a local folder with a git repo in it. 
    You are the asked to find a git project that you like and pull that project through the command line in
    to your folder and edit one of its file. 
    You are then asked to create a repo on github and push the changed project to your repo. 
   </p>
   <p>Completed: https://github.com/Alexander-Milligan/ModuleEight.git</p>
   
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


