# Image Resizer — resize to a target size for uploads

> Resize a photo to a maximum dimension in your browser and download it. Useful for meeting upload size limits in verification and onboarding forms. Nothing uploaded.

A small tool that does one thing well: A resizer that scales a photo down to a maximum width or height and hands back the smaller file.

**[▶ Open the tool](index.html)** — runs entirely in your browser; nothing is uploaded.

## What it does

Verification and onboarding forms often reject images that are too large or too high-resolution. This resizes proportionally in your browser and lets you download the result — and because it re-encodes, it also drops EXIF and GPS metadata as a side effect.

The image is processed locally and never uploaded.

## How to use it

1. Drop or choose the photo.
2. Set the maximum dimension (longest side, in pixels).
3. Download the resized copy.

## FAQ

### Is my photo uploaded?

No. It is resized in your browser and never sent anywhere.

### Does it keep the aspect ratio?

Yes. It scales so the longest side matches your limit and the shape is preserved — no stretching or cropping.

### Will resizing remove metadata too?

Yes, as a side effect. Re-encoding through a canvas produces a file with only pixels, so EXIF and GPS are dropped.

## Topics

`onboarding-tools`, `image-resizer`, `resize-image`, `image-dimensions`, `upload-size-limit`, `photo-resize`

## Related

- [FaceOnLive](https://faceonlive.com) — on-premise face recognition, liveness detection, and ID verification SDKs for developers
