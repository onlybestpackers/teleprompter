# 🎬 Teleprompter — free, open source, voice-follow

A free teleprompter that runs in your phone's browser. Paste your script, put the phone under your camera, and read. In **Points mode** it listens to you and moves to the next point as you speak.

**Live:** https://onlybestpackers.github.io/teleprompter/

Made by **AI With Ankit** — [Instagram](https://www.instagram.com/ai_withankit) · [YouTube](https://www.youtube.com/@aiwith_ankit) · [Facebook](https://www.facebook.com/aiwithankit)

---

## Features

- **🎯 Points mode (cue cards):** each point of your script is one big card. No word-by-word reading, so you talk naturally.
- **🎤 Voice-follow:** as you speak, the card's keywords turn green; once you've said enough of it, the next card comes up by itself. Works with Hindi, Hinglish and English (Chrome speech recognition).
- **📜 Scroll mode:** classic auto-scrolling script with speed, font size and line-height controls.
- **Reading line at the top:** made for a phone mounted right under the camera, so your eyes stay near the lens.
- **🪞 Mirror** (for glass teleprompters) and **↻ rotate** 90° / -90°.
- **Themes:** dark, soft, light, yellow-on-black. Optional guide line and 3-second countdown.
- **⏱ Timer** in points mode (turns yellow at 45 s, red at 60 s — Reel length).
- **🔗 Share link:** the script is compressed into the link itself (nothing is uploaded anywhere).
- **Screen stays on** while you read (Wake Lock), fullscreen, and **installable** as an app (PWA).
- **Back button** returns to the editor instead of closing the app.
- Controls: tap = next card · swipe = previous/next · long-press = pause + controls · keyboard / Bluetooth remote (Space, arrows, PageUp/PageDown).

## Script format (Points mode)

```
HOOK: Google ne free mein de diya website banane wala AI

- Google Stitch [👉 screen dikhao] 1,000 credits free
- India mein available, sirf Gmail chahiye
- ChatGPT se 10 guna fast design

# CTA
Comment karo WEBSITE, link DM mein bhejunga
```

- Blank line, `-` or `1.` = new card
- `HOOK: …` or a `# CTA` line = label on the card
- `[ … ]` = an action cue (shown as a chip, not meant to be read out)

## Use it

1. Open the live link in **Chrome on Android** (voice-follow needs Chrome; everything else works in any modern browser).
2. *Add to Home screen* from the ⋮ menu to use it like an app.
3. Allow the microphone when asked (only for voice-follow).
4. **Tip:** set the phone's media volume to 0 while recording — Android can play a short beep when the mic restarts.

## Privacy

Everything runs in your browser. Your script stays in your phone's local storage (or inside the share link you create). There's no server and no account. Voice-follow uses the browser's built-in speech recognition (Chrome sends the audio to Google's speech service for this).

## Run it yourself

It's one HTML file — no build, no dependencies. Download the repo and open `index.html`, or host the folder on any static host (GitHub Pages, Netlify…). Voice-follow needs HTTPS (or `localhost`).

## Contributing

Issues and pull requests are welcome.

## License

[MIT](LICENSE) © 2026 Ankit (AI With Ankit)
