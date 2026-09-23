# MyFridge

MyFridge is a mobile‑first, single‑page groceries dashboard designed to help household members track their groceries and organize their goods in a clean, modern interface. Built with pure HTML, CSS, and JavaScript, Fairways focuses on elegant dark‑mode visuals, simple data displays, and smooth interactions.

---

## Overview

MyFridge combines two core functions:

1. **Grocery Tracker**
   - What's in the fridge
   - Amount of food
   - Estimated expiration date
2. **Recipe Recommendations**
   - Dishes based off what is in the fridge, prioritized by estimated expiration date
   - Simple to complex based off number of ingredients and cookware potential
The goal is a single, focused dashboard page with a clean layout and ample negative space, optimized for mobile devices and still looking great on larger screens.

---

## Features

### Dashboard Layout

- **Single‑page design** (`index.html`)
- **Multiple card layout** with a maximum content width of **480px**
- Sections/cards may include:
  - What is in the fridge separated by categories (vegetables, meats, condiments, sauces, etc)
  - Add date
  - What is expiring soon
  - What is needed to maximize recipes
  - Speciality section with potential recipes organized by difficulty and cooking time
  - Weekly planner for what recipes to create
### Visual Design

Light and airy with colorful pops of color to make things fun and engaging
- Primary colorway:
  - Complimentary **natural pastels** and **warm tones** accents
  - **White lettering** for maximum legibility
- Charts use a **warm accent color** 
- **Fun font** choice for ease of legibility but fun and viewing
- **Elegant design** emphasizing:
  - Ample negative space
  - Clear hierarchy
  - Minimal clutter

### Interactions & Animations

- **Smooth hover animations** on link buttons and interactive elements
- Subtle transitions for card hover/focus states to reinforce the modern feel
- Focus on simple, performant CSS transitions (no heavy animation libraries)

- **HTML**  
  - Single `index.html` file
  - Semantic structure for cards, charts, and forms

- **CSS**  
  - Custom stylesheet (e.g., `styles.css`)
  - Dark theme, responsive layout, and card styling
  - Utility classes for spacing and typography
  - Smooth hover states and transitions

- **JavaScript**  
  - No frameworks or build tools
  - Handles:
    - Data fetching (e.g., GHIN data via API if available, and weather API)
    - Chart rendering (simple custom charts or minimal vanilla JS chart logic)
    - State management for the bag organizer
    - Basic local storage for user data (optional)

> **Note:** There are no external frameworks (React, Vue, etc.) and no bundlers or build tools. The site is a static deployment.

---

## Data Sources

Top rated recipes from food Network and trusted online sources

## Accessibility & Contrast

Because Fairways is dark‑mode first, attention is given to accessibility:

- High contrast between text and backgrounds
- Sufficient contrast ratios for neon green and turquoise against dark surfaces
- Clear focus states for interactive elements
- Legible font sizes and spacing for mobile users

---

## Deployment

Fairways is deployed as a static site on **Vercel**.

### Project Structure

```text
/
├─ index.html
├─ styles.css
└─ script.js
