# Neevii Ink 0.1.24

- Generate complete images with full-canvas Text to Image and Image to Image modes for compatible local and cloud models.
- Add numbered reference images for image-to-image prompts and use an expanding multiline prompt field.
- Follow model preparation and generation with real progress information and a progress bar.
- Upscale selected generations or opened canvas images into a separate larger document, with source-dependent multiplier choices and exact output dimensions.
- Choose Enhance Detail in the Upscale section to copy the visible canvas, resize it, then enhance the full image. SeedVR2 is the default, with available Qwen and FLUX Klein alternatives. Keep the resized base and enhanced layer together while preserving the original document.
- Try experimental Local Creative tiled diffusion and Context Anchored refinement options with compatible local ComfyUI setups.
- Disable unavailable local models and report missing LLaDA nodes or companion weights before submitting a job.

Local AI weights and third-party custom nodes are optional and are not included in these installers. MiniMax H3 remains experimental and subject to its upstream community licence. Cloud models require configured provider access. Output limits and available controls depend on the model and source image.

Windows x64: unsigned offline installer with WebView2 included. Linux x86_64: offline per-user installer for Ubuntu 24.04 or newer. See SHA256SUMS.txt to verify the installers.