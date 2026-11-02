# Black Excellence — WEDE5020 Website Project

## Project overview

Black Excellence is a fictional Durban-based sneaker and streetwear brand focused on premium, culturally inspired footwear. The website showcases the brand story, collections, product catalogue, and enquiry/contact experience for customers looking for modern street luxury with African heritage.

This project was developed as a front-end web project for WEDE5020 and includes responsive design, dynamic product interactions, form validation, SEO enhancements, and a polished storefront experience.

## Student information

- Student: [Insert student name]
- Student number: [Insert student number]
- Module: WEDE5020 — Portfolio of Evidence (PoE)
- Project stage: Part 3
- Brand: Black Excellence
- GitHub repository: [Insert repository URL]
- Published website URL: [Insert Netlify or hosting URL]

## Website goals

- Present the Black Excellence brand clearly and professionally
- Showcase premium sneaker collections in a user-friendly format
- Provide dynamic storefront search and filtering
- Allow visitors to enquire about products or contact the brand
- Improve discoverability through SEO best practices
- Create a responsive website that works across mobile, tablet, and desktop

## Included pages

- Home
- About / Our Story
- Shop / Products
- Collections
- Community
- Enquiry
- Contact
- Thank You

## Key features

### Responsive design

- Flexible layouts for mobile, tablet, and desktop
- Mobile-friendly navigation and content structure
- Responsive product cards, gallery items, and forms

### Dynamic product catalog

- Product search by name, colour, style, and category
- Category filters such as low-top, high-top, and runner
- Sorting by featured, price, and name
- Product cards rendered from local JSON data with fallback content

### Gallery lightbox

- Product image modal/lightbox with larger preview
- Keyboard navigation support
- Close controls and focus return
- Responsive image sizing and smooth interaction

### Forms and validation

- Product enquiry form with required inputs and validation
- General contact form with validation and feedback
- Clear user-friendly error messages
- Immediate validation feedback on input and on submit
- Email fallback for users who prefer to send via mail client

### SEO and accessibility

- Unique page titles and meta descriptions
- Open Graph metadata for social sharing
- Descriptive alt text on images
- Semantic structure with meaningful headings
- Skip link for keyboard users
- Accessible form labels, focus states, and ARIA live regions

## Tech stack

- HTML5
- CSS3
- JavaScript (vanilla)
- JSON data file for product catalog
- Netlify-ready deployment configuration

## Project structure

BlackExcellence_WEDE5020_Part3/
├── BlackExcellence_Part3_Website/
│   ├── index.html
│   ├── about.html
│   ├── products.html
│   ├── collections.html
│   ├── community.html
│   ├── enquiry.html
│   ├── contact.html
│   ├── thank-you.html
│   ├── robots.txt
│   ├── sitemap.xml
│   ├── netlify.toml
│   ├── README.md
│   ├── CHANGELOG.md
│   ├── css/
│   │   ├── styles.css
│   │   └── part3.css
│   ├── data/
│   │   └── products.json
│   ├── images/
│   │   └── sneakers/
│   ├── js/
│   │   ├── logic.js
│   │   └── main.js
│   ├── docs/
│   │   ├── PART3_DESIGN.md
│   │   ├── SEO_NOTES.md
│   │   └── SUBMISSION_CHECKLIST.md
│   ├── screenshots/
│   │   └── part3/
│   └── tests/
│       ├── logic.test.cjs
│       ├── static_audit.py
│       └── ui_smoke.py
└──

## Local setup

1. Open the project folder in a code editor.
2. Use a local HTTP server if needed, for example:
   - Python:
     python -m http.server 8000
   - Or open the files directly in a browser for basic viewing.
3. Visit the site in a browser at:
   - http://localhost:8000

## Run checks

The project includes JavaScript logic tests and validation checks.

To run the logic tests:

node tests/logic.test.cjs

To run the JavaScript syntax check:

node --check js/main.js
node --check js/logic.js

## Deployment

This project is configured for Netlify deployment and includes:

- netlify.toml
- sitemap.xml
- robots.txt

To deploy:

1. Push the project to a GitHub repository.
2. Connect the repository to Netlify.
3. Set the publish directory to the project root.
4. Deploy and verify the site.

## SEO notes

The site includes basic SEO improvements such as:

- keyword-focused page titles
- metadata descriptions
- descriptive heading hierarchy
- social preview metadata
- descriptive image alt text
- responsive images and lazy loading
- XML sitemap and robots file

## Accessibility notes

Accessibility practices included:

- visible focus states
- semantic HTML
- labels for form controls
- skip link
- proper contrast against dark backgrounds
- live regions for form status messages

## Testing summary

The project was checked for:

- navigation accuracy
- search and filter behavior
- sorting logic
- responsive layout behavior
- gallery lightbox interaction
- form validation and submission flow
- metadata and page structure

## Future improvements

Possible enhancements for a production version could include:

- real product backend and database integration
- order submission workflow
- more advanced analytics
- richer gallery with thumbnails and slideshow
- CMS-based catalogue management

## Final note

This website is designed to present Black Excellence as a premium, culturally rooted sneaker brand with a modern e-commerce feel. It balances branding, interactive functionality, and user experience while keeping the implementation lightweight and accessible.
