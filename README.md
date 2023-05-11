# AOTY Add-ons

Hello. Here is a few different scripts I have made for AOTY (albumoftheyear) compiled into one big script with a settings menu for all of them.

Note: If you already have other of my scripts installed, remove it, it will bug out


# Features
## Unrounded Scores
AOTY scores as of now are rounded to have no decimals. This script removes that rounding and lets you put however many decimals you would like it to display.

### Unrounded Scores Settings:
- Toggle (On/Off) [Default: On]
- Decimals to show on main album pages (Int) [Default: 1]
- Font size to show on main album pages (Int) [Default: 39]
- Decimals to show on small album previews (Int) [Default: 2]
- Font size to show on small album previews (Int) [Default: 18]

## Hide Scores
This script was made with the idea that sometimes seeing album scores before listening to said album can influence your thoughts on it and set higher/lower expectations. This script attempts to fix that by hiding all scores, track ratings, and must hear badges when enabled.

### Hide Scores Settings:
- Toggle (On/Off) [Default: Off]
- Show score if already rated (On/Off) [Default: On]
- Hide critic reviews (On/Off) [Default: Off]
- Score replacement text (Str) [Default: N/A]

## Best Tracks Highlighter
If tracks are above a certain score with a certain amount of ratings they will be bolded.

### Best Tracks Highlighter Settings:
- Toggle (On/Off) [Default: On]
- Minimum score to bold (Int) [Default: 90]
- Minimum number of ratings to bold (Int) [Default: 25]

## Rated Album Shuffle
Script to select a random album from your (or someone else's) ratings. This was made to find a random album to relisten to.

### Rated Album Shuffle Guide
- Go to a user's ratings page (Example: https://www.albumoftheyear.org/user/Rob/ratings/)
- Make sure you are on the first page of that user's ratings.
- Click backslash once, you will then be taken to a random page of the user's ratings.
- Click backslash one more time and you will be redirected to a random album from that page.

### Rated Album Shuffle Settings:
- Toggle (On/Off) [Default: On]
- Keybind (Int) [Default: 220 (Backslash)]

For the keybind you must enter the key code for the key you would like. If you do not know how to find this go to https://keycode-visualizer.netlify.app.

## Average Artist Rating
Script that automatically calculates a user or critics average rating of an artist when viewed.

### Average Artist Rating Settings:
- Toggle (On/Off) [Default: On]

## Tracklist Sorter
Adds a button to sort a tracklist by the highest rated songs.

### Tracklist Sorter Settings:
- Toggle (On/Off) [Default: On]

## Tracklist Score Average
Adds text to see the average rating of songs on a tracklist and also your personal average.

### Tracklist Score Average Settings:
- Toggle (On/Off) [Default: On]
- Decimals to Round (Int) [Default: 2]

## Quick Add Tags
Lets you quickly add a tag just by pressing enter.

### Quick Add Tags Settings:
- Toggle (On/Off) [Default: On]

## Quick Track Adder
Adds an option add tracks faster by being able to go to the next section you need to fill out whenever the enter key is pressed instead of manually clicking it. Also adds a feature that adds the rym URL for the album on the "Add Tracks" section of the page.

### Quick Track Adder Settings:
- Toggle (On/Off) [Default: On]

## Quick RYM URL
Feature I use to get track times to add from RYM faster. The text here would normally be quite long so here is a link to a pastebin containing all the info: https://pastebin.com/raw/C774Jb4f

### Quick RYM URL Guide
- The first option just adds a redirect to the "Add Tracks" text in the corrections area.

- The second option automatically the RYM URL to your clipboard. 

- The third option makes it so it only does the previous steps if the page does not return a 404. 

Steps for the third option to work:
1. The first time you use it you must go to the corrections page you are adding track lists to
2. Refresh it once if nothing pops up.
3. It should open a page asking for permission.
4. Click "Always allow domain" then it will work.

Note: This feature is not perfect and was mainly made for myself, if you have any issues with it at all be sure to let me know.

### Quick RYM URL Settings
- Toggle Quick RYM URL (On/Off) [Default: Off]
- Toggle Automatically Copy RYM URL (On/Off) [Default: Off]
- Toggle Validate RYM URL (On/Off) [Default: Off]

## Better Rating Colors
Adds rating colors that more accurately represent the score. This option adds 10 different colors based on the rating while the normal has only 3.

### Better Rating Colors Settings:
- Toggle (On/Off) [Default: Off]
- Score of 1-9 Color (Str) [Default: #D76666]
- Score of 10-19 Color (Str) [Default: #E07D70]
- Score of 20-29 Color (Str) [Default: #E2956F]
- Score of 30-39 Color (Str) [Default: #E5B56E]
- Score of 40-49 Color (Str) [Default: #E2BC85]
- Score of 50-59 Color (Str) [Default: #D6DB7D]
- Score of 60-69 Color (Str) [Default: #B3DD7C]
- Score of 70-79 Color (Str) [Default: #9AE27D]
- Score of 80-89 Color (Str) [Default: #90E27D]
- Score of 90-100 Color (Str) [Default: #86E27D]

## Better Album Lengths
Adds seconds to the Total Length section on albums.

### Better Album Lengths Settings:
- Toggle (On/Off) [Default: On]


# Additional Notes
If you have any suggestions, notice any bugs, or have any feedback you can create an issue on this repository.
