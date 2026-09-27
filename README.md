# Python Quiz Game
A simple quiz game built with python
## Table of contents
- [Table of contents](#table-of-contents)
- [Features](#features)
- [Project structure](#project-structure)
- [Requirments](#requirments)
- [Installation](#installation)
- [Envoirment Setup](#envoirment-setup)
- [Usage](#usage)
- [Example output](#example-output)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [Licence](#licence)
- [Author](#author)


## Features
- Quiz system
  - Asks the player multiple questions
  - Cheks the answers automaticlly
  - Calculates the final score
- Result storage
  - Saves quiz results in `results.txt`
- Admin mode 
  - Asks the admin password
  - Checks if the password is currect or not
  - keeps the private information outside the main python file
  - Loads the password from `.env`

## Project structure
```text
python_quiz_game/
│   main.py
│   question.py
|   requirements.txt
│   .env.example
│   .gitignore
│   README.md
```
### File description
- `main.py` - main file used to run quiz game
- `questions.py` - stores questions ans answers
- `requirements.txt` - lists the python packages needed for the project
- `.env.example` - shows the envoirment variables needed by the project
- `.gitignore` - tells git which files and folders should not be tracked
- `README.md` - contains the project documantation
  
## Requirments
Before running the project, make sure you have:
- `python 3`
- `python-dotenv`

## Installation
1. open a terminal in the progect folder .
2. check that phyton is installed :
```bash
python --version
```
3. install the pythin packages:
```bash
pip  install -r requirements.text
```

## Envoirment Setup
1. Create a `.env` file from `.env.example`:
```bash
cp .env.example .env
```
2. Open the new `.env` file 
3. Replace the example value with youre own password
```text
QUIZ_ADMIN_PASSWORD=put_your_password_here
```
5. Save the file

> Do not commit your `.env` file, because it may contain private information.

## Usage 
1. Open a terminal in the project folder
2. Run the quiz game
```bash
python main.py
```
3. Choose `yes` or `no` for admin mode
4. Of you choose `yes`, enter the password from your `.env` file
5. Enter your name
6. Answer the questions
7. See your final score and message
8. Your result is saved in `results.txt`

## Example output
```text
do you want yo open admin mode? yes/no: no

what's your name? Hediye

.welcome.

what language are we using? python

correct!

what command starts a git? git commit

wrong!

what command shows git status? git add

wrong!

your score is:  1 out of  3
keep practicing,  Hediye!
```

## Roadmap 
- [x] Add multiple quiz question
- [x] Calculate the final score
- [x] Save results to a file
- [x] Add admin mode 
- [ ] Add more quiz questions
- [ ] Add difficultly levels
- [ ] Add a timer

## Contributing

## Licence

## Author
Create by [Hediye Ghahremani](https://github.com/hediye-ghahremani-me)
