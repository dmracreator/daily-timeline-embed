# Daily timeline embed

A no-dependency GitHub Pages embed that shows the active activity in white using `Europe/Amsterdam` time. Every other activity is grey; the highlight advances automatically at each listed start time.

## Edit the schedule

In `index.html`, edit the `items` list. Each entry is `[start time, bold label, description]`, with a 24-hour `HH:MM` start time.

## Publish for Notion

1. Create a GitHub repository and upload these files.
2. In the repository’s **Settings → Pages**, deploy from the `main` branch at `/ (root)`.
3. Copy the Pages URL (for example, `https://YOUR-USER.github.io/daily-timeline/`) and paste it into a Notion `/embed` block.
