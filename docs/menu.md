# Menu

This section covers navigation/menu setup for the delivered WordPress project.

## Primary Menu Management

1. Go to `Appearance > Menus`.
2. Select the primary menu used in the header.
3. Add/remove/reorder menu items as needed.
4. Save menu and verify on front end.

## Custom Build Notes (Confirmed in Theme Code)

Navigation-related customizations in child theme include:

* Header top bar alignment behavior
* Translator area alignment in top row
* Styled "book appointment" button icon treatment in header
* Footer menu separator/link styling for secondary footer menu

## Common Menu Item Types

* Custom links
* Pages
* Categories (for blog navigation)

## Dropdown / Submenu Guidance

* Keep top-level labels short.
* Group related links under one parent item when needed.
* Do not overload a single dropdown with too many links.

## Mobile Menu Guidance

Because no dedicated mobile mockup was supplied, mobile menu behavior follows practical responsive standards:

* Use a collapsed/toggle menu pattern on small screens.
* Keep menu depth shallow for usability.
* Ensure touch spacing is sufficient between links.
* Test open/close interactions and submenu expansion on mobile.

## QA Checklist

* All menu links open the correct destination.
* Active/current page state is visible where applicable.
* No overlapping text or clipped dropdowns on tablet/mobile.
