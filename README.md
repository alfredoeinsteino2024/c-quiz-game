# Quiz Game

A command-line general knowledge quiz game with 10 multiple-choice questions.

## Features
- 10 diverse questions covering science, geography, history, and culture
- Real-time scoring with immediate feedback
- 70-point threshold to "qualify for the next stage"
- Replay option to try again
- Proper input handling and buffer management
- Personalized experience with player name

## How to Run
```bash
gcc QUIZ.c -o quiz
./quiz
```

## Gameplay
- Answer 10 multiple-choice questions
- Each correct answer awards 10 points
- Score 70+ points to qualify
- Get instant feedback after each question
- Option to replay after finishing

## Sample Questions
- What planet is known as the Red Planet?
- Who invented the light bulb?
- What is the capital of France?
- Which country is known as the Giant of Africa?
- And more...

## What I Learned
- Input handling and buffer management with `fgets()` and `getchar()`
- String manipulation using `strcspn()` to remove newlines
- Control flow with nested conditionals
- Boolean logic for game state management
- Creating interactive user experiences
- Score tracking and threshold systems

## Code Highlights
- Uses `fgets()` instead of unsafe `gets()` for string input
- Properly clears input buffer to prevent scanf issues
- Implements a game loop with replay functionality
- Provides clear user feedback throughout

## Known Issues
- Score doesn't reset between replays (minor bug in the outer loop)
- Could be enhanced with question randomization
- Could use arrays/structs for cleaner question management

## Future Improvements
- Add question randomization
- Create difficulty levels
- Implement a high score system
- Add more question categories
- Store questions in external file

## Author
Built while learning C programming and game logic fundamentals.
