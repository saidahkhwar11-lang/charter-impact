# Charter Impact | من حصة إلى أثر

Static bilingual GitHub Pages website for Al Reyada School's cover-period Charter Challenges project.

## Current version
- Arabic / English switch with RTL/LTR support.
- Clean lightweight home page.
- Main content stays hidden until the user opens a section.
- 24 Charter Challenge cards are rendered only when the Cards section is opened.
- Quick nomination from any challenge card.
- Teacher enters only: Teacher Name, Grade/Class, Student Names.
- Unlimited student names can be submitted together in one click.
- Date, challenge number/title, and Charter element are captured automatically.

## Microsoft saving connection
The nomination interface is ready. Direct saving requires a Microsoft / Power Automate endpoint.
Open `app.js` and set:

`const NOMINATION_CONFIG={endpoint:'YOUR_ENDPOINT_HERE'};`

The site sends one JSON submission containing teacher name, class, all selected student names, date, challenge number/title, and Charter element.

## GitHub Pages
Upload these files to the repository root:
- index.html
- styles.css
- app.js
- README.md

Then publish from `main` / `(root)` in GitHub Pages.
