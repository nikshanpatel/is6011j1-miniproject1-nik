# The difference between cloning and forking a repository on GitHub

## **Forking**

A fork is a copy of a repository that allows you to freely experiment with changes without affecting the original project. A forked repository differs from a clone in that a connection exists between your fork and the original repository itself. In this way, your fork acts as a bridge between the original repository and your personal copy where you can contribute back to the original project using [Pull Requests](https://help.github.com/articles/about-pull-requests).

Forking a project is as easy as clicking the  **Fork**  button in the header of a repository. Once the process is complete, you'll be taken right to your the forked copy of the project so you can start collaborating!

> ### Example:
>Forking a repository is a simple two-step process. We've created a repository for you to practice with!
>1.  On GitHub, navigate to the  **[nikshanpatel](https://github.com/nikshanpatel)**/**[is6011j1-miniproject1-nik](https://github.com/nikshanpatel/is6011j1-miniproject1-nik)** repository.
>2.  In the top-right corner of the page, click  **Fork**.
>
  >  ![Fork button](/section-3/fork-vs-clone.png)   

That's it! Now, you have a  _fork_  of the original **_nikshanpatel/is6011j1-miniproject1-nik_** repository.

Check out the  [help article](https://help.github.com/articles/fork-a-repo) for more information about forking, including steps on how to keep your fork synced up with the original project.

## **Cloning**

When you create a new repository on GitHub, it exists as a  [remote](https://help.github.com/articles/about-remote-repositories) location where your project is stored. You can clone your repository to create a local copy on your computer so that you can sync between both the local and remote locations of the project.

Unlike forking, you won't be able to pull down changes from the original repository you cloned from, and if the project is owned by someone else you won't be able to contribute back to it unless you are specifically invited as a [collaborator](https://help.github.com/articles/permission-levels-for-a-user-account-repository). Cloning is ideal for instances when you need a way to quickly get your own copy of a repository where you may not be contributing to the original project.

To clone a repository, head over to the main page of a project and click the _Clone or download_ button to get the the repository's HTTPS or SSH URL. Then, you can perform the clone using the `git clone` command in your command line interface of choice. For a step by step guide, check out the [cloning a repository](https://help.github.com/articles/cloning-a-repository/) article.
