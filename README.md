# What Is This Repo?

This is Olin Rocketry's preferred parts for electrical hardware design. This includes everything from the lowliest of capacitors and resistors to IC's like voltage regulators and even microcontrollers.

# Why Is This Repo?

1. When multiple people work on the same PCB, it is extremely useful to be able to pull from the same parts list (especially when working on different machines).

2. When the same team is working on different PCB's it makes ordering parts to populate those boards much easier. 

# How To Use This Repo

Click that "fork" button in the top right hand corner of this page and select your Github username. 

This should take you directly to your fork. You can tell because the upper left hand corner should read

>YOUR-USERNAME / preferred_parts

If not please navigate to your fork. 

Once there, click that green "code" button and hit the clipboard to copy. 

In the terminal, navigate to the directory where you want to put preferred_parts (hint: it should probably be somewhere close to where you put files for Olin Rocketry)

Next, clone the repository: 

    $ git clone https://github.com/YOUR-USERNAME/preferred_parts

Then, go to the **original** preferred parts repository. If you are reading this, you are probably here already.

Hit the green code button and the clipboard to copy.

In the same terminal as before, `cd` into the repository you just cloned: 

    $ cd preferred_parts

and enter: 

    $ git remote add upstream https://github.com/Olin-Rocketry/preferred_parts.git

and you're done! To get parts that others have added after you've done this procedure, `git pull` like normal. To add your own parts, `git push` like normal, and then check out how to make a [pull request](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/about-pull-requests). 

 If you prefer a tutorial with more pictures, check [this one](https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/fork-a-repo) out. 