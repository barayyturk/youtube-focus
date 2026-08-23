# YouTube Focus Extension

For installation and everyday use, see [USER_GUIDE.md](USER_GUIDE.md).

This is a free-to-run Manifest V3 YouTube focus and content blocker. Its first
working release uses local keyword matching and does not call YouTube, an LLM,
or any paid service.

## Current behavior

- Detects the first page load.
- Detects YouTube single-page navigation through `pushState`,
  `replaceState`, `popstate`, and `yt-navigate-finish`.
- Handles regular videos, Shorts, and live videos.
- Sends the URL, detected video ID, title, and navigation reason to the
  background worker.
- Lets the user set a topic from the extension popup.
- Can use the current video title and description as a local anchor.
- Pauses and covers videos that do not match the active topic or anchor.
- Cleans up stored tab state when a tab closes.

## Load it in Chrome

1. Open `chrome://extensions`.
2. Turn on **Developer mode**.
3. Choose **Load unpacked**.
4. Select this `youtube-focus-extension` directory.
5. Open a YouTube video, then inspect the extension service worker console to
   see the navigation event.

## Free-first path

1. Use the popup and `chrome.storage.local` settings for the active topic.
2. Use the blocking overlay driven by the navigation event.
3. Use transparent local keyword rules.
4. Add optional transcript/AI support only behind an explicit configuration,
   because YouTube Data API and hosted LLM services are not guaranteed to be
   free.
