# Assessment 1 – Set Exercises (Web Dev)
**Student:** Long Pham  
**Course:** BSc Computing with Foundation  
**Module:** Web Development  
**Assessment:** Set Exercises – Exercise 1 (Semantic Markup)  
**Deadline:** 26 November 2025

---

## Table of Contents
1. [Overview](#overview)
2. [How to Run](#how-to-run)
3. [Project Structure](#project-structure)
4. [Implementation Notes](#implementation-notes)
   - [HTML Semantics Used](#html-semantics-used)
   - [Layout and Styling Choices](#layout-and-styling-choices)
   - [Accessibility Considerations](#accessibility-considerations)
   - [Responsiveness](#responsiveness)
5. [Marking Criteria Mapping](#marking-criteria-mapping)
6. [Testing & Validation](#testing--validation)
7. [Known Limitations & Next Steps](#known-limitations--next-steps)
8. [Version History](#version-history)
9. [References](#references)

---

## Overview
This repository contains my solution for **Set Exercise 1: Semantic Markup**. The task is to rebuild a recipe webpage similar to the class screenshot using correct semantic HTML and basic CSS for structure and presentation.

My page is titled **“Cooking with Andy!”** and presents a recipe for **Chocolate Chip Cookies**. It includes:
- A flexible header with the site title and a simple navigation bar.
- A recipe title and short description.
- An **Ingredients** section using an unordered list.
- A **note banner** about egg substitutes.
- An **Instructions** section using an ordered list.
- A simple footer banner.

---

## How to Run
1. Open `index.html` directly in any modern web browser (Chrome, Edge, Firefox, Safari).  
2. No build tools or server are required.

---

## Project Structure
```
.
├── index.html        # Main page with embedded CSS and content
└── README.md         # This file
```

---

## Implementation Notes

### HTML Semantics Used
- `<!DOCTYPE html>` and `<html lang="en">` for a standards‑compliant, English‑language document.
- `<head>` contains metadata: `<meta charset="utf-8">` and `<title>` for the browser tab text.
- `<header class="site-header">` groups the top banner content:
  - `<h1>` site title: *Cooking with Andy!*
  - `<nav>` primary navigation with three links: *Home*, *Blog*, *Browse*.
- Main content uses clear, readable headings:
  - `<h2>` for the recipe name: *Chocolate Chip Cookies*.
  - `<p>` for a brief description.
  - `<h3>` sub‑headings for **Ingredients** and **Instructions**.
- Lists for recipe content:
  - `<ul>` for ingredients (unordered items).
  - `<ol>` for step‑by‑step instructions (ordered sequence).
- Informational banner implemented as a full‑width table with a paragraph inside, to draw attention to egg substitutes.
- Footer banner also presented using a full‑width table with text *“Cooking With Andy © 2024”*.

> **Note:** For stricter semantics, the two table banners could be refactored to use `<aside>` (for the note) and `<footer>` (for the bottom banner) with CSS for layout. I kept tables to match the simple “grey bar” look as in many beginner screenshots, but I recognise tables are for data rather than layout.

### Layout and Styling Choices
- Embedded CSS inside a single `<style>` block for simplicity (no external stylesheet).
- Header uses **Flexbox** to stack the title above the navigation and keep everything aligned left:
  - `display: flex; flex-direction: column; align-items: flex-start; gap: 8px;`
- Neutral **light grey** background on header and banners for clear section separation.
- Blue links with no hover effects, intentionally minimal to keep the exercise basic.
- Spacing managed with `margin` props and limited `max-width` on text blocks to maintain readable line length.

### Accessibility Considerations
- Language declared: `lang="en"`.
- Logical heading order: `h1` → `h2` → `h3` supports screen reader navigation.
- Lists used for list‑like content (ingredients and steps).
- Adequate text contrast on light grey areas with default browser colours.
- Navigation uses a proper `<nav>` element with anchor links.
- Future enhancements noted below (e.g., skip links, focus styles).

### Responsiveness
- The page uses fluid widths (`width="100%"` on banners) so it scales to the viewport.
- Text content constrained with `max-width` for readability on large screens.
- Flexbox header layout adapts naturally to different widths.
- No media queries are required for the current scope.

---

## Marking Criteria Mapping

| Criterion | How it’s addressed in this submission |
|---|---|
| **Use of semantic elements** | Proper use of `header`, `nav`, `h1–h3`, `p`, `ul`, `ol`, `li`. Banners presently use `<table>` (see note) and could be refactored to `<aside>`/`<footer>` for stricter semantics. |
| **Standard HTML structure** | Valid `<!DOCTYPE html>`, `<html>`, `<head>` with `<meta charset="utf-8">`, and `<title>`. |
| **Formatting & Comments** | Code is indented, grouped, and includes explanatory comments in the CSS and HTML sections for clarity. |
| **Project organisation** | Minimal but tidy structure with a single HTML file for this exercise and this README. |
| **Extension work (optional)** | Flexbox for header alignment, responsive full‑width banners, and readability constraints (`max-width`). |

---

## Testing & Validation

**Manual checks performed**
- Opened `index.html` in Chrome and Edge: renders correctly with header, nav, content sections, and banners.
- Resized window from mobile width to desktop: layout remains readable; navigation stays accessible.
- Readability: paragraphs and lists constrained for comfortable reading.

**Recommended validation (for assessor or future self)**
- Run HTML through the **W3C Markup Validator** to confirm no structural errors.
- Check colour contrast using a tool such as **WebAIM Contrast Checker** if custom colours are added later.
- Keyboard navigation pass: ensure links are focusable and visible; optionally add `:focus` styles in CSS.

---

## Known Limitations & Next Steps
- **Tables used for layout:** Replace with semantic elements and CSS:
  - Note banner → `<aside>` with a class (e.g., `.note-banner`).
  - Footer banner → semantic `<footer>`.
- **Hover/focus states:** Add explicit hover and focus styles for better usability.
- **Active page indication:** Use a class on the current nav link for orientation (e.g., `.active`).
- **External CSS:** Move styles to `styles.css` for scalability and reuse across future pages.
- **ARIA & landmarks:** Consider `role="navigation"` (not required, but can help in some assistive tech contexts) and a “Skip to content” link.
- **Meta viewport:** Add `<meta name="viewport" content="width=device-width, initial-scale=1">` to optimise for mobile devices.

---

## Version History
- **v1.0 – 26 Nov 2025:** Initial submission for Assessment 1 (Set Exercises).

---

## References
- MDN Web Docs: HTML elements and semantics.  
- W3C HTML Standard (for structural best practice).  
- Visual Studio Code: formatting and indentation utilities.
