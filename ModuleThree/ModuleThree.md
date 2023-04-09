<h1>Module Three:  Git Status & Gitignore file</h1>
    <h2>Status</h2>
        <p>The git status command is one of the most used commands as it allows you to view the stage you are at and the file stage, such as Mfile.txt is modified or Dfile.txt means file has been deleted. There are a number of flags for the command that are very helpful, like status -s = status short: this will give a short output within columns and has flags RED and green colour coding such as the M AND D mentioned before.</p>
        <p>Green M = Modified and staged</p>
        <p>Green A = files that have just been added.</p>
        <p>Red D = files that have been deleted.</p>
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
