<!-- nnw-theme-identity:start -->

# Ringo

<!-- nnw-theme-identity:end -->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="screenshots/readme-dark.png">
  <img alt="Ringo on Mac and iPhone in light and dark mode" src="screenshots/readme-light.png">
</picture>

Ringo is a calm, focused reading theme for [NetNewsWire](https://netnewswire.com),
inspired by the article design of [Reeder Classic](https://www.reederapp.com/classic/).

## Highlights

- **Large images.** Photos, videos and figures extend into the page margins,
  while their captions stay aligned with the text.
- **Readable contrast.** All text colors meet the WCAG AA contrast ratio of at
  least 4.5:1, and AAA (7:1) when Increase Contrast is turned on, in light and
  dark mode.
- **Light and dark.** Follows the system appearance on Mac, iPhone and iPad.
- **Your text size.** Follows the text size chosen in NetNewsWire on the Mac
  and Dynamic Type on iPhone and iPad.
- **Comfortable line length.** The article sits in a narrow column that grows
  with the text size, and headlines wrap into balanced lines.
- **Calm layout.** Images the publisher floats stay beside the text at no more
  than half the column width, and wide tables and code blocks scroll instead
  of breaking the page.
- **System fonts.** Uses the San Francisco family; nothing is downloaded.

### JavaScript

Turn on Article JavaScript in NetNewsWire for Ringo to apply all of its
styles. Ringo stays readable without it, but some fixes need a
small script, which then adds:

- **Cleaner articles.** Hides the empty paragraphs (`<p>&nbsp;</p>`) that many
  feeds use as spacers and a heading at the very start of the article that
  repeats its title, and keeps WordPress images that only state their width
  from being squashed.
- **Footnotes in place.** Opens the footnotes of common providers in a popover
  next to their marker instead of jumping to the end of the article, and keeps
  a marker on the same line as its word.
- **Copy button.** Puts a button in the top right corner of every code block
  that copies the code to the clipboard.
- **Date in your language.** Shows the publication date and time in your language.
- **Theme settings.** The R logo in the article header opens the theme
  settings, where you can check for updates. A dot on the logo tells you when
  a new version is available. The update check connects to GitHub.

## Install

[Add to NetNewsWire](https://jonastaedcke.github.io/nnw-ringo/install/) · [NetNewsWire Theme Marketplace](https://dave-atx.github.io/nnw-theme-marketplace/#dejonastaedckethemesringo)

With Article JavaScript on, Ringo tells you about new versions itself (see
above). You can also subscribe to the
[release feed](https://github.com/jonastaedcke/nnw-ringo/releases.atom) in
NetNewsWire. It announces updates; it does not install them.

## Credits

- [Ember](https://github.com/dave-atx/ember-nnw-theme) by Dave Marquard: the
  script that opens the footnotes of common providers as popovers is adapted
  from its footnote adapter (Apache License 2.0).
- [nnw-theme](https://github.com/dave-atx/nnw-theme) by Dave Marquard: the
  tooling that checks, renders and packages the theme.
- [Reeder Classic](https://www.reederapp.com/classic/): the inspiration for the
  article design.
- [Zhang liven](https://unsplash.com/@lvenfoto):
  [“Misty blue mountains rise above calm water”](https://unsplash.com/photos/BiLh-YznD0I)
  (Unsplash License).
