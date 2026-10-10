KAM KAM: YOUR OWN COPY
======================

This folder is the whole app. It needs no account and works offline.
Your progress is saved on whichever device and browser you use it in.

WHAT'S IN THE FOLDER
   index.html             the app itself (fonts included)
   listen-....mp4         the audio for the Listen tab (all recordings in one file)
   sw.js                  keeps it working offline
   manifest.webmanifest   name and icon for the home screen
   icon-180.png, icon-192.png, icon-512.png, icon-maskable.png   the kam kam icon

UPDATING A COPY YOU ALREADY HOST (for example on GitHub Pages)
   Upload all of the files above and replace the old ones. Your progress
   stays, because it lives in your browser, not in these files.
   The audio file's name changes whenever the recordings change, so an
   older listen-.... audio file may still be there. It does no harm, but you
   can delete it to save space.
   The first time you open the app after updating, it may still show the
   old version. Close it and open it again to get the new one.

PUTTING IT ON A PHONE FOR THE FIRST TIME
   Phones won't run an app straight from a downloaded file, so the folder
   needs a web address first. Any free static web host works.

   GitHub Pages (free, permanent)
   - Make a free account at github.com and create a new public repository.
   - Use "Add file" > "Upload files" and upload everything in this folder.
   - Go to Settings > Pages, choose "Deploy from a branch", pick "main",
     and save. After a minute or two your app is at
     https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/

   Then open the address on your phone:
   - iPhone (Safari): Share > Add to Home Screen.
   - Android (Chrome): menu > Install app (or Add to Home screen).
   It gets its own icon, opens full screen and works without internet.
   The audio is saved for offline use too, the first time the app loads
   with internet (it is about 3.5 MB).

MOVING YOUR PROGRESS
   In the app: More > Back up your progress > Copy code. Paste that code
   into More > Restore on the other device.

ON A COMPUTER
   Just double-click index.html to open it in your browser. Keep the
   audio file in the same folder so the Listen tab can play it.
