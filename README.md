# Git-Workshop-Attendees

This repo is meant for acquainting participants of the Git & GSoC workshop (organized by IET On Campus, BIT Mesra annually) with the process of *properly* contributing to a repository on GitHub. Make sure you have [installed git](./Git_Install_Instructions.md) and followed the [configuration instructions](./Git_Config_Instructions.md). In case of any doubts, head over to the *#git-github* channel on [our slack workspace](https://kutt.it/ietslack). Also, this repo includes the [workshop slides](./Git_Github_Slides.pdf), which has links to some great resources for learning Git and GitHub!

## Instructions:

Follow these steps to create your first pull request! (Do **NOT** copy paste the commands, they are examples! Use commands specific to your case.)

- Fork this repo: Click on fork on the GitHub page.

- Clone your fork (Click on `clone or download` on **your fork's page** and use the link):

  ```git
  git clone https://github.com/aksh1618/Git-Workshop-Attendees
  ```

- Create a branch: `current_year_<your roll number>`:

  ```git
  git branch 2018_be1013015
  ```

- Checkout the branch:

  ```git
  git checkout 2018_be1013015
  ```

- Create an MD file with name `<rollno>_<name>.md`:

  ```git
  touch be1013015_aakarshit_uppal.md
  ```

- Open it and write stuff about yourself! (Try to keep it short :P)

- Add the file to git:

  ```git
  git add be1013015_aakarshit_uppal.md
  ```

- Commit with message: Add `<your name>`:

  ```git
  git commit -m "Add Aakarshit"
  ```

- Push while creating remote link for your branch:

   ```git
   git push --set-upstream origin 2018_be1013015
   ```

- Go to GitHub and select `Compare & pull request`

- Select current year's branch as base for `ietbitmesra/Git-Workshop-Attendees` (Ex: `2018`)

- Click `Create pull request`.

- Wait for approval !