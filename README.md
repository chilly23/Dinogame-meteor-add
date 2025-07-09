Chrome Dino: Meteor Mode
A reimagined version of the classic Chrome Dino game — with a dark twist.

When you’re offline, everything seems fine.
But the moment you go online, a meteor shower falls from the sky to end your run.

![Dino Meteor Demo](https://cdn.hashnode.com/res/hashnode/image/upload/v1661865487055/sUO3zdyCt.jpg)

Features
Classic Dino Gameplay
Play as the Dino just like the original Chrome game.

Online Detection Twist
The game checks your internet status — it only spawns meteors if you're online.

Meteor Showers on Reconnection
If you go back online while playing, meteors rain down, killing the dino in seconds.

Canvas & Image Manipulation
All transitions, crash animations, and “User is Online” messages are rendered on canvas.

Hardcoded Doom
You can't dodge the meteors. They're inevitable. Just like connection in modern life.

Screenshots
Offline Gameplay	Online Transition
classic dino run	meteors falling + crash

How It Works
- When the game starts offline, it's just like normal.
- After a delay (e.g., 5 seconds), if you're online, the meteorsEnabled flag is triggered.
- Multiple meteors fall from the top with random speed and direction.
- Upon hitting the horizon 3 times, the game ends with a custom “User is Online” crash screen.
