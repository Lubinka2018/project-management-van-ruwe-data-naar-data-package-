# Past

## Reminder: workflow

- Work in groups of three (or pairs); 'pair programming' style.
  - One of you is the _driver_: they share their screen and perform the actions.
  - The other(s) support(s) the driver, by e.g. looking up questions, and being
    active and engaged with the driver's work.
- Switch roles so that everyone in your team has been in the driver's seat:
  - The driver zips the entire project, and emails it to a partner *before the
    break*.
  - The recipient unzips all and confirms the project is complete.
  - Do not worry if you have not been able to finish the exercises. You can take
    your project to the next step.
- Ask for help when needed, we are happy to support you!
  - Use the "Ask for help" button in your breakout room. (Note that raised hands
    and chat messages will not be seen outside the room!)
  - A helper will join your breakout room.

## Exercise

**Before you start:** Make sure you have received the complete project folder as
a zipped file from your partner. Unzip the files.

Your project is growing! As you are continuing, it is good to keep track of your
changes, so that work done with different states of the project can be
adequately assessed later on. Your job will be to start a git project in GitHub Desktop, and create a first version of your project.

1. Open the program GitHub Desktop.
1. In Github Desktop, click on `File` and then `New Repository`. This will prompt you to fill in the "name" and "local path" of the repository. Make sure to tick the box "Initialize this repository with a README".
1. A new folder is created on your computer where changes can be tracked. There also is a file created `README.md`. In Github Desktop, click on `Show in explorer` to look at this new folder.
1. In another explorer, find the unzipped data folder you received and copy it into your new git folder.
1. In GitHub Desktop, notice that changes are automatically noticed. But the changes are not tracked yet (not picture has been taken).
1. In Github Desktop, take a "snapshot" of the changes in this new version, write a title and description of the changes and click on `Commit to main`
1. In the explorer, open the README.md file with a text editor (e.g., notepad) and write some documentation about the dataset.
1. In Github Desktop, (the same as before) take a "snapshot" of the changes in this new version, write a title and description of the changes and click on `Commit to main`.
1. In Github Desktop, click on `Publish repository`. Follow the prompt to `Sign in` to GitHub.
1. Now you can publish your repository in the cloud. Untick `keep this code private` and click on `Publish repository`.
1. When you are done, share the url with your partner (you don't need to zip the data this time).
1. In GitHub Desktop, your partner clicks on `File` and then `Clone a repository`. Your partner fills in the url and the local path on their computer where a copy of the project will be downloaded.
1. Your partner just downloaded it onto their computer. They should link it to their GitHub account as well.
1. In Github Desktop, they should click on `Publish repository` and follow the prompt to `Sign in` to GitHub.
1. Now you they publish the repository in the cloud. Untick `keep this code private` and click on `Publish repository`.
1. Now they can continue as the driver during [FUTURE](future.md).

## What if you finish early?
- Do some archeology by clicking on `History` (top left column, next to `Changes`).
  - Inspect the different commits you made, and what changed.
  - Try right-clicking on a past commit and select `checkout commit`, and then confirm by clicking `checkout commit`.
  - Inspect the state of your project in the explorer.
  - To go back to your latest version, click in the top on `Detached HEAD` and under Default branch, click on `main`.
- Ignore some things that you never want to put into a version.
  - Click on `Repository` and then `Repository settings`. Select `Ignored files` and try out this functionality.



## References and links

- [Software Carpentry's Version Control with Git](https://swcarpentry.github.io/git-novice/)
- [Keepachangelog.com](https://keepachangelog.com/en/1.0.0/)
- [Semantic versioning](https://semver.org/spec/v2.0.0.html)
- [Documentation and metadata](https://the-turing-way.netlify.app/reproducible-research/rdm/rdm-metadata.html)
- [eScience center documentation guidelines](https://guide.esciencecenter.nl/#/best_practices/documentation)
- [CodeRefinery's lesson on documentation](https://coderefinery.github.io/documentation/)

## Watch a presentation on changelogs (manual version control)

<iframe width="560" height="315" src="https://www.youtube.com/embed/7GhMCBZG10s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

_[View the transcript here](../transcripts/project_history.md)_
