## **Biology 824 Assignment Week 3- Version Control with Git and Github**

---
> Here are some FAQs about Github!


1. **When should you use Git for a project?**

Github is a **version control system**. This has a number of awesome benefits for your project!

+ Github can track every change you make to a file, so you can always go back to look at all your steps. Similarly, if you make a mistake and ruin your work, you can always go back to old versions!

+ Github allows you to merge files with collaborators. Multiple people may work on a project at once, with a record of every change made by every person!

Github is great for solo workers and big teams- both will benefit from the tracked changes, and the team will benefit from easy collaboration!

---

2. **What kind of files/info should be saved in a Git repository? What types of files/info should not be included in a Git repo?**

Github is great for:

+ Text files- such as a big document that needs multiple edits, perhaps from multiple people!

+ Code- again, that might need several rounds of editing and perfecting!

However, Github cannot store large files, such as a huge dataset. Also, don’t forget that if your Github is public, **do not store any private information** as it will be accessible by anyone.

---

3. **What are the commands to undo a commit?**

To go back to a previous version of a file, you can use `git checkout` 
This restores the previous version of the file.
You can simply type `git checkout HEAD~1 [yourfile]` to go back one step.
Alternatively, you can enter a specific version of a file (perhaps a few steps back) to revert back, for example: `git checkout [myoldversion]`

Alternatively, you can use `git revert [IDofyourincorrectcommit]`
However, this will make a new commit to undo your old one. It will not be the same as deleting your old commit.

---

4. **One of your repositories is in a “detached HEAD” state. How do you fix this?**

A **detached headspace** can happen if you hit the command `checkout` without specifying where to go. You must re-attach your head before making any more changes.
To do this you can simply type:
`git checkout master`


---

5. **Your boss has no idea what Git is or why you are using it. Explain the pros / cons of using Git for your research project. Explain the pros / cons of hosting your project in a public (or private) repository on Github/Bitbucket/Gitlab/etc.**

*Pros* 

+ Easy collaboration- the ability to merge files with ease, and track everyone’s changes

+ Back up of previous files- and easy restoration if mistakes are made!

+ Nice and accessible to anyone working on the project- simply share the link!

+ Long term storage- if a project is re-opened years later, it’s all there!

+ Github can be free if you use public mode

*Cons*

+ If your repository is public, anyone may access it and you may have issues if you are working on confidential work

+ You cannot store huge data files on Git, so this still needs to be done elsewhere


---

