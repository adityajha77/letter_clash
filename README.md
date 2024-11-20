# Letter Clash Game

**Letter Clash** is a word game where players (or the computer) must come up with a word starting with the last letter of the previous word. The game includes a timer, score counter, and dynamic background that changes every 5 successful word entries.

## Features
- Play against the computer or with friends (up to 4 players).
- Timer starts with 45 seconds, resetting after each successful word.
- Background color changes every 5 correct words.
- A score counter displays on the right side of the screen.
- The game uses random words from a dictionary API to ensure no repetition.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **API**: DataMuse API (for fetching random words)
- **Database**: PostgreSQL (for storing words)
- 
## How to Play
1. Choose your gameplay mode: **Play with Computer** or **Play with Friends**.
2. The game will show a random word (e.g., "apple").
3. Players must type a word that starts with the last letter of the given word (e.g., "e" → "elephant").
4. A timer will count down from 45 seconds. If the timer runs out, the next player gets a turn.
5. The game ends when a player fails to answer in time or when a word is repeated.

## How to Run the Game Locally

### Prerequisites:
- Node.js (version 14 or higher)
- PostgreSQL (if using the database option)

- ### install all required modules like express,nodemon,etc.
