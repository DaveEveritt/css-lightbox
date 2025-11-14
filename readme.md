# CSS lightbox

A responsive CSS-only lightbox: [view demo](https://daveeveritt.github.io/css-lightbox/).

Tested in: Chrome, Edge (OS X/Win), Firefox, Safari (desktop/mobile), Brave

## TO DO

- [ ] add Next and Previous buttons?
- [ ] animate opacity on close (hm. Fixes welcome!)

## DONE

- [x] simplify close box with `position: absolute`
- [x] move figcaption to bottom and centre text
- [x] make opacity default animation, leave drop-down as option
- [x] make entire image click to close
- [x] make gallery preview image height adjustable
- [x] use CSS custom properties for some colors
- [x] fix non-scrolling image height issue
- [x] rewrite HTML and CSS to use `figure` and use `figcaption` tags
- [x] set CSS variables for the crucial dimensions
- [x] fix bug where part of the clickable preview is obscured at wider screen sizes
- [x] center the preview image with `object-fit` and `object-position`
- [x] add breakpoint to separate larger from mobile sizes

---

<small>Very extensively adapted from a good foundation: [Create a pure css image lightbox](https://webdesignerhut.com/pure-css-image-lightbox/)</small>

<!-- alternative version here: https://codepen.io/gschier/pen/HCoqh -->