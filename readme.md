# FFCompact…
FFCompact is a simple `userChrome.css` stylesheet that removes all the horrible padding in the navigation bar and the title bar on the latest MacOS version of Firefox. It is untested on other operating systems.

![Preview](preview.png)

Enjoy!

## Setup…
Navigate to `about:config` in the address bar and accept the risks. Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and toggle it to `true` (by double clicking on it).

Put `userChrome.css` in `~/Library/Application Support/Firefox/Profiles/<ProfileID>/chrome` and start Firefox or restart Firefox if it is running.
