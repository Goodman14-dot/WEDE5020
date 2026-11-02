Part 2 focused on the visual design of the site
Created one external stylesheet, `Css/style.css`, linked from every page
  (`Home.html`, `About us.html`, `Products.html`, `Service.html`, `Contact.html`).
  
JavaScript

1. Accordion on Services (jQuery slideToggle).
2. Products are built from Data/catalogue.json with JavaScript, with search, category filter and sort.
3. Lightbox on Products (click, arrow keys, Esc, focus handling).
4. Interactive Leaflet / OpenStreetMap map on Contact.
5. Animations: CSS fade-in on page load and a JavaScript scroll reveal on cards.
6. Renamed Css/Styles.Css to Css/style.css; the pages linked to style.css, so the styles failed to load on case-sensitive hosting.
7. Fixed image and video paths (images/ to Images/); the Services videos pointed at the wrong folder.
8. Removed srcset entries that pointed to files that do not exist.
9. Corrected product names, descriptions and alt text so they match the images; renamed images and videos with descriptive names.
10. Added the missing charset and viewport tags, and restored the responsive media queries (tablet and mobile) and the web fonts.
11. Closed unclosed elements on About, Services and Contact; replaced the Contact page Google Maps embed (which sat inside the details list) with a Leaflet map.
12. Moved inline styles into style.css, removed unused hero styles and fixed heading order.
13. Renamed Home.html, About us.html , Products.html/Services.html to lowercase names.
14. Video sizes now keep the video's own proportions.

New
1. Added enquiry.html and contact.html forms with validation, the enquiry response and the compiled email.
2. Added Js/main.js, validation.js, products.js, services.js, enquiry.js, contact.js and map.js, and Data/catalogue.json.
3. Added search, category filter and sort, the lightbox, the accordion, the map and the animations.
4. Added SEO tags, robots.txt, sitemap.xml, structured data and the security measures listed above.
5. Added the Enquiry link to the navigation on all pages and "Enquire" links on each product.
