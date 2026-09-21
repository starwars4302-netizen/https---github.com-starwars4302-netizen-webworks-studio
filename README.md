# Hill & Hollow Coffee — Week 4 Starter Project

## Scenario
WebWorks Studio has received an approved visual direction for a small promotional landing page.

Your job is to implement that direction using **Tailwind CSS utility classes**.

## Important
The starter HTML is intentionally:
- semantic
- minimally styled
- responsive only after you add the appropriate Tailwind utilities

The Tailwind Play CDN script is already included in `index.html`.

## Before You Begin
1. Create:
   `webworks-studio/week04-tailwind/`
2. Place these starter files inside that folder.
3. Open the entire folder in Visual Studio Code.
4. Open `design-reference.svg` and review the supplied design direction.
5. Preview `index.html` in your browser.
6. Add Tailwind classes directly to the existing semantic HTML.

## Preserve
- Existing written content
- Semantic HTML structure
- Meaningful image alternative text
- Existing links and contact information

## Your Goal
Use Tailwind utilities to translate the supplied visual direction into a polished, responsive webpage.

## Tailwind Decisions
Before submitting, replace the placeholders below with approximately three examples.

### Decision 1
**Used:**  
**Why:**  

### Decision 2
**Used:**  
**Why:**  

### Decision 3
**Used:**  
**Why:**  

## Live Site
Add your published GitHub Pages URL here.

## Reminder
The Tailwind Play CDN is being used for this instructional sprint only. It is intended for development, not production deployment workflows.

Refer to the Week 4 Canvas assignment for all requirements and submission directions.


## Tailwind Decisions

### Example 1: Responsive Grid Layout
* **Used:** `grid grid-cols-1 md:grid-cols-2 gap-8 md:gap-12`
* **Why:** This solved the problem of cross-device layouts. On mobile screens, it stacks elements (like the hero text/image and the menu cards) vertically for easy scrolling, then automatically expands into side-by-side columns on medium desktop monitors to maximize screen space.

### Example 2: Maximum Width Container boundaries
* **Used:** `max-w-6xl mx-auto px-6`
* **Why:** This prevented the website content from stretching out awkwardly to the edges of wide widescreen desktop viewports. It sets a clean bounding box boundary, centers the site content horizontally, and adds padding on mobile so content never clings directly to the glass edge.

### Example 3: Consistent Interactive Visual Hierarchy
* **Used:** `transition-colors hover:bg-amber-800 focus:ring-2 focus:ring-offset-2`
* **Why:** This fulfills key accessibility and user interaction goals. It provides a smooth visual feedback cue when users hover over an anchor link, and uses an outline ring state so keyboard-only users can clearly track exactly where their interactive navigation focus is on the webpage.