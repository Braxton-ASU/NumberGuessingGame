# Structure
The overall structure of this repository is a main branch, dev branch, feature branches, and hotfix branch.

## Main
This repo likely follows the approach of keeping the main branch protected, so there is only the one initial commit on this branch so far.

# Dev
The dev branch seems to be where work is mainly incorporated until an appropriate time to release to the master branch

## Feature Branches
 * Feature1
 * Feature2
 * Feature3

 There are three separate feature branches currently for working on new functionality that will likely be brought into dev

## Hotfix
It appears there was one critical error in main that needed a fix


# learning Summary
 * In this assignment I learned that rebase is simialr to merge in joining some branches together, but it is different in that it moves one branch to have its base on the other. That is, the commits of one branch are applied as if they happened linearly on the one branch they were rebased to. I learned that multiple commits are able to be retroactively combined through squashing, and I learned that rather than a whole branch/set of commits being joined onto another branch, one can select an individual commit to apply.

 * In the history for the three features, feature1 is gone and doesn't clutter the history; feature2 merged from dev more after the changes from feature3 were incorporated, so now the history of feature2 shows feature3.

 * One might use rebasing when a clean linear structure is important to a commit log, and one might use merging when it is more important to trace back what branch spcific commits came from.
