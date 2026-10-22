# Bento changelog

What changed in each version of Bento. Download the latest from the [Releases page](../../releases/latest).

## 0.17.0 — October 22, 2026

### New

- Workflows, in a new Automate section: make recipes that run files through several tools in a row with one click — like “Phone video for social” (reframe, fix the sound, compress) or “Scan to searchable PDF”. Each step uses the tool’s settings or one of your presets; keep only the final file or every step’s.
- Watch folders: point a recipe at a folder, and every new file put in it is done by itself while Bento is open. Results go where you choose; originals move into a “Done” folder, and you get a notification.
- Recipe steps: Compress, Convert, Rotate, Crop to a shape, Split video, Speed, Reframe, Blur Faces, Overlay, Auto captions, Contact sheet, Sound, Extract Audio, Convert Images, Text from Image, Compress PDF, Split PDF, PDF to Images and Remove Details. A step that splits (a video into parts, a PDF into pages) sends each part through the rest of the recipe.
- AI apps can run your recipes too (bento_run_recipe).
- PDF Pages: put pictures on a page — a logo, a signature, a photo. Use the Picture tool to choose a file (click, or drag to set the size), or press ⌘V to paste a copied picture. Move, resize and turn it like any markup, and “Remove white background” makes a signature scanned on white paper sit cleanly on the page.

### Fixed

- Keyboard shortcuts in PDF Pages (⌘V, ⌘Z, ⌘D…), Subtitles and Text & Image Overlay (⌘Z, ⇧⌘Z) now work with the Thai keyboard layout and other non-Latin layouts.

## 0.16.3 — October 21, 2026

### New

- Every tool on Home has its own little hand-drawn animation: a sketch of what it does sits in the card’s corner, and when you point at a card it plays the story — a video squeezed smaller, film snipped, a page scanned into text. Hand-drawn in light and dark.

## 0.16.2 — October 21, 2026

### New

- Text from Image: copy the text out of screenshots, photos, scans and PDFs — read on your Mac, in Thai, English, Chinese, Japanese and many more. Capture from Screen (⇧⌘2) grabs text from anywhere and copies it. Keep the layout or get flowing paragraphs, edit it, save it as a text file, translate it (macOS 15), or turn a scan into a searchable PDF you can search and copy from.
- Convert Images, in a new Images section: turn HEIC, PNG, WebP and other pictures into JPEG, HEIC, AVIF, WebP, PNG or TIFF; set a quality or a size limit (“under 1 MB”); resize by longest side or percent; and remove the location or every detail. Many pictures at once, each with its own settings if you like.
- PDF Pages text boxes: click the page (or drag for the width) and type, then choose the font — including the PDF’s own — size, bold, italic, alignment, text color, and a background and border that can each be none. Drag to move, double-click to change.
- Resize and turn drawings, shapes, arrows and text boxes in PDF Pages: pick one with Select, drag a corner to resize (⇧ keeps its shape) or the round handle to turn it (⇧ turns in 15° steps).
- Change Text matches the PDF’s font: Bento uses the font itself when it’s on your Mac, loads Windows fonts like Angsana New and Cordia New from Microsoft Office, and repairs Thai text that Word saved wrongly (า read as ำ, stray spaces).
- Edit PDFs in PDF Pages: highlight, underline or strike through text, draw, and add rectangles, ovals and arrows in any color; click a line to retype it (the new words match its font and size); and fill in forms. Click a markup to recolor or delete it, and ⌘Z undoes. Everything is saved as standard PDF markups, so Preview and Acrobat can still change them.
- PDF Pages has a page view, now the default: thumbnails in a sidebar (drag its edge to make it wider and the thumbnails grow), and every page full size beside it. ↑ ↓ go to the previous or next page, and zoom with a pinch, ⌘+ ⌘− ⌘0, or Fit Width, Fit Page and 50–400%. Switch to the grid any time; its pages can now be much larger (⌘+ ⌘−) and rearrange to fit.

### Improved

- Run a tool again right away: after you close the “done” popup, the files stay in the list ready to go — change a setting or pick another folder and run them again. Files you moved to the Trash leave the list.
- PDF Pages: press Space to see the selected page larger, and Space again to close it, like Quick Look.
- Keyboard, everywhere: ← → jump 10 seconds back or ahead in every video (⇧← ⇧→ for 1 second, , and . for one frame), and ↑ ↓ go to the previous or next file in the Player and in every file list. In the Player, the volume moved to ⌥↑ ⌥↓.

### Fixed

- PDF Pages: dragging pages to reorder them works again, with a badge showing how many pages you’re moving.

## 0.16.1 — October 21, 2026

### New

- Blur Faces: Bento finds the faces in a video (on your Mac) and hides them as they move — blurred, pixelated or with a black box. Leave anyone visible with a switch, and add boxes for number plates, screens or name tags.
- Reframe & Color: turn a landscape video into 9:16, 1:1 or 4:5 for Reels, TikTok and posts without cutting anything off — a blurred copy (or a color) fills the space. Zoom and drag to frame it, and fix colors with Auto-enhance, brightness, contrast, saturation and warmth.
- Sound: fix the sound of videos and audio files — louder or quieter, even loudness (Web, Voice, TV), less background noise, fades, mute, or music under the video that dips while people talk (or replaces the sound). The picture is copied untouched.
- Trim has three modes: Keep a part (now with fade in and out), Cut out — remove ads, mistakes or waiting from the middle, with a preview that skips them — and Split, into parts every few minutes, equal parts, parts under a file size (25 MB for Discord) or at your own marks.
- HDR videos (most iPhone videos) no longer look washed out after Compress or Convert: Bento converts them to normal colors, with a tip and a switch to keep HDR instead.
- Player: hold the mouse down on the picture to play at 2× until you let go, like YouTube. A quick click still plays or pauses.
- Subtitles can translate captions into any language right on your Mac (macOS 15 or later) — for example English speech into Thai captions.
- Subtitles: use a subtitle track that’s already inside an MKV or MP4, Find & Replace across every caption, and Fix drift — set when two lines are really spoken and everything in between is stretched to fit.
- Video to Image makes contact sheets: a grid of frames from the whole video with each frame’s time and the video’s details, in one picture.
- Video to Image can give a video a cover: the frame you’re on, or any picture. Players like Apple TV, VLC, Plex and Infuse show it; nothing is re-encoded.
- Inspect can edit details: title, caption, date taken or recorded, and place for photos and videos; title, artist and album for audio; title, subject, author and keywords for PDFs. With several files, move all their dates at once (camera on the wrong time zone) or set one date. Always saved as copies.
- Speed & Reverse: make a video faster (up to 16× timelapse) or slower (down to 0.1×), slow down just one part with a smooth ease in and out like iPhone slo-mo, play it backwards or as a boomerang, and loop it a number of times or to an exact length. The preview plays it the way it will be saved, and voices can keep their natural pitch.
- PDF Pages: drop PDFs and pictures to see every page in one grid. Drag to reorder, rotate, duplicate or delete pages (⌘Z undoes), then save one PDF (merge), just the selected pages, or split it — every page, every few pages, by ranges like 1-3, 4-, or one PDF per original file.
- Turn photos and scans into a PDF in PDF Pages: each picture can be exactly its own page, or sit on A4, Letter and other paper. Double-click a picture page to move it, resize it, crop it, turn it or straighten a tilt.
- When saving from PDF Pages you can add page numbers (style, position, size, start number), lock the PDF with a password, and compress it in the same step.
- PDF to Images: save PDF pages as PNG, JPEG, HEIC, TIFF or WebP, at screen or print resolution, for all pages, the first, or a list like 1-3, 5.
- Finder Quick Actions “Combine into PDF with Bento” and “Save PDF Pages as Pictures with Bento”, and new tools for AI apps to combine, split and turn PDFs into pictures.
- Status dots in the sidebar: while you're on another page, a tool that's working (or the Player while it plays) shows a Pumpkin Spice dot on its icon, and a green dot once it finishes. The green dot goes away when you open the tool. Hover an icon to read its status.

### Improved

- Every video tool opens MKV, WebM, AVI, FLV and other formats macOS can’t read itself — Trim, Crop, Speed, Compress, Merge, Rotate, Overlay, Subtitles and Video to Image. The first time, Bento makes an MP4 copy in the background (usually seconds, nothing re-encoded) and shows its progress; after that the file opens right away. New videos are saved as MP4 next to the original.

### Fixed

- Video controls no longer disappear while you hold the mouse on the progress bar or volume slider.

## 0.16.0 — October 20, 2026

### New

- Convert, Rotate, Extract audio, Compress PDF and Download give each file or link its own settings too. With nothing selected the panel changes them all; select some (⌘- or ⇧-click, or drag a box) to change just those. A line above the settings says which files you're changing, and “Apply to All” makes them match.
- Each video in Compress has its own settings. The panel changes the video you’re previewing, or every selected video at once (⌘- or ⇧-click, or drag a box): only the option you change is copied, so their other differences stay. “Apply to All Videos” gives the whole list the same settings, and new videos start from the last ones you used.
- Video to Image: make an animation (GIF, WebP or APNG) from a few seconds, save the frame at the playhead as JPEG, PNG, HEIC, TIFF, WebP or BMP (step frame by frame with ← →), or export a sequence of frames into a folder. The panel explains every option, with a size estimate before you save.
- Multi-page PDFs and TIFF scans in Inspect show page thumbnails on the left: click one to go there; the page you're on is highlighted as you scroll, and the zoom bar shows “Page 3 of 12”. Page Up / Page Down flip TIFF pages.
- Inspect shows any text file as text — logs, configs, .env, scripts without an extension, subtitles, code — instead of just an icon. Thai (Windows-874), UTF-8 and UTF-16 are read correctly; ⌘F searches and the zoom bar sizes the text.
- Inspect opens archives — ZIP, TAR/TGZ, 7z, RAR, ISO and more: browse the folders inside, filter by name, and click any file to preview it (zoom works there too). Extract selected files or everything, or open a file in its own Inspect tab (nested ZIPs included).
- Inspect zooms PDFs and images: the − % + Fit bar, ⌘= ⌘− ⌘0, pinch, or ⌘/⌥-scroll (the mouse wheel zooms pictures). Click the % for actual size.

### Improved

- While a tool works, its main button says what it's doing with three jumping dots — “Compressing”, “Converting”, “Trimming”, “Making captions”, “Downloading” and so on — with Stop or Cancel right below.
- Trim, Crop, Text & image overlay, Subtitles, Video to Image, Merge and the Compress preview have the media player's controls: a progress bar you can click or drag, play/pause, volume, time and playback speed. In Crop, Overlay and Subtitles they sit under the picture so they never cover what you're dragging.
- Compress video explains when a video is already as efficient as the chosen quality (marked ⊜): Bento never makes a file bigger than its original, so raising Quality doesn’t change it — lower Quality or Resolution to save more.
- PDFs in Inspect scroll smoothly as one long page instead of flipping page by page.
- Clicking the empty part of a scroll bar in Inspect jumps straight to that spot, and you can keep dragging.

### Fixed

- Tool cards on Home are all the same size at any window width (long names and summaries are shortened, with the full text on hover).

## 0.15.1 — October 20, 2026

### New

- Trim, Crop, Text & image overlay and Subtitles have a Clear button to close the current video. Overlay keeps your layers for the next one; Subtitles asks first if there are captions.

### Improved

- Every file list works the same way now — Player, Compress, Convert, Rotate, Extract audio, Compress PDF, Merge, Download and Inspect: click to select, ⌘/⌃/⇧-click or drag a box for several, × or ⌫ to remove, ⌘A for all, and ≡ to reorder where order matters.
- Compress and Merge get the same resizable bar as the Player between the preview and the list.

## 0.15.0 — October 20, 2026

### New

- Volume control: point at the speaker for a slider; click it (or press M) to mute. ↑ ↓ change the volume. Bento remembers it.
- Subtitles and audio: the CC button (or C) turns subtitles on and off, and the ⚙ menu picks the subtitle language, audio track and speed. A subtitle file next to the video shows up too, or add one from the menu.
- Theatre mode in the Player (T, or the button next to full screen): the settings panel steps aside so the video gets the whole width. Click it again for the default view.
- Drag the bar above the playlist to make it taller or shorter (the video takes the rest); double-click the bar to reset.
- Player plays MKV, WebM, AVI, FLV, WMV, MPEG and other formats macOS can’t: Bento repackages them for playback in seconds (nothing re-encoded when the video is H.264/HEVC), keeping every audio and subtitle track. Unusual codecs (VP9, AV1, MPEG-4…) are converted once. Uses the free FFmpeg helper.
- Pop-up view (P, or the picture-in-picture button): the video in a small window that stays on top of every app, on every desktop. Resize it from any edge (it keeps the video's shape) and drag it anywhere; point at it for the same controls as the main player (subtitles, audio, speed and volume included).
- Every tool has an ⓘ next to its title: click it for what the tool does, step-by-step how to use it, and tips. It stays open until you close it.

### Improved

- Player has YouTube-style controls over the picture: a progress bar that grows when you point at it (with the time under the pointer), play and next, time, and the title. They fade away while playing.
- Playlist: × removes a file; select several with ⌘- or ⌃-click, ⇧-click for a range, or drag a box across them, then press ⌫ or Remove. Drag the ≡ handle to reorder.
- Drop files on the Player while something plays — even in full screen — and they join the playlist and start playing right away. A file that's already in the playlist just plays.
- Videos whose extra audio tracks used to play all at once now play one at a time, and every track is listed.

## 0.14.0 — October 20, 2026

### New

- Subtitles: make captions automatically with Whisper, right on this Mac (nothing is uploaded) — Thai, English and 90+ languages, or translate any language to English. Models download once: Fast, Balanced or Best.
- Edit captions in a list and on a zoomable timeline: fix words, drag to retime, split, merge, add at the playhead, or move them all earlier or later. Undo and redo work here too.
- Save the video with a subtitle track viewers can turn on or off (no re-encoding), or export SRT and WebVTT files. Import SRT/VTT too; a subtitle file next to the video opens with it.
- Caption styles: font, size, color, bold/italic, outline, shadow, background box, maximum width, line gap, alignment and position (or drag the caption on the preview). Save your own styles; five starters included.
- Burn into video: draws the captions into the picture with your style, so they show everywhere — Instagram, TikTok, any player. The preview shows exactly what you’ll get.
- Overlay presets: save layer sets like your watermark or ticker style, with four starters (watermark, news ticker, 5-second title, rolling credits).
- Add Text & Images with Bento in Finder: puts your chosen overlay preset on every selected video, or opens the editor. AI apps can add overlays too (bento_add_overlay).
- Undo and redo in Text & image overlay (⌘Z / ⇧⌘Z, or the arrows at the top). A whole drag, a burst of typing or a slider move undoes in one step; adding, deleting and reordering layers are steps of their own.

### Improved

- Each layer in the overlay list has a ⋯ menu: bring to front or back, duplicate, hide and delete.

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

