# SkillSpring — Figma Import and Submission Guide

## What is included
- `figma_design/SkillSpring_Desktop_Design.svg` — full-page desktop visual reference (1440 px wide)
- `figma_design/SkillSpring_Mobile_Design.svg` — mobile visual reference (390 px wide)
- `website/` — working responsive website preview in HTML/CSS/JavaScript
- `DESIGN_SYSTEM.md` — color, type, component, and Auto Layout specifications

## Import the SVG design into Figma
1. Open Figma and create a new Design File.
2. Open the `figma_design` folder from this ZIP after extracting it.
3. Drag `SkillSpring_Desktop_Design.svg` onto the Figma canvas, or use File → Place image and select the SVG.
4. Repeat for `SkillSpring_Mobile_Design.svg`.
5. These SVGs give you a close visual design reference. Depending on Figma's SVG import behavior, elements may come in grouped. Check text and grouping after import.

## Important requirement: Auto Layout and components
Importing an SVG does **not** automatically create true Figma Auto Layout or reusable components. To meet the assignment exactly, select/rebuild these elements in Figma:
- Select the header's logo, links, and CTA and use Shift + A for Auto Layout.
- Create a Primary Button component.
- Create a Feature Card component and use three instances.
- Create a Navigation Link component.
- Create color and typography styles using the values in `DESIGN_SYSTEM.md`.
- Create/adjust a 390 × 844 mobile frame and ensure content stacks without horizontal overflow.
- Save the editable Figma file and set link access to “Anyone with the link can view” if your faculty asks for it.

## Preview the website
Extract the ZIP, open `website/index.html` in Chrome.

## GitHub upload
1. Extract the ZIP.
2. Create a public GitHub repository named `skillspring-responsive-landing-page` (unless your teacher asks for private).
3. Upload the contents of this project folder. Include the SVGs, website folder, and documentation.
4. In the repository, copy the URL from the browser address bar.
5. Paste that URL into the Google Sheet mentioned in the college message.
6. If requested, also submit the Figma file's share link.

## Student explanation
**Product:** SkillSpring is a fictional online learning platform.

**Target audience:** College students, beginners, and early-career learners who want to develop practical technical, design, business, and creative skills.

**Design choices:** Purple represents creativity and progress. White space, readable typography, consistent spacing, and rounded cards make the interface clear and approachable. The desktop layout uses two columns in the hero and three feature cards; the mobile layout stacks content vertically for smaller screens.
