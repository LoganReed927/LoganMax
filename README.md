# Logan & Max Project 2
The information below was how my partner and I stored our code from the last project and it worked pretty well!

Important!:
How to copy this repo to your ..../ct310 folder and work on it:

    1. cd to your ct310 folder and do the following commands:
        git pull origin master | This must be done FIRST before anything, always!
        git branch [name your branch] | This is a copy of the master, you'll be temporarily writing code here
        git checkout [name from above] | Checkout the branch
    2. You are now able to add updates to this branch
    3. When you're done editing, add your changes/then commit them to github:
        git add . | Adds the changes you made to the checked out branch
        git commit -m "This is where a message goes about what you added in this commit"
        git push origin [name of your branch] | Pushes your changes of this branch to github!

How to copy and overwrite fuel folder in your ~username/ folder:

This must be done FIRST when working on this code! (after updating master as mentioned above)

You'll see that there is a copy of the fuel folder in this repo. That is not the actual location of the fuel folder. This is so that the fuel folder gets copied into the repo. This also means that your fuel folder is not being updated in ~username/fuel.

To fix this:

    1. cd to ..../ct310
    2. cp -TR ./fuel ../../ This should update the fuel folder in your home dir.

