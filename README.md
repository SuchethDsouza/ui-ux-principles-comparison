# UI/UX Principles Comparison

A small UI/UX case study comparing two versions of a fictional e-commerce website, **DisasterMart**:

- **Against UI/UX principles:** demonstrates common usability and visual-design problems.
- **Following UI/UX principles:** redesigns the experience with clearer navigation, consistent styling, a structured product grid, accessible form feedback, and a simpler checkout flow.

## Live demos

- [Version against UI/UX principles](https://lydian-avenue-vlj.julius.site?utm_source=shared_artifact&ref=2S9BJZX4ZX95)
- [Version following UI/UX principles](https://foremost-sturgeon-to2.julius.site?utm_source=shared_artifact&ref=PQJ8GWTP263D)

These demos are hosted externally on Julius AI. The HTML files in this repository are the local project files.

## Key UI/UX comparisons

| Principle | Against the principles | Following the principles |
|---|---|---|
| Color and contrast | Clashing colors and difficult-to-read text | Consistent palette and clearer contrast |
| Typography | Inconsistent text styles and hierarchy | Readable, consistent typography |
| Navigation | Vague labels and hard-to-find search | Clear categories and visible search |
| Visual hierarchy | Important content competes for attention | Clear headings, spacing, and emphasis |
| Layout | Misaligned and inconsistently spaced cards | Aligned, responsive product grid |
| Buttons | Unclear and inconsistent action labels | Familiar labels such as “Add to Cart” |
| Forms | Vague labels and unhelpful errors | Clear labels and field-specific validation |
| Checkout | Unnecessary steps and confusing wording | Simplified guest checkout and order summary |
| Accessibility | Small text and weak descriptive cues | Keyboard focus, accessible labels, and clearer feedback |
| Distractions | Repeated promotions and unnecessary motion | Fewer distractions and restrained motion |
| Consistency | Controls and styles vary across the page | Reusable, consistent visual patterns |
| Overall experience | More confusion and cognitive load | A clearer, easier-to-follow user journey |

## Project structure

```text
ui-ux-principles-comparison/
├── README.md
├── against-principles/
│   ├── index.html
│   └── NOTES.txt
└── following-principles/
    ├── index.html
    └── NOTES.txt
```

## Run locally

No build tools or dependencies are required.

1. Download or clone this repository.
2. Open `against-principles/index.html` in a modern browser to view the intentionally poor design.
3. Open `following-principles/index.html` to view the redesigned version.

Alternatively, run a local server from the repository root:

```bash
python -m http.server 8000
```

Then open the relevant file in your browser:

- `http://localhost:8000/against-principles/`
- `http://localhost:8000/following-principles/`

## Scope and safety

This is an educational front-end demonstration, not a production shopping system. The products are fictional. The pages simulate shopping interactions and do not process real payments or orders. Use invented contact and address details in the demo.

## Learning outcome

The project illustrates how visual consistency, information hierarchy, clear navigation, accessible form feedback, and a shorter checkout journey can improve usability.
