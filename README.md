# morse-code-player

Plays Morse Code messages using light and sound. 

- Supports escape-room-style classroom challenges and puzzles.

- Simple, portable, standalone, offline-able, complete app in one html file.  

# How to "Install"
- Click the green **`[Code]`** button, top right-ish.
- Click on **`Download ZIP`**.
- Click the downloaded ZIP file.
- Click the **`morse-code-player-main`** directory.
- Double Click **`morse-code-player.html`**.
> Alternately use any method to download or copy-n-paste the above **`morse-code-player.html`** into an html file on your computer.
> Alternately use `git` `clone`, which is why github _exists_.
# How to Use
- Click the Play button.
- Click the secret/invisible textarea under the Play button to enter _your_ message.
<br>_FYI- The default message is a chemistry clue for **salt water**_.
- It is easy to customise the app by tweaking the html file. <br>For instance, change the **`speed`** variable to change delivery speed.

> Use in your professional escape room by removing the textarea, hard coding your message and running inside a kiosk-mode browser or [Electron](https://www.npmjs.com/package/electron)
### Credit 
ChatGPT v2023-02-18, for the `playTone()` and `stringToMorseCode()` functions (after _many_ retrains because of it's current incompetance utilizing asynchronous resources) and the first drafts of the `play` and `stop` svg shapes.
