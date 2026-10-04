# Profile mission-brief intro

User-supplied MP4 and profile card, added on 2026-10-05.

- `intro-once.gif`: full 15-second video at 960 × 960 / 10 fps, followed by the supplied card. It has no looping extension and holds the last frame after playback. GIF playback has no audio.
- `mission-brief.png`: 960 × 960 static card for reduced-motion viewers.
- `mission-brief-original.png`: the unmodified 3840 × 3840 supplied card for full-resolution viewing.
- `ascii-video.mp4`: 1440 × 1440 H.264/AAC copy of the supplied video, retaining the audio and full 15-second duration.

The profile README links to the MP4 but uses the single-play GIF inline: GitHub's Markdown renderer strips custom video/script elements and cannot implement an `onended` image swap. Reloading the page can replay the GIF; browser/user animation settings can override playback.

Rebuild locally with `profile/build-intro-media.ps1`. The source files in Downloads and Temp are not modified. `palette.png` is a local build artifact, not part of the published media.
