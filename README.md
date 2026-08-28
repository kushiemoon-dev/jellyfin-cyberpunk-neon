<div align="center">

### jellyfin-cyberpunk-neon

**Cyberpunk-themed CSS skin for Jellyfin: monospace structure, clip-paths, neon accents**

[![Jellyfin](https://img.shields.io/badge/Jellyfin-10.11.8+-00A4DC?style=flat-square&logo=jellyfin&logoColor=white)](https://jellyfin.org)
[![Version](https://img.shields.io/badge/version-0.1.0-green?style=flat-square)](https://github.com/kushiemoon-dev/jellyfin-cyberpunk-neon/tags)
[![No plugin required](https://img.shields.io/badge/plugin-none_required-gray?style=flat-square)]()

</div>

---

## Overview

A custom CSS skin for Jellyfin with a cyberpunk aesthetic: monospace type, angular clip-path shapes, bracket-style UI accents, and a restrained neon palette (magenta / red / cyan on a violet-black base). No plugin required, no Jellyfin fork, just a single CSS file loaded through Jellyfin's built-in Custom CSS field.

---

## Install

1. Jellyfin **Dashboard → General → Branding → Custom CSS code**
2. Paste:

```css
@import url('https://cdn.jsdelivr.net/gh/kushiemoon-dev/jellyfin-cyberpunk-neon@v0.1.0/skin-inline.css');
```

3. **Save** → `Ctrl+Shift+R` to clear the browser cache

---

## Local Preview

```bash
cd preview
python3 -m http.server 8000
# → http://localhost:8000
```

---

## Palette

| Variable | Value | Usage |
|----------|-------|-------|
| `--cn-base` | `#0d0a18` | Main background |
| `--cn-primary` | `#ff2cf7` | Magenta accent |
| `--cn-secondary` | `#ff003c` | Brackets / danger states |
| `--cn-tertiary` | `#00fff2` | Cyan / info states |

---

## Rollback

Clear the Custom CSS field in Jellyfin to return to the default skin immediately.
