# Hasan Ahmed Siam Portfolio Documentation

## 1. Project Overview

This is a static portfolio website for **Hasan Ahmed Siam (Siam)**, a Video Editor and Graphic Designer based in Noakhali, Bangladesh.

The website presents Siam as a creative service provider for:

- Small businesses
- Restaurants and hotels
- Local businesses
- Personal brands
- Content creators and YouTubers
- Social media pages
- Startups
- Online businesses

The site uses plain HTML, CSS, and JavaScript. It does not require a build tool or package installation.

## 2. Project Files

| File or folder | Purpose |
| --- | --- |
| `index.html` | Page structure, content, navigation, portfolio cards, services, contact form, and footer |
| `stayle.css` | Layout, responsive rules, palette, typography, cards, buttons, hover states, and reveal styling |
| `main.js` | Smooth navigation, active section state, scroll reveal, back-to-top control, card hover behavior, and rotating professional title |
| `images/` | Portfolio images and service illustrations |
| `README.md` | Original repository readme; contains legacy author and project information |
| `DOCUMENTATION.md` | Current product and maintenance documentation |

The stylesheet is named `stayle.css` in the existing project. Keep this spelling unchanged unless the HTML reference is updated at the same time.

## 3. Information Architecture

### Home / Hero

The first viewport communicates the main professional identity:

- Name: Hasan Ahmed Siam
- Preferred name: Siam
- Title: Video Editor & Graphic Designer
- Short value statement about videos, design, brands, creators, and technical knowledge
- Location: Noakhali, Bangladesh
- Availability: Open to creative projects
- Primary CTA: View My Work
- Secondary CTA: Contact Me
- Profile image and professional title rotation

### About Me

The About section explains Siam's background and working direction:

- Computer Science & Engineering student
- Video editing and graphic design focus
- Digital content creation and small business interest
- Intended clients and audiences
- Technical foundation: Python, JavaScript, TypeScript, HTML, CSS, React, Git, Windows, and Linux

The About section now includes an `Expert in Tools` showcase with downloaded SVG logos for:

- Adobe After Effects
- DaVinci Resolve
- Adobe Photoshop
- Adobe Illustrator
- Adobe Premiere Pro

The logos are stored in `images/tools/` and are presented as compact responsive tool cards.

### Selected Work

The portfolio grid currently contains six creative case-study placeholders:

- Brand Identity System
- Social Campaign
- Thumbnail Direction
- Editorial Layout
- Motion Graphics Opener
- Short-Form Video Edit

Each card contains an image, a project description, category data, skill tags, and a contact-based request-details link. Visitors can filter the grid by All Work, Graphic Design, Video, or Social Content.

Replace the placeholder images and `href="#"` links with real project pages, Behance links, Google Drive links, YouTube links, or hosted videos before launch.

### Services

The services section communicates the current offer:

- Video Editing
- Social Media Content
- Graphic Design
- Promotional Design

The descriptions mention reels, Shorts, YouTube edits, transitions, color correction, audio sync, posts, posters, banners, advertisements, thumbnails, and branding materials.

### Contact

The contact section includes:

- Project invitation copy
- Freelance availability
- Service focus
- Noakhali, Bangladesh location
- Name, email, and message form fields

The form is currently visual only. It needs a backend, Formspree, EmailJS, Netlify Forms, or another form service before it can send messages.

### Footer

The footer contains the name, section navigation, and professional identity/location line.

## 4. Visual Design System

### Color Palette

The website uses a warm brown and parchment palette defined in `stayle.css` under `:root`:

| Variable | Color | Recommended role |
| --- | --- | --- |
| `--palette-lightest` | `#f6e7d9` | Main page background, light text |
| `--palette-light` | `#d8c5b1` | Navigation, tags, soft surfaces |
| `--palette-soft` | `#bca39b` | Badges, hover surfaces, secondary accents |
| `--palette-muted` | `#a68d7b` | Borders, muted text, separators |
| `--palette-warm` | `#8b6a54` | Supporting text and secondary accents |
| `--palette-brown` | `#6f4e37` | Main accent, service hover, buttons |
| `--palette-deep` | `#5c3b26` | Card headings and button hover states |
| `--palette-dark` | `#4a2c1e` | Body copy and borders |
| `--palette-darker` | `#3a1e14` | Hero heading |
| `--palette-darkest` | `#2c0f0c` | Navigation active state, footer, primary text |

When adding new styles, use the variables instead of introducing unrelated colors.

### Typography

External Google fonts are loaded in `index.html`:

- Montserrat: navigation, footer branding, and strong UI labels
- Open Sans: section headings
- Playfair Display: hero professional title
- Unbounded: available for future display use

The page also includes Font Awesome for icons.

### Layout Language

The current visual language uses:

- Fixed pill navigation on desktop
- Large editorial hero type
- Warm neutral surfaces
- Rounded cards and buttons
- Grid-based project and service layouts
- Subtle lift effects on cards
- Strong contrast between light content areas and dark footer

## 5. Interaction Behavior

`main.js` currently provides:

- Smooth scrolling for navigation links
- Responsive menu toggle for tablet and phone layouts
- Active navigation item changes while scrolling
- Scroll reveal classes for major content containers
- Back-to-top button after scrolling down
- Hover lift effect on project, skill, and service cards
- Portfolio filtering by category
- Rotating typewriter title in the hero
- Client-side contact form feedback and reset behavior

The startup loading overlay was removed. The reveal transition is intentionally very short at approximately `0.04s` in the current stylesheet.

## 6. Responsive Behavior

The CSS includes responsive rules for tablet and phone widths:

- Desktop uses wide section margins and horizontal layouts.
- At smaller widths, content stacks vertically.
- Project and service grids collapse to one column on phones.
- Images become fluid and receive a maximum width.
- Desktop navigation is hidden on phone layouts.
- CTA buttons become full width on small screens.
- Text wrapping and horizontal overflow are constrained.

Before publishing, test at minimum:

- 1440 x 900 desktop
- 1024 x 768 tablet
- 390 x 844 phone

## 7. Asset Guidelines

The `images/` directory currently contains JPG, PNG, and SVG assets. Every portfolio image should represent the work described by its card.

For a professional creative portfolio:

- Use real screenshots, artwork, thumbnails, and video stills.
- Use consistent image ratios within the project grid.
- Add accurate `alt` text describing the visual work.
- Compress large images before publishing.
- Use a real video thumbnail or poster frame for video projects.
- Link each card to a case study, video, or gallery instead of leaving `href="#"`.

The current images are inherited or illustrative placeholders and some do not literally match their new creative project labels. Replacing them is the highest-value content improvement.

## 8. Content Writing Guidelines

Keep future copy:

- Specific about the service and outcome
- Short enough to scan quickly
- Focused on the client, audience, and communication goal
- Free of generic filler such as "Lorem ipsum"
- Honest about current experience and capability
- Consistent with the name Siam and the location Noakhali, Bangladesh

Prefer:

> I edit short-form videos with clean pacing, captions, color correction, and platform-ready framing.

Avoid:

> I provide high-quality solutions for all your needs.

## 9. Known Limitations

1. The contact form has client-side feedback but no email delivery service. Connect Formspree, EmailJS, Netlify Forms, or a backend before launch.
2. The current project images do not all match their creative labels. Replace them with Siam's actual work samples.
3. The page has no dedicated case-study pages or video embeds.
4. The current social/profile URLs are intentionally omitted until Siam provides real accounts.
5. `README.md` contains legacy repository information and should be rewritten for Siam's portfolio.

## 10. Recommended Next Improvements

### Priority 1: Trust and conversion

- Add real portfolio images and links.
- Connect the contact form to a working submission service.
- Add real social/profile links when available.
- Add a downloadable CV or creative profile PDF only if available.

### Priority 2: Creative portfolio depth

- Add separate Video Projects and Graphic Design filters.
- Add project detail pages with brief, role, process, tools, and final result.
- Embed selected YouTube, Vimeo, or hosted video work.
- Add before-and-after examples for editing and design.

### Priority 3: Technical polish

- Improve keyboard focus states and form feedback.
- Consolidate the duplicate responsive media-query blocks in `stayle.css`.
- Rename `stayle.css` to `style.css` only with a coordinated HTML update.

## 11. Maintenance Workflow

1. Update content in `index.html`.
2. Add or replace matching files in `images/`.
3. Use palette variables from `stayle.css` for new visual styles.
4. Update `main.js` only for behavior changes.
5. Run `node --check .\\main.js` after JavaScript edits.
6. Search for old identity, placeholder links, and placeholder copy before publishing.
7. Test desktop and mobile layouts in a browser.

## 12. Launch Checklist

- [ ] Replace all placeholder project images.
- [ ] Add real project/case-study URLs where available.
- [ ] Connect and test the contact form.
- [ ] Confirm name, title, location, and education details.
- [ ] Check every image `alt` attribute.
- [ ] Test navigation and back-to-top behavior.
- [ ] Test mobile layout and keyboard focus.
- [ ] Rewrite the legacy README.
- [ ] Run JavaScript syntax validation.
- [ ] Publish only after real work samples are visible.
