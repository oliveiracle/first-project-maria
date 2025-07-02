# MARIA Spa Website
[Live Site] (https://oliveiracle.github.io/first-project-maria/)

**MARIA Spa** is a clean and minimalist website designed to reflect the values of quiet luxury, natural healing, and holistic well-being. It was created for a high-end spa that offers exclusive, personalized treatments in serene locations across cities like London, Paris, and New York.
The website focuses on simplicity and elegance, allowing users to explore the philosophy behind the brand, learn about the programs offered, and get in touch for bespoke bookings. Every section is crafted to convey calm, trust, and the refined nature of the MARIA Spa experience.

## UX

### User Stories
- As a first-time visitor, I want to easily understand the spa's concept from the homepage and have the site work perfectly on my device (desktop or mobile), so I can effeciently decide if this service is for me.
- As a customer who values the story behind a brand, I want to read about the spa's philosophy and history, so that I can connect more deeply with its values.
- As a potential customer with questions, I want to easily find the spa's contact information, including a form and a map, so that I can have my questions answered.
- As a user, I want the navigation menu to be consistent and predictable across all pages, so that I can move through the site efficiently without getting lost.
- As a potential customer, I want to see a gallery of high-quality photos of the spa's facilities, so that I can get a better sense of the atmosphere and environment.
- As a user with a visual or motor impairment, I want the site to be built with accessibility in mind, so that I can navigate and consume the content without barriers.
- As a customer, I want to find links to the spa's social media accounts, so that I can follow the brand for updates and inspiration.


### Acceptance Criteria and Tasks

#### Homepage

***Accceptance Criteria:**
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
- It displays high-quality photos.
- Images can be enlarged when clicked.

**Tasks:**
- Create `gallery.html (or a gallery section).
- Use Bootstrap Grid or Modal for layout.
- Optimize images for web performance.
  




