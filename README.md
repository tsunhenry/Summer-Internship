# Summer-Internship

To upload your code: (apologies in advance if you already know how to do this, I was under the impression you might not have too much experience using GitHub? Just ignore this if you already know how to do it.)

Step 1: Navigate to a new folder where you want to store the code for github

Step 2: Run "git clone git@github.com:tsunhenry/Summer-Internship.git", might need SSH for it. There are plenty tutorials on how to set this up.

Step 3: Copy and paste your code to the repository (this new folder)

Step 4: Make sure that the code is in the same level as this folder. I assume you have one short script/ one file for now?

Step 5: Run "git add ."

Step 6: Run "git commit -m 'Udeepa's first commit'"

Step 7: Run "git push" or any similar commands that Git suggests.

Your code is now stored on Github on the "master branch". I will be able to pull your updates by running "git pull".

In the future, if you want to work on the code, but not contaminate what's already on this "Master branch", you can create a side branch:

Step 1: Navigate to the root of this project/ where this Readme is stored.

Step 2: Run "git checkout -b <branch_name>" (omit <> when you have your own name eg "git checkout -b Udeepa_test_branch")

Step 3: You can also save this side branch on github, just run step 5-6

Step 4: Run "git push -u origin <branch_name>"

Lastly, if you feel that your test code on this side branch is ready for deployment/ ready to merge with the master:

Step 1: Run "git checkout master" to go back to Master

Step 2: Run "git merge <branch_name>" to merge <branch_name> to master.

Step 3: Run "git commit -m 'merge <branch_name> to master'"

Step 4: Run "git push"

Note: Repository is currently Public. I named it summer internship so other people won't be able to find this on google. I'd highly recommend we move on to a private repository!
