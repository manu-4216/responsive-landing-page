# responsive-landing-page
This is a mobile-first responsive landing page, built from a psd file (mobile and desktop versions)

* `CSS` + `HTML` only, with clean code (structure, comments, BEM)
* `Sass` for separating the `CSS` files using `@import`
  * entry point: `./css/root.scss`)
  * output css bundle: `./css/root.css` -> compiled directly by a code editor pluggin
  * declaration of constants (breakpoints, colors), fonts, mixins in separate files
* fluid typography with vh and vw units [*(source)*](https://www.smashingmagazine.com/2016/05/fluid-typography/)


Final webpage available here:
------------------------
[https://manu-4216.github.io/responsive-landing-page/](https://manu-4216.github.io/responsive-landing-page/)


Optimizations:
* use multiple images of multiple sizes
* add autoprefixer to the build (update: done)
