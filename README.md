# MARIA Spa Website
[Live Site](https://oliveiracle.github.io/first-project-maria/)

**MARIA Spa** is a clean and minimalist website designed to reflect the values of quiet luxury, natural healing, and holistic well-being. It was created for a high-end spa that offers exclusive, personalized treatments in serene locations across cities like London, Paris, and New York.
The website focuses on simplicity and elegance, allowing users to explore the philosophy behind the brand, learn about the programs offered, and get in touch for bespoke bookings. Every section is crafted to convey calm, trust, and the refined nature of the MARIA Spa experience.

## UX

### User Stories
I created a set of user stories to help shape the design and structure of the website. These stories reflect what differente types of users might when visiting the site. Following below are the user stories.
- As a first-time visitor, I want to easily understand the spa's concept from the homepage and have the site work perfectly on my device (desktop or mobile), so I can efficiently decide if this service is for me.
- As a customer who values the story behind a brand, I want to read about the spa's philosophy and history, so that I can connect more deeply with it's values.
- As a potential customer with questions, I want to easily find the spa's contact information, including a form and a map, so that I can have my questions answered.
- As a user, I want the navigation menu to be consistent and predictable across all pages, so that I can move through the site efficiently without getting lost.
- As a potential customer, I want to see a gallery of high-quality photos of the spa's facilities, so that I can get a better sense of the atmosphere and environment.
- As a user with a visual or motor impairment, I want the site to be built with accessibility in mind, so that I can navigate and consume the content without barriers.
- As a customer, I want to find links to the spa's social media accounts, so that I can follow the brand for updates and inspiration.
These helped me stay focused on usability, consistency, and user experience during the project.

### Acceptance Criteria and Tasks

#### Homepage
**Accceptance Criteria:**
- The homepage clearly displays the spa's name, logo, and primary tagline.
- A clear Call-to-Action (e.g., "Book Your Program") is visible.
- The website layout is fully responsive and adjusts cleanly across various screen sizes, from mobile to desktop.
- Main navigation is present and accessible.

**Tasks:**
- Build the index.html structure with semantic HTML (header, main, footer).
- Implement the header with logo, navigation links, and CTA button.
- Add the main h1 and p content to the hero section.
- Use Bootstrap's grid and CSS media queries to ensure the layout is responsive.

#### Philosophy Page
**Acceptance Criteria:**
- A dedicated "Philosophy" page exists, linked from the main navigation.
- The page presents the story of the spa in a readable format.
- The page includes at least one high-quality image that reflects the brand's essence.

  **Tasks:**
- Create the philosophy.html page.
- Add text content using appropriate heading and paragraph tags.
- Add an  element with a relevant source and alt text.
- Style the page for a premium reading experience.

#### Contact Page
**Acceptance Criteria:**
- Contact page is accessible via the main nav.
- It includes a functional form with fields: Name, Email, Message.
- Submit button is visible.
- Embedded map shows the spa location.

**Tasks:**
- Create `contact.html`.
- Build the form using `label` and `input`.
- Embed Google Maps via `<iframe>`.
- Style using Bootstrap and custom CSS.

#### Navigation
**Acceptance Criteria:**
- Navbar is consistent across all pages.
- All links point correctly.
- Logo always links to homepage.
- Links have hover state styling.

**Tasks:**
- Reuse the same navbar code in all HTML files.
- Confirm `href` values are accurate.
- Add CSS for hover effects.

#### Accessibility
**Acceptance Criteria:**
- All images have descriptive `alt` text.
- Text and background color contrast meets WCAG AA standards.
- Website is keyboard-navigable.
- Semantic HTML is used site-wide.

**Tasks:**
- Write alt text for all images.
- Test color contrast with a checker tool.
- Ensure buttons/links are focusable via keyboard.
- Validate HTML using W3C Validator.

#### Gallery (Optional/Extra)
**Acceptance Criteria:**
- A gallery section or page exists.
- It displays high-quality photo
- Images can be enlarged when clicked.

**Tasks:**
- Create `gallery.html (or a gallery section).
- Use Bootstrap Grid or Modal for layout.
- Optimize images for web performance.
  
#### Design Approach
The visual and the user experience aims to reflect the spa's values - calm, excluisivity, and minimalism. I used:
- A neutral color palette with soft contrasts.
- Large, clear fonts for easy reading.
- Simple navigation that stays the same on every page.
- A layout that adjusts smootly on mobile and desktop.
- Clean sections with space to let each element "breathe".

### Wireframes
 I created wireframes before beginning development to plan the sctructure and layout of the site. As the design envolved during the build process, I made several visual and function improvements. Therefore, some wireframes will be updated to reflect the final version of the project more accurately.

## Homepage (Desktop): 
## Homepage (Mobile):
## Philosophy Page:
## Contact Page:
## Programs Page:



### Design
The MARIA Spa website was designed to reflect an atmosphere of refined simplicity, calm, and elegance. It's design choices reinforce the values of quiet luxury and natural care.

### Color Scheme
The main colors used throughout the site include:

- #333333 - a deep charcoal used for text and primary elements, evoking seriousness and modern elegance.
- #ffffff -  clean white used for backgrounds and cointaners to keep the design light and minimal.
- #cccccc - soft gray used for subtle hover effects and secondary tones.
- transparent overlays and subtle shadows are used to create a sense of depth whothout clutter.

### Typography
Two carefully chosen fonts from Google Fonts enhance the brand's visual identity:
- Cormoront Garamond - https://fonts.google.com/specimen/Cormorant+Garamond
  Used for headings and brand name, this serif font conveys elegance, heritage, and a touch of old-world refinement.
  
- Raleway - https://fonts.google.com/specimen/Raleway
  Used for body text and navigation, this sans-serif font adds a modern and clean contrast, ensuring readability and balance.

### Icons
Font Awesome is used across the site to add visual clarity and brand personality:
- Icons like spa, users-line, envelope, and social media logos are used in navigation, contact areas, and footer.
- These icons are styled in white to match the site's color scheme and adjust on hover for acessibility and feedback.

### Index.html Page:
fa-flask-vial — https://fontawesome.com/icons/flask-vial?f=classic&s=solid
Represents natural ingredients and treatments.

fa-users-line — https://fontawesome.com/icons/users-line?s=solid
Symbolizes group or personalized therapies.

fa-hourglass-start — https://fontawesome.com/v5/icons/hourglass-start?s=solid
Suggests the passage of time and slow living.

fa-spa — https://fontawesome.com/icons/spa?s=solid
Reinforces the spa and wellness concept.

fa-instagram, fa-facebook-f, fa-pinterest-p — 
https://fontawesome.com/icons/instagram?f=brands&s=solid
https://fontawesome.com/v5/icons/facebook-f?f=brands&s=solid
https://fontawesome.com/v5/icons/pinterest-p?f=brands&s=solid
Social media icons for footer links.
A Custom favicon was added using the <link rel="icon" type="image/png" href="assets/images/icon.png"/> tag to enhance brand identity and browser tab recognition.

### Contact.html Page:
fa-instagram, fa-facebook-f, fa-pinterest-p — 
https://fontawesome.com/icons/instagram?f=brands&s=solid
https://fontawesome.com/v5/icons/facebook-f?f=brands&s=solid
https://fontawesome.com/v5/icons/pinterest-p?f=brands&s=solid
Icons repetead for user acessibility.
A Custom favicon was added using the <link rel="icon" type="image/png" href="assets/images/icon.png"/> tag to enhance brand identity and browser tab recognition.


### Philosphy.html Page:
fa-instagram, fa-facebook-f, fa-pinterest-p — 
https://fontawesome.com/icons/instagram?f=brands&s=solid
https://fontawesome.com/v5/icons/facebook-f?f=brands&s=solid
https://fontawesome.com/v5/icons/pinterest-p?f=brands&s=solid
Icons to ensure brand consistency.
A Custom favicon was added using the <link rel="icon" type="image/png" href="assets/images/icon.png"/> tag to enhance brand identity and browser tab recognition.

All icons are styled using Font Awesome 6.7.2.

### Layout
- The layout is fully responsive, built with Bootstrap 5, and adjusts smootly across devices from mobile to large desktops.
- The header and navigation bar remain consistent on all pages.
- Key sections like the hero, contact form and story content are centered and spaced with careful padding and aligment.

### Visual Aesthetic
- Hero backgrounds feature serene photography (e.g., plant in water) thay conveys calmeness and align with the brand's essence.
- Light shadow and transparency are used to soften the visual experience and make content easier to read over images.

- 








