# unframe

A tiny tool that pulls a GIF apart. Open a GIF, flip through it one frame at a time, and save any frame as a PNG.

## How to use

1. Open a GIF by clicking the preview area or dragging a file onto it.
2. Step through the frames with the arrow buttons, the slider, or the left and right arrow keys.
3. Hit Save frame to export the current frame as a PNG.

The frame counter, size and frame delay are shown under the preview.

## Run it

**In a browser:** open `index.html`. That's it, nothing to install.

**As a Windows app:** grab `unframe.exe` from the Releases page and run it.

## Build the exe yourself

You need Python on Windows. Put `index.html`, `app.py`, `unframe.ico` and `build.bat` in one folder and double-click `build.bat`. The exe ends up in `dist/unframe.exe`.

## Notes

- GIF files only.
- The font (Nunito) loads from Google Fonts, so it only shows up when you're online. Offline it falls back to a similar system font.
- Everything runs locally. Your GIFs are never uploaded anywhere.

## Credits

Made with credit to euro: https://github.com/yooroh
