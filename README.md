# Working with Git

This is the Team 3303 guide for working with Git, primarily from Git Bash or just regular Bash.


- [Installing Git on Windows](#installing-git-windows)
- [Installing Git on Mac OS / Linux](#installing-git-mac-os-linux)
- [Cloning the Repo](#cloing-the-repo)


<a name="installing-git-windows"></a>
## Installing Git on Windows

If you're working on Windows, you'll want to install either [Git for Windows](https://git-for-windows.github.io/) or [GitHub Desktop](https://desktop.github.com/). GitHub Desktop has its own set of instructions and guides, so check out their homepage if you're using that.

For the rest of this guide, it will be assumed that Windows users are using Git for Windows, since it installs "Git Bash", which will allow the user to work with the same commands as users on Mac OS and Linux.


<a name="installing-git-mac-os-linux"></a>
## Installing Git on Mac OS / Linux

If you're working on Mac OS or Linux, installing Git is typically as easy as installing with either Homebrew or Aptitude, respectively.


<a name="cloning-the-repo">
## Cloning the Repo

If you don't already have the repository cloned to your machine, head over to the [team's page on GitHub](https://github.com/Team3303) and select the repo you need to work on.

From the repo's page, select **Clone or Download**, make sure the title of the popup says **Clone with HTTPS**, then copy the URL in the popup.

In Bash (or Git Bash), `cd` to the directory where you'll be keeping all of your repositories locally. Once in that directory, run the following:

```
git clone <url-you-copied-from-github>
```

Inserting the URL you copied from GitHub. After running, make sure you `cd` into the directory that Git just created (it should have the same name as the project by default).
