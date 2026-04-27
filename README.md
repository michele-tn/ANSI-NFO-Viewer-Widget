# ANSI NFO Viewer Widget  
*A lightweight HTML5 widget for viewing classic `.NFO` files encoded in CP437, faithfully rendered in DEMOSCENE style.*

## Overview

This widget was designed for environments where nostalgic digital culture, clean rendering, and self-contained deployment matter. It provides a dedicated viewer for legacy `.NFO` files — the text-based information files historically distributed with digital productions, underground archives, scene releases, independent software communities, and early online networks.

Unlike ordinary text viewers, this widget correctly interprets **Code Page 437 (CP437)** character encoding, preserving the original line-drawing characters, shading blocks, borders, and iconic ASCII/ANSI artwork that define the visual language of the DEMOSCENE, underground computing culture, and retro cyber aesthetics.

The result is an authentic, pixel-perfect reading experience directly inside a browser-based container or embedded interface.

![ANSI NFO Viewer Widget Preview](https://github.com/michele-tn/ANSI-NFO-Viewer-Widget/blob/main/NFO_CP437_Viewer.jpg?raw=true)

---

## Purpose

The widget solves a common problem: modern browsers and editors often display old `.NFO` files incorrectly, replacing box-drawing characters with broken symbols or malformed Unicode output.

This component restores the intended appearance by:

- Decoding raw `.NFO` files using **IBM CP437**
- Preserving original spacing and alignment
- Rendering monospaced layouts accurately
- Supporting classic ANSI-inspired presentation
- Displaying scene text exactly as originally authored

---

## Core Features

### Accurate CP437 Decoding

The widget converts legacy DOS-era text encoding into modern Unicode while preserving:

- Extended line characters
- Block shading
- Borders
- Symbols
- Scene typography

This is essential for authentic `.NFO` visualization.

### DEMOSCENE Visual Style

The interface adopts the aesthetics associated with classic scene viewers:

- Dark background
- Crisp monospaced fonts
- Retro terminal contrast
- Centered content area
- Minimal chrome
- Focus on text artwork

### Drag & Drop Support

Users can load `.NFO` files instantly by dropping them into the viewer window.

### File Picker Import

Standard file selection is also available for controlled environments where drag & drop is disabled.

### Responsive Layout

The widget adapts to different viewport sizes while maintaining readable proportions and fixed-width formatting.

### Zero Dependency Deployment

Built as a self-contained HTML/CSS/JavaScript widget with no external frameworks required.

---

## User Experience

When a file is loaded, the widget immediately parses the content and displays it exactly as intended. Titles, release notes, greetings lists, credits, documentation, manifest files, and full ASCII logos remain aligned and readable.

Scrolling is smooth and optimized for long text archives or scene productions.

The experience feels closer to opening a respected legacy scene viewer than reading plain text in a browser.

---

## Typical Use Cases

### DEMOSCENE Archives

Ideal for preserving and reading accompanying text files from:

- intros  
- demos  
- music disks  
- graphics packs  
- coding productions  
- competition releases  

These files often contain credits, greetings, technical notes, and release commentary.

### Underground Digital Culture Collections

Useful for historical archives related to:

- bulletin board systems (BBS)  
- independent digital communities  
- underground software circles  
- retro network culture  
- early internet subcultures  

### Cyberpunk / Retro-Tech Installations

Perfect for exhibitions, themed websites, and interfaces inspired by:

- terminal aesthetics  
- neon noir environments  
- dystopian retro-futurism  
- hacker-era visual language  
- vintage command-line environments  

### Retro Computing Preservation

Excellent for collections containing:

- DOS utilities  
- shareware archives  
- legacy software packages  
- scene toolkits  
- preserved floppy/CD releases  

### Internal Documentation with Fixed Layout

Can also be repurposed for structured monospaced text documents where alignment matters.

### Embedded Systems / Kiosk Interfaces

Because the widget is lightweight and self-contained, it can run inside controlled viewer environments or custom dashboards.

---

## Technical Architecture

The widget is implemented using standard web technologies:

- **HTML5** for structure  
- **CSS3** for retro styling and layout  
- **Vanilla JavaScript** for file handling, decoding, rendering, and interactions  

No server-side dependency is required.

---

## Rendering Logic

The decoding engine maps original CP437 byte values to modern Unicode equivalents. This ensures characters such as:

- `█`
- `▓`
- `▒`
- `│`
- `─`
- `┌`
- `┐`
- `└`
- `┘`

appear correctly, maintaining scene artwork integrity.

Whitespace and tabs are normalized to preserve alignment.

---

## Design Philosophy

The widget intentionally avoids clutter. `.NFO` files are cultural artifacts, and the interface respects that by keeping the content central.

Every visual choice supports readability and authenticity.

---

## Why This Widget Matters

`.NFO` files are more than plain text. They document an era defined by creativity, limitation-driven design, typography skills, experimentation, and decentralized digital communities.

They represent a bridge between computing history, underground art, and the origins of many modern digital subcultures.

This viewer helps preserve that heritage in a modern environment without compromising its original identity.

---

## Download

Ready-to-import package for compatible environments:

➡️ [Download GB_NFO_CP437_Viewer.cwp](https://github.com/michele-tn/ANSI-NFO-Viewer-Widget/blob/main/GB_NFO_CP437_Viewer.cwp?raw=true)

---

## Deployment

The widget is ideal for publication as a **GitHub Gist**, where the source remains transparent, portable, and easy to reuse.

Its compact structure makes it suitable for:

- quick sharing
- versioning
- embedding
- community forks
- archival publication

---

## Final Notes

If you care about scene history, ASCII art, cyber aesthetics, or simply want `.NFO` files to look the way they were meant to look, this widget provides a clean and faithful solution.

Modern browser. Classic soul.
