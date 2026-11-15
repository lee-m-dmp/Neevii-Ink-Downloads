# Neevii Ink 0.1.25

Released 15 November 2026 - build f5b39223

- Improved Photoshop PSD drag import, masked groups, blend modes and layer effects, including bevel and emboss.
- Faster, reliable Merge Visible and Flatten Image on the imported document, preserving transparency and avoiding a blank canvas flash.
- Clearer aligned controls for generation area, mode, output, upscale method and source; restart ComfyUI from the header menu.
- Full-canvas generation from transparent merged layers and bounded Qwen image references.
- New 1.25x, 1.5x and 1.75x upscale options. Tiled SeedVR2 and Enhance Detail support outputs beyond 8K when the selected size fits the model and output pixel budget.
- Fixed the canvas freeze when returning to the original after upscale, surrounding tile transparency during painting, and missing Upscale History in the new document.

Windows: unsigned x64 offline installer, with WebView2 runtime included. Existing publisher prompts may appear.
Linux: x86_64 Ubuntu 24.04+ / glibc 2.39, offline per-user RUN installer; no root or FUSE required.

Local model weights and ComfyUI custom nodes remain separate optional downloads. Available modes and output sizes depend on the selected model and source dimensions.

The source repository remains private. This release contains only the Windows installer, Linux installer, checksums and these notes.
