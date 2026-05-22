# Postit Board

A single-page idea board with hand-tracking interactions.

→ **Live**: <https://724ch.github.io/postit-tool/>
→ **Case study**: <https://724ch.github.io/postit-tool/case-study.html>

## Usage

- Click anywhere on the canvas → start typing a note
- Drag notes to move · double-click to edit · ⌘Z to undo
- Shift+click two notes → connect (or disconnect)
- `Hand` button → camera-based hand tracking (right hand grabs, left hand modifies)
- Drop or `⌘V` an image → image note

## Stack

Vanilla JS · D3.js (tree layout) · MediaPipe Hands · Pretendard · localStorage.
No build step, no framework — single HTML + CSS.
