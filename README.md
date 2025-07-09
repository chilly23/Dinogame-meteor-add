# Chrome Dino: Meteor Mode

A reimagined version of the classic Chrome Dino game — with a dark twist.

When you’re offline, everything seems fine.  
But the moment you go online, a meteor shower falls from the sky to end your run.

![Dino Meteor Demo](https://cdn.hashnode.com/res/hashnode/image/upload/v1661865487055/sUO3zdyCt.jpg)

## Features

- **Classic Dino Gameplay**  
  Play as the Dino just like the original Chrome game.

- **Online Detection Twist**  
  The game checks your internet status — meteors only spawn if you're online.

- **Meteor Showers on Reconnection**  
  If you go back online mid-game, meteors rain down and end your run.

- **Canvas & Image Manipulation**  
  Transitions, crash animations, and “User is Online” messages are rendered on canvas.

- **Hardcoded Doom**  
  You can't dodge the meteors. They're inevitable — like the internet itself.

## Screenshots

| Offline Gameplay | Online Transition       |
|------------------|--------------------------|
| Classic Dino run | Meteors falling + crash |

## How It Works

- When the game starts offline, it behaves like the original.
- After a delay (e.g., 5 seconds), if you're online, the `meteorsEnabled` flag activates.
- Multiple meteors fall from the top with randomized speed and position.
- After 3 hits, the game ends with a custom “User is Online” crash screen.
