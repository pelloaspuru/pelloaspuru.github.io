My personal website hosted at pelloaspuru.github.io

Built with [Jekyll](http://jekyllrb.com) and [Hyde](http://hyde.getpoole.com).

Some notes:

# _includes

### archives.html 

### collecttags.html 

### disqus_comments.html 

### google_analytics.html 

### head.html 

- 

### mathjax.html 

### sidebar.html 

- to change/hide the list of pages in the left sidebar, allows to add picture etc.

### social_links.html 

# _layouts

- 

# _site

- 

# fonts

- 

# icons

- Stores the `.svg` icons.
- Search for icons in: `https://fontawesome.com/`

# assets

- 

# photos

- This folder contains the profile pictures for the website.

# public

- Hosts favicons

## css

### hyde.css

hyde.css is the higher-level folder that sets up the global features of the website.

- `@font-face` defines a new type of font.
- Set `max-width: 70rem;` to change the width of the main page.
- Set `text-align: justify;` to justify the main text body of the page.
- Change `sidebar` and `sidebar-about` characteristics.
  - header `h1` charateristics: size, font type etc.
  - links `a` characteristics: color, hover etc.
  - ...

### poole.css

- Set `max-width: 50rem;` to widen the main page.
- Define `.filter-green`, `.filter-gray-light` etc. as filters to change colours of .svg icons.

## _config.yml 
- changes the sidebar title and subtitle.
- Default YAML values establishes the underlying characteristics of each page type.

## index.md 
- configures the front page of the website. 

## publication.md, about.md and category.html... 
- configure the remaining of the website pages.
