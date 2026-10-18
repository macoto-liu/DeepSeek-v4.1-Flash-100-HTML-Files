# DeepSeek V4.1 Flash 1017 — 100 HTML Files

One hundred self-contained HTML studies generated with **DeepSeek V4.1 Flash 1017** from the same prompts used by [MiaAI-Lab's DeepSeek-v4.1-Flash-100-HTML-Files](https://github.com/MiaAI-Lab/DeepSeek-v4.1-Flash-100-HTML-Files).

**Live index:** <https://macoto-liu.github.io/DeepSeek-v4.1-Flash-100-HTML-Files/> · **Repository:** <https://github.com/macoto-liu/DeepSeek-v4.1-Flash-100-HTML-Files>

## Browse

Open **[`index.html`](index.html)** for the visual index: search all one hundred pieces, preview them, open any study, and read the original prompt behind it.

- `pages/` — 100 standalone HTML files, one per prompt
- `prompts/` — the 100 source prompts
- `shots/` — preview images used by the index
- `index.html` — searchable gallery linking every page

## Notes

Every study is a single self-contained HTML file: inline CSS, JavaScript, SVG and canvas, with no external fonts, libraries, images or network requests. Each one is responsive and can be opened directly in a browser.

The prompts come from the MiaAI-Lab collection linked above. The implementations in `pages/` were generated with DeepSeek V4.1 Flash 1017.

## Run locally

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000/>.

## Verification

- 100/100 pages load with no console or page errors
- no external asset or network references in any study
- all inline scripts pass syntax checks
- checked at 1440px desktop and 375px mobile widths
