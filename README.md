# Semantic Document Structure Lab

This project is a technical exploration of **Information Architecture** and **Modern Semantic HTML**. The goal is to move beyond generic `<div>` containers to create a meaningful document outline that improves accessibility, SEO, and machine readability.

## Project Goal

To prototype common web interface patterns (Search Results, Review Streams, etc.) using the most accurate HTML5 semantic elements and CSS layouts (Grid and Sticky positioning).

## File Overview

### `index.html` (The Dashboard)

The `index.html` file acts as the **central hub or directory** for the laboratory. Its primary functions are:

- **Pattern Navigation**: Provides an organized list of different layout modules developed during the project.
- **Component Context**: Each link is wrapped in a descriptive `<article>` card that explains the technical challenge solved by that specific layout (e.g., handling high-density data or social feedback streams).
- **Information Architecture**: Demonstrates a high-level site structure, showing how secondary pages relate back to a primary entry point.

### Technical Patterns Explored

- **Semantic Data Marking**: Utilizing `<data>`, `<time>`, and `<meter>` to provide machine-readable values alongside human-readable text.
- **Document Outlining**: Proper nesting of `<header>`, `<main>`, `<section>`, and `<aside>` to create a logical hierarchy for assistive technologies.
- **Advanced Layouts**: Implementation of sticky sidebars, high-density result grids, and responsive "mobile-first" reflowing.
- **Accessibility (A11y)**: Enhancing interactive elements with `aria-label` and replacing purely visual indicators (like text-based stars) with accessible semantic equivalents.

## Why Semantics?

By using elements like `<article>` and `<nav>` instead of `<div>`, we ensure that:

1. **Screen Readers** can navigate the page via landmarks.
2. **Search Engines** can better index the most important content on the page.
3. **Developers** can maintain the code more easily through self-describing tags.
