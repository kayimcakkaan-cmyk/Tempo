TEMPO
=====

Tempo is a workout planner that runs in any modern web browser.
Build training plans, track your sets and rest periods, schedule your
week, and follow your progress over time.


FEATURES
--------
- Plan builder: add exercises with sets, reps, rest time and weight,
  then reorder them.
- Ready-made templates: chest and triceps, back and biceps, legs,
  full body.
- Workout mode: complete sets one by one. Warm-up sets are tracked
  separately.
- Rest timer with a beep and vibration when the rest ends.
- Weekly plan: assign saved plans to days of the week.
- Progress: completed workouts, day streak and a last-7-days chart.
- Records, body measurements and calendar pages.
- Share a plan as a code, and import a plan from a friend's code.
- Backup code: export all your data and restore it on another device.
- Languages: English, Turkish, German, Spanish and French.
- Light and dark theme.
- Soft click sound on buttons.


GETTING STARTED
---------------
1. Download or clone this repository.
2. Open Tempo.html in your browser (Chrome, Edge, Safari or Firefox).
3. Tap START on the welcome screen.

To use Tempo on your phone, host the file on a static web host such as
GitHub Pages and open the link. You can add it to your home screen from
the browser menu.


DATA AND PRIVACY
----------------
All data is stored locally in your browser. Nothing is sent to a server.

Your data belongs to the browser and the address you open Tempo from.
Opening it in a different browser, or from a different address, shows
an empty app. Use the backup code to move your data between devices.

"Delete all data" in Settings permanently removes everything.


GOOGLE SIGN-IN (OPTIONAL)
-------------------------
Google sign-in needs your own OAuth Web Client ID. Set it in the
GOOGLE_CLIENT_ID constant inside the file.

The page must be served over http or https (for example GitHub Pages),
and that address must be added to your Google Cloud project. It will not
work when the file is opened directly from your computer.


KNOWN LIMITATIONS
-----------------
- Only the main menu, home screen and settings are fully translated.
  The other screens are in Turkish for now.
- Rest timer notifications are not available yet. The timer uses a
  sound and vibration only.
- Vibration works in Android browsers. iOS Safari does not support it.


LICENSE
-------
Add your license here.
