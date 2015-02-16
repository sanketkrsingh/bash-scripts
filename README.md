# dmenu_mpd
Shell script for perfoming operations on mpd via dmenu and mpc client

Features:
* dmenu_mpd helps you to perform every single fuction of mpc via interactive dmenu
* You may also view and download lyrics of song being played.
* It simply decrease the access time for playing music, searching & loading playlist etc... 

Prerequisite:
* mpd
* mpc
* dmenu
* glyrc

Usage:
* First change variable **MPCLYRICSDIR** content i.e. the path to your lyrics directory
* Bind this script with some keyboard shortcut
* Once invoked you can perform all the mpc specific commands
* MPC command can be executed with or without the STDOUT being displayed.
     * If STDOUT is not required, execute mpc commands normally Ex:
       * *mpc stop*
       * *mpc repeat* etc.
     * If STDOUT is required, add @ as suffix to mpc command. Ex:
       * *mpc ls @* (or) *mpc ls@*
       * *mpc playlist@* (or) *mpc playlist @* etc.
* Use "*mpc lyrics*" for displaying lyrics (excluding " quotes)
* It searches lyrics via glyrc and download it to specified directory
   mentioned in variable **MPCLYRICSDIR**
   
   Thats's all,
   Thanks...
