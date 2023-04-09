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
