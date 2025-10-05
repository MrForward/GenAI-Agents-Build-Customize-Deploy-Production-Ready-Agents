# 🖼️ Assets – Images, GIFs, and Diagrams

> Central place for all visual assets used across the repository.

## 📋 Overview
Use this folder to store media that improves docs, READMEs, and social posts:
- Screenshots and annotated flows
- Architecture diagrams
- Demo GIFs and short MP4 clips
- Social cards and thumbnails

---

## 🗂️ Recommended Structure

```
assets/
├── diagrams/           # architecture and flowcharts
├── screenshots/        # UI and terminal shots
├── gifs/               # short product demos (5–10s)
├── social/             # banners, share images
└── logos/              # project or partner logos
```

---

## 🧭 Usage Guidelines
- Keep filenames kebab-case and descriptive (e.g., research-agent-flow.png)
- Prefer optimized PNG/SVG for diagrams; use GIF/MP4 for demos
- Keep GIFs under 5–10 seconds, <5 MB when possible
- Add alt text and short captions in READMEs for accessibility

---

## 🔧 Creating Great Demo GIFs
- Frame a single task end-to-end in 5–10 seconds
- Zoom to 120–140% for readability
- Highlight the cursor and key steps
- Trim dead time; speed up by 1.1–1.3x if needed

---

## 📎 How to Reference in Markdown

```md
![Research Agent Flow](./diagrams/research-agent-flow.png)

<p align="center">
  <img src="./gifs/research-agent-demo.gif" alt="Research agent demo" width="700" />
</p>
```

---

## ✅ Checklist Before Commit
- Files optimized and reasonably small
- Filenames descriptive and consistent
- Sensitive data redacted in screenshots
- License/attribution included if required

---

Last updated: October 2025 • PRs with improved assets welcome.
