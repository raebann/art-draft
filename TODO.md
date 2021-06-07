# TODO

## Missing/Incomplete Pages
- taxonomy/tag index page
- projects index page
- publications page
- about page (diff layout fr headshot?)
- 404 page

## Theme
- add a (scrollable) dropdown menu to "Projects" menu
  - make sure this works properly on mobile!
- allow customizing colours (at least accent colour, maybe also fg/bg)
- postcss?
- taxonomies! i.e. tags in frontmatter
- maybe include bold font for site name?
- dark theme media query? (switch to css vars)
  - make sure to include options for both themes for any customizable colours
- uhh make sure this is mobile-friendly
  - the main difficulty here is the menu
- add a `favicon.ico` (or add an empty one so browser doesn't get a 404)

## Other
- write some docs (take existing docs and revamp fr new site)
- review accessibility everywhere
- review page speed everywhere
  - in particular with images-- what does hugo have in terms of optimizing those?
  - also look into [font-display](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face/font-display) to avoid FOIT
  - check that production has good caching for static assets
- review SEO (specifically meta tags in `<head>`: description, etc)
- `robots.txt`?
- create macros(?)
  - images: image tag with alt text, optionally in figure w figcaption
  - blockquotes: figure with blockquote, figcaption, & cite
