# IS-114-Projects

Course IS-114 at UiA - IT & Informationsystems

Microsoft Windows 11, v. 23h2

Username GitHub: HenellTT

Git application version: git version 2.46.0.windows.1

Figuring out how to work around VS Code and GitHub.
Right now using GitHub Desktop application to see and save my respo locally on my pcs - that way I can use VS Code and use an extension called Live Server - whereas I can see my changes live on a remote window/local website each time I save.
I tried to use Codespace extension, where it launches a Remote Window and whenever a change is committed within a branch, it goes straight to the GitHub.com respo. But I was not able to use Live Server-extension whilst having Codespace open, so I had to find another solution.

Trying to figure out how to commit changes to a branch. - Just figuring things out:
Do I just need to save things on VS Code, then just Commit it on GitHub Desktop Application?
Answer - Yes.

Currently trying to use Git Bash to commit changes to README.md, however I still need to figure out how to do it.
Such confusion
I have now succeeded to commit and push changes through Git Bash - I tried to commit and push through Git as soon as I cloned my respo to git terminal, however it didn't seem to work, always got a text:
"On branch working, Your branch is up to date with 'origin/working', nothing to commit, working tree clean"
I had no clue how to fix this issue, I tried git status, which just sent the same message, I tried looking high and low through reddit and github articles, if there were any solutions, however did not find any. I concluded to contact our assistent teacher, Tobias, who recommended to change the README.md text on notepad w/ 'notepad README.md', then do 'git add \*', 'git commit -m "[Message]"' and then 'git push'
This worked and he explained that git needs register a changed in the clone respo, or else it wont push it - which then explains 'Your branch is up to date with 'origin/working'' - There wasn't any change in the respo to commit.
Now it works as it should

Test

Testing notepad README.md

Testing VS Code README.md
