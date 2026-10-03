# 3kb Cookie Clicker
<img width="1080" height="686" alt="image" src="https://github.com/user-attachments/assets/8abd18bf-d225-4167-b903-a32285d960db" />

### A simple cookie clicker game made on Data URI (in a single line) and written under 3 kilobytes!
##### What's so special about it:
- Plays crumpling sound on click on cookie.
- Adds +1 to the score when clicked on the cookie.
- The cookie was drawn in canvas using JS.
- Sound was encoded in base64 instead of any hosting.
- Everything works local and offline.
##### How to use it:
1. Download the repo or clone it.
2. Go to ```/dist```.
3. Open ```uri.txt``` and copy the code.
4. Paste it in your browser's URL bar.
##### How it works:
When you click on the cookie (made inside canvas) which is inside the button tag, on click it plays audio from base64 encoded mp3 which is set as the source and a simple script count each score by adding +1.
##### Building
```
npm install
node build.mjs
```
