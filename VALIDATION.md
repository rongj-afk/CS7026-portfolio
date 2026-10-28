# Validation record

Checked on 25 October 2026.

## HTML5 and CSS

- HTML: W3C Nu Html Checker (https://validator.w3.org/), "Validate by File Upload".
- CSS: W3C CSS Validation Service (https://jigsaw.w3.org/css-validator/), "By file upload", default settings.

| File | Checker | Result |
|---|---|---|
| `index.html` | Nu Html Checker | Passed |
| `project1_changi.html` | Nu Html Checker | Passed |
| `project2_air-new-zealand.html` | Nu Html Checker | Passed |
| `project3_moon-and-stars.html` | Nu Html Checker | Passed |
| `project4_nyu-shanghai.html` | Nu Html Checker | Passed |
| `resume.html` | Nu Html Checker | Passed |
| `contact.html` | Nu Html Checker | Passed |
| `css/style.css` | W3C CSS Validator | Passed |

If a file is edited after this date, check it again and update its row.

## Navigation and media

- Every local link, image, stylesheet and font path exists, with the same letter case as the file on disk.
- Every in-page anchor target exists, including `index.html#projects`.
- Every page's menu links to Home (`index.html`), Projects (`index.html#projects`), Resume (`resume.html`) and Contact (`contact.html`).
- Each project page has Previous and Next links: Changi -> Air New Zealand -> Moon and stars -> NYU Shanghai -> Changi.
- Each HTML file has one main heading (`h1`), links to the one shared stylesheet (`css/style.css`), and has no inline styles or scripts.

Deployment to the course `www` folder and the GitHub repository are separate submission steps.
