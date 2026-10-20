# Bento changelog

What changed in each version of Bento. Download the latest from the [Releases page](../../releases/latest).

## 0.13.0 — October 20, 2026

### New

- Text & image overlay: put titles, captions, logos and animated GIFs on a video. Drag to place, resize with handles, rotate, with snapping to the center and edges.
- Scrolling text: choose left, right, up or down for news tickers and rolling credits. It loops with an adjustable gap and speed.
- Text styles: any font, size, color, bold and italic, alignment, shadow, outline and a background box.
- Animated GIF, APNG and WebP images loop (or play once and hold the last frame).
- Each layer has opacity, start and end times on a timeline, and fade in/out. The preview matches the saved video exactly, and the sound is kept.
- Each layer’s bar in the timeline has grips: drag them to set when the layer appears and disappears (they snap to other layers and the video’s ends), drag the middle to move it, double-click for the whole video.
- The overlay timeline zooms with the scroll wheel, a pinch or the zoom buttons (⌘= / ⌘− / ⌘0); scroll sideways, Shift + wheel or Shift + drag to move along. The ruler shows times, and dragging stays smooth.
- Drag layers in the list or the timeline to change which one is in front.

### Improved

- The collapsed sidebar fits the window buttons exactly, with a small tab on its edge to expand it.

## 0.12.0 — October 20, 2026

### New

- Automatic updates: Bento checks once a day and shows a banner when a new version is out. Nothing installs until you choose Install and Restart.
- Settings → General → Updates: turn automatic checks on or off, or Check Now.
- Every update is signed and verified before it replaces Bento, so a damaged or altered download is never installed.

## 0.11.0 — October 20, 2026

### New

- After cleaning: see what was removed, inspect the cleaned copy, or move the original to the Trash. Clean all files in the strip at once.

### Improved

- Remove metadata is now part of Inspect: a zone under the details shows what a file contains and saves a cleaned copy.
- Remove Metadata with Bento in Finder now shows the cleaned copies in Inspect.

### Fixed

- Finder actions could miss files when the tool was already open.

## 0.10.0 — October 20, 2026

### New

- Remove metadata: save cleaned copies of photos, videos, audio and PDFs without GPS location, camera/device, author, software or tags.
- Everything or Location only, with an option to keep the date taken.
- Before and after: each file shows what it contains, and after cleaning Bento re-checks the copy and shows what was removed.
- JPEG, PNG and MP4/MOV are cleaned without quality loss; photos keep their orientation and colors.
- Remove Metadata with Bento in Finder’s right-click menu, and bento_remove_metadata for AI apps.

## 0.9.0 — October 19, 2026

### New

- Inspect: preview any file with macOS’s Quick Look (documents, images, video, audio, code and more) and see everything about it.
- Details: size, dates, Finder tags, permissions, and the website a download came from.
- Photos: camera, lens, exposure and the date taken, plus GPS with a map link. Video and audio: codecs, resolution, frame rate, bitrates and tags. PDFs: pages, author and security.
- Every Spotlight attribute, MD5/SHA-256 checksums, Copy all info, and Open in a matching Bento tool.
- Show Info in Bento in Finder’s right-click menu, and bento_file_info for AI apps.

## 0.8.0 — October 19, 2026

### New

- Player: play videos, music and photos (including animated GIFs) from one playlist, one after another.
- Slideshows: set how long each photo shows, crossfade or cut between items, loop and shuffle, fit or fill.
- Full screen presentation: controls fade away when the mouse is still. Space, ← → and Esc to control it.
- The playlist is remembered between launches. Files macOS can’t play offer a one-click Convert to MP4.
- Play with Bento in Finder’s right-click menu.

## 0.7.1 — October 19, 2026

### Fixed

- Merge preview: a photo added after a video showed as a black frame. The preview now jumps to new items and shows them fully faded in.
- Merge preview: clicking an item in the list showed a black frame at the start of its fade.

## 0.7.0 — October 19, 2026

### New

- Merge videos: join videos and photos into one video, in any order. Drag to reorder.
- Mini player: preview the whole merge exactly as it will be saved, and click any item to jump to it.
- Per-item settings: how long each photo shows, which part of each video to use, and whether to keep its sound.
- Merge output: 16:9, 9:16, 1:1, 4K or matching the first item; fit with a blurred, black or white background, or fill; fades between items.
- Merge with Bento in Finder’s right-click menu, and bento_merge_videos for AI apps.

## 0.6.1 — October 19, 2026

### New

- Presets for Trim: save how much to cut from the start and end, and a maximum length. Starters: Shorts · first 60 s, Skip first 5 s.
- Presets for Crop: save the shape and position of the crop box; it adapts to any video size. Starters: 9:16, 1:1, 4:5 and 16:9.
- AI apps can trim and crop with your saved presets too.

## 0.6.0 — October 19, 2026

### New

- Saved presets: save any tool’s settings under a name, then apply them in one click from the Presets menu.
- Ready-made presets for Compress video: Discord · 25 MB, Email · 10 MB and Instagram Reel · 1080p.
- Finder Quick Actions: right-click files → Compress, Convert, Extract Audio, or Rotate or Flip with Bento.
- Settings → Quick Actions: choose a preset for each action, and whether it starts right away or opens Bento first.
- AI apps can use your presets: bento_list_presets, plus a saved_preset option on every tool.

## 0.5.0 — October 19, 2026

### New

- Compress PDF: Small, Balanced and High presets. Keep text mode shrinks the pictures while text stays searchable.
- Flatten pages mode for scanned documents: the smallest files, with each page saved as a compressed image.
- PDF options: image resolution, JPEG quality and removing document metadata.
- AI apps can compress PDFs too, with bento_compress_pdf.

### Improved

- If a PDF can’t get any smaller, Bento says so instead of saving a bigger copy.

## 0.4.0 — October 19, 2026

### New

- Convert video: open MKV, WebM, AVI and more, and save as MP4 (H.264 or HEVC), MOV (H.264 or ProRes), MKV or WebM.
- Fast convert: when the video is already in the right codec, Bento repackages it instantly with no quality loss.
- Extract audio: save a video’s sound, or convert audio files, as MP3, M4A, WAV, FLAC, ALAC or Opus.
- Rotate / Flip: turn videos right, left or 180°, or mirror them. Fast mode is instant and lossless.
- AI apps can use the new tools too: bento_convert_video, bento_extract_audio and bento_rotate_video.

## 0.3.0 — October 19, 2026

### New

- AI apps can use Bento through MCP: Claude Desktop, Claude Code, Cursor, VS Code, Windsurf, LM Studio, Gemini CLI, Codex and Zed.
- AI tools: video info, compress, trim, crop, link info and download, with live progress sent back to the AI app.
- Settings → AI: turn AI access on, choose allowed folders, and connect apps with one click (or copy the setup).
- Folder permissions: Bento asks before an AI app uses a new folder (Allow once, Always allow, Don’t allow).
- AI activity page lists every AI request with progress, results and Stop; AI jobs also show in Compress and Download with an AI badge.

### Improved

- Your own batches and AI batches take turns, so the hardware encoder stays fast.

### Fixed

- Connecting Claude Desktop while it was open was undone when Claude quit. Bento now restarts it for you.

## 0.2.0 — October 19, 2026

### New

- Trim video: filmstrip timeline with drag handles, exact times, and Fast (lossless) or Precise (frame-accurate) cuts.
- Timeline zoom: pinch or ⌘-scroll, a time ruler and overview bar, frame stepping with ← →, and loop playback (L).
- Crop video: drag the crop box, pick 16:9, 9:16, 1:1, 4:5 or 4:3, or type exact pixels.
- Download video from YouTube, TikTok, Instagram, Facebook and 1,000+ sites, with a one-time verified setup.
- Download as MP4, MOV, MKV or WebM, or audio as MP3, M4A, Opus, FLAC, ALAC or WAV.
- Playlists expand to show the progress of every video.
- Optional browser login for private or login-only posts.
- Favorites: star a tool to pin it to the top of Home.
- What's New in Settings.

### Improved

- The sidebar shows the Bento logo and collapses to an icon rail (⌃⌘S).
- Search moved to the top of Home (⌘F).
- ⌘1–⌘6 jump to Home and each tool.
- One “Done” dialog for every tool, with Reveal in Finder and an optional Move to Trash.
- Video thumbnails skip black intros and fade-ins.

### Fixed

- The settings panel lost its margin at the smallest window size.
- A blue focus ring appeared around Home at launch.

## 0.1.0 — October 19, 2026

### New

- Compress video: Small, Balanced, High and Target size presets, plus codec, resolution, frame rate and audio options.
- Compress many videos at once, or a whole folder, with a before/after preview.
- Fast hardware encoding (H.264 and HEVC) on Apple Silicon and Intel.
- Light and Dark themes that follow macOS, plus custom JSON themes: Olive Garden Feast, Sunrise Glow and Midnight.
- Home page with tool cards, and a sidebar for switching tools.
- Bento app icon, and a DMG installer with a first-launch guide.

