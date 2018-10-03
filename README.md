# Git-Workshop-Attendees

This repo is meant for acquainting participants of the Git & GSoC workshop (organized by IET On Campus, BIT Mesra annually) with the process of *properly* contributing to a repository on GitHub. Make sure you have [installed git](./Git_Install_Instructions.md) and followed the [configuration instructions](./Git_Config_Instructions.md). In case of any doubts, head over to the *#git-github* channel on [our slack workspace](https://kutt.it/ietslack). Also, this repo includes the [workshop slides](./Git_Github_Slides.pdf), which has links to some great resources for learning Git and GitHub!

## Instructions:

- Fork this repo: Click on fork on the GitHub page.

- Clone your fork: 

  `git clone https://github.com/aksh1618/Git-Workshop-Attendees`

- Create a branch: current_year_<your roll number>: 

  `git branch 2018_be1013015`

- Checkout the branch: 

  `git checkout 2018_be1013015`

- Create an MD file with name <rollno>_<name>.md: 

  `be1013015_aakarshit_uppal.md`

- Write stuff about yourself! (Try to keep it short :P)

- Add the file to git: 

  `git add be1013015_aakarshit_uppal.md`

- Commit with message: Add <your name>: 

  `git commit -m "Add aakarshit"`

- Push while creating remote link for your branch:

   `git push --set-upstream origin 2018_be1013015`

- Go to GitHub and select `Compare & pull request`

- Select current year's branch as base for `ietbitmesra/Git-Workshop-Attendees` (Ex: `2018`)

- Click `Create pull request`.

- Wait for approval !