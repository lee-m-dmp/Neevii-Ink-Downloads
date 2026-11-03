# Neevii Ink 0.1.21

Editable group copy/paste, reliable Flatten and document closing, and reduced recovery and scratch growth.

## Added

- Copy and paste complete editable layer groups between documents with Ctrl+C and Ctrl+V.
- File → Save Backup keeps an independent document copy without changing your working filename.

## Fixed

- Newly created and duplicated groups copy without saving first; groups can move below the bottom group without becoming nested inside it.
- Flatten works on affected retained half-float documents, including editable text.
- Surviving document canvases stay visible when another document closes.
- Automatic recovery uses two rotating copies per document and skips unchanged edits. Manually kept backups remain separate.
- Inactive decoded-image caches trim to three generations within16GiB when eligible, while live documents and irreplaceable recovery data remain protected. Existing older caches and backups are preserved.

## Downloads

Exactly two installers: unsigned Windows x64 NSIS with offline WebView2, and Linux x86_64 offline per-user RUN. Linux targets Ubuntu24.04+ / glibc2.39. Verify downloads with SHA256SUMS.txt.

Frozen private application source: f364b18182a2e43a8e1679ef122d174ff418854d. Application source remains private. WSL2 qualification does not claim physical native-Ubuntu tablet acceptance.
