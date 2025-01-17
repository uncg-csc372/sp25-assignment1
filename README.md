# sp25-assigment1
First Homework Assignment.

## Practice with GitHub 
For this part of the assignment, you will get practice using GitHub in order to collaborate/contribute with other students in the class. We will be using this repository to do that. First, we want to compile a list of hobbies for all of the students in the course. Then, we will dynamically order the compiled list of hobbies from least to most popular.

## You need to obtain a copy of this repository to your local computer so you can add your changes, then publish them back to the origin.
There are two common ways to do so. 

- A: Clone the repository, create a new branch, make changes there, push the new branch back to the origin if you are an authorized collaborator, create a pull request and have your changes merged.

- B: Fork the repository to create your own repository off of origin. Clone your own copy, make changes, push them to your fork, then create a pull request to the original repository to have your changes merged. 
We will use option B. 

## Step One: Fork the repository
On GitHub, click on the button for forking this repository to create your own copy to your GitHub profile. Keep the name the same.

## Step Two: Clone the repository to your local directory
- Do not go into any previously created repositories!
- Start up VSCode IDE, close any folders that you may have open by clicking File->Close Folder.
- Click on the Source Control tab, then clone a repository.
- Clone your own fork of this repository and open it in Visual Studio Code, in your OneDrive location, navigate to your workspace for CSC372 projects.

## Step Three - Make Edits
- Open the file student_hobbies.txt. Add a hobby to the list of hobbies and include your UNCG ID (the thing before @ on your uncg email address)  in parentheses. 
- You should also find a hobby that you share with someone else (i.e. a hobby someone else added that you also enjoy). For the hobby you share, you should add your UNCG ID in parentheses, separated by a comma.
- Based on the number of people who share the hobby, move the line to the appropriate part of the file where the hobbies shared by the most people are at the bottom of the file and the hobbies shared by the fewest number of people are at the top of the file.

For example, the student_hobbies.txt file may look like this when you first download it:

```
photography (1.xchen2)
hiking (1.sentini)
rock climbing (1.ctomsko)
```

Consider a student whose ID is c_stuckey who enjoys languages and also enjoys hiking. After the student has completed this part of the assignment, the file would look as follows:

```
photography (1.xchen2)
rock climbing (1.ctomsko)
languages (1.c_stuckey)
hiking (1.sentini, 2.c_stuckey)
```

## When you are done, add, commit and push your changes to your own fork of the repository.
Use Menu shortcuts, or use the terminal within Visual Studio Code to type in commands.

## Finally, submit a pull request to the shared repository
In your own fork, click on Contribute -> Open Pull Request. Before you open the pull request, make sure your fork is up to date with this original repository. 
If it says you are behind, you will need to merge the original main to your fork main. It's usually a few button clicks but you may need to edit student_hobbies.txt file again to remove the extra text inserted by the merge conflict. In the title of the pull request, include your first and last name as it shows up on the class roster. Create the pull request.
