## Part 3 Changelog
| Date | Change | Reason |
|------|--------|--------|
| 2026-11-03 | Fixed [describe the Part 2 problem] | Lecturer feedback on Part 2 |
| 2026-11-03 | Added JSON listings with search and filter | Part 3: dynamic content |
| 2026-11-03 | Added FAQ accordion, Leaflet map and lightbox | Part 3: interactive elements |
| 2026-11-03 | Added SEO meta tags, robots.txt and sitemap.xml | Part 3: SEO |
| 2026-11-03 | Added enquiry and contact forms with validation | Part 3: forms |
| 2026-11-03 | Updated README and references | Part 3: documentation |

## References
- Leaflet - https://leafletjs.com
- OpenStreetMap contributors - https://www.openstreetmap.org/copyright
- Formspree - https://formspree.io
- MDN Web Docs - https://developer.mozilla.org
- Images: [your photo sources]# TN Real Estate — Website Project

## Project Title
TN Real Estate Website (WEDE5020 POE)

## Student Information
- Name: [Your Full Name]
- Student Number: [Your Student Number]
- Group: [Your Group, if applicable]

## Project Overview
A seven-page website for TN Real Estate, a new property and
accommodation service that connects people with homes, rooms, offices,
and event spaces to rent or buy. The site lets visitors search and
browse listings by category, and gives property owners a way to list
their own properties.

## Website Goals and Objectives
- Let people search for and enquire about properties online.
- Give property owners an easy way to list their properties.
- Make it simple to find rooms, homes, offices, and event venues in one place.

### Key Performance Indicators (KPIs)
- How many property enquiries come in each month.
- How many properties get listed by owners.
- How many visitors use the search bar.

## Target Audience
Home buyers, renters, students, business owners, and anyone planning an
event who needs a home, room, office, or venue.

## Key Features and Functionality
- Homepage with a large search bar and property categories.
- Properties page showing available homes, prices, and details.
- Rooms page for people looking for affordable rooms.
- Hotels & Accommodation page for short stays and holidays.
- Event Venues page for weddings, meetings, and other events.
- A "List Your Property" page so owners can submit their properties.
- Contact page with details for enquiries.
- Consistent navigation menu across all seven pages.

## Design and User Experience
- **Colour Scheme:** Navy blue, white, and grey, to feel clean and trustworthy.
- **Typography:** A single font (Arial) used throughout the site.
- **Layout:** A large search bar on the homepage, clear category cards,
  and simple buttons throughout, so information is easy to find.

## Technical Requirements
- Domain name (planned): tnrealestate.co.za
- Built with HTML, CSS, and (in Part 3) JavaScript.

## Timeline and Milestones
| Milestone | Target |
|---|---|
| Planning and research | Part 1 due date |
| HTML structure (all 7 pages) | Part 1 due date |
| CSS styling and responsive design | Part 2 due date |
| JavaScript functionality (search, etc.) | Part 3 due date |
| Testing and going live | Final due date |

## Part 1 Details
This submission includes:
- The HTML structure for all 7 required pages (Home, Properties, Rooms,
  Hotels & Accommodation, Event Venues, List Your Property, Contact).
- A consistent header, navigation menu, and footer on every page.
- Folder structure: root HTML files, with `css/`, `js/`, and `images/` subfolders.

## Part 2 Details
This submission also includes:
- A single external stylesheet (`css/style.css`) linked from every page.
- A CSS reset (`*`), base typography, and a navy/white/grey colour scheme
  applied site-wide, per the approved proposal.
- The navigation menu built as a `nav > ul > li > a` structure, styled
  with `nav ul` (flexbox) and `nav ul li a` selectors.
- A homepage search bar (`.search-bar`) with a location input, a
  category dropdown, and a search button — front-end only for now;
  it will be wired up to real search results in Part 3.
- A reusable `.container` / `.container div` grid pattern used for the
  homepage category cards and every listings page (Properties, Rooms,
  Hotels & Accommodation, Event Venues) — any `div` placed inside a
  `.container` is styled automatically, without needing an extra class.
- Interactive states (`:hover`, `:focus`, `:active`) on links, buttons,
  and form fields, plus `box-shadow` for depth on cards and buttons.
- Full responsive design: two breakpoints — `@media screen and
  (max-width: 768px)` for tablet and `@media screen and (max-width:
  480px)` for mobile — the `.container` grids collapse from 3 columns
  to 2 to 1, the navigation stacks vertically, and the search bar
  stacks into a single column on smaller screens.
- Screenshot evidence of the desktop, tablet, and mobile views has been
  added to `/screenshots` and is referenced below.

### Known Placeholders To Update Before Final Submission
- **No real property photos were supplied**, so every listing currently
  shows a grey "Photo Coming Soon" box (`.photo-placeholder`) instead of
  a real image. Replace these with actual `<img>` tags once you have
  photos, following the same pattern used in the T.C. Carpentry/CrenShaws
  sites (`srcset` with a few resized versions of each photo).
- **Contact page map**: `contact.html` has an HTML comment showing
  exactly where to paste your Google Maps `<iframe>` embed code.
- **List Your Property page form**: `list-property.html` has an HTML
  comment showing where to paste your Google Forms `<iframe>` embed code.
- **Phone/email** on the Contact page, and the listing prices/suburbs
  on the Properties/Rooms/Hotels/Venues pages, are placeholders — swap
  in your real listings once you have them.

### Screenshot Evidence
| Page | Desktop | Tablet | Mobile |
|---|---|---|---|
| Home | `screenshots/home-desktop.png` | `screenshots/home-tablet.png` | `screenshots/home-mobile.png` |
| Properties | `screenshots/properties-desktop.png` | `screenshots/properties-tablet.png` | `screenshots/properties-mobile.png` |
| Rooms | `screenshots/rooms-desktop.png` | `screenshots/rooms-tablet.png` | `screenshots/rooms-mobile.png` |
| Hotels & Accommodation | `screenshots/hotels-desktop.png` | `screenshots/hotels-tablet.png` | `screenshots/hotels-mobile.png` |
| Event Venues | `screenshots/venues-desktop.png` | `screenshots/venues-tablet.png` | `screenshots/venues-mobile.png` |
| List Your Property | `screenshots/list-property-desktop.png` | `screenshots/list-property-tablet.png` | `screenshots/list-property-mobile.png` |
| Contact | `screenshots/contact-desktop.png` | `screenshots/contact-tablet.png` | `screenshots/contact-mobile.png` |

*(Add the actual PNG/JPG screenshots to a `screenshots/` folder in the
repository root before submitting — capture each page at ~1440px wide
for desktop, ~800px for tablet, and ~375px for mobile using your
browser's device toolbar or dev tools.)*

## Sitemap
```
Home (index.html)
├── Properties (properties.html)
├── Rooms (rooms.html)
├── Hotels & Accommodation (hotels.html)
├── Event Venues (venues.html)
├── List Your Property (list-property.html)
└── Contact (contact.html)
```
All pages are on the same level and are reachable from the main
navigation menu on every page.

## Changelog

### Part 1
- [Date] — Initial HTML structure created for all 7 pages.
- [Date] — Consistent header, navigation, and footer added to every page.

### Part 2
- [Date] — Linked a single external stylesheet (`css/style.css`) from every page.
- [Date] — Applied the navy/white/grey colour scheme and Arial
  typography from the approved proposal.
- [Date] — Built the homepage search bar and category cards.
- [Date] — Built the Properties, Rooms, Hotels & Accommodation, and
  Event Venues listing pages using a `.container`/`.container div` grid.
- [Date] — Added `box-shadow` to cards and buttons, and `:hover`,
  `:focus`, `:active` states to nav links, buttons, and form fields.
- [Date] — Implemented responsive design: added `@media screen and
  (max-width: ...)` breakpoints at 768px (tablet) and 480px (mobile).
- [Date] — Added placeholder comments for the Google Maps embed
  (Contact page) and Google Form embed (List Your Property page).

## References
- MDN Web Docs — CSS Grid Layout: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout
- MDN Web Docs — Using media queries: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries
- MDN Web Docs — CSS pseudo-classes (`:hover`, `:focus`, `:active`):
  https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes
- Google Maps embed used on the Contact page: https://www.google.com/maps
  (no API key required for basic `output=embed` iframes).
- Google Forms used for the List Your Property page: https://forms.google.com

## Part 3 chanelog
| data |change | reason |
|------|-------|--------|
2026-11-01 | AddedJSON-driven lisstings with search and filter | part 3: dynamic conteny and search  |
