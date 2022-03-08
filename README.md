Open a terminal and change directory (cd) to the result found by searching with Alfred limiting itself to folders.

Download from releases.

This workflow uses some code from https://github.com/raguay/MyAlfred/blob/master/AlfredBrowserToolbox.alfredworkflow and https://github.com/LeEnno/alfred-terminalfinder.

I don’t like tabs for terminals so it is intentional that each terminal is in its own window. If you want to see a script with support for opening in tabs, take a look at https://github.com/LeEnno/alfred-terminalfinder.

	bt 	→ 	searches for a dircectory and opens it in a 
			terminal
	bf 	→ 	searches for a directory and opens it in a 
			finder
	bft 	→ 	opens a terminal with the current directory 
			which finder shows
	btf 	→ 	opens a finder showing the current directory 
			in your terminal

Set the variable term_type  (click on the "Configure workflow and variables" button [𝓍]) to "Terminal" (without quoates) to work with Terminal.app or "iTerm2" to work with iTerm2.app. The scripts will only work with recent version of iTerm2 which implement the newer applescript API.

Changes:

Only one really. Instead of using the "Reveal file in Finder" function built in it's using AppleScript to open the folder and is now equivelent to the "Open File" action triggered with the spacebar.

Enjoy bananas.
