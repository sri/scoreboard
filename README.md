# scoreboard
A basketball scoreboard for my little one.

See it in action: https://sri.github.io/scoreboard/index.html

# Features
- displays a game clock and a shot clock
- display scores for two teams
- shot clock will reset to 24 when
- shot clock won't be displayed game only has that many seconds left
- clocks will pause at the end of quarters and overtime
- overtime starts automatically when at the end of a game, score is the same
  (if you hit a buzzer beater, and then after the end of the game, the score
    is tied, unpause the clock to start overtime)
- allows for team selection

- TODO: use localstorage to save state; allow selecting mins per quarter

# Usage
- touch the team name to select different teams
- touch the clock to start/pause it
- touching on a team's score increments it by one

# Testing
- tested on Pixelbook (latest Chrome) & iPad (latest Safari)

# Tech
Everything is in a single HTML file. Uses ES6 (classes). Uses font from Google & the Bulma CSS framework.
