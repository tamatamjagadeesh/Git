This is Readme File
All Clear
Git Command:
git init -b main
git add filename
git commit -m "Sentence"
git log
//Every time you make changes to the file you need to add it to the staging then commit
we can skip the staging to commit using the following command
git commit -a -m "Sentence"
git diff // to Find the what changes are made
git diff --staged // this is to find the changes at staging
//To add all the files to stage we need following command
git add .
// If we need to Delete any important file or we can consider as hide the files before uploading into public repository we need to delete the file in git
git rm --cached delete.txt

//To Create and SSH Key we need to use the following command
ssh-keygen -o
