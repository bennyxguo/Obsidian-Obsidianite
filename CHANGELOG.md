# CHANGELOG

## Version 1.1.3 (Nov 21, 2020)

### New Diamonds 💎

- Completely reworked custom checkbox with awesome animations!
- Added front-meta theme styles.

### Improvements ⚡️

- Changed external links’ styles in preview mode, made it more suitable in sentences. (Before they are italic formats, which doesn’t look natural)
- Making link urls and formatting part less bright, reduce focus from the the actual content part.
- Adding themed style for image links
- Changed the block-quote to have full width.

### Fixes 🔧

- Editor mode’s links font color is same as the formatting markup color, makes it hard to read.
- Fixed list circle icon not showing as a full circle. Thanks to the sharp eyes out there spotting this!

## Version 1.1.2 (Nov 18, 2020)

### New Diamonds 💎

- Themed editor view blockquote
- Themed editor view tags

### Improvements ⚡️

- Dimming the brightness of internal link brackets in editor view.
- At default bold text, headline, italic text for clutter free editor mode are disabled, due to the changing of the interface while editing, creates an uncomfortable experience with writing.

## Version 1.1.1 (Nov 17, 2020)

### Improvements ⚡️

- Taking the suggesting from the community, removing the clutter free editor mode's headings `h1, h2, h3`, now just hide the `#` completely instead.

### Fixes 🔧

- Fixed the clutter free editor mode for list are not displaying correctly if spaces are added in front or at the back of the `+` sign.
- Fixed the clutter free editor mode destroyed the display of numbers for ordered lists.

## Version 1.1.0 (Nov 17, 2020)

### New Diamonds 💎

- Added fully advanced clutter free mode for:
  - HR lines
  - inline-code
  - Headings
  - Lists
  - Bold text
  - Italic text
- Added customizable theme variables at the beginning of css file, so it’s easier for theme editors to fine tune the theme. (Will add more variables at this part later versions)

### Improvements ⚡️

- Reorganized all the CSS styles code to place editor mode and preview mode styles together, for easier syncing with two.
- Changed the colors of the navigation icons to less standout while inactive.

### Fixes 🔧

- Bold LaTeX disappears in the preview

## Version 1.0.4 (Nov 7, 2020)

### New Diamonds 💎

- Added the `check box` custom styles
- Added `Dracula` syntax colors for `code blocks` in both preview and editor mode. (These two mode's code syntax colors may varies, because each use different renderer in Obsidian.)
- Added the [Glow Sans SC](https://github.com/welai/glow-sans) Chinese font as a default for Chinese characters. For those that want to use it, you must install the font on your OS. (#1)

> Code Block Syntax color support require you have Obsidian version 0.9.10+, also require to install the [cm-editor-syntax-highlight-obsidian](https://github.com/deathau/cm-editor-syntax-highlight-obsidian/releases/tag/0.0.1) plugin.

### Improvements ⚡️

- Changed the matching logic for all special tags, now if the tag contains the special tag's words, will make them turn into special colors (before we need the special tag word be the starting of the tag to work).

### Fixes 🔧

- Changed the use of border style instead of background style for `hr` tags, as `death-au` found out that background doesn't render in PDF export.
- Fixed the `inline code blocks` keep shaking in preview mode, when typing new letters in the editor.

## Version 1.0.3 (Nov 1, 2020)

### Tweaks 💎

- Making link's text much more clear and readable with the custom underline style.
- Changed the editor view of the link style to match the effect of the preview link style.

## Version 1.0.2 (Oct 31, 2020)

After being writing and reading for hours myself, I find a few tweaks needed to be made.

So I did a lot of little and big tweaks to make Obsidianite theme have a better user experience.

I have also adapted to Obsidian's plugin standard of version naming convention, removing the "v".

Hope you all like this update, and please feel free to give me feedbacks! Happy note taking! 💎

### Tweaks 💎

- Enhanced on the **BOLD** text, now using a gradient text color for amazing eye catchy experience, but not too much that will hurt our eyeballs.
- Reworked on the major colors, reduced the use of pink-purple colors for better long term reading and writing. (The purple colors looks good at first, but after long writing and reading, it feels a bit too much of a highlight).
- Obisidian title bar's text had changed to Obsidianite blue, just to stay overall color sync.
- Changed the color of file icon next to the file title, again to stay overall color sync.

## Version 1.0.1 (Oct 31, 2020)

### Bug fixes 🐛

- Fixed when numbered list going over 10+, the text in preview mode will randomly drop into 2 lines.
- Fixed a few spelling errors in the css documents.
