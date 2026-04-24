# Tilt Shift — Assets needed

Drop these files in this folder. `tiltshift.html` already references them — placeholders fall back gracefully until the real files are in.

## Marketing & gallery

| Filename | Usage | Recommended size |
|---|---|---|
| `tiltshiftMain.jpg` | Card thumbnail on `index.html` (Work grid + Talks & Resources) | 1600×900 (16:9), ~250 KB |
| `tiltshiftVideo.mp4` | Hero video on `tiltshift.html` | 1080p, H.264, ~10–30s loop, muted, <8 MB |
| `tiltshift-poster.jpg` | Fallback poster for the hero video | 1920×1080 |
| `tiltshift1.jpg` … `tiltshift6.jpg` | Gallery screenshots (6 images) | 1920×1080 |

## Inline documentation screenshots

These appear inside the doc sections to illustrate options and UI. 16:9 recommended.

| Filename | Shown in section | Content |
|---|---|---|
| `doc-install.jpg` | Installation | URP Renderer asset with Miniature Camera + Time Control features added |
| `doc-inspector.jpg` | TiltShiftRenderFeature | Full custom inspector, collapsible sections visible |
| `doc-timecontrol.jpg` | TiltShiftTimeControlFeature | Time Control inspector — Game Speed + Frame Skip |
| `doc-focus-zones.jpg` | TiltShiftSettings | Diagram / in-game shot with near / focus / far zones labeled |
| `doc-presets.jpg` | TiltShiftPreset | Inspector with the preset dropdown open, showing the 5 built-in presets |
| `doc-depth-texture.jpg` | Troubleshooting | URP Renderer asset zoomed on the Depth Texture checkbox |
| `doc-debug-overlay.jpg` | Troubleshooting | Debug mode active — green / red / blue zones visible in the Game view |

## Optional (Asset Store submission)

- `tiltshift-icon.png` — 160×160 square icon
- `tiltshift-key.jpg` — 1950×1300 key image

## Notes

- Missing files show an elegant gradient placeholder with a mono-font label — no broken icons.
- Clicking any inline doc screenshot opens it in the lightbox.
- To replace a placeholder: just drop the file in. No HTML edit needed.
