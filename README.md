# Kagami-Taiga
 Salvatore project
 
Submitting Patches

Patches are always welcome! Please submit your patches via LineageOS Gerrit. You can do this by using these commands:

(From root android directory)
. build/envsetup.sh
(Go to repo you are patching, make your changes and commit)
cmgerrit <for(new)/changes(patch set)> <branch/change-id>

repo start master .
(Make your changes and commit)
repo upload .
Note: "." means the current directory For more help on using this tool, use this command: repo help upload

Make your changes and commit with a detailed message, starting with what you are working with (i.e. "vision: Update Kernel") Commit your patches in a single commit. Squash multiple commits using this command: git rebase -i HEAD~<# of commits>

To view the status of your and others' patches, visit LineageOS Code Review

Getting Started

To get started with Android/LineageOS, you'll need to get familiar with Git and Repo.

To initialize your local repository using the LineageOS trees, use a command like this:

repo init -u git://github.com/Kagami-Taiga/android.git -b master
Then to sync up:

repo sync
Please see the LineageOS Wiki for building instructions.

Buildbot

All supported devices are built weekly and periodically as changes are committed to ensure the source trees remain buildable.

You can view the current build statuses at Kagami-Taiga Jenkins

