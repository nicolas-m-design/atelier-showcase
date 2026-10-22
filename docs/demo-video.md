# Atelier demo video

The 36-second video records Atelier running locally with Marvin’s fictional drone fleet. It shows canvas pan and zoom, sidebar focus, entry into a live preview, switching from Warehouse 1 to Warehouse 2 and back, and exit to the grouped canvas.

## Recording

Recorded on 22 October 2026 in Chrome at 1710 × 930 CSS pixels, using the real application controls and an isolated project list containing only Marvin. The preview uses its authored 1440 × 900 viewport. The product and its automatic fleet clock run normally.

The final take is continuous. Browser frames were sampled against elapsed wall time and placed on a 30 fps timeline without speeding up the app. Only 17 ms of unused tail was omitted. A pointer with smooth approach paths was added to the logged input positions because the tab capture omits the native cursor. These paths illustrate the actions; they are not recorded mouse telemetry. Four short captions appear in a separate band below the captured interface.

Delivery: silent H.264 MP4, 1710 × 1000, 30 fps, 36 seconds, approximately 1.3 MB, yuv420p and fast-start. The sRGB composition was transformed to Rec.709 limited range. The PNG poster was extracted from the encoded video at two seconds, converted back to sRGB and given an ICC profile.

## Review

A separate pre-recording critical pass narrowed the tour to established drone screens, required readable pauses and explicit mode changes, and required verification of GitHub playback. Aircraft inspection was tried during rehearsal; browser-capture compositing problems made switching warehouses the clearer final action.

The finished export was fully decoded: all 1,080 frames passed the format, dimensions, rate, silence, fast-start and Rec.709 metadata checks. The first export omitted two color metadata fields; the final file corrects those fields without changing the transformed image pixels. Playback was checked at 960 px wide through the ending, and transition frames were inspected for loading states, clipping, unrelated windows and unintended content. The overview establishes screen relationships; the existing stills remain useful for closer inspection.

The public repository contains only the reviewed media and showcase documentation. Raw takes, capture events, reproduction scripts and private source/build identity are retained locally. No application source, machine registry or project setup files are published.

## Transcript

- **0–11 seconds:** Pan and zoom across Analytics and Settings screens on Atelier’s canvas.
- **11–15 seconds:** Choose Drone fleet overview in the sidebar to focus its frame.
- **15–20 seconds:** Enter the live preview. Atelier displays Exit preview controls outside the product.
- **20–26 seconds:** Select Warehouse 2. Marvin updates the map to its tank compound, inspection hall and two assigned aircraft.
- **26–29 seconds:** Return to Warehouse 1 and its active flight.
- **29–36 seconds:** Exit preview and return to the grouped canvas.

## Public player

The README poster opens a native HTML video player on this repository’s GitHub Pages site. The player has no application code, account, tracking or external embeds. GitHub’s normal MP4 file page offers a download rather than inline playback, so the direct file remains available as a separate download. The player inherits Atelier’s quiet canvas presentation and Inter typography; it adds no product interface or new visual system.
