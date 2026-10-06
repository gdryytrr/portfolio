# Eighty6ix video editing portfolio

Static GitHub Pages version of your portfolio.

## Publish
Create a public repository named portfolio under gdryytrr. Upload index.html and portfolio.js into the repository root. In Settings > Pages, choose Deploy from a branch, main, and / (root), then Save. GitHub will display the live URL when publishing completes.

## Add videos
Edit portfolio.js. Add one object per video to the videos array, separated by commas:

```js
{
  title: "My new edit",
  url: "https://drive.google.com/file/d/YOUR_FILE_ID/view",
  embed: "https://drive.google.com/file/d/YOUR_FILE_ID/preview",
  category: "Short-form",
  description: "Pacing, captions and sound design"
}
```

For YouTube, use embed: "https://www.youtube-nocookie.com/embed/YOUR_VIDEO_ID". For a direct MP4/WebM, set embed: null and url to the video link. Use the matching video ID in each URL.

Commit the changes to update the published site. This static version has no in-page editor or backend. Your current hosted portfolio stays available during migration.
