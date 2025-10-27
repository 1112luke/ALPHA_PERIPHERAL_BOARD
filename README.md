<h1 align="center">🥵🚀NDXP Alpha Peripheral Board🚀🌡️</h1>

<p align="center">
  <img width="973" height="979" alt="Screenshot 2025-10-26 at 5 07 59 PM" src="https://github.com/user-attachments/assets/fe4b48fa-06d6-4dd9-9ad1-3563d5a91e83" />
</p>

<h4 align="center">This is the repository for the HARDWARE DESIGN ONLY. Software for the board can be found <a href="https://github.com/1112luke/NDXPCOMPUTER">here</a></h4>

## Introduction

This board has the following peripherals:

- 0-5v ADC (x12)
  used for pressure sensors
- 

## Contributing
This repository is open at all times to any member submitting a Pull Request and merging their code directly into the main branch after approval! If you don't know what a Pull Request is, or if this is your first time using github, it is recommended that you watch [this](https://docs.github.com/en/get-started/start-your-journey/hello-world) guide before you begin.

### Requirements
Before you do anything, make sure you:
 - Have [git](https://git-scm.com/downloads) installed on your computer (macos should by default).
 - Have [kicad](https://www.kicad.org/) installed on your computer
 - Are added as a repository contributor (ask a team lead)

To make a contribution, the generall process is:

<b><i>clone/pull → branch → make your changes → add;commit;push → request approval for merge</i></b>

Each step is broken down as follows:

### Clone/Pull 🤖
If this is your first time interacting with this repository on your local machine, execute the following command in the location on your computer you wish to clone the repository to:

```
git clone https://github.com/1112luke/CubeFlightComputer
```

If you have the repository already and wish to begin a new contribution <b><u>it is important that you get the most recent version of the repository: </u></b>

```
git switch main
git pull origin main --rebase
```

### Branch 🪾
Once you have an up to date copy of the repository on your local machine, you will need to create a new branch for your contribution:

```
git branch -c branch-name
```

```
git switch branch-name
```

Feel free to name it whatever you want. Be descriptive!

### Make Your Changes 👨‍💻
At this point, you are free to make whatever changes you want! Any time you are working in your local copy, you do not have to worry about messing up the project. Feel free to delete the entire thing if you want!
 - Experiment
 - Break Things
 - Absolutely Cook 👨‍🍳

<b>THIS IS HOW WE LEARN!!</b>

### Add;Commit;Push 💡
When you are satisfied with your contribution, execute the following steps to push your changes to github for review:

```
git add .
```

```
git commit -m "your-descriptive-message"
```

```
git push origin branch-name
```

Once that is done, your code should be pushed to this repository! The final step is to submit a pull request for your code to the main branch using this website, and it will be reviewed for merge shortly!


### RULE OF THUMB!!
In general, commits to github should be <b>small</b> and <b>frequent</b>! This ensures that everybody is working with the most up to date version of the code!
