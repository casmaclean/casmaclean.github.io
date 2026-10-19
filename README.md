# Casuarina Maclean — personal website

A plain HTML/CSS site. There is no build step, so whatever is in these files is what the website shows.

## Files

| File | What it is |
| --- | --- |
| `index.html` | Home page (introduction, "Currently", LinkedIn button) |
| `education.html` | Education page (degrees, research, skills) |
| `experience.html` | Experience page |
| `volunteering.html` | Volunteering & Community Engagement page |
| `style.css` | Colours, fonts and layout for every page |
| `assets/casuarina-maclean.jpg` | Portrait photo |
| `assets/motifs/` | The casuarina watermark and divider motifs (SVG) |
| `robots.txt` | Asks AI training crawlers not to collect the site (search engines still allowed) |

## Editing text on GitHub

1. Open the repository on github.com and pick the branch you want to edit from the branch menu (top left of the file list).
2. Click the file you want to change, e.g. `education.html`.
3. Click the pencil icon (✏️ "Edit this file").
4. Change only the words **between** the tags. For example, in
   `<p>I tutor in the School of ...</p>` edit the sentence but leave `<p>` and `</p>` alone.
5. Click **Commit changes…**, write a short note (e.g. "Update Italian level"), and commit.

Tips:
- `&amp;` shows as **&**, and `&nbsp;` is a space that won't break across lines.
- To add another bullet point, copy a whole `<li>…</li>` line and change its words.
- To add another entry to a timeline, copy a whole `<li>` … `</li>` block (from `<li>` to its matching `</li>`) and paste it where it belongs.
- The menu at the top of each page is repeated in all four files. If you change it, change it in each file.

## Common updates

- **LinkedIn:** in `index.html`, change the address in the `LinkedIn` button's `href="..."`.
- **Photo:** upload a new square image named `casuarina-maclean.jpg` into `assets/`.

## Previewing locally (optional)

Open `index.html` in a web browser, or run `python3 -m http.server` in this folder and visit http://localhost:8000.
