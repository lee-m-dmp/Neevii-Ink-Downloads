# Neevii Ink 0.1.20

Faster layer merges, more precise painting and sampling, and improved text editing.

## Added

- Clip or release a layer directly from its row, with clearer indentation for clipped layers.
- Pressure shortcuts in the Brush, Eraser and Blend headers, plus a moving Clone Stamp source crosshair.
- Eyedropper Point Sample and quick average-area choices.
- Live installed-font previews in a movable browser that stays open beside the text controls.

## Fixed

- Faster layer merges, preserved clipped content, more stable History navigation and fewer merge flashes.
- Accurate one-pixel dots and continuous lines; Pencil stays hard while Brush hardness controls antialiasing.
- Sharp zoomed pixels across colour depths and inactive documents, with improved document switching.
- Eyedropper cursor alignment, Clone Stamp colours after conversion, and Current & Below sampling coverage.
- Text bounds, baseline placement, font selection and selection dragging; font-browser docking and reopening.
- Reliable mask-feather updates and prompt Space-pan hand-cursor feedback.

## Downloads

Exactly two installers: Windows x64 with the offline WebView2 runtime, and Linux x86_64 as an offline per-user `.run` installer. Verify downloads with `SHA256SUMS.txt`.

Windows is unsigned and may show a publisher prompt. Linux targets Ubuntu 24.04 or newer (glibc 2.39).

Build: `6b06e5b3fea6ec34bc0625e28f56ed90b3494547`, version `0.1.20`. Application source remains private. WSL2 checks do not replace a native Ubuntu physical-tablet test.
