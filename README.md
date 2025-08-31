# allons-y CSS

This is a CSS file that provides basic typography for any website, especially a website with a lot of text to read. It's based on a few principles of classic design with a modern twist and my own personal preferences.

Basically, it's how I like to read a page online.

There are no colors, fonts, or structure, just margins and sizes to make a generally readable article. I use it as a base and create a separate file for each individual site's styles.

This is based on the whole "lobotomized owl" design system, as shown by [this talk by Andy Bell](https://www.youtube.com/watch?v=5uhIiI9Ld5M).

## What is this?

`allons-y` is a minimal, opinionated CSS system for readable, vertical content. It’s not a framework, not a theme, and not a reset (though it uses one). It’s just a set of sensible defaults for vertical rhythm, spacing, and readable line lengths—no colors, no fonts, no layout, no nonsense. Drop it in, and your text-heavy site is instantly more comfortable to read.

Inspired by classic book design, modern web best practices, and a little bit of stubbornness about what makes a page feel good to read.

## Why?

Because most CSS frameworks are overkill for simple, text-driven sites. I wanted something that just makes paragraphs, headings, lists, and other content blocks look right—without fighting with a million utility classes or overwriting someone else’s design system.

## How does it work?

- Uses a vertical rhythm for all content blocks (think: vertical content stacks, not side-by-side grids)
- Applies a "lobotomized owl" selector (`* + *`) for consistent spacing between elements ([read more](https://css-tricks.com/the-lobotomized-owl/))
- Keeps line lengths readable and font sizes sensible
- No colors, no fonts, no layout—just spacing and sizing
- Easy to override: just add your own CSS after

For more on the thinking behind this, check out [Utopia.fyi](https://utopia.fyi/) for fluid type and space, [The Lobotomized Owl](https://css-tricks.com/the-lobotomized-owl/) for the spacing trick, and [Every Layout: The Stack](https://every-layout.dev/layouts/stack/) for vertical content stacks.


## How to use

1. Download or copy `allonz-y.css` into your project.
2. Link it in your HTML before your own styles:

	```html
	<link rel="stylesheet" href="/path/to/allonz-y.css">
	<link rel="stylesheet" href="/your-site-styles.css">
	```

3. Add your own colors, fonts, or layout as needed. This file only sets up spacing and readable defaults.

**Note:** Depending on your chosen font, you may want to adjust `line-height` or `letter-spacing` for best results. The defaults are tuned for common web fonts, but every typeface is a little different.

## Demo

I've installed a demo with some dummy text on my server at [https://www.yakdrive.io/allonz-y](https://www.yakdrive.io/allonz-y).

## Inspirations

- Anything by [Edward Tufte](https://www.edwardtufte.com/), including [Tufte CSS](https://edwardtufte.github.io/tufte-css/)
- Anything by [Jan Tschichold](https://en.wikipedia.org/wiki/Jan_Tschichold)
- [Technical Web Typography: Guidelines and Techniques](https://www.smashingmagazine.com/2011/03/technical-web-typography-guidelines-and-techniques/)
- [Intro to Golden Rule Typography](https://pearsonified.com/golden-ratio-typography-intro/)
- [Utopia.fyi](https://utopia.fyi/)
- [The Lobotomized Owl](https://css-tricks.com/the-lobotomized-owl/)
- [Every Layout: The Stack](https://every-layout.dev/layouts/stack/)
