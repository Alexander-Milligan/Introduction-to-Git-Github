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
    <p>3. Now type <samp style="color: #000">"git config --global user.name "yourname" " this is setting the workspace/folder with a git user name.</p>
    <p>4. Now type "git config --global user.email "youremail@gmail.com" " this is setting the workspace/folder with a git user email.</p>
    <p>5. Type "git init" and your folder's name: The git init command initializes a new git repository.</p> 
    <p>6. Type "git add" and your file's name: The git add command adds a change in the working directory and to the staging area.</p>
    <p>7. Type "git commit -m "your comment based on this task.":</p>
    <p>8. Type "git push -u origin master" This will push any commits from the local to the master Branch.</p>

<h2>Conclusion</h2>
    <p>Onnce all step have been carried out I had my first repository with a folder and a file within that folder. Through carrying out these step a number of times there where little code hits that are very handy to know if anything goes wrong, one of the most important lines that help me a lot was "git status(obviously), git remote -v" and remembering that if I don’t "git commit -m "Comment" then nothing will be pushed. This is an easy task but for someone that is not normalised to git it can take some time to visuilize the proccess.</p>
