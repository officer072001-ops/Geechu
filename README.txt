=========================================
GEECHU'S BIRTHDAY WEBSITE - SETUP GUIDE
=========================================

WHAT'S IN THIS FOLDER:
- geechu_birthday.html   -> the website itself, just open it in a browser
- photos/                -> put her 10 photos here
- (you'll add)           -> song.mp3 goes directly in this main folder

------------------------------------------
STEP 1: ADD HER PHOTOS
------------------------------------------
1. Put your 10 photos inside the "photos" folder.
2. Name them simply: photo1.jpg, photo2.jpg, photo3.jpg ... photo10.jpg
   (jpg or png both work, just keep the file extension consistent)
3. Open geechu_birthday.html in a text editor (like VS Code).
4. Find lines that look like this (there are 10 of them):
       <div class="pic">📷 Photo 1</div>
5. Replace each one with:
       <div class="pic"><img src="photos/photo1.jpg"></div>
   (change the number to match: photo2.jpg, photo3.jpg, etc.)

------------------------------------------
STEP 2: ADD THE BACKGROUND SONG
------------------------------------------
1. Save your song as: song.mp3
2. Put it in the SAME folder as geechu_birthday.html (not inside "photos")
3. That's it — the code already looks for "song.mp3" automatically.
   It will start playing 2 seconds after she clicks "Yes" on the hug question.

------------------------------------------
STEP 3: SET THE REAL PASSWORD
------------------------------------------
1. Open geechu_birthday.html in a text editor.
2. Find this line near the bottom:
       const CORRECT_PASS = "123456";
3. Change "123456" to her actual date of birth, e.g. "14021999"

------------------------------------------
STEP 4: OPEN / SHARE THE WEBSITE
------------------------------------------
- To preview: just double-click geechu_birthday.html to open it in your browser.
- To send it to her: zip this whole folder and share it, then she should
  unzip it and open geechu_birthday.html the same way.
- For the best experience (works on her phone too), you can host it for free on:
  Netlify Drop (netlify.com/drop) — just drag and drop this folder.

Happy Birthday to Geechu! 💕
