# Black Excellence — WEDE5020 Website Project

## Student information

- **Student:** Langelihle Amahle Ntshangase
- **Student number:** **[INSERT STUDENT NUMBER BEFORE SUBMISSION]**
- **Module:** WEDE5020 — Portfolio of Evidence (PoE)
- **Stage:** Part 3 — Enhancing Functionality and SEO
- **Chosen organisation:** Black Excellence (fictional Durban-based sneaker/streetwear brand)
- **GitHub repository:** **[PASTE LECTURER-ASSIGNED PRIVATE REPOSITORY URL]**
- **Published site URL:** **[PASTE VERIFIED NETLIFY OR OTHER DEPLOYMENT URL]**

## Project Overview

Black Excellence is a Durban-based sneaker and streetwear brand inspired by African culture, identity and modern street fashion.

The website includes:

Home

Our Story

Shop

Collections

Community

Product Enquiry

Contact and Support

Part 1 focused on planning and the basic HTML structure. Part 2 introduced CSS styling and responsive design. Part 3 adds JavaScript functionality, form validation, interactive features and search engine optimisation.

## Website Goals

The main goals of the website are to:

Present the Black Excellence brand and sneaker collection clearly.

Make the website easy to use on desktop, tablet and mobile devices.

Allow customers to search, filter and sort sneakers.

Allow visitors to send product and general enquiries.

Improve the website's visibility through basic SEO techniques.

## Part 3 Features

**Shop**

The Shop page includes:

Product search

Category filtering

Product sorting

Responsive product cards

Sneaker image viewer

Product information and pricing

Sneaker information is loaded from the project's product catalogue using JavaScript.

## Collections

The Collections page includes:

A featured sneaker drop

Additional Black Excellence sneaker collections

Responsive product images

Links to the Shop and Enquiry pages

## Product Enquiry Form

The enquiry form allows customers to enquire about:

A selected sneaker

Size availability

Product information

Pricing and availability

JavaScript is used to check that the required information has been entered correctly.

## Contact Form

A separate contact form is available for general customer messages and support enquiries.

The form includes:

Name

Email address

Contact category

Message

Form validation checks that required information is entered before submission.

## Interactive Map

The Contact page includes an interactive map showing the Durban and Umhlanga areas.

The map uses Leaflet and OpenStreetMap.

## Responsive Design

The website was designed to work across different screen sizes.

The main responsive breakpoints are:

Desktop: above 1024px

Tablet: 1024px and below

Mobile: 720px and below

Layouts, navigation, images and text adjust depending on the available screen size.

## SEO

The following search phrases were considered when writing website content:

Black Excellence sneakers

Durban sneaker brand

South African streetwear sneakers

Black and gold sneakers

Lifestyle sneakers South Africa

## SEO Improvements

The website includes:

Unique page titles

Meta descriptions

Clear H1, H2 and H3 heading structure

Descriptive image alt text

Internal links between pages

Responsive images using srcset

Lazy-loaded images

robots.txt

sitemap.xml

Social media preview metadata

## Performance and Security

Several basic techniques were used to improve the website:

Product images are available in different sizes.

Images lower down the page use lazy loading.

JavaScript files are stored within the project.

Forms are validated before submission.

No passwords or login details are stored in the source files.

HTTPS can be used when the website is published through Netlify.

## Website Structure

BlackExcellence_Part3_Website/
│
├── index.html
├── about.html
├── products.html
├── collections.html
├── community.html
├── enquiry.html
├── contact.html
├── thank-you.html
│
├── css/
│   ├── styles.css
│   └── part3.css
│
├── js/
│   ├── logic.js
│   └── main.js
│
├── data/
│   └── products.json
│
├── images/
│   ├── logo files
│   └── sneaker images
│
├── screenshots/
│   └── part3/
│
├── robots.txt
├── sitemap.xml
├── netlify.toml
├── README.md
└── CHANGELOG.md

## Testing

The website was checked at desktop, tablet and mobile screen sizes.

Testing included:

Navigation links

Product search

Product filters

Product sorting

Sneaker image viewer

Enquiry form validation

Contact form validation

Responsive layouts

Images and local files

Testing screenshots are stored in the screenshots/part3 folder.

## Publishing

The website can be deployed using Netlify.

Before submitting the final project:

Add the correct student number.

Push the final website files to the lecturer-assigned GitHub repository.

Deploy the website to Netlify.

Add the final website URL to the sitemap and README.

Test both forms on the published website.

Check the website on desktop and mobile.

Submit the GitHub and published website links.

## Changelog

See CHANGELOG.md for the changes made throughout Parts 1, 2 and 3.

## References

MDN Web Docs. CSS Grid Layout.
https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout

MDN Web Docs. Responsive Images.
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Responsive_images

MDN Web Docs. HTML Form Validation.
https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Forms/Form_validation

Netlify. Forms Setup.
https://docs.netlify.com/manage/forms/setup/

Netlify. Create Deploys.
https://docs.netlify.com/deploy/create-deploys/

Leaflet. JavaScript Mapping Library.
https://leafletjs.com/

OpenStreetMap Contributors.
https://www.openstreetmap.org/copyright