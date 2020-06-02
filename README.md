# minimal-firefoxcss-dark
![preview](https://j.gifs.com/P7wZpW.gif)

A collection of configurable CSS files that transforms Firefox into a responsive, minimal, and functional browser.

## Addon dependencies
**[Tree Style Tab](https://addons.mozilla.org/en-US/firefox/addon/tree-style-tab/) paired with [TST Colored Tabs](https://addons.mozilla.org/en-US/firefox/addon/tst-colored-tabs/) is highly recommended in order to get the intended experience!**
If you decide not to use these addons, you can either remove files with the "tst" prefix from `userChrome.css` or delete them.

## Installation
* In Firefox's preferences, ensure that the native dark theme is enabled, preferably on compact mode.
* Put `userChrome.css` and `userChrome` in your Firefox profile root's `chrome` directory.
* In your Tree Style Tab preferences, change the theme to Vertigo and paste the contents of `tst-css.css` into Advanced > Extra style rules.

## Configuration
Modify `vars.css` to suit your specific needs. Differences from varying window buttons sizes to color preferences can be accomodated for. To apply these changes to TST, you can copy + paste the variables into `tst-css.css`.

CSS files are modularized so as to ease configuration and debugging. If you don't like how this theme affects a certain part of Firefox, you can just remove the CSS file associated with it.

## Contribution
All help is appreciated, whether it be in the form of feedback, issue tracking, or pull requests!

## Acknowledgements
Much inspiration and code was taken from [compact TST CSS](https://www.reddit.com/r/FirefoxCSS/comments/7emhsq/my_compact_treestyletab_css_and_sidebar_hover/), [Responsive Minimal Firefox](https://www.reddit.com/r/FirefoxCSS/comments/8j0tek/responsive_minimal_firefox/), and [Blur Style Bookmarks Bar + Autohide](https://www.reddit.com/r/FirefoxCSS/comments/famrs0/blur_style_bookmarks_bar_autohide/). Thank you to the authors of these styles!
