# Sublime Text 3 Installation Guide
* 1. Install <strong>Sublme Text 3</strong> from http://www.sublimetext.com/3
* 2. Check for <strong>Node.js</strong> in “Programs and Features” on your pc, if none install it from here https://nodejs.org/
* 3. Install <strong>Package Control</strong> from here https://packagecontrol.io/installation: In View > Show Console and than paste the code from the link.
* 4. For the rest of this guide we’ll mostly use Ctrl+Shift+P key combination, after that write in the opened field Install Package, press Enter, write the name of the package we want to install and Enter again.
* 5. If you’ve already installed Sublime, you could check the installed packages like this: Ctrl+Shift+P, then write List Packages
* 6. So we’ll start with installing <strong>Emmet</strong> like written in point 4. More about Emmet here http://emmet.io/
* 7. Install <strong>SublimeLinter</strong> (point 4). SublimeLinter will help you write cleaner, better, more bugfree code! After the full install (including point 11) you should see yellow (warnings) and red (errors) points in your CSS and JS code.
* 8. Open Windows Command Prompt and write this code and press Enter:
```
npm install g csslint
```
* 9. Wait a bit for the code to process and write this, press enter and wait for the output again:
```
npm install g jshint
```
* 10. Install <strong>SublimeLinter-csslint</strong> (point 4).
* 11. Install <strong>SublimeLinter-jshint</strong> (point 4).
* 12. Install <strong>Super Calculator</strong> (point 4). More about this package here https://github.com/Pephers/SuperCalculator
* 13. Final (optional) step: Ctrl+Shift+P, write Preferences: Settings User, press Enter, replace the code you see with this one, save the file:
```
{
"color_scheme": "Packages/User/SublimeLinter/Monokai (SL).tmTheme",
"translate_tabs_to_spaces": true,
"highlight_line": true,
"fade_fold_buttons": false,
"ignored_packages":
[
"Vintage"
]
}
```
This step is for some visual enhancements.
* 14. Install <strong>HTML-CSS-JS Prettify</strong> (point 4).
