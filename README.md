# YouTube Focus

A calm Chrome extension that helps you stay focused on one subject while watching YouTube.

YouTube Focus compares video titles and descriptions with your chosen focus topic. Videos that do not match your focus are paused and covered so you can stay with the reason you opened YouTube.

## Features

- Focus on a specific topic
- Use the current video as a focus anchor
- Block unrelated videos
- Turn Focus Mode on and off from the popup slider
- Automatically save focus settings
- Supports regular videos, Shorts, and live videos
- Uses local keyword matching
- No account required
- No external API or AI service required

## Download

Download the latest version from the [Releases page](https://github.com/YOUR-USERNAME/youtube-focus/releases).

Download the ZIP file attached to the latest release, then follow the installation instructions below.

## Installation

YouTube Focus is currently installed manually through Chrome Developer Mode.

1. Download the latest ZIP file from the [Releases page](https://github.com/YOUR-USERNAME/youtube-focus/releases).
2. Unzip the downloaded file.
3. Open Chrome and go to:

   ```text
   chrome://extensions
   ```

4. Turn on **Developer mode** in the top-right corner.
5. Click **Load unpacked**.
6. Select the unzipped `YouTube-Focus-Extension` folder.
7. Open or reload a YouTube tab.
8. Click the YouTube Focus icon in the Chrome toolbar.

## How to use it

### Focus by topic

1. Open the YouTube Focus popup.
2. Enter a topic, such as:

   ```text
   advanced quantum computing
   ```

3. Click **Save focus**.
4. Browse YouTube normally.

Videos that do not sufficiently match your topic will be blocked.

### Use a video as an anchor

1. Open the video you want to use as your reference.
2. Open the YouTube Focus popup.
3. Click **Use current video as anchor**.
4. The anchor is saved and applied immediately.

YouTube Focus uses the video's title and description to identify related videos.

### Turn Focus Mode off or on

Use the slider in the popup:

- Slider off: Focus Mode is disabled.
- Slider on: Your saved topic or anchor is applied again.

The slider saves automatically.

## Troubleshooting

### The extension says “Open a video first”

Make sure the active tab is an actual YouTube video page.

If the video was already open before installing or reloading the extension:

1. Reload the YouTube tab.
2. Open the YouTube Focus popup again.
3. Click **Use current video as anchor**.

### Nothing is being blocked

Check that:

- Focus Mode is switched on.
- A focus topic or anchor has been saved.
- You are using `www.youtube.com`.
- The YouTube tab was reloaded after installing the extension.
- Your focus topic is not empty.

### A relevant video is blocked

YouTube Focus uses local keyword matching, so it does not perfectly understand every video's meaning.

Try using a shorter or more specific topic, or use a representative video as an anchor.

## Privacy

YouTube Focus is designed to work locally in your browser.

- Focus settings stay on your device.
- No browsing history is sent to a server.
- No focus topic is sent to an external service.
- No YouTube API key is required.
- No AI service is required.

## Usage rights

This project is published without a license.

All rights are reserved by the copyright holder. You may view the source code, but you may not copy, modify, redistribute, sublicense, or use it commercially without permission.
