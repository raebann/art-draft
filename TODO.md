# TODO

## Missing/Incomplete Pages
- taxonomy/tag index page
- projects index page
- publications page
- about page (diff layout fr headshot?)
- 404 page

## Theme
- iamges in single project pages need description/caption
  - if possible support markdown
- add a (scrollable) dropdown menu to "Projects" menu
  - make sure this works properly on mobile!
- wide image lists look weird when there's less than four images
  - do we even want wide images/image lists? discuss
- allow customizing colours (at least accent colour, maybe also fg/bg)
- postcss?
- taxonomies! i.e. tags in frontmatter
- maybe include bold font for site name?
- uhh make sure this is mobile-friendly
  - the main difficulty here is the menu
  - also the image grids/lists need some work
- add a `favicon.ico` (or add an empty one so browser doesn't get a 404)
- review animations & @prefers-reduced-motion

## Other
- write some docs (take existing docs and revamp fr new site)
- review accessibility everywhere
- review page speed everywhere
  - in particular with images-- what does hugo have in terms of optimizing those?
  - also look into [font-display](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face/font-display) to avoid FOIT
  - check that production has good caching for static assets
- review SEO (specifically meta tags in `<head>`: description, etc)
- `robots.txt`: no indexing for anyone!
- create macros(?)
  - images: image tag with alt text, optionally in figure w figcaption
  - blockquotes: figure with blockquote, figcaption, & cite
