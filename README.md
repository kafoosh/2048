# Photo 2048

2048 played with your own photos. Each tile value (2, 4, 8 … 2048) is shown as one of your pictures, and merging two matching photos turns them into the next photo on your "roll".

## Play

Open `index.html` in a browser, or serve the folder with any static host (GitHub Pages works as-is: Settings → Pages → deploy from this branch, root folder).

- **Phone:** swipe on the board.
- **Keyboard:** arrow keys or WASD.
- **Undo** reverts your last move.

## Your photos

The roll has 11 frames, one per tile value from 2 up to 2048. Until you add your own, each frame uses a built-in sample picture.

- **Add photos** picks several images at once (on a phone this opens your photo library or camera) and fills empty frames in order.
- Tap a frame to **Replace** it, move it **Earlier**/**Later** in the order, or go back to its sample.
- On desktop you can also drag image files onto the page.
- Photos are center-cropped to a square, shrunk to 360×360, and saved in the browser's local storage on your device. Nothing is uploaded anywhere.
- Tiles past 2048 show the number on a colored tile.

Your game, best score and photos persist between visits. On a phone you can use "Add to Home Screen" to run it full screen like an app.

## Files

- `index.html` contains the whole game (HTML, CSS and JavaScript) with no build step or dependencies.
- `manifest.webmanifest` and `icon*` are for home-screen installs.
