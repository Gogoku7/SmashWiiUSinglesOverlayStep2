# SmashWiiUSinglesOverlayStep2
Step 2 of a project to create a dynamically editable overlay for Super Smash Bros. Wii U Singles usable for any tournament streamer using HTML, JavaScript, CSS and C#.

Changes from Step 1:
- Added Character icons
- Added score

**How to use in Open Broadcaster Software (OBS Studio):**
- Add a new Browser source to your scene.

![alt img](https://imgur.com/FCYcy8M.png)

- Check the Local file checkbox and click Browse.

![alt img](https://imgur.com/VLLhL43.png)

- Select gameOverlay.html of this project.
- Set the resolution and framerate. (1920 x 1080 at 60 frames per second recommended)
- Check Refresh browser when scene becomes active checkbox.

![alt img](https://imgur.com/zLKg09t.png)

You are now ready to stream with the overlay.

As the streamed set(s) progress, you can update the overlay by changing:

- #player1Box (the background image of the player box of player 1)
- #player1ScoreText:before (the score of player 1)
- #player1Character (the logo of the character of player 1)
- #player1NameText:before (the name of player 1)
- #player2Box (the background image of the player box of player 2)
- #player2ScoreText:before (the score of player 2)
- #player2Character (the logo of the character of player 2)
- #player2NameText:before (the name of player 2)
- #roundBoxText:before (the current round)

at the bottom of styles.css

At this step, the overlay doesn't dynamically update whenever the css is altered, you have to move back and forward between the scene with the overlay and another scene to show an updated overlay.
