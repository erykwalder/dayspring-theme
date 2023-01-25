# Dayspring Theme

This theme is inspired by the unmaintained [al dente](https://github.com/chad-bennett/al-dente-obsidian-theme) legacy theme. Mostly it is just a color theme with some rounded edges, using Obsidian's theme variables and as little custom CSS as possible.

![Fullsize Screenshot](/screenshots/fullsize.png)

## Other Changes

### H6s Beside Paragraphs

This idea is from [Joschua](https://joschuasgarden.com/50+Slipbox/CSS+Obsidian+Snippets). This allows for putting things like verse numbers besides paragraphs in an unobtrusive way, outside of the flow of the main text. This also works on mobile and in embedded content.

![H6 Screenshot](/screenshots/h6.png)

### Hidden Frontmatter in Preview

Frontmatter is not displayed in preview, it is treated as hidden metadata.

### Alternative Note Styling

Notes can be changed to an alternative styling with a serif font and darker background by setting the CSS class in the frontmatter.

```
---
cssclass: altnote1
---
```

`altnote1`, `scripture`, and `source` can all be used interchangeably to set the note to use this styling.

![Alt Style Screenshot](/screenshots/altstyle.png)

## Fonts

This theme uses two fonts:

-   [Crimson Pro](https://fonts.google.com/specimen/Crimson+Pro)
-   [Figtree](https://fonts.google.com/specimen/Figtree)

The fonts are included as variable weight fonts in the CSS, but it may help to install them locally.

## Other Screenshots

![Callouts Screenshot](/screenshots/callouts.png)

![Math Screenshot](/screenshots/math.png)
