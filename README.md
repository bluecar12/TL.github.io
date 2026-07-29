# The Wedding Chronicle — GitHub Pages Site

A simple, elegant static site themed like a classic newspaper with wedding-style typography.

## Theme

- **Colors**: Warm paper cream (`#f7f1e3`), deep ink black, soft brown accents — inspired by aged newsprint.
- **Fonts**:
  - **Great Vibes** — flowing script for the main title (wedding feel)
  - **Playfair Display** — elegant serif for headings
  - **Libre Baskerville** — classic readable serif for body text (newspaper feel)

## Contents

- Featured video player (replace the sample with your own)
- Two customizable links (gallery + RSVP as examples)

## Deploy to GitHub Pages

1. Create a new repository on GitHub (or use an existing one).
2. Upload `index.html`, `style.css`, and this `README.md`.
3. Go to **Settings → Pages**.
4. Under **Source**, select the branch (usually `main`) and `/ (root)`.
5. Save. Your site will be live at `https://YOUR_USERNAME.github.io/REPO_NAME/`.

## Customize

### Change the video

In `index.html`, find the `<video>` tag and replace the `src`:

```html
<source src="YOUR_VIDEO_URL.mp4" type="video/mp4">
```

Or use a YouTube embed (uncomment the iframe and replace `YOUR_VIDEO_ID`):

```html
<iframe 
  src="https://www.youtube.com/embed/YOUR_VIDEO_ID" 
  ...>
</iframe>
```

### Change the links

Edit the two `<a href="...">` elements inside the “Important Notices” section.

### Change the title / text

Edit the text in the masthead (`h1`, tagline, edition) and captions to match your event.
