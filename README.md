# Birthday Wish

A small birthday page. Single static file, no dependencies.

**Live:** https://xhang-l.github.io/birthday-wish/

## How to customize

Everything lives in the `CONFIG` object at the top of the inline `<script>` in `index.html`:

| Key | What it does |
|---|---|
| `name` | Her nickname / name |
| `birthday` | Date, format `YYYY-MM-DD` |
| `from` | Sign-off at the bottom |
| `secretTxt` | Text revealed by holding the photo |
| `finalTxt` | Big text at the end |
| `lines` | Array of paragraphs |

Drop a `photo.jpg` next to `index.html` and it replaces the placeholder frame automatically.
