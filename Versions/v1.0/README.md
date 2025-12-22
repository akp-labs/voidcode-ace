# VoidCode – v1.0

Version 1.0 is the **first stable public release** of VoidCode Ace distribution.

This version delivers a functional, lightweight web-based code editor with multi-language support, file operations, and basic execution for HTML.

It is intentionally designed to remain simple while exposing enough internal logic for learning and extension.

---

## Available Builds

### 1. Standalone Build (`single-file/`)

**VoidCodeIDE_dA_v1.0.html**

- Entire editor contained in a single HTML file
- Includes UI, styles, logic, and Ace Editor integration
- Fully portable and offline-ready
- Ideal for quick use, sharing, or archival

---

### 2. Modular Build (`modular/`)

**index.html + style.css + script.js**

- Same functionality as the standalone build
- Code separated for readability and maintainability
- Recommended for learning, customization, and future development

---

## Core Features

- Ace Editor integration with:
  - Syntax highlighting
  - Autocompletion
  - Snippets
  - Command palette
- Language mode switching at runtime
- File operations:
  - New file
  - Open local file
  - Save file locally
- Clipboard operations:
  - Copy, Cut, Paste (with fallbacks)
- Editor controls:
  - Word wrap toggle
  - Font size adjustment
  - Go to line
  - Theme switching
  - Fullscreen mode
- HTML execution:
  - Run in new tab
  - Run inside iframe preview
- Keyboard shortcuts for common actions

---

## Browser Compatibility

Tested on modern Chromium-based browsers and Firefox.

JavaScript must be enabled.  
Some browser security policies may restrict local file behavior.

---

## Design Notes

- No backend or server
- No build tools
- No frameworks beyond Ace Editor
- Direct DOM and API usage
- Minimal UI inspired by classic desktop editors
- Best suited for mobile phones and tabs

---

## Known Limitations

- Not a full IDE
- No project-level file tree
- No compilation or runtime for non-HTML languages
- No persistent settings storage (yet)

---

## Version Status

✔ Stable  
✔ Feature-complete for initial release  
✔ Suitable for learning and experimentation  

> Note: This version may contain bugs, rough edges, or logic gaps.  
> Contributions, bug reports, and improvements are encouraged.

