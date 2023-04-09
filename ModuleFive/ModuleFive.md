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
 

  

