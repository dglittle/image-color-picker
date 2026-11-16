# Image Color Picker

**Live: https://dglittle.github.io/image-color-picker/**

Read exact pixel colours out of an image. Paste an image (Ctrl/Cmd+V), drop it on the page, or open a file. Hover to see the RGB of the pixel under the pointer; click (or tap, on a phone) to keep a pixel's value on screen until the next click.

The values are the image's stored pixel values: the image is decoded without colour-space conversion, drawn to a canvas at its natural size with no smoothing, and read from there. Zooming only changes the display (nearest-neighbour), never the values.

A single static `index.html`, no build step and no dependencies.

MIT licensed.
