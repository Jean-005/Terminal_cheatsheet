ls - Lists the names of files and subdirectories in your current working directory
ls -l - Displays all the contents of a directory in long format
ls .a - Lists all contents in the curent working directory, icluding the hidden files and directories
ls -t Orders files and directories according to the time they were last modified 
-a - To show hidden files
cd - To navigate to the main home directory 
cd <directoryname> Takes named directory as argument and switches into that directory
tab - To complete a command
clear - To clear the terminal
cd .. - To move up one directory
pwd - Print Working Directory
mkdir <filename> - Creates a new directory in the current working directory
touch <filename> Creates a new file inside the current working directory
mv <filename> <destinationdirectory/> - Moves source file (first argument) into destination directory (second argument)
open . - Open the current working file
open <filename> _ Opens names file
mv <filename> .. Moves named file up one directory
cp <filename> <destinationdirectory/> Copies files or directories (first argument) into a destination folder (second argument)
cp * <destinationdirectory/> Selects all the files in the current working directory and copies them into a destination folder 
cp <filename> .. Copies named file up one directory
rm - Deletes files 
rm -r <foldername> Deletes specific diretory including all of its child directories
pb copy - Copies to clipboard
git init - Command creates an empty Git repository
git status / gst - Displays the state of the current working directory including showing you which changes have been staged/not staged plus which files are being tracked by Git
git add  - Adds a change to the currrent working directory. Informs git that you will be adding updates to a particular file in the next commit
git add --all - Adds all the changes in the whole directory and not just the current file 
git commit -m "message" - Enables you to take snapshots of a repository over time/ stages the changes made locally in a working directory on user's machine
git log - Lists all the commits in a repository's history
Q - To quit git log display and return to normal terminal
command S - To save files (VS Code)
command +/- - To zoom in/out the terminal
git restore - Restores the file to the last committed version (effectively undoes any changes that have been made since then). The file must be part of an earlier commit as 'restore' does not work for newly created files since the last commit
git revert - Undoes changes to a repository's commit history
:wq - Used to write (save) and quit 
git pull origin main - Fetches commits from the main branch of the origin remote into the local origin branch. It then it merges the origin main into the local branch 
git push origin main - Pushes the current local branch to the branch of the matching name in a remote repository
