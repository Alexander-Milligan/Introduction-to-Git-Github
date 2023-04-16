
<div class="header">
    <div class="logo"><img src="Logo.png"/></div>
</div>
<div class="container">
<h1>Course Summary</h1>
<p>This course will take the user through an introduction to git and github, the course covers the history, purpose, workflow and functions of using git and github. The course has been designed and created to give the user the knowledge and capability to create and interact with their repository on Github.</p>

<p>The course will teach and run the user through using git commands to push, pull, merge, fetch, add, commit and get the status of the stage the files/folders are in at that point. The course has been referenced from Traversy Media, programmingwithmosh and overlaid with a github learning lab beginner’s course.</p>


<h1>Module One: What Git is & Setting Git Up</h1>
<p>Git is a Version Control System (VCS) that allows computer files to be tracked when changed/developed, git operates on a tree system where the user can create branches of the main branch. This allows clients to work within a grouped project folder and contribute changes to that project on single branches that are separate to the main/master branch.</p>
<p>The staging area (git add) is where git’s power lies as all members of the project can discussed the branch that is to be merges with the main branch beforehand, which adds an extra level of error checking before any merge happens.</p>
<p>Git was created in 2005 by Linus Torvalds and Junio C Hamano, Linus Torvalds also created Linux and the Linux kernel, git does not have any specific coding language so is extremely coder friendly, hence why half the world’s companies are using it to create their projects.</p>


<h2>Installation Requirement</h2>
<p>In this module you will be required to setup a working environment that entails installation of git, git bash and a github account; along with a text editor of your choice.</p>

<h2>Module One Assessment: Course Folder Setup</h2>
<h3>Assessment Brief</h3>
<p>You are required to follow the steps below to create a repository on github, you can choose to make your repository public or not; this is your preference. Following the assessment steps below will set up your folder and repository that is required to complete this course. When you have finish the course you will send your repository url for verification and to receive your certificate of completion.
</p>

<samp><h1>Introduction to Git & Github: Your name here</h1>
<h2>Course Assessment Layout</h2>
<p>This repository is set up to store the assessment results for completing the IGG course.</p>
<samp>1. Module One: What Git is & Setting Git Up</samp> 
<p>By this readme being setup and here stats that the assessment was followed and complered.</p></samp>

<h2>Steps</h2>
    <p>Once all installation requirements have been met please follow these steps. </p>
    <p>1. Create a folder named “IGG-yourname” on your computer. </p>
    <p>2. Open the new folder, right click any white space in the folder and select “git bash here”. </p>
    <p>3. Create the README.md file by typing echo Introduction > READEME.md, copy the following texted in to the README file and save.</p>
    <p>“Introduction to Git & Github: Your name here
        This candidate repository has been set up to store the assessment materials for completing the IGG course.

        Candidate Name:  Your name here
        Course starting Date: The date you start this course

        Course Layout

        1.	Module One: What Git is & Setting Git Up
        2.	Module Two: Workflow & Staging
        3.	Module Three: Git Status & Gitignore file
        4.	Module Four: Diff Tools & Viewing History
        5.	Module Five: Push, Merge, Pull & Fetch
        6.	Module Six: History Error Assessment
        7.	Module Seven: Pull, Edit, Push Assessment
        8.	Module Eight: Repository Security

        By this readme being setup and here stats that the Module One Assessment was followed and completed”
</p>
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



<h1>Module Two: Workflow & Staging</h1>
    <h2>Non-linear Workflow</h2>
        <p>A git workflow is a suggestion/recipe for how a team will use Git to achieve working on a project in a consistent way with more functionality and productivity. </p>
        <p>With the option of creating single branches for individuals to work on the main project and then discuss gives any project that is carried out in git is instantly given an error checking and development stage before any merges to the master project.</p>
    <h2>Staging</h2>
        <p>The staging area is the where files are placed ready to be committed and allows the developer to keep editing the files staged; this allows freedom of development on two layers, the developers work area and the branch (group discussion development) before the main merge.  </p>
        <p>The main command to stage a file is "git add filename" this will place the file and any changes in to the staging area. Once the files are in the staging area you can then commit them for every change you make with a comment but it is advised to try and keep your commits to every five changes.</p>
    <h2>Module Two Assessment: Committed. Modified & Staged</h2>
        <h3>Module Brief:</h3>
        <p>You are required to create a folder named “ModuleTwo” inside your IGG folder with a file named “README.md”. You are then asked to write an essay based on the three states of git within your README.md file in your new ModuleTwo folder.</p>
        <p>Once you are finished your essay please push it to your IGG repository, remember to add, commit and have a good comment on the commit.</p>
        

            
            
<h1>Module Three: Git Status & Gitignore file</h1>
    <h2>Status</h2>
        <p>The git status command is one of the most used commands as it allows you to view the stage of the files you are working on, such as Mfile.txt are modified or Dfile.txt means file has been deleted.</p>
        <p>Green M 	= Modified and staged</p>
        <p>Red D 	= files that have been deleted</p>
        <p>Green A 	= files that have just been added</p>
        <p>Orange 	= text in this colour means that the branch is behind or in front of the remote</p>
        <p>Cyan 	= text in this colour means the branch matches its remote</p>
    <h2>Gitignore File</h2>
        <p>The gitignore file is used to tell git what to ignore, from folders to individual files and certain file types. This helps with security throughout the project due to the capability of hiding sensitive data files or things like api keys and more.</p>
        <p>Do not carry out these steps; they are hits for the up and coming assessment</p>
        <p>1. To create the gitignore file type "echo gitignore > gitignore" with no extension.</p>
        <p>2. To ignore folders type "foldername" within the gitignore file.</p>
        <p>3. To ignore files type filename and extension.</p>
        <p>4. To ignore all file types you can type "*.txt" or the file extension you want to ignore.</p>
        <p>5. If you place a # before any text in the ignore file it will be seen as a comment within the ignore file. </p>
        <p>6. In the command line you can type "echo newtext >> filename.txt" and it will append the file, this is due to the >> symbol which means appending.</p>
        <p>7. The "git mv filename" command is used to move files and can be used to rename files "rm filename.txt newfilename.txt".<p>
    <h2>Module Three Assessment: Create a Gitignore File</h2>
        <h3>Assessment Brief</h3>
            <p>In this assessment you are required to create a folder within your IGG folder named ModuleThree. In this folder you are asked to create a file named README.md and a file named testignore.txt through the git bash command line. You are then asked to create a gitignore file through the command line and then type the line you need to ignore the testignore.txt in the gitignore file; after this is complete you will add, commit and then push the changes to the remote repository.</p>
            <p>You are required to give a short discription within the ModuleThree folders REDME file of how you completed this assessment.</p>

<h1>Module Four: Diff Tools & Viewing History</h1>
    <h2>Diff Tools</h2>
    <p>The git diff tool is used to compare staged files with the remote files, to see the changes in a one screen view. The git diff takes two sets of input data (fileone.txt fileone.txt) this will give an output of the file in the two different stages. You can see the git diff tool/function as a comparer command, below are some very helpful command hits. </p>
        <p>1. Typing git config --global diff.tool "your text editor" will set your text editor to open with diff commands.</p>
        <p>2. git config --global difftool.vscode.cmd = sets the cmd file to open.</p>
        <p>3. git config --global difftool.vscode.cmd "code --wait" this command will stop git from processing your changes before you are finish editing.</p>
        <p>4. git config --global difftool.vscode.cmd "code --wait --diff this set git vs code for diff files.</p>
        <p>5. git config --global difftool.vscode.cmd "code --wait --diff $LOACL $REMOTE" = Placeholders for copies of new files.</p>
    <h2>Viewing History</h2>
        <p>Checking your branch commit history can be very helpful and is used some time to help project to keep moving forward and not double check areas. The git log command is the main default command to view your commit history.</p>
        <p>1.	Typing git log" will show a history of all the commits on that branch</p>
        <p>2.	Typing git log --online" will show a history of the repository’s online commits</p>
        <p>3.	Typing git show HEAD~1" this is one step back within the commit history</p>
        <p>Git sometimes uses its own terms for objects; an example is a blob meaning a file and a tree meaning a folder. Once you have use git and github for a while you will get normalized to these terms. 
Being able to undo your last changes is always helpful and can be carried out by typing "git clean -fd", this will undo local changes where the f means file and the d means directory.
</p>
    <h2>Module Four Assessment: Display the Third Commit Log</h2>
        <h3>Assessment Brief</h3>
            <p>You are required to create a folder named ModuleFour within your IGG folder, you are then asked to create a file named README.md inside your IGG folder. You will then place the log history from the third commit comment inside your README file. You are then asked to add it, commit it and then push it to the main branch, make sure you comment on this commit is clear on its purpose.</p>
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
        <p>1. The default push command is "git push -u origin main"
        <p>2. git push -u origin "BranchName": This command will push any changes from the local repository to the remote repository branch.</p>
        <p>3. git push "remote url" "BranchName": This command will push any changes from the local repository to the remote repository branch.</p>
        <p>4. git push --all: This command will push any changes from the local repository to the remote repository branch as long as the command comes from the command line within the directory and branch.</p>
        <p>5. git branch -D branch_name: This will delete a branch on the remote.</p>
    <h2>Pull</h2>
        <p>Description: The git pull command is used to download content from your remote repository and will update your local repository. This command is two commands in one, a fetch and a merge.</p>
        <p>1. git pull</p>
        <p>2. git pull remote: Fetch the specified remotes copy of the current branch and immediately merge it into the local copy</p>
        <p>3. git pull --no-commit remote </p>
        <p>4. git pull --no-commit remote: This will integrate the remote branch with the local</p>    
        <p>5. git pull --rebase: This is a method of combining your local unpublished changes with the latest published changes</p>
    <h2>Fetch Request</h2>
        <p>Description: Git fetch will download the remote repository. Git fetch is a safer way to get the remote files from a repository than git pull due to the fact that it does not change any of the files in the process.</p>
        <p>Git fetch is a more safer way to get the remote files from a repository than git pull due to the fact that it does not change any of the files in the process.</p>
        <p>1. git pull = git fetch + git merge.</p> 
        <p>2. The default command is: "git fetch remote-url" </p> 
    <h2>Merge Request</h2>
        <p>Description: Git merge requests will join all development histories together from one branch to another or the main branch.</p>
        <p>3. The git merge command can give you the power to merge specific area of the development.</p>
        <p>4. The default comand is: "git merge"</p>
    <h2>Module Five Assessment: Push, Merge, Pull & Fetch Commits</h2>
        <p>You are required to create a folder named ModuleFive within your IGG folder, you are then asked to create a file named README.md. Within this file you are to carry out each task push, fetch, edit, push, pull, edit and push. </p>
        <p><b>Please follow the steps below to complete the assessment.</b></p>
        <p>1.	Create a folder by typing “mkdir ModuleFive”</p>
        <p>2.	Create a file by typing “echo Assessment five > README.md”</p>
        <p>3.	Type “git add *”, “git commit –m “CLEAR COMMENT HERE”, “git push –u origin master” ”</p>
        <p>4.	Type “git fetch URL-OF-REMOTE”</p>
        <p>5.	Once you have the readme file back; open it in your text editor and place this texted in it “This edit is to show that a push and fetch request has been successfully completed.”</p>
        <p>6.	Type “git add *”, “git commit –m “CLEAR COMMENT HERE”, “git push –u origin master” ”</p>
        <p>7.	Type “git pull URL-OF-REMOTE”</p>
        <p>8.	Open the readme file in your text editor again and place this texted inside “This is an edit to show that a pull request has been completed successfully.”</p>
        <p>9.	Type “git add *”, “git commit –m “CLEAR COMMENT ON LAST STAGE HERE”, “git push –u origin master” ”</p>
      
   


<h1>Module Six:  History Error Assessment</h1>
    <h2>Catalyst: </h2> 
        <p>This problem accords mainly when an text editor is used to commit and the a command line is used to push or pull, the switch between the compiler/text editor to the command line seems to cause a history lag and then a committing error.</p>
    <h2>Rendering Steps</h2>
        <p>1. The first step to render this error is to check that your remote master is up to date, if not then try pushing your master branch.</p>
        <p>2. This failed and it was found that pulling the master and replacing it with the local branch would render the error and refresh the history, this would mean taking a copy of the last updated file and restoring the last master branch to the local.</p>
        <p>3.The last step was to push the updated master branch on the local to the remote master. Once this was completed and checked online (remote) merge the main with the master and all commit history errors where rendered</p>
    <h2>Assessment Brief</h2>
        <p>You are required to create a folder named "ModuleSix" and create a readme file within it. This assessment is based on a git main (default) branch and a master branch, where the master branch has a history of three commits more than the main branch and the main branch has a change that was not committed.</p>
        <p> You are asked to type out the commands used to render this error in your README.md file. Without setting the scenario up; follow the rendering log that has been given below with a command example that hints at how many steps there are.</p>
        <p>Your README file will be viewed and assessed for your mark.</p>
<h2>Example of readme notes that are required</h2>
    
<h2>Task Command Path</h2>
        <p>1. git command</p>
        <p>2. git command</p>
        <p>3. git command</p>
        <p>4. git command</p>
        <p>5. git command</p>

 

<h1>Module Seven: Pull, Edit, Push Assessment</h1>
    <h2>Assessment Brief</h2>
    <p>For this assessment you will need to create a new repository named ModuleSevenPull, you are then required to pull this repository (https://github.com/Alexander-Milligan/ModuleSevenPull.git)in to your new repository and edit the ModuleSevenREADME.md file to say “Hello Module Seven after being pulled and edited”. Save the file in a new ModuleSeven folder in your IGG folder and add, commit and push the folder and file to your repository.</p>
    <p></p>

<h1>Module Eight:  Repository Security</h1>
    <h2>Assessment Brief</h2>
    <p>There are a number of security features that github has for repository’s, in this module you will learn about the first two features, secret scanning and code scanning. There are five main option/features in github for repository security and it is very helpful to know of them all.</p>
    <h2>Secret Scanning</h2>
        <p></p>
    <h2>Code Scanning</h2>
        <p></p>
    <h2>Assessment Eight: Repository Security</h2>
        <h3>Assessment Brief</h3>
        <p>In this assessment you are required to write an essay based on the Security Advisories, Dependabot Alerts and the Security Policy features functions. You are then asked to create a folder named “ModuleEight” inside your IGG folder and place your essay in your ModuleEight folder. Once you have completed these steps, please add, commit and push your new folder to your IGG repository.</p>
        
<h1>Course Conclusion </h2>
    <p>Once you have finish Module Eight you have finish the course and are asked to follow the course completion steps below. Thank you very much for following this course.</p>
    <b><p>Congratulation & Well Done</p></b>
<h1>Course Completion Steps</h2>
    <p>Once all modules have been completed please send your github repository url to SaltireCourses@gmail.com, where your course will be evaluated and marked. You one be contacted within two weeks of sending your course link and you will get your certificate of completion as well.</p>

</div>
