# SW Service NPI Guideline - Server Package

This folder contains two deployment options for the current guideline page.

## Option 1: CDN version

- `sw-service-npi.html`
- Uses Tailwind CSS from CDN: `https://cdn.tailwindcss.com`
- Use this version if the server/client environment can access external CDN resources.

## Option 2: No-CDN / offline version

- `sw-service-npi-no-cdn.html`
- Does not use Tailwind CDN.
- Required CSS is embedded directly in the HTML file.
- Use this version if the server/client environment cannot access external resources.

## Notes

- Both files are standalone static HTML files.
- No local `styles.css` or `script.js` is required for the current page.
- The Project Information section is temporarily hidden in the HTML and is not shown on the page at this stage.
