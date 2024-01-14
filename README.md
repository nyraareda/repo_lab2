#lab_Day2


#Removing branches


#Remove branch 'dev' locally

git branch -d dev

#if the branch contain unmerged changes use this command

git branch -D dev


#Remove branch remotly

git push origin --delete dev

-----------------------------------------------------------

#Remove branch 'test' locally

git branch -d test

#if the branch contain unmerged changes use this command

git branch -D test


#Remove branch remotly

git push origin --delete test

---------------------------------------------------------------

#Listing Tags

#To list all tags 

#use this command
git tag

#to display additional information such as the commit associated with each tag, you can use this command

git tag -n

----------------------------------------------------------------------------

# Deleting Tags

#Delete a Tag Locally

git tag -d v1.7

#Delete a tag remotely

git push origin --delete v1.7


--------------------------------------------------------------------------------


#Putting an image


![git image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR7zIsOlQ0tppVMpDyorl2nf6Eqq3wXYx1Liw&usqp=CAU)

-----------------------------------------------------------------------------------------

#secret file

#there are another ways to make file ignore 

#if the file already checked in , you should at first make it un tracked 

git rm --cashed file.txt

#if you want git to make all files and directories when you make a commit in any Git repository
add it to the file named ignore and this located inside git in these directories ~/.config/git/ignore


#if you don't want to create file .gitignore , you can open your text editor and open file called 

.git/info/exclude

#and any rules you will add in it will not be checked in
