# Список команд к работе с файлами

1) *pwd* - print working directory  
2) *cd* - change directory  
3) *ls* - list directory contents  
4) *touch* - create a file  
5) *mkdir* - create a directory  
6) *cp* - copy [what] [where] 
7) *mv* - move [what] [where]  
8) *cat* - copy contents of a file  
9) *rm* - remove a file  
10) *rmdir* - remove a directory  
11) *rm -r* - remove a directory with everythin inside
12) *&&* - for several commands
13) *~* - home directory


# Список команд Git
 *git version* - версия Git
 *git config* --global user.name "SomeName"
 *git config* --global user.email "SomeEmail@gmail.com"
 *cat ~/.gitconfig* or *git config --list* - read current name and email
 *git init* - create a Git repository
 *rm -rf .git* - undo making a repository
 *git add filename.txt* - add a file to the staging area
 *git add --all*
 *git commit -m "comment"* - commit a file with a comment
 *git log* - get a list of previous commits
 *cd ~* + *ls -la .ssh/* - checking if SSH-key has already been generated. If the folder is empty, there is no SSH key
 *ssh-keygen -t ed25519 -C "e-mail"* - generate a new SSH key. After the SSH key is generated you can see it with the command *ls -a ~/.ssh*. There will be 2 files. One of them is .pub, it's a public key. The second file is a private key. Don't share it with anyone.
 *ssh-keygen -t rsa -b 4096 -C "e-mail"* - generate a new SSH key as well
 *git remote add origin git@github.com:timurtagirov/first-project.git* - make a remote repository
 *git remote -v* - see info on remote repository
 *git push -u origin main* - push commits to remote repository for the first time
 *git push* - push commits to remote repository
 *git clone* - clone a remote repository on local computer
