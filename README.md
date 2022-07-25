<h1 align="center">
  <br>
  <a href="https://i.imgur.com/JBHWXnX.jpeg"><img src="https://i.imgur.com/JBHWXnX.jpg" alt="Spreedsheet To Non-Steam Games" width="1800"></a>
  <br>
</h1>

<h3 align="left"> Fill out The Template Spreadsheet, Then Run The Application. Quickly Import Hundreds of Non-Steam Games, DRM-Free Games, Fan-Made Games, Emulated Games, or Apps into your Steam Library!
</h3>
<hr>

<h5 align="center">
• This application is Free, Open Source, and Lightweight. It also supports both Windows and Linux! <br> <br>  
• This application does NOT install onto your Computer or Steam Deck. <br> 
(which means it does not hide ANY files deep into your system, and can be deleted in a few clicks) <br> <br> 
• Great for backing up your Non-Steam Game Library in spreadsheet form. <br>  
(so you won't have to worry about loosing it, and adding the library back one by one) <br> <br> 
• Easliy share the EXACT same Non-Steam Game library across multiple devices by cloning and changing a completed spreadsheet. <br>
(ctrl+H  aka  "Find and replace" is your friend when it comes to editing a cloned spreadsheet for a diffrent devices game directories) <br> <br> 
</h5> <hr>

## Where Do I Start / How do I Download
Start by downloading and filling out the Template Spreadsheet. An example of a properly completed spreadsheet can be viewed below!

• At this time you can not turn your already existing Non-Steam Game Library into a compatible spreadsheet. <br>
• Do NOT generate your own spreadsheet from scratch and expect it to work. DOWNLOAD, EDIT, AND USE THE TEMPLATE ONE.<br>
• DO NOT delete the first row and DO NOT delete or move ANY column when filling out the Template Spreadsheet. You CAN resize the columns width for your convenience.<br>
• Spreadsheets can be opened and editied with programs such as Microsoft Excel or (the free) Google Sheets. <br>
• The Spreadsheet contains 22 Columns. <br>


## How to Fill Out Each Column on The Template Spreadsheet

The first row of the Template Spreadsheet will give you general information on what should live under each column. Expand an option below for more detailed info on each column:<br><br>
Remeber: DO NOT delete the first row and DO NOT delete or move ANY column when filling out the Template Spreadsheet.<br> 
(View a picture example of a completed speadsheet below)<br>

<details><summary><b>Column A - localconfig.VDF Location and Notes</b></summary>
Column A Row 0 is extremely important, You are REQUIRED to paste the directory of your localconfig.vdf. This file can be found ...
Here is an example of what should be in the Column A Row 0:<br><br>
C:\Program Files (x86)\Steam\userdata\119139580\config\localconfig.vdf<br><br>
(ensure the "localconfig.vdf" is on the end of the directory, just like you can see above)<br>
After that is complete, you do not need to repeat this for subsequent rows. Instead, the other rows get ignored by the app and are great for your own notes and organization. For you Steam Deck or Linux users, try this for Column A Row 0:<br>
????/Steam/userdata/119139580/config/localconfig.vdf
</details>

<details><summary><b>Column B - Application Name</b></summary>
Type out the application name, no quotes needed. Examples comes in included in the (required) template Spreadsheet file.
</details>

<details><summary><b>Column C - Steam Collections (AKA categories or tags)</b></summary>
Tags (These are also known as collections, great for grouping your games together into categoires. YOU MUST CREATE THE CATEGORIES IN STEAM FIRST, at this time this spreedsheet will not do that for you. Examples comes in included in the (required) template Spreadsheet file. If you are unsure what Steam Collections are, then leave this row empty.
</details>

<details><summary><b>Column D - Target/Exe</b></summary>
This points to the exe of the Non-Steam game/app. Type out the exe’s directory surrounded by quotes. This is also where you can point to emulated games individually which is done in a slightly different way, More info on that is located further down. Examples comes in included in the (required) template Spreadsheet file.
</details>

<details><summary><b>Column E - Start In/StartDir</b></summary>
(The folder that the exe is located in) Type the folder directory of the exe in quotes. Examples comes in included in the (required) template Spreadsheet file.
</details>

<details><summary><b>Column F - Cover Art Location</b></summary>
This column allows you to fill out the look of that Vertical "book-like" cover art which is shown in the library (AKA "p"). Type out the directory of the file of your device (example: C:\Users\Name\Pictures\Pic.png) followed by .cover, then by the file extension.
The app will copy, paste, then rename the copy of that picture into the following folder (...\Steam\userdata\USER_ID\config\grid). PNG and JPG/JPEG and GIF’s are supported
At this time the app does not support links to images but I am looking into adding this feature which will be very useful for pointing to a steamGrid photo. (Note if/when support for this feature comes it will download the image onto your device and place it in the steam folder it needs to be in to show up in your library) Examples comes in included in the (required) template Spreadsheet file. If you are unsure about what a Steam games cover art is, or don't want it applied, then leave this row empty. 
</details>

<details><summary><b>Column G - Banner (aka header) Location</b></summary>
This column allows you to fill out the Horizontal art shown in the library. Type out the directory of the file of your device (example: C:\Users\Name\Pictures\Pic.png) followed by .banner, then by the file extension.
The app will copy, paste, then rename the copy of that picture into the following folder (...\Steam\userdata\USER_ID\config\grid). One time for the steam desktop library and a second time for the steam big picture library. After Steam OS's look replaces big picture this may need to be updated. PNG and JPG/JPEG and GIF’s are supported
At this time the app does not support links to images but I am looking into adding this feature which will be very useful for pointing to a steamGrid photo. (Note if/when support for this feature comes it will download the image onto your device and place it in the steam folder it needs to be in to show up in your library) Examples comes in included in the (required) template Spreadsheet file. If you are unsure about what a Steam games banner art is, or don't want it applied, then leave this row empty. 
</details>

<details><summary><b>Column H - Hero Location (The really large banner art shown in the library)</b></summary>
This column is for applying that really wide banner art that is shown on a games launch page from the library. Type out the directory of the file of your device (example: C:\Users\Name\Pictures\Pic.png) followed by .hero, then by the file extension.
The app will copy, paste, then rename the copy of that picture into the following folder (...\Steam\userdata\USER_ID\config\grid). PNG and JPG/JPEG and GIF’s are supported
At this time the app does not support links to images but I am looking into adding this feature which will be very useful for pointing to a steamGrid photo. (Note if/when support for this feature comes it will download the image onto your device and place it in the steam folder it needs to be in to show up in your library) Examples comes in included in the (required) template Spreadsheet file. If you are unsure about what a Steam games hero art is, or dont want it applied, then leave this row empty.
</details>

<details><summary><b>Column I - Logo Location (The words/logo art shown in the library.</b></summary>
This column is for applying the logo that shows up on the launch page for the game in your library, These logos are typically the title of the game. (example: C:\Users\Name\Pictures\Pic.png) followed by .logo, then by the file extention.
The app will copy, paste, then rename the copy of that picture into the following folder (...\Steam\userdata\USER_ID\config\grid). PNG and JPG/JPEG and GIF’s are supported
At this time the app does not support links to images but I am looking into adding this feature which will be very useful for pointing to a steamGrid photo. (Note if/when support for this feature comes it will downloaded the image onto your device and place it in the steam folder it needs to be in to show up in your library) Examples comes in included in the (required) template Spreadsheet file. If you are unsure about what a Steam games logo art is, or dont want it applied, then leave this row empty. 
</details>

<details><summary><b>Column J - Icon Location/Icon</b></summary>
This column is for applying the Small "box" icon that appears next to the name your Steam library on desktop Steam (The art appears if you create a shortcut for your non-steam game on the desktop). Type out the directory of the file of your device (example: C:\Users\Name\Pictures\Pic.png) followed by .cover, then by the file extention.
The app will copy, paste, then rename the copy of that picture into the following folder (...\Steam\userdata\USER_ID\config\grid). PNG and JPG/JPEG and GIF’s are supported
At this time the app does not support links to images but I am looking into adding this feature which will be very useful for pointing to a steamGrid photo. (Note if/when support for this feature comes it will downloaded the image onto your device and place it in the steam folder it needs to be in to show up in your library) Examples comes in included in the (required) template Spreadsheet file. If you are unsure about what a Steam games cover icon art is, or dont want it applied, then leave this row empty. 
</details>

<details><summary><b>Column K - Location of Logo json File</b></summary>
A json file is used to adjust the logo position. Type out the directory of the file with the file extension. If you are unsure about what a Steam games cover art is, or don't want it applied, then leave this row empty.
</details>

<details><summary><b>Column L - App ID/ Entry ID</b></summary>
Please leave this row completely empty.  int 10 chars
</details>

<details><summary><b>Column M - ShortcutPath</b></summary>
Unknown. Might be Vestigial. It's safe to leave this row empty and appears empty in the template spreadsheet.
</details>

<details><summary><b>Column N - LaunchOptions</b></summary>
Enter any launch options here. If unsure leave this row empty as seen in the template spreadsheet.
</details>

<details><summary><b>Column O - AllowOverlay</b></summary>
This column detemns weather or not the steam overlay should be enabled or disabled. The steam overlay is that menu that appears overtop of games when the controllers home button is pressed. 0 stands for off (disabled), while 1 stands for on (enabled). This is useful as very rarely some non steam games will crash when the steam overlay is active/activated. This setting actually might also be vestigial, and require testing. The example seen in the template spreadsheet enables the steam overlay for every game, which is what users would typically want, so if you are unsure just set all your rows to 1 under this column.
</details>

<details><summary><b>Column P - AllowDesktopConfig</b></summary>
Just type either a 0 or 1
</details>

<details><summary><b>Column Q - IsHidden</b></summary>
Might be Vestigial, Just Type either a 0 or 1. Enter zero if unsure
</details>

<details><summary><b>Column R - LastPlayTime</b></summary>
Might be Vestigial, Just Type either a 0 or 1. Enter zero if unsure
</details>

<details><summary><b>Column S - OpenVR</b></summary>
I believe that this option. Just Type either a 0 or 1, If unsure enter 0
</details>

<details><summary><b>Column T - Devkit</b></summary>
Unknown. Possibley an Int Number. It's safe to enter enter zero in the rows you create under this column.
</details>

<details><summary><b>Column U - DevkitGameID</b></summary>
Unknown at this time. It's safe to leave the rows under this column empty.
</details>

<details><summary><b>Column V - DevkitOverrideAppID</b></summary>
Unknown at this time. It's safe to enter zero
</details>

## Limitations

There are a number of traits that steam does not track for Non-Steam games, that it DOES track for native steam games. So because of that, Unfortunately I could not implement them into the spreadsheet. Here is a list of the (unfortunately) unchangeable game traits (At time of writing).  

Time played (both for last two weeks and total).  Friends Playing.   % of achievements complete (duh).   Hours played.   Release Date.   Meticritic Score.   Steam Review (score).   Size on disk.   Tags used by the steam store (such as “Single-Player” “multi-player” “Coopertave Play” “Full Controller Support”, etc).    ”detailed information” (such as community hub, activity, guides, friends who play)

## How to Add Emulated Games Individually To Your Steam Library, Instead of The Whole Entire Emulators Themselves

## How to Add Custom Library Art / Where Do I Find it

## Known Issues and To-Do List

<details><summary><b>Known Issues</b></summary>
• Unknown at this time.
</details>

<details><summary><b>To-Do List</b></summary>
• Exisiting Steam Addon-Library TO Spreadsheet Functionality <br>
• Mac Support <br>
• Playnite Support <br>
</details>
