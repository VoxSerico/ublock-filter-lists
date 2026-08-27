# YouTube annoyances filter list

Filter list for annoyances in YouTube's desktop layout.

* Remove the pink gradient from the progress bar.
* Restore the progress bar's original red color.
* Fix horizontal scrollbar sometimes appearing in fullscreen.
* Remove shorts shelf in Home.
* Remove shorts shelf in Search.
* Remove shorts in Search.

## Installation ([uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/))

Manually copy and paste one url per row because github doesn't allow `abp:` protocol links:

1. Open the uBlock Origin extension's dashboard.
2. Click on **Filter lists**
3. Scroll all the way down and click on **Import...**
4. Paste in the URLs of raw filterlist file(s), one per row: 
```txt
https://raw.githubusercontent.com/VoxSerico/ublock-filter-lists/refs/heads/master/youtube-no-most-relevant
https://raw.githubusercontent.com/VoxSerico/ublock-filter-lists/refs/heads/master/youtube-bugfixes
https://raw.githubusercontent.com/VoxSerico/ublock-filter-lists/refs/heads/master/youtube-no-pink-progress-bar
https://raw.githubusercontent.com/VoxSerico/ublock-filter-lists/refs/heads/master/youtube-no-mixes
https://raw.githubusercontent.com/VoxSerico/ublock-filter-lists/refs/heads/master/youtube-no-shorts
```
5. Click **Apply changes**

The filter list should now appear under the **Custom** subheading. Refresh any YouTube browser tabs to see the changes.
