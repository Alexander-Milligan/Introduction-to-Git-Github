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
            <p>The creation stage is the first and can be seen as the untracked work directory.

