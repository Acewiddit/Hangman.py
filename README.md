# Hangman
## Project Overview
This Hangman game which is writen in Python, allows two players to take turns playing Hangman, where one player selects a secret word and the other attemps to guess it within a limited number of attemps. This project is developed using Agile methodology, which allows incremental development, collaboration, and regular review.

## Project Scope
### Included Features
* Python-based Hangman game
* Graphical User Interface (GUI)
* Two-player, turn-based gameplay
* Secret word input or random word selection
* Letter guessing functionality
* Visual Hangman Progress
* Win/Loss
* Restart option

### Excluded Features
* Online multiplayer
* Databases or persistent storage
* User accounts or authentication
* Sound effects or animation

## Agile Methodology
This approach will allow for a rapid feedback and adaptation throughout the development of this project.
* Development made in small split increments
* Shared product backlog
* Informal discussions during library sessions or over video calls

## Team Organisation & Roles
<img width="602" height="93" alt="Screenshot 2025-12-17 111711" src="https://github.com/user-attachments/assets/38232d8f-d4ee-4964-aea1-6899f72c2199" />

## Requirements Specification
### Functional Requirements
* The program should allow Player 1 to enter or generate a secret word
* The program should allow Player 2 to guess letters
* The program should display correctly guessed letters
* The program should track incorrect guesses
* The program should display a visual Hangman representation
* The program should determine win and loss conditioins
* The program should allow the game to be restarted

### Non-Functional Requirements
* The application should be intuitive and easy to use
* The program should respond to user input within one second
* The GUI should be readable and accessible
* The application should run in standard Python environments

## User Stories
* As a player, I want to guess letters so I can reveal the hidden word
* As a player, I want to see incorrect guesses so I know how many attempts remain
* As a player, I want to restart the game so I can play again
* As a playe, I want a clear interface so the game is easy to understand

## Product Backlog 
<img width="538" height="249" alt="Screenshot 2025-12-17 114239" src="https://github.com/user-attachments/assets/c94c29e0-45eb-4afc-8bea-74de0f66715f" />

## Program Design
### Architecture
The program will use a Model-View-Controller (MVC) structure:
* Model: Game state, secret word, guesses
* View: GUI (Tkinter)
* Controller: Input handling and game flow
### Software used:
* IDLE (Python GUI)
* Tkinter

## Iterative Development Plan
### Sprint 1
* Implement game rules and logic
* Validate letter input
* Win/Loss logic
### Sprint 2
* Build GUI using Tkinter
* Connect game logic to interface
* Display Hangman progress
### Sprint 3
* Testing ang bug fixing
* Documentation
* Final refinements

## Testing Strategy
* Manual testing of each feature
* Boundary testing (maximum incorrect guesses)
* Peer testing within the group
* Regression testing after changes

## Reflection
Using an Agile approach helped the team focus on delivering core functionality first before improving the user interface. Regular communication ensured tasks were shared fairly, and iterative testing reduced defects early in development.

## Evidence Included 
* Sprint backlog table
* Screenshots of GUI development
* Code commits and version history
* Final application screenshots
