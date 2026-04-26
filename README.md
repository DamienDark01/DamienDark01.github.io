# Agri-Sense Website

This is a static multi-page website for the Agri-Sense project.

## Project Structure

Main entry pages:
- index.html
- domain.html
- milestones.html
- documents.html
- slides.html
- about.html
- contact.html
- purchase.html

Assets:
- styles.css
- script.js
- images/

Document pages:
- documents-proposal.html
- documents-checklist.html
- documents-final-set.html

## How to Run

Option 1: Open directly
1. Open index.html in your browser.
2. Navigate using the top menu.

Option 2: Run a local server (recommended)
1. Open terminal in this folder.
2. Run: python -m http.server 5500
3. Open: http://localhost:5500/index.html

If Python is not installed, you can use the VS Code Live Server extension and start from index.html.

## Quick Edit Workflow

1. Update page content in the relevant .html file.
2. Adjust design in styles.css.
3. Update behavior in script.js.
4. Refresh browser and test links.

## Notes

- This site does not require npm, build tools, or database setup.
- Keep all files in the same folder level as currently structured so relative links continue to work.
