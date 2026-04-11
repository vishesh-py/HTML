# The Mahabharata: HTML Learning Project

A static multi-page website built to practice core HTML concepts through one theme: *The Mahabharata*.

## Quick Revision (2-Minute Read)

Use this when you need to revise HTML quickly before practice/interview/lab work.

1. `index.html`: Basic page structure + text formatting + image + iframe + audio.
2. `characters.html`: Repeated content blocks and internal sections.
3. `story.html`: Long-form content + timeline table.
4. `gallery.html`: Media-heavy page using images + video.
5. `contact.html`: Full form controls + FAQ content.
6. Shared layout on all main pages: `header`, `nav`, `section`, `footer`, and a "Back to Top" link.

## Project Structure 🪷

```text
.
├── index.html
├── characters.html
├── story.html
├── gallery.html
├── contact.html
├── README.md
└── images/
    ├── (all media assets: jpg, jpeg, webp, mp3, m4a, mp4)
    └── vishesh.html
```

## Page-Wise Revision Notes

### 1) Home Page (`index.html`)
- Main intro content and page navigation.
- Demonstrates:
- `img`
- `iframe`
- `audio` + `source`
- inline text formatting like `strong` and `i`

### 2) Characters Page (`characters.html`)
- Structured sections for Pandavas, Kauravas, and other key characters.
- Demonstrates:
- semantic grouping with `section`
- heading hierarchy with `h1`, `h2`
- repeated content layout with images + descriptive text

### 3) Story Page (`story.html`)
- Contains key events, teachings, and a timeline table.
- Demonstrates:
- long structured narrative blocks
- `table`, `thead`, `tbody`, `tr`, `th`, `td`
- internal section navigation with IDs

### 4) Gallery Page (`gallery.html`)
- Visual section showing scenes and art forms.
- Demonstrates:
- media display with `img`
- embedded playable media using `video`
- section-wise visual grouping

### 5) Contact Page (`contact.html`)
- Contact details + form + FAQ.
- Demonstrates:
- complete form flow using `form`, `label`, `input`, `select`, `datalist`, `option`, `textarea`, `button`
- `mailto:` link usage
- practical grouping of user-input fields

## HTML Concepts Covered

### Document Basics
- `<!DOCTYPE html>`
- `html`, `head`, `meta`, `title`, `body`

### Text and Layout
- `h1` to `h4`
- `p`, `div`, `br`
- `strong`, `i`
- `ul`, `li`

### Navigation and Linking
- `a` links to same page sections (`#top`)
- `a` links across pages (`index.html`, `story.html`, etc.)
- special links like `mailto:`

### Media
- `img`
- `iframe`
- `audio`, `source`
- `video`

### Tables
- `table`, `thead`, `tbody`, `tr`, `th`, `td`

### Forms
- `form`, `label`, `input`
- `datalist`, `option`
- `select`, `textarea`, `button`

### Semantic HTML
- `header`, `nav`, `section`, `footer`

## Navigation Pattern Used

Each main page contains:
- A top heading (`id="top"`)
- A shared navigation bar linking all major pages
- A "Back to Top" anchor button at the bottom

This is a good example of simple, reusable static-site navigation.

## Run Locally

Because this is a static HTML project, no build step is required.

1. Clone/download the project.
2. Open the folder in VS Code.
3. Open `index.html` in your browser.

Optional: use Live Server extension for auto-refresh while editing.

## Deployment

Live on Vercel:
https://html-smoky-two.vercel.app/

## Quick Practice Checklist

Use this checklist to self-test revision:

- Can I create a full HTML document skeleton from memory?
- Can I build multi-page navigation with anchors?
- Can I add image, audio, and video correctly?
- Can I create a semantic sectioned layout?
- Can I build a clean table with header/body?
- Can I build a complete form with multiple input types?

## Contribution

Suggestions and improvements are welcome. Feel free to open an issue or submit a PR.

## Support

If this helped in your HTML revision, consider starring the repo ⭐
