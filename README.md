# jellyfin-cyberpunk-neon

Skin custom Jellyfin — structure cyberpunk (monospace, clip-paths, brackets) + palette neon sobre (magenta / rouge / cyan sur base violet-noir).

Compatible **Jellyfin 10.11.8+**. Aucun plugin requis.

## Install

1. Jellyfin **Dashboard → General → Branding → Custom CSS code**
2. Coller :

```css
@import url('https://cdn.jsdelivr.net/gh/kushiemoon-dev/jellyfin-cyberpunk-neon@v0.1.0/skin-inline.css');
```

3. **Save** → `Ctrl+Shift+R` pour vider le cache navigateur

## Preview local

```bash
cd preview
python3 -m http.server 8000
# → http://localhost:8000
```

## Palette

| Variable         | Valeur    | Usage                |
|-----------------|-----------|----------------------|
| `--cn-base`     | `#0d0a18` | Fond principal       |
| `--cn-primary`  | `#ff2cf7` | Accent magenta       |
| `--cn-secondary`| `#ff003c` | Brackets / danger    |
| `--cn-tertiary` | `#00fff2` | Cyan / infos         |

## Rollback

Vider le champ Custom CSS dans Jellyfin → skin standard immédiatement.
