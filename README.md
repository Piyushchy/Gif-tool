# Gif-tool

A browser-based editor for cropping animated GIFs into freeform shapes and
compositing one GIF over another. The editor is a static page and does not
require a build step or server-side processing.

## Use the editor

Open [the hosted editor](https://piyushchy.github.io/Gif-tool/) or open
`index.html` in a modern browser.

### Crop a GIF

1. Choose or drop a GIF.
2. Draw a freehand shape or select Polygon and place points around the area to
   keep. Use Finish shape to close a polygon.
3. Preview frames, adjust zoom, and optionally select **Trim to shape**.
4. Select **Export GIF**, then **Download GIF**.

### Overlay GIFs

1. Select **Overlay**, then choose a base GIF and an overlay GIF.
2. Drag the overlay preview or edit its position and scale.
3. Pause playback to select and edit frames in either timeline. You can blank
   frames, skip moments, or hold a track's last frame.
4. Select **Export GIF**, then **Download GIF**.

## Privacy

GIFs are decoded, edited, and encoded locally in your browser. They are not
uploaded to a server.

## GitHub Pages

The site is published from the `main` branch's root directory. To publish a
fork, open **Settings → Pages**, choose **Deploy from a branch**, and select
`main` and `/(root)`. The site is available at
`https://<your-account>.github.io/<repository>/`.
