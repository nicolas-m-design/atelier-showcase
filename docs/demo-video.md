# Atelier demo video

The 33-second video shows five Robot UI screens, the linked UI library and the preview-source chooser. It removes the zoom-control demonstration and uses the actual macOS arrow cursor.

## Recording

Recorded on 22 October 2026 using real local Atelier controls and a private capture fixture. Robot UI is a generic project label. Its five pages and UI library come from Marvin’s unmodified fictional fleet prototype. The screen manifest is curated into Operations and Workspace rows; product code remains in its own project.

The video is an edited walkthrough: an 18-second board/library take, a three-second held cutaway of the actual native macOS branch menu, and a 12-second branch start/stop take. The menu is captured UI, not a drawn replacement. Local main, codex/fleet-review and codex/library-review refs are real demo refs with identical content; no design differences are implied. Starting a branch runs Atelier’s committed-export recipe, validates its manifest and displays its commit. Stop returns to Working preview.

Browser frames are sampled against elapsed wall time and placed on a 30 fps timeline without speeding up the app. Short input calls leave sampling gaps. The automation marker is removed from an empty part of the project rail. A real NSCursor.arrow asset, with its native hotspot, follows authored paths to logged action positions; these paths are illustrative, not mouse telemetry. Captions sit below the interface.

Delivery: silent H.264 MP4, 1710 × 1000, 30 fps, 33 seconds, approximately 0.8 MB, yuv420p and fast-start. Browser sRGB pixels and the ICC-converted native capture are transformed to Rec.709 limited range. The poster is decoded from the final movie at two seconds, converted back to sRGB and tagged with an ICC profile.

## Review

The pre-recording critical pass required a compact board, readable library sections, actual branch options, a verified branch start/stop, and honest demo-branch scope. The finished file fully decodes all 990 frames and passes format, dimensions, rate, silence, fast-start and Rec.709 checks. Settled and transition frames were inspected for loading, clipping, cursor duplication and unrelated content. This is a feature demonstration, not a performance benchmark or a seamless loop.

Raw takes, event logs, native cursor provenance, reproduction scripts and private source/build identity stay local. The public repository contains reviewed media and showcase documentation only.

## Transcript

- **0–4 seconds:** Five Robot UI screens appear in Operations and Workspace groups.
- **4–8 seconds:** Open UI library and review its colour foundations.
- **8–12 seconds:** Choose Typography to inspect the product’s text styles.
- **12–18 seconds:** Choose Dashboard charts to inspect its working components.
- **18–21 seconds:** A native menu cutaway shows Working preview, main and two local review branches.
- **21–23 seconds:** codex/fleet-review is selected; Start preview is available.
- **23–29 seconds:** Start the branch preview. Atelier prepares it and displays the branch and commit.
- **29–33 seconds:** Stop the managed preview and return to Working preview.

## Public player

The README poster opens a native HTML video player on GitHub Pages. Native controls, download and transcript remain available, with no scripts, account, analytics or external embed. GitHub’s MP4 file page is download-only.
