# Basketball Scoreboard

A fully-featured basketball scoreboard application for my little one.

**[See it in action](https://sri.github.io/scoreboard/index.html)**

---

## Features

### Timekeeping
- **Game Clock** - tracks the main game time with automatic quarter/period management
- **Shot Clock** - 24-second shot clock that automatically resets when points are scored
- **Auto-pause** - clocks pause automatically at the end of quarters and overtime periods
- **Quarter Advancement** - click on the quarter indicator to advance to the next period

### Scoring
- **Two-team Scoring** - track scores for both teams with touch-to-increment controls
- **Smart Scoring** - shot clock automatically resets to 24 seconds when points are added

### Game Management
- **Overtime Support** - automatically starts overtime when the score is tied at the end of regulation
  - If you hit a buzzer beater and the score is tied after the period ends, simply unpause the clock to start overtime
- **Team Selection** - choose from multiple teams by clicking/touching the team name
- **Buzzer Sound** - authentic buzzer sounds at the end of each period

---

## Usage

| Action | Result |
|--------|--------|
| Touch team name | Select different teams |
| Touch the clock | Start/pause the game clock |
| Touch a team's score | Increment score by 1 point |
| Touch quarter indicator | Advance to next quarter |

---

## Technical Details

**Architecture**: Single-file HTML application
**JavaScript**: ES6+ with class-based architecture
**Styling**: Bulma CSS framework
**Fonts**: Google Fonts
**UI Design**: Enhanced by Claude

---

## Browser Compatibility

Tested and verified on:
- Pixelbook (Chrome, latest)
- iPad (Safari, latest)

---

## Roadmap

- [ ] LocalStorage integration to save and restore game state
- [ ] Configurable quarter/period duration settings

---

*Built with love for family game nights*
