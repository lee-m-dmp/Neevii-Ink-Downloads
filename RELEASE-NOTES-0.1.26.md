# Neevii Ink 0.1.26

Released 17 November 2026 · build 7ac9b8d7

- Upscaler and Enhance Detail now support ACEScg and linear-sRGB documents in 16-bit and 32-bit floating point, using the standard image-generation colour workflow.
- Float upscale results retain working colour space, output precision, source transparency and semantic viewer settings. Enhance Detail retains the native resized base and its separate enhancement history.
- Improved painting responsiveness for masked Pass Through groups containing filters such as Surface Blur, by reusing full-quality filter results during mask strokes.
- Undo/Redo and History navigation keep the adjustment mask visible while restoring the mask stroke.

Windows: unsigned x64 offline installer with the WebView2 runtime included.
Linux: x86_64 Ubuntu24.04+ / glibc2.39 offline per-user RUN installer; no root or FUSE required.

AI operations use the reviewed model input range. Model weights and ComfyUI custom nodes remain separate optional downloads; available modes and output sizes depend on the model and source dimensions.

The application source remains private. Public release files are exactly the Windows installer, Linux installer, checksums and these notes.
