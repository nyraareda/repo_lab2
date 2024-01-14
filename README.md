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

