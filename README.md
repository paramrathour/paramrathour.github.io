# Editorial - Jekyll Theme

A Jekyll version of the [Editorial](https://html5up.net/editorial) theme by [HTML5 UP](https://html5up.net/). Jekyll integration by [Andrew Banchich](https://andrewbanchi.ch/) and hosted by [GitHub Pages](https://pages.github.com/).

This repository contains all the files used for making [this](https://paramrathour.github.io/) site except media assets such as images and documents. Those are stored in a seperate repository called [website-assets](https://github.com/paramrathour/website-assets).

To build it locally, first ensure that the jekyll environment (`JEKYLL_ENV`) is set to `production`.
This can be achieved by running the following command
```
export jekyll_env="production"
```

## Features Added

- Added Jekyll Plugins: used [Github Actions](https://jekyllrb.com/docs/continuous-integration/github-actions/) to run these Plugins
	- [Jekyll Target Blank](https://github.com/keithmifsud/jekyll-target-blank) - Open links other than the host in a new tab (suggested by [Tirthankar](https://wermos.github.io/blog/))
- Cross-platform Favicon support using [realfavicongenerator](https://realfavicongenerator.net/) (suggested by [Tirthankar](https://wermos.github.io/blog/))
- LaTeX support using [MathJax](https://www.mathjax.org/)
- [reCAPTCHA v2](https://developers.google.com/recaptcha/docs/display) support for forms
- Dark Mode Toggle with [slider](https://www.w3schools.com/howto/howto_css_switch.asp) and [javascript](https://stackoverflow.com/questions/42468553/using-sessionstorage-for-saving-dark-mode) inspirations
- [Return to Top Button](https://codepen.io/rdallaire/pen/neMvbX)
- [Accordion](https://www.w3schools.com/howto/howto_js_accordion.asp) for collapsible content
- Time Table (inspired from [Rwitaban](https://github.com/dropTableUsers42))
- Custom URL redirects (inspired from [Sreeman](https://iamsreeman.github.io/))
- [404 Page](https://paramrathour.github.io/404)
- Custom Title of each webpage in the format `page.title | site.author` (inspired from [Aryaman](https://aryamanmaithani.github.io/))
- Option to add hyperlinks to the main images of a page