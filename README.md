
<!-- Logo image -->
<p align="center">
  <img
    width="400"
    src="https://flashcards-519da.web.app/static/media/logo.6d3f27e3fc0c4a7bc3b3.png"
    alt="Starship – Cross-shell prompt"
  />
</p>

<p align="center">

<!-- Licence Badge -->
<a href="https://github.com/CSC510-Group18/FlashCards/blob/main/LICENSE">
<img src="https://img.shields.io/github/license/CSC510-Group18/flashcards?style=plastic"></a>

<!-- Workflow Badge -->
<a href="https://github.com/CSC510-Group18/FlashCards/blob/main/.github/workflows/backend_tests.yml" alt="Python Backend Tests">
<img src="https://github.com/CSC510-Group18/FlashCards/actions/workflows/backend_tests.yml/badge.svg?branch=main"/> </a>

<!-- Codecov Badge -->
<a href="https://app.codecov.io/gh/WolfByteCollective/FlashCards" alt="Codecov">
<img src="https://codecov.io/github/WolfByteCollective/FlashCards/branch/main/graph/badge.svg"/> </a>

<!-- Python Version Badge -->
<a href="https://img.shields.io/badge/python-v3.12.2-yellow.svg" alt="Python version">
<img src="https://img.shields.io/badge/python-v3.12.2-yellow.svg"/> </a>

<!-- Release Badge -->
<a href="https://img.shields.io/github/release/JohnDamilola/FlashCards?color=brightblue" alt="Release">
<img src="https://img.shields.io/github/release/JohnDamilola/FlashCards?color=brightblue"/> </a>

<!-- Ruff Badge -->
<a href="https://img.shields.io/badge/ruff-v0.9.7-brightgreen.svg" alt="Ruff version">
<img src="https://img.shields.io/badge/ruff-v0.9.7-brightgreen.svg"/> </a>

</p>


## Description
Are you a student and having trouble preparing for tests and exams? Look no further. FlashCards also helps you memorize all that hard-to-remember information with online flashcards so that you ace your exams!

FlashCards is a spaced repetition learning platform to <b>create</b>, <b>memorize</b> and <b>share</b> your knowledge list using flashcards.

1. Create folders
2. Add decks to folder
3. Decks in folder redirected to Practice Deck
4. Leaderboard
5. Quiz Mode
6. Recently visited Decks

## Watch Flashcards in Action
[Watch FlashCards Video](./images/FlashCards-2.mp4)

## Tech Stack
<a href="https://flask.palletsprojects.com/en/2.2.x/"><img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" /></a>
<a href="https://www.typescriptlang.org/"><img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" /></a>
<a href="https://reactjs.org/"><img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" /></a>
<a href="https://firebase.google.com/"><img src="https://img.shields.io/badge/firebase-ffca28?style=for-the-badge&logo=firebase&logoColor=black" /></a>
<a href="https://github.com/"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="https://ant.design/"><img src="https://img.shields.io/badge/Ant%20Design-1890FF?style=for-the-badge&logo=antdesign&logoColor=white" /></a>
<a href="https://www.heroku.com/"><img src="https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white" /></a>

## Installation
```bash
conda create -n flashcards python=3.12.2
conda activate flashcards
pip3 install .
```

## Getting started:
- **Backend** -> [See README.md](backend/README.md)
- **Frontend** -> [See README.md](frontend/README.md)

## Current Screens

<p style="display: flex; flex-wrap: wrap; justify-content: center; gap: 15px; ">
  <img src="./images/dashboard.png" alt="Demo Screens 1" width="250px" height="250px style="object-fit: cover;" />
  <img src="./images/deck to folder.png" alt="Demo Screens 2" width="250px" height="250px style="object-fit: cover;" />
  <img src="./images/decks in folders.png" alt="Demo Screens 3" width="250px" height="250px style="object-fit: cover;" />
  <img src="./images/practice deck.png" alt="Demo Screens 4" width="250px" height="250px style="object-fit: cover;" />
  <img src="./images/quiz.png" alt="Demo Screens 5" width="250px" height="250px style="object-fit: cover;" />
  <img src="./images/quiz complete.png" alt="Demo Screens 6" width="250px" height="250px style="object-fit: cover;" />
  <img src="./images/leaderboard.png" alt="Demo Screens 7" width="250px" height="250px style="object-fit: cover;" />
</p>



## Future Roadmap [See here](https://github.com/users/JohnDamilola/projects/1)
### Phase 1:
- [x] Create database ER diagram
- [x] User Login
- [x] User Signup/Create Account
- [x] Explore or Search Public FlashCards
- [x] Create/Read/Update/Delete <b>Decks</b> <i>(collections of cards)</i>
- [x] Create/Read/Update/Delete <b>Cards</b>
- [x] FlashCard Practice Mode
- [x] Add Unit testing
- [x] Setup backend and frontend deployment

### Phase 2:
- [x] Add slider to navigate through the decks
- [x] Folder Creation
- [x] Add decks to the folders, and redirect them to the Practice Deck on click
- [x] Quiz mode 
- [x] Show recently visited decks on dashboard
- [x] Leaderboard that shows the email, count of correct and incorrect answers, and rank of a particular user.

### Phase 3:
- [ ] Add a dashboard providing insights on study habits, quiz results over time, and areas needing improvement, helping users to plan their study strategy.
- [ ] Enable collaborative learning by enabling users to share flashcards seamlessly with friends, classmates, or study groups
- [ ] Progress tracking by subject and review options like retrying incorrect questions
- [ ] Chrome Extension feature that enables users to highlight text on websites or online PDFs and instantly create flashcards from their selections.
