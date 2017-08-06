# MergeKeys
Merge Netwok Hotkeys in Autohotkey (AHk)

Use at your own risk

<b>LATEST CHANGES</b>

8/16/2012 Beta 2.11
-Added support for space bar hotkeys (Random beta keys tab)
-Adjusted fold code for very small tables

<b>PAST CHANGES</b>

6/16/2012 Beta 2.10
-Fixed bug introduced in 2.09 that caused delay when using action hotkeys on small tables

6/16/2012 Beta 2.09
-Fixed auto-close for SNG/tournament registration/de-registration pop ups broken by last Merge update
-Fixed bug with check, call, bet, raise, fold, all-in hotkeys in big windows (hopefully this takes care of it)

6/14/2012 Beta 2.08
-Fixed bug with check, call, bet, raise, fold, all-in hotkeys

6/14/2012 Beta 2.07
-Fixed issue that caused mousewheel functionality to fail
-Fixed/optimized pot betting functionality (Aero theme, classic will be updated in next version)
-Fixed fold/bet/call issues on smallish tables
-Various minor adjustments

6/11/2012 Beta 2.06
-Fixed/changed SNG/tourney reg functionality
-Fixed issue that caused mousewheel functionality to fail
-Fixed/optimized pot betting functionality

6/10/2012 Beta 2.05
-Added check and call hotkeys do both option
-Fixed some test code left in last version that caused unexpected behavior
-Optimized pot betting (still needs more fixing)

6/9/2012 Beta 2.04
-Fixed mousewheel functionality
-Fixed virtual mousewheel functionality
-Fixed stack hotkey functionality
-Fixed cascade functionality
-Made adjustments to pot betting
-Eliminated things in the UI that are no longer necessary for Merge 6.0

6/8/2012 Beta 2.03
-Added sit back in automatically (Random Beta Keys tab)
-Fixed auto-close for tournament de-reg windows
-Fixed mouse hotkey assignment issue
-Fixed cash game buy-in window handling (cash)
-Likely fixed call hotkey button issue experienced by some

6/7/2012 Beta 2.02
-Fixed issue with auto-fire pot bets (for real this time)

6/7/2012 Beta 2.01
-Fixed issue with auto-fire pot bets

6/7/2012 Beta 2.00 (first Merge 6.0 client compatible release)
Should be working:
-Everything on the first tab
-Layout manager
-SNG/Tourney buy in window handling
-Timebank
-Next/last table keys
-Cash game buy in window handler
-Activate window under cursor
-The buy in window handler shouldn't close the tournament rebuy window (or anything else) any longer
-More?

10/29/2011 Beta 1.64
-Layout manager redone (old layouts will need to be redone)
-Table frame and auto-activate lag issue fixed

9/20/2011 Beta 1.63
-Eliminated forced upgrades
-Added news popup

9/19/2011 Beta 1.62
-Added option to close SNG win pop ups

9/18/2011 Beta 1.61
-Fixed mousewheel lag on mini tables

5/18/2011 Beta 1.60
-Added cascade table hotkey
-Enabled fold check box un-click for Black chip
-Adjusted table frame
-Fixed all-in, which was broken in 1.59
-Optimized a few other functions
-Disabled auto-click bet amount due to a couple reports of it causing unwanted min-raises

5/14/2011 Beta 1.59
-Fixed bug that was causing table frame to appear around lobby
-Fixed issue introduced in one of last few versions that was causing cursor not to move to active table (when that function is on) if the lobby was the last active window
-Adjusted pot betting auto-fire
-Made adjustments to auto click bet amount box, as there were two reports of it auto-raising rarely
-Added auto-open option for MergeMods

5/10/2011 Beta 1.58
-Fixed bug that was causing table frame to appear and stay in one spot when frame active table off
-Fixed issue introduced in one of last two versions that caused mouse to move to top left of windows when auto-fire pot betting buttons used
-Fixed stack tables function to eliminate stacking non-Merge windows (hopefully)
-Adjusted some other functions

5/10/2011 Beta 1.57
-Fixed bug that was causing table frame to use excessive amount of memory
-Table frame now resizes with active window

5/9/2011 Beta 1.56
-Eliminated manual user name/client name setup
-Fixed issue with some tournament lobbies being recognized as tables
-Adjusted/optimized pot betting
-Added Tournament/SnG Register button (only works in lobby)
-Added SnG pop-up window closer

5/5/2011 Beta 1.55
-Added an auto setup function for client/user name
-No longer need to do mouse setup for some Merge skins or redo on others when changing interface colors
-Added next/last windows hotkeys
-Optimized a lot of older functions
-Fixed/optimized mousewheel on mini tables
-Numpad hotkey issue fixed
-Checking is free bug should be fixed
-Fixed check/call issue on mini tables that was causing check boxes to be clicked when buttons not active
-Fixed issue with some functions that caused unexpected behavior in non-table Merge client windows

4/6/2011 Beta 1.54

-Fixed some performance issues
-Fixed auto buy in, which was broken by last Merge release
-Reintroduced auto accept when checking is free (may be buggy)

3/14/2011 Beta 1.53

-Fixed problems introduced in 1.51 and 1.52

3/12/2011 Beta 1.52

-Fixed a bug that was causing Bet/Raise not to work in certain circumstances
-Cleaned up some minor bugs

3/12/2011 Beta 1.51

-Fixed "Click Bet Amount Box" hotkey
-Made Minimize MergeKeys to tray optional (Random Beta Keys tab)
-Added link to setup video to Player Setup tab
-Fixed an issue that popped up occasionally with mouse hotkeys

3/9/2011 Beta 1.5

-Added auto time-bank
-Added Buy in window handler
-Added activate table with mouse over
-Cleaned up a lot (all?) errors caused by Merge 5.0 release

11/11/2010 Beta 1.31

-Fixed bug that screwed up hotkeys on tables in mini mode

10/25/2010 Beta 1.30

-Major rewrite of code for better efficiency
-Added all-in to mouse buttons
-Fixed fold issue (on a couple of tested machines)...let me know if there are issues
-Temporarily disabled Auto-check functionality (working to improve for future release)

9/1/2010 Beta 1.29

-Tweaked a couple things that should improve performance.
-Combined Standard and Mini versions into one exe.
-Fixed error in stack mode....still haven't debugged fully, use at your own risk.

7/12/2010 Beta 1.28

-Error that caused table switching problems corrected
-Mouse wheel...custom colors "Execute" button enabled on Player Setup tab.....for real this time.

6/11/2010 Beta 1.27

-Auto checking works if "Auto Check" is on (only if using fold hotkey).
-Mouse wheel...custom colors "Execute" button enabled on Player Setup tab.
-Error that caused mouse to become totally unresponsive if "Bet/Raise" hotkey was pressed when no value in bet amount box corrected.
-Error that caused move mouse to active table/frame active table to work on some non-table windows corrected.
-Fixed a bug I carelessly introduced in one of the last couple releases that caused the layout manage not to work properly sometimes for 10+ table layouts.

3/16/2010 Beta 1.26

-Fixed issue with table frame randomly popping up around other windows and the pot betting buttons not working under certain circumstances
-Fixed issue with fold hotkey.
-Included my table layouts in the Misc file....if you have a 1920x1200 monitor, all you have to do is move the layout.txt files over to the Setup Files folder.

3/11/2010 Beta 1.25

-Fixed issues with table frame not closing when program closed
-Added a version checker....will get a message box telling you a new version is available
-Now includes installer.
-If you have an earlier version installed, will attempt to move settings file and table layout files from c: to "setup files" subdirectory.
-Corrected error that broke pot betting when auto-fire option was on (forgot to take out test code).

3/9/2010 Beta 1.24

-Added support for Draw/Stand Pat for draw games....currently resides in the "Random Beta Keys" tab.

3/8/2010 Beta 1.23

-Fixed a couple issues that were causing problems exiting the app and with performance in general.
