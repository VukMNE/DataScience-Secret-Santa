# How to upload photos to this repository?

You have two options for uploading photos:

If you are willing to share, you can take the picture of the greeting card that you received, and you can upload it to Google Drive [here](https://drive.google.com/drive/folders/1im8frKGNGXJ_ngh-kfc6Lw01XRxRe6wV?usp=sharing).

If you prefer to do it via GitHub, here are the instructions:

Click the “Fork” button at the top right.

You’ll now have your own copy of that repository in your github account.

Now, on your computer, go to the folder where you want to clone this project, and start a terminal/shell/command prompt and type:
```
git clone git@github.com:YOUR_GITHUB_USERNAME/DataScience-Secret-Santa
```

You’ll now have a local copy of your version of that repository.

Now, through command prompt, go to the folder where you have this project:
```
cd DataScience-Secret-Santa
```
Add a connection to the original repository.

```
git remote add myfriend git://github.com/VukMNE/DataScience-Secret-Santa
```

Make changes to files.
git add and git commit those changes
git push them back to github. These will go to your version of the repository.

Note: if you get an error like:
```
error: src refspec master does not match any.
error: failed to push some refs to 'git@github.com:username/the_repo'
```

Then try git push origin HEAD:gh-pages (see [this stackoverflow question](https://stackoverflow.com/questions/4181861/message-src-refspec-master-does-not-match-any-when-pushing-commits-in-git)). Typing git show-ref can show what reference to put after HEAD.

If you did not encounter any errors, proceed with the following:

Go to your version of the repository on github.

Click the “Pull Request” button at the top.

Note that your friend’s repository will be on the left and your repository will be on the right.

Click the green button “Create pull request”. Give a succinct and informative title, in the comment field give a short explanation of the changes and click the green button “Create pull request” again.
