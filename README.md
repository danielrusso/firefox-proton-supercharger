## Firefox 119+ Proton Supercharger

> ℹ️ This userChrome.css tweak has been updated to work with Firefox 119.0+ as of October 28, 2023

<img width="1348" alt="Screenshot 2023-10-31 at 12 22 24 PM" src="https://github.com/danielrusso/firefox-css-minimalist-proton-tab-bar/assets/532904/54993e22-a69e-4fcb-8bac-a58bcf82ee64">

Simple userChrome.css tweak for Firefox 119+ (Proton) tab bar to make it more minimalistic while retaining the soul of Proton by doing the following:

 * Removes the shadow from the active tab.
 * Adds a slight border next to each active tab for clarity and organization.
 * Reduces the opacity of inactive tabs to make active tab easier to find.
 * Adjusts the favicons on tab bars to be 50% grayscale.
 * Always show the audio icon if a particular tab is playing audio and better highlight them

### Compatibility

Requires Firefox 119+ (has not tested with ESR) with Proton interface.

Please Note: This adjustment works best with the "Light" theme, but is also compatible with "Dark" and "Alpenglow" themes. Not tested for compatibility with any other Mozilla or third party themes.

This has only been tested on Mac OS Sonoma. Additional testing for Windows will follow at a later date. Use this file at your own risk.

### Installation
1. Enter `about:config` into your Firefox URL bar and follow the instructions in the disclaimer.
2. Search for `toolkit.legacyUserProfileCustomizations.stylesheets`; make sure this is set to `true`.
3. Enter `about:support` into your URL bar and click "Show Folder" (Windows) or "Show In Finder" (Mac OS) next to Profile Folder.
4. Create a new folder called `chrome` and copy `userChrome.css` file into that directory; this will overwrite any existing `userChrome.css` file.
5. Restart Firefox.

### Uninstallation
1. Enter `about:support` into your Firefox URL bar and click "Show Folder" (Windows) or "Show In Finder" (Mac OS) next to Profile Folder.
2. Delete the `chrome` directory or `userChrome.css` file in the user profile folder.
3. You may optionally set `toolkit.legacyUserProfileCustomizations.stylesheets` in `about:config` to `false`.
4. Restart Firefox.

### To-Do

1. Add smooth transitions for hover states.
2. Test on Windows.

### Bugs, Feature Requests, Pull Requests, etc.

Please feel free to file an issue with any of these requests. I am happy to review pull requests as well.

This is the first Firefox CSS adjustment I have made, so I am happy to also accept any recommendations and suggestions.

### License

You are free to incorporate this into any other `userChrome.css` themes so long as the terms of the license (MIT License) are maintained.
