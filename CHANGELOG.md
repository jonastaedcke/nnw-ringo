# Changelog

## [1.12.0](https://github.com/jonastaedcke/nnw-ringo/compare/v1.11.1...v1.12.0) (2026-10-24)

### Added

* give the code header the code's color, set off by a line
* blend image and video backgrounds close to the page's into the page, except while pointed at
* hide line breaks next to blocks that are already spaced

### Fixed

* wrap loose text between two line breaks in paragraphs

## [1.11.1](https://github.com/jonastaedcke/nnw-ringo/compare/v1.11.0...v1.11.1) (2026-10-23)

### Fixed

* color code blocks that a feed split into unstyled spans
* limit code snippet embeds to 80% of the window height

## [1.11.0](https://github.com/jonastaedcke/nnw-ringo/compare/v1.10.0...v1.11.0) (2026-10-23)

### Added

* highlight the syntax of code blocks
* link the license and the latest release notes in the theme settings

### Fixed

* keep the popover below a footnote in the first paragraph

## [1.10.0](https://github.com/jonastaedcke/nnw-ringo/compare/v1.9.0...v1.10.0) (2026-10-23)

### Added

* fold toggle cards like a details box
* link the release notes in the theme settings
* set alerts and callout cards off like quotes

### Fixed

* keep images in footnotes and list items in the column
* keep the line breaks before and after blocks
* space wrapped tables like the blocks around them

## [1.9.0](https://github.com/jonastaedcke/nnw-ringo/compare/v1.8.0...v1.9.0) (2026-10-23)

### Added

* give links and buttons a hover and focus state
* hide a horizontal rule right before a heading
* size CodePen embeds from their src and center images in <center>

### Fixed

* color the settings close button like the R on the photo
* drop the underline and bold of link text wrapped in <u> or <strong>
* find a footnote's note by its return link when the feed drops ids
* recognize footnote links whose scheme differs from the page's base

## [1.8.0](https://github.com/jonastaedcke/nnw-ringo/compare/v1.7.0...v1.8.0) (2026-10-22)

### Added

* animate the theme settings in and out

### Fixed

* dim buttons only slightly, so filled ones keep their contrast
* let Tab reach the theme settings' buttons and return focus on close

## [1.7.0](https://github.com/jonastaedcke/nnw-ringo/compare/v1.6.0...v1.7.0) (2026-10-22)

### Added

* add theme settings with an update check
* open footnotes of common providers as popovers
* scale the text up on the iPad

### Fixed

* give footnote markers one size and seat and keep footnote popovers clear of the window edges
* hide line breaks before and after blocks
* hide the external link when the article has none
* hide WordPress's teasers for other articles
* inset Ghost galleries from the window edges
* keep details boxes in the column
* keep nested, borderless and code tables plain
* keep the proportions of images sized by inline style or automatic sizes
* keep WordPress emoji images in the line
* never synthesize bold or italic
* show video embeds from unknown hosts at 16:9 and keep the height of other embeds

## [1.6.0](https://github.com/jonastaedcke/nnw-ringo/compare/v1.5.0...v1.6.0) (2026-10-21)

### Added

* show the dateline in the browser language

### Fixed

* stop articles with wide images from scrolling sideways

## [1.5.0](https://github.com/jonastaedcke/nnw-ringo/compare/v1.4.2...v1.5.0) (2026-10-21)

### Added

* add a copy button to code blocks

### Fixed

* restyle footnote popovers and markers

## [1.4.2](https://github.com/jonastaedcke/nnw-ringo/compare/v1.4.1...v1.4.2) (2026-10-20)

### Fixed

* crop the feed icon to a square and color only the header links
* draw horizontal rules in the code surface color
* extend a details box like a figure and keep its media in it
* hide line breaks between list items
* quote the feed name in the icon's alt text and space the icon from the dateline
* show the code surface color behind media until it loads

## [1.4.1](https://github.com/jonastaedcke/nnw-ringo/compare/v1.4.0...v1.4.1) (2026-10-20)

### Fixed

* give embedded iframes a 16:9 height ([#2](https://github.com/jonastaedcke/nnw-ringo/issues/2))
* hide a heading that repeats the article title at the start of the body
* hide padding paragraphs that hold only empty inline elements
* keep linked bylines in the accent color ([#1](https://github.com/jonastaedcke/nnw-ringo/issues/1))
* remove the outer margins of blocks inside captions
* round the corners of floated media
* start the first block of nested article bodies flush with the header
* use the feed title as the icon's alt text ([#1](https://github.com/jonastaedcke/nnw-ringo/issues/1))

### Documentation

* license the theme under Apache-2.0
* show Ringo on Mac and iPhone in light and dark mode in the README

## [1.4.0](https://github.com/jonastaedcke/nnw-ringo/compare/v1.3.0...v1.4.0) (2026-10-19)

### Added

* hide empty padding paragraphs
* round extended media corners while the window leaves room

### Fixed

* lay out queer.de image boxes and drop duplicate enclosure thumbnails

### Documentation

* explain why Article JavaScript helps

## [1.3.0](https://github.com/jonastaedcke/nnw-ringo/compare/v1.2.0...v1.3.0) (2026-10-19)

### Added

* add increased contrast palette for light and dark mode

### Fixed

* float media with sanitized WordPress alignment classes

### Documentation

* add light and dark README previews
* update highlights and note AI-assisted development

## [1.2.0](https://github.com/jonastaedcke/nnw-ringo/compare/v1.1.1...v1.2.0) (2026-10-18)

### Added

* lay out Ghost and WordPress galleries, bookmark cards and portrait videos

### Fixed

* let text wrap around floated images
* round embeds without a border and keep enclosures in the column

## [1.1.1](https://github.com/jonastaedcke/nnw-ringo/compare/v1.1.0...v1.1.1) (2026-10-17)

### Fixed

* extend WordPress caption boxes like figures

## [1.1.0](https://github.com/jonastaedcke/nnw-ringo/compare/v1.0.0...v1.1.0) (2026-10-16)

### Added

* generate design tokens with Style Dictionary
* scale type and spacing from base tokens
* show the feed icon in the article header

### Fixed

* meet WCAG AA text contrast in light and dark mode

### Documentation

* list the theme's highlights in the README

## 1.0.0 (2026-10-15)
