# Git Exercice

this project in the answer of the first part of the S1 excercices ( Git )

Remote repository
# Predict what master and origin/master refer to in R2, and check. What is in the file bold.txt in R2? Why?

Since the R2 is not merged with the new changes , the branch doesn't take the changes of "bold.txt"  from R1 . So "bold.txt" contain the old version in the R2 and not the one updated by R1 .
Remote repository on GitHub.

# Modify something in R1, commit. Try to send it to RG. Why is it refused? How can you effectively send your last modification online? Send it on your RG repository.

after modifying the file in R1 repository we cannot push it to the github, because it doesn't contain the latest updates of "bold.txt"  pushed before R3 ( and not merged). the solution is to pull the latest repository available from github, then merge the changes manually , and finally push the latest version to github

# Note about the Reamdme File : 
after seeing the files in the github ( the push succeeded ) , i added this README.md via the Add Read Me button , directly from the github Interface ,
