# konradturek.com

Personal website of Konrad Turek. Built with [Jekyll](https://jekyllrb.com/) and the
[Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme; design adapted from
[cpfdata.com](https://github.com/cpfdata/cpfdata.github.io). Hosted free on GitHub Pages.

## How to update the website

Edit a file on github.com (pencil icon ✏️), then click **Commit changes**.
The website updates automatically after 1–2 minutes (progress: **Actions** tab).

| What you want to change | File |
|---|---|
| Home page (intro, affiliations, contact) | `index.md` |
| About | `_pages/about.md` |
| Research | `_pages/research.md` |
| LEEP project page | `_pages/leep.md` |
| **Add a publication** | `_pages/publications.md` |
| **Add a conference presentation** | `_pages/conferences.md` |
| Top menu | `_data/navigation.yml` |
| Site name, footer links, header colour | `_config.yml` |
| Photo | `assets/images/konrad.webp` |
| PDF files | `assets/files/` (link as `/assets/files/NAME.pdf`) |
| Styling (fonts, colours) | `assets/css/main.scss` (additions at the bottom) |

### Publication format

One paragraph per publication, with an empty line between entries:

```
Turek, Kalmijn (2026) **[Title](https://link)**, *Journal*, 54(32): 1009–1050 [[OSF code](https://osf.io/xxxx)]
```

- `**...**` = bold, `*...*` = italic, `[text](link)` = link.
- Do not use the `|` character in entries (it turns the line into a table).
- To upload a PDF: open the `assets/files` folder on github.com → **Add file → Upload files**.
