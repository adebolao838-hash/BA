# Adebola Olaore — Business Analysis Portfolio

This version keeps the Business Analysis portfolio structure and removes the large hero logo/monogram. Project cards open dedicated case-study pages.

## Individual project pages
Each project page includes:
- One main image at the beginning
- Project Description
- Project Period
- Client / Organisation
- Domain
- Evidence
- Team Size
- Position
- Platform / Application
- Server / Database
- Methodology
- Responsibilities
- Achievements
- Project PDF link

## Adding a new project
1. Copy `projects/project-template.html` and rename it, e.g. `customer-retention.html`.
2. Replace the project title, description and metadata in that file.
3. Add the project card to `index.html` inside `.project-grid`.
4. Add the main image and evidence images to `images/`.
5. Add the final PDF to `pdfs/`.
6. Change the PDF link in the project page to the new filename.

There is no hard 10-project limit. You can keep adding cards and project pages using the same pattern.

## Replacing images
The current images are SVG placeholders. You can replace them with JPG or PNG files. If you keep the same filenames, the HTML does not need to change.

## Replacing PDFs
Replace the placeholder PDFs in `pdfs/` with your actual project PDFs, keeping the same filename, or update the link in the relevant project page.

## Run in VS Code
Open the folder in VS Code and use Live Server on `index.html`.
