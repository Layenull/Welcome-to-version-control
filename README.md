Welcome to you first introduction to Version control Git and Github here you will learn how to use two of the most useful tools in every programmers aresenal which enables us to not only backup our code but also collaborate with people ranging from small distances like a room down the hall in your hostel to larger ones like an office all the way in okinawa japan all from the comfort of your current location so yeah these are pretty important tools and if you stick with this tutorial you'll become well versed in the concept of version control in no time as you will make your first contribution to an open source project here.

I know you're a beginner and may feel intimidated but never let that stop you from learning. Just know any expert you know now was as clueless as you may be now, some may have been even more clueless so enjoy the ride and move at your own pace. If you feel you're mates are making microsoft or google level applications now calm down don't worry learn first you sef will soon oppress them so DEVELOPER welcome and Happy Hacking

![Git and Github logo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQmAS6S5CmPrAMnxRdr30K_js46NIRnDOFBRLweFc9e2aN0vDu4eUw-TUYjBQQMG9DreI0&usqp=CAU)

<ins>What is Git and why should I use it?</ins>

Git is a version control system that helps you track changes to your code over time. It's like having a time machine for your code!

Imagine you're writing a novel, and you want to keep track of all the different drafts. You could create a new file for each draft, but that would be messy and difficult to keep track of. Instead, you could use Git to create a repository for your novel.

A repository is a container for your code. It stores all of the different versions of your code, and it allows you to switch between them easily.

Git is also a distributed version control system, which means that everyone working on the novel can have their own copy of the repository. This makes it easy to collaborate on projects with other people.

<ins>How to download and install Git</ins>
![Git logo](https://git-scm.com/images/logo@2x.png)

Step 1: Go to the Git Downloads page: https://git-scm.com/downloads
Step 2: Select the version of Git that is appropriate for your operating system.
Step 3:Click the "Download" button.
Step 4:Once the download is complete, run the installer file.
Step 5:Follow the instructions in the installer to complete the installation.

<ins>How to create an account on GitHub</ins>
I imagine since you're already here you did all these steps correctly congratulations DEVELOPER ✨🎉🎉 heres a doughnut for all your hard work 🍩

![GitHub logo](https://1000logos.net/wp-content/uploads/2021/05/GitHub-logo.png)

Step 1:Go to the GitHub website: https://github.com
Step 2:Click the "Sign up" button.
Step 3:Enter your username, email address, and password.
Step 4:Click the "Sign up" button.
Step 5:Confirm your email address.
Step 6:Once your email address is confirmed, you can start using GitHub.
Additional tips:

If you are using a Mac, you can also install Git using Homebrew. To do this, open a terminal window and run the following command:
brew install git
Once you have installed Git, you can verify the installation by running the following command:
git --version

<ins>Documentation !!!</ins>
Any good documentation is like a map, it shows you where you are, where you're going, and how to get there without getting lost.

When you're learning something new, documentation can be your best friend. It can help you understand the basics, learn about the different features, and troubleshoot any problems you encounter.

Documentation is also important because it can help you learn about the best practices for using a particular tool or technology. This can save you a lot of time and frustration in the long run.

Of course, documentation isn't always the most exciting thing to read. But it's worth it to take the time to read through the documentation some people say before you start using a new tool or technology, some say while using it. Generally i say just use what works for you as long as you don't skip on reading the docks 👍🏿 It will help you learn faster and avoid making common mistakes.

Here's a bonus tip: When you're reading documentation, don't be afraid to skip around. You don't need to read it from cover to cover. Instead, focus on the sections that are relevant to what you're trying to do at the time.

I hope this helps!

I recommend reading the Git documentation: https://git-scm.com/doc

![Git workflow diagram](https://www.gliffy.com/sites/default/files/image/2021-04/image-blog-what-is-gitflow-diagram%20%281%29.jpg)

<ins>How to use Git</ins>

Git is a powerful tool, but it can be a bit tricky to learn at first. Here is a basic overview of how to use Git:

Step 1: Create a Git repository. You can do this by running the following command in a terminal:
(git init)

Step 2: Add files to your repository. You can do this by running the following command:
(git add <filename>)

Step 3: Commit your changes. You can do this by running the following command:
(git commit -m "Your commit message")

Step 4: Push your changes to a remote repository. This is the remote location where save and can share your code with other people if you feel so. To push your changes to a remote repository, you need to have an account with a Git hosting service like GitHub. Once you have an account, you can run the following command to push your changes:
(git push origin master)

You may not understand this now but alwayyyyys i mean alwayyyyyys ENSURE YOU PUSH YOUR CODE TO GIT HUB AFTER YOU'VE MADE AN IMPORTANT CHANGE TO IT !!! ensure you repeat that phrase to yourself at leasted 12 times a day and don't be like me who had to spend a whole extra 24hrs re-coding a feature i already worked on but didn't push to git hub after my hard-drive crashed 😅😅😅 the only saving grace keeping me from starting the whole project over again is cause i had a good chunck of the code backed up to git hub so i could clone an exact copy of my code back to my system using the Git clone command and the best part of it all is even if i didn't repair my hard drive, as long as you have you're code on Github you can clone it to any system you feel like.

![Git branch diagram](https://user-images.githubusercontent.com/1256329/117236177-33599100-adf6-11eb-967c-5ef7898b55dc.png)

<ins>How to create and manage branches</ins>

A Git branch is a copy of the main codebase. Branches are useful for isolating changes from the main codebase while you are working on them.

For example, imagine you're working on a new feature for your novel. You don't want to add the new feature to the main codebase until it's finished and tested. So, you can create a new branch for the feature and work on it there.

To create a new branch, run the following command:

git checkout -b <branch_name>
This will create a new branch called <branch_name>.

To switch to a different branch, run the following command:

git checkout <branch_name>
To merge two branches, run the following command:

git merge <branch_name>
This will merge the specified branch into the current branch.

![Git merge conflict diagram](https://i.stack.imgur.com/qq6hL.jpg)

<ins>How to resolve merge conflicts</ins>

Merge conflicts occur when two branches have made changes to the same file. To resolve merge conflicts, you need to manually edit the file and choose which changes you want to keep.

For example, imagine you and your friend are both working on the same chapter of your novel. You both make changes to the same paragraph. When you try to merge your branches, Git will detect the merge conflict and ask you to resolve it.

To resolve the merge conflict, you need to open the file in a text editor and compare the two versions of the paragraph. Then, you need to choose which changes you want to keep.

![Git collaboration diagram](https://svg.template.creately.com/jkw3k76e4)

How to collaborate on projects with other people

To collaborate on a project with other people, you can share your repository with them. They can then clone the repository and start making changes.

Once they have made their changes, they can push them to the remote repository. You can then pull their changes down to your local repository and merge them into your branch.

Git is a powerful tool that can help you track changes to your code over time and to collaborate with other people. It can be a bit tricky to learn at first, but it's worth it in the long run.

I hope this tutorial has been helpful! you can watch this tutorial for more help https://www.youtube.com/watch?v=RGOj5yH7evk
