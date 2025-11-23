# Web Dev I - Set Exercises Assessment Portfolio

This repository contains my solutions for the Set Exercises assessment for the Web Dev I (CCO4007-20P,SEP-CA,TRI1,2025-2026) module at Bath Spa University. This assessment tests my knowledge of fundamental web development techniques using HTML and CSS.

## Overview

This portfolio demonstrates my ability to create reusable web components and apply key front-end techniques, including semantic HTML, responsive design, accessibility, and modern CSS layout. It consists of four exercises, each focusing on a different area of web development:

** Exercise 1: Semantic Markup: – Focuses on using semantic HTML elements to structure content (*Cooking with Andy: Recipe Component*).
** Exercise 2: CSS Styling: – Focuses on styling web pages using CSS (*Machine Gym: Futuristic UI Component*).
** Exercise 3: Page Layout: – Focuses on creating effective page layouts using CSS (*J's Gallery: Responsive Gallery Component*).
** Exercise 4: Web Accessibility: – Focuses on creating accessible web content (*The Wondering Photographer: Accessible Store Component*).

Each folder contains the necessary files for the exercise, as provided in the assignment. The deliverables for this assignment are the code solutions for each of the four exercises. All code must be pushed to this GitHub repository before the deadline: - November 26, 2025.

## Submission

To submit this assignment:

1. Ensure all exercises are functioning as expected.
2. Commit and push all code to this GitHub repository.
3. Copy the link to this repository.
4. Paste the link into the submission portal on Ultra to confirm the submission.

## Learning Resources

To prepare for this assessment, I utilised the following online resources:

** W3Schools:  <https://www.w3schools.com/> – For learning HTML and CSS fundamentals.
** SoloLearn:  <https://www.sololearn.com/> – For interactive coding tutorials and practice.
** YouTube: (various channels) – For video tutorials and explanations of web development concepts.
- I also used AI tools to check my work and to get advice on why code was not working and how to improve it.

---

## 1. Cooking with Andy: Recipe Component (`Exercise1.html`)

: Description: --------------------   
A simple, friendly recipe website for chocolate chip cookies, designed as a reusable recipe component. Imagine you're building a larger cooking website – this component can be easily dropped in to display any recipe.

: Key Reusability Features: -------------------- 

** Semantic HTML: -   Uses clear HTML5 tags to define sections (like `<article>`, `<aside>`), making it easy to integrate into any project. This ensures the component is easily understood by other developers and assistive technologies.
** Modular CSS: -   Styles are scoped to the component using a CSS module or BEM-style naming conventions, helping to prevent conflicts with other styles in a larger project. This means you can drop this component into any website without worrying about CSS clashes.
** Customisable: -   Easy to adapt for different recipes by changing the content within the HTML structure. You could even use JavaScript to dynamically load recipe data into this component.

: Techniques Used: -------------------- 

- Semantic HTML structure to clearly separate sections of the page (e.g., header, main content, lists).
- Proper heading hierarchy (`<h1>`, `<h2>`) to improve readability and accessibility.
- Use of ordered and unordered lists to present ingredients and step-by-step instructions.
- Accessible emphasised text using `<em>` to highlight important notes or warnings.
- Simple CSS styling with background colours to create visual separation between sections and improve overall presentation.

---

## 2. Machine Gym: Futuristic UI Component (`CSS-Styling.html`)

: Description: --------------------   
A futuristic AI training concept website, designed as a reusable UI component with a sci-fi theme. Think of this as a widget you could use in a larger dashboard or application.

: Key Reusability Features: -------------------- 

** Theming: -   CSS variables allow for easy customisation of colours and fonts, making it simple to match the component to any design system.
** Scalable: -   Uses relative units (`em`, `rem`) for font sizes and spacing, ensuring it looks good at any size and on any device.
** Responsive: -   Adapts to different screen sizes using media queries, ensuring a consistent user experience across devices.

: Techniques Used: -------------------- 

- Container-based layout to keep content centred and visually organised.
- Google Fonts integration to give the design a distinctive, modern feel.
- Highlight boxes to draw attention to key pieces of content or features.
- Responsive design using media queries so the layout adapts to different screen sizes.
- Use of `box-shadow` and `border-radius` to create depth and softer, more polished UI elements.
- Careful colour contrast choices to support readability and basic accessibility.

---

## 3. J's Gallery: Responsive Gallery Component (`index.html`)

: Description: --------------------   
A photography portfolio website designed as a reusable image gallery component. This could be used in any website where you want to display a collection of images or videos, such as a portfolio, e-commerce site, or blog.

: Key Reusability Features: -------------------- 

** Dynamic Content:  Easily populated with different images and videos via JavaScript, making it simple to update the gallery with new content.
** Flexible Layout:  CSS Grid allows for various grid configurations, so you can easily change the number of columns and rows to fit your needs.
** Media Handling:  Supports mixed media types, including images and videos, making it versatile for different types of content.

: Techniques Used: -------------------- 

- CSS Grid for a flexible, responsive image gallery layout.
- Floating image with text wrapping to combine visual content and descriptions side-by-side.
- Embedded video with playback controls to showcase motion content alongside still photography.
- Responsive media rows using Flexbox to keep content aligned on different screen sizes.
- More complex grid positioning to experiment with featured images and varied layouts.
- `object-fit` on images to maintain consistent sizing and cropping without distortion.

---

## 4. The Wondering Photographer: Accessible Store Component (`index.html`)

: Description: --------------------   
An accessible travel photography print store, designed as a reusable e-commerce component. This component could be integrated into any website to sell products, with a strong focus on accessibility.

: Key Reusability Features: 

** Accessible:  Built with accessibility in mind, ensuring usability for all users, including those with disabilities.
** Modular:  Can be easily integrated into any e-commerce platform or website.
** Customisable:  Easy to adapt for different products and branding using CSS variables and a well-structured HTML layout.

: Techniques Used (Accessibility & UX): --------------------

- Strong focus on web accessibility throughout the layout and interactions.
- ARIA labels to improve screen reader support for interactive elements.
- Semantic HTML elements to give structure and meaning to the page for assistive technologies.
- Keyboard navigation support so key interactions are usable without a mouse.
- High contrast focus states to make interactive elements easier to see and use.
- Accessible button roles and clear labelling for clickable elements.

: Techniques Used (Layout & Responsiveness): -------------------- 

- CSS Grid for the product gallery to neatly display multiple items.
- Responsive header layout using Flexbox for navigation and branding.
- Accessible shopping cart interface designed with clarity and ease of use in mind.
- Mobile-first responsive design to ensure the store works well on phones and tablets before scaling up to larger screens.

---

## What I Learned Across These Projects

Across these four projects, I built up my front-end skills step by step:

** From basic structure to richer layouts:   
  In *Cooking with Andy*, I focused on getting the foundations right: semantic HTML, clear headings, and well-structured lists. This gave me a solid base for content structure before worrying about visuals. In *Machine Gym*, I moved on to stronger visual styling with containers, Google Fonts, shadows, and rounded corners, which helped me understand how CSS can change the “feel” of a page without changing the underlying HTML.

** From simple pages to media-rich, responsive designs:   
  With *J’s Gallery*, I started working with more complex layouts using CSS Grid and Flexbox, plus images and embedded video. This project pushed me to think about how content behaves on different screen sizes and how to keep a gallery layout consistent and visually balanced.

** From “looks good” to “works for everyone”:   
  In *The Wondering Photographer*, I shifted the focus to accessibility and real-world usability: ARIA labels, keyboard navigation, focus states, colour contrast, and a simple shopping cart flow. This helped me see that good web design is not just about appearance, but also about making the site usable for people with different needs and devices.

** Overall progression:   
  Taken together, these four components show a clear progression:
  - Start: basic static page with semantic structure (*Cooking with Andy: Recipe Component*).
  - Next: stronger visual identity and responsive styling (*Machine Gym: Futuristic UI Component*).
  - Then: complex layouts and multimedia content (*J’s Gallery: Responsive Gallery Component*).
  - Finally: accessibility, UX, and e-commerce style interactions (*The Wondering Photographer: Accessible Store Component*).

This sequence reflects how front-end skills naturally build on each other: from HTML structure, to CSS styling, to layout systems, and finally to accessibility and user experience considerations.
