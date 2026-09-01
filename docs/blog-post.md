# Blog Post

This page type documents single blog post pages.

## Implementation Notes

* Built from WordPress single post template styling in the delivered project scope.
* Content is managed in `Posts` and rendered with consistent blog post design.

## Custom Build Notes (Confirmed in Theme Code)

Single post template includes customizations for:

* Featured image container sizing/spacing
* Share box alignment and icon/button styling
* Custom social icon network output and clipboard label behavior ("Copy link")

## Expected Post Structure

* Title
* Featured image
* Post body content (headings, paragraphs, lists, media)
* Optional metadata (date, author, category)
* Optional related/next-prev navigation depending on current theme settings

## Editing Instructions

1. Go to `Posts` and open the target post.
2. Edit content in Gutenberg editor.
3. Keep heading order semantic (`H2` then `H3`, avoid jumping levels).
4. Add alt text to images for accessibility.
5. Preview before publishing.

## Content Guidelines

* Use short paragraphs for readability.
* Keep image sizes optimized for performance.
* Use consistent button/link styles when adding CTAs inside posts.
* Avoid hard-coded inline styles unless necessary.

## Responsive Notes

* Confirm image widths and tables/embeds are not overflowing on mobile.
* Long URLs should wrap correctly.
* Test post readability across desktop/tablet/mobile previews.
