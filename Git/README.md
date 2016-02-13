# Git-How to
## Intro
### Git client
There are many git clients out there. When starting with git use [SourceTree.](https://www.sourcetreeapp.com/) SourceTree is the best git tool when starting out. It shows you everything in an easy to understand way, while being a true git client.

There are 2 other git clients that I would not recommend:
 - The git tool for eclipse. I have yet to meet someone where it did not screw up their entire project.
 - The GitHub client. This one is better than the eclipse one however it does not learn you how to work with git very well. When it will go wrong, you have no idea what it did and how to fix it.

On linux? Use [GitKraken](http://www.gitkraken.com/). [It is still in beta though.](http://aztechbeat.com/2015/10/axosofts-gitkraken-undo-button-git-private-beta/) If you are a command-line lover you can also use that.

![don't become this guy](http://www.explainxkcd.com/wiki/images/4/4d/git.png)  
↑ don't become this guy.

### IDE

[IntelliJ](https://www.jetbrains.com/idea/ )  
If you haven't done so already. I would highly recommend you check out IntelliJ. This IDE works a lot better with cloning and importing your git project.

### How does this guide work?
Many people have described git in many ways. This is a collection of articles. Hopefully put into an order where you get the most of every tutorial. For every link I recommend until how long you should read. However if you like it, you are welcome to keep reading.

[CodeCademy course](https://www.codecademy.com/learn/learn-git)  
Besides this guide, there is also a Codecademy course about git
What is git and how does it use version control

### GitHub account

[A giant GitHub guide](http://blog.pluralsight.com/github-tutorial)  
You have to create a github account for this course. You can read this giant guide and you will be up to date with everything.

[GitHub help page](https://help.github.com/)  
If you have problems with GitHub, you can search this help page for a solution.

### Other
[GitHub education pack](https://education.github.com/pack)  
Free stuff. Awesome, right!

## Rule #1: Git is hard
Don’t worry if you don’t understand it all in one go. It gets better with time.


## What is git and how does it use version control
[Git Magic: Chapter 1](http://www-cs-students.stanford.edu/~blynn/gitmagic/ch01.html)  
Why version control?

[Git Book: Chapter 1.3](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)   
What are the ideas behind git?


## How do I use git?
[Learn git branching: First 4 levels](http://pcottle.github.io/learnGitBranching/)  
Try a few git commands. Don’t worry if you don’t remember the exact commands. SourceTree will have buttons for it and handle the exact code in the background.

[Atlassian: Branching](https://www.atlassian.com/git/tutorials/using-branches)   
What were those branches?

[Git Book: Merge Conflicts](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging#Basic-Merge-Conflicts)  
When combining stuff, it might not always go to plan.

[Atlassian: Reset](https://www.atlassian.com/git/tutorials/undoing-changes/git-reset)  
These changes are not going to work out. It isn’t me, it’s you.

[GitReady: Stashing](http://gitready.com/beginner/2009/01/10/stashing-your-changes.html)  
Stashing. How to put your code to the side for a while.

[The git book: Ignoring Files ](https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository#Ignoring-Files)   
.gitignore is really useful. No longer accidentally commit files you shouldn't add. Many eclipse files need to be excluded, just like all the compiled files in your bin folder. (Nobody will want to see these changes).  P.S. GitHub can also create a standard gitignore for you.

![standard git committing](https://raw.githubusercontent.com/newnottakenname/Guides/master/Git/Git-HowTo.png)


[Git fundamentals](https://www.youtube.com/watch?v=sevc6668cQ0)  
So now you know what git is and how it can be used. Now it is time to go deeper and learn how git works on a lower level. The talk is 46 minutes long, but really helpful. For instance, you will learn why it is not good practice to push large files to git.

https://try.github.io/levels/1/challenges/1  
If you still feel like you don't know everything, you can also try this tutorial from GitHub.

## Workflow (Optional, but makes your life easier)
Ok, I now know how people work with git. How should I be applying it?  
https://www.atlassian.com/git/tutorials/comparing-workflows/centralized-workflow  
https://www.atlassian.com/git/tutorials/making-a-pull-request  

They were talking about something called a pull request. Pull whatta?  
https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow (Until “Where To Go From Here”)  

Gitflow will make your life a lot easier. No-one wants to merge your work of the entire week and has time to review it all.  
https://guides.github.com/introduction/flow/  
Use gitflow in GitHub
## Wanna see something cool? (Extra)

## References for git
http://stackoverflow.com/questions/315911/git-for-beginners-the-definitive-practical-guide/5968622#5968622  
Didn’t understand something? StackOverflow has the answer.

https://git-scm.com/docs  
The official documentation of all the git commands.

http://rogerdudler.github.io/git-guide/files/git_cheat_sheet.pdf  
A cheat sheet for the most used git commands.

http://nvie.com/img/git-model@2x.png   
The original image of the git-flow model

# Scrum
http://plan.io/blog/post/132075702083/scrum-a-collection-of-some-of-the-best-resources  
What is scrum

https://www.reddit.com/r/scrum/comments/3o7ls2/does_scrum_really_work_i_mean_really/  
Why doesn’t scrum work for me?

http://www.aaron-gray.com/a-criticism-of-scrum/  
https://medium.com/swlh/agile-is-the-new-waterfall-f7baef5d026d  
Why should I hate Scrum?

https://www.atlassian.com/agile/kanban  
What is Kanban (Extra)

## Tools for scrum
https://www.zenhub.io/  
Full fledged scrum tool, can only be used inside GitHub. Only for Chrome though.

https://waffle.io/  
Easy to use agile function that integrates with GitHub.

https://trello.com  
The allround best way to use when you don’t use GitHub.

# Cool stuff (Extra)

[Travis CI](https://travis-ci.org/)  
No-one wants to see if your tests are succeeding by pulling your branch and locally running the tests. This service will take all your commits and run tests on them. Great for annoying your teammates that their tests are not succeeding.

https://www.doc.ic.ac.uk/~susan/475/unmain.html  
How to write unmaintainable code
