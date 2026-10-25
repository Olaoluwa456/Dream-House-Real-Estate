# Dream House Real Estate — Sample Showcase Website

A responsive, image-rich static website concept for a Nigerian real-estate agency. It is built with HTML, CSS and vanilla JavaScript (no Lovable, framework, API key or paid dependency required).

## Included pages

- `index.html` — home page, quick search, featured properties, services, neighbourhood cards and educational content.
- `properties.html` — searchable and filterable sample listings.
- `property.html?id=...` — property details and interactive image gallery.
- `services.html` — buying, renting, selling, land and management service descriptions.
- `about.html` — brand story and principles.
- `contact.html` — validated inquiry form and local demo submission feedback.
- `faq.html` — expandable property questions and due-diligence reminders.
- `legal.html` — draft Terms & Conditions, Privacy Notice and Property Disclaimer.
- `assets/css/styles.css` — responsive visual system.
- `assets/js/app.js` — listing data, filtering, favourites, gallery, forms, mobile menu and cookie preferences.

## Preview locally

1. Extract the ZIP file.
2. Open `index.html` in a modern browser. For the most reliable local-storage and URL behaviour, use a static local server, such as VS Code's Live Server extension or Python's built-in server from this folder: `python -m http.server 8000`.
3. Visit `http://localhost:8000`.

The photo assets load from Unsplash image URLs, and web fonts load from Google Fonts, so an internet connection is needed for those external assets. The layout still has backgrounds and readable text if an image cannot load.

## Important before showing a real client

- The supplied phone number is a placeholder: `080X XXXX XXX`. Replace it with the verified business number in `assets/js/app.js` (the `PHONE` constant) and update the contact/legal page details as appropriate.
- Every property, price, feature and image in this sample is illustrative. Do not represent them as verified or currently available listings. Replace them with the client's real, permissioned property details and photographs.
- The contact form works as a *demo*: it validates fields and stores a sample inquiry in the visitor's browser local storage. It does **not** send email or reach the business. Before production, connect a secure backend/CRM/email handler, protect form data, and update the privacy disclosures.
- Cookie preferences are stored locally. There are no analytics or advertising scripts in this package.
- The Terms, Privacy Notice and Property Disclaimer are draft templates only. Have Nigerian-qualified counsel adapt them to the real business and its data processing before launch; this demo is not a legal compliance certification.
- Add the real agency address, office hours, registration information and real staff details only after the client confirms them.

## Deployment

Upload the extracted folder contents to any static hosting service that supports HTML, CSS and JavaScript. Keep the `assets` folder at the same relative path. Because this package has no backend, publishing it will not enable real lead delivery until the inquiry form integration is added.
