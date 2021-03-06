# Google Photos Creations Auto Save

Google Photos is a wonderful tool. Of its wonders are the "creations" (aka "Auto-awesome") it generates effortlessly for you... or rather almost effortlessly.

If you happen to have a lot of these "creations" generated, the current UI (as of March 2017) has you manually click on "Save" ONE BY ONE and then scroll and click again to sae all the creations...

That's inefficient! Here is a Macro that'll do that for you. It's not perfect, but it'll easily get 90% of the job done.

# How to use

1. Install iMacros browser extension for whichever browser you use
  - Official website: http://imacros.net/
  - Firefox add-on: https://addons.mozilla.org/en-US/firefox/addon/imacros-for-firefox/
  - Google Chrome add-on: https://chrome.google.com/webstore/detail/imacros-for-chrome/cplklnmnlbnpmjogncfgfijoopmnlemp?hl=en
2. Open the macro pane by clicking on the iMacro logo likely in the top right corner of your browser.
3. Right click on "#Current.iim" -> Edit Macro.
4. Copy/paste the content of the `google-photos-imacro-batch-save.iim` file from this repo into the iMacro editor window.
5. Save, play the macro.
6. Be happy.
7. Note: if you're here it means you likely have more "creations" to save than one play/run of this macro will save. For that, there is a "Repeat Macro" option at the bottom of the iMacro pane. Set a number of runs (say, 50?), and click the "Play (Loop)" button.
8. Note 2: if you really have a lot of creations, try using the file `google-photos-imacro-batch-save-bigger-batches.iim` instead. Batches are bigger, meaning less page refreshes and more clicking.

# Caveats

1. Macro only tested on Mozilla Firefox. Supposed to be browser-agnostic. If it's not, please fix it and send a pull request.
2. If this macro goes crazy and kills your browser, photos, friends, family and/or pets, I'm not responsible. Software provided "as-is", use at your own risk.
