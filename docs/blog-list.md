# Blog List

The blog list page is the archive page showing multiple posts (cards/list items) and linking to individual blog posts.

## Implementation Notes

* Built with WordPress posts archive behavior plus delivered front-end styling.
* Styling aligns with homepage/static page visual system.
* Desktop mockup guided design; mobile behavior is responsive best-fit.

## Custom Build Notes (Confirmed in Theme Code)

Blog archive has custom styling in child theme CSS for:

* Archive spacing and container layout
* Custom sort wrapper UI (`.custom-blog-sort-wrap`, form/select styling)
* Sidebar search widget styling
* Entries spacing and responsive behavior

## Content Source

* Blog list content is sourced from WordPress `Posts`.
* Each card item generally uses:
  * Featured image
  * Post title
  * Excerpt/summary
  * Publish date and/or category (if enabled in template)
  * Read more link

## Editing Blog List Behavior

1. Go to `Posts` in WordPress admin to add/edit content.
2. Ensure each post has:
   * Featured image
   * Clean title
   * Short intro/excerpt
   * Correct category/tags (if used)
3. The archive page updates automatically based on published posts.

## Design and QA Rules

* Keep featured image aspect ratios consistent where possible.
* Use similar excerpt lengths to avoid uneven card heights.
* Avoid overly long titles that break layout.
* Check pagination and card spacing after publishing new posts.

## Responsive Notes

* Desktop multi-column cards should collapse into fewer columns on tablet/mobile.
* Ensure tap targets are comfortable and card links remain clear.
