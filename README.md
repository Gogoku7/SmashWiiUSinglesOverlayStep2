# SmashWiiUSinglesOverlayStep2
Step 2 of a project to create a dynamically editable overlay for Super Smash Bros. Wii U Singles usable for any tournament streamer using HTML, JavaScript, CSS and C#.

Changes from Step 1:
- Added Character icons
- Added score
- Added Ports
- Added jQuery.js to dynamically update the overlay when the CSS is altered.
- Added fitty.js to dynamically resize the text in the overlay when the CSS is altered.

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

- #player1Character
- #player1NameText:before
- #player1Port
- #player1ScoreText:before
- #player1TwitterText:before
- #player2Character
- #player2NameText:before
- #player2Port
- #player2ScoreText:before
- #player2TwitterText:before
- #roundBoxText:before
- #tournamentBoxText:before

at the bottom of styles.css

At this step, the overlay dynamically updates whenever the CSS is altered!
