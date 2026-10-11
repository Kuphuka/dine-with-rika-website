# Dine with Rika website
Static site (HTML/CSS/JS). No build step.

Run locally in VS Code: install the "Live Server" extension, right-click index.html, "Open with Live Server".

Deploy to Netlify: drag the whole folder onto app.netlify.com/drop (or connect the repo).

Update content: edit the arrays at the top of the script in index.html (services, gallery, packages and clients). Replace images inside assets/images/ keeping file names, or change the paths in those arrays. Food and team photos are shown in the gallery rather than repeated across the homepage.
Video: the cinematic hero background uses assets/video/hero.mp4 and hero-poster.jpg. The kitchen video playlist uses the two clips in anita/.
Logo: the uploaded dine logo.jpeg is traced to transparent vector paths in assets/images/brand/dine-logo.svg. The header and footer use this artwork without a white or black background tile.
Enquiries: the validated event enquiry form opens WhatsApp with a prefilled message. Update WHATSAPP_NUMBER in index.html if the business number changes.
SEO: the page title, descriptions, social sharing metadata and LocalBusiness structured data are in the head of index.html.
