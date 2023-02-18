# morse-code-player

Plays Morse Code messages using light and sound. 

- Supports escape-room-style classroom challenges and puzzles.

- Simple, portable, standalone, offline-able, complete app in one html file.  

# How to use

- Download the **`morse-code-player.html`** file. 
 - Open the html file in your browser.<br>
 Or Find the file in your downloads folder (or wherever it downloaded) and open it in a browser.
- Click the Play button.
- Click the secret/invisible textarea under the Play button to enter _your_ message.
<br>_FYI- The default message is a clue for **salt water**_

> Use in your professional escape room by removing the textarea, hard coding your message and running inside a kiosk-mode browser or [Electron](https://www.npmjs.com/package/electron)
### Credit 
ChatGPT v2023-02-18, for the `playTone()` and `stringToMorseCode()` functions (after _many_ retrains because of it's current incompetance utilizing asynchronous resources) and the first drafts of the `play` and `stop` svg shapes.
