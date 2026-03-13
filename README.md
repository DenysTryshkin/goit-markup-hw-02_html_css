## Mentor Acceptance Criteria

### Project
- **A1** The project root contains an `images` folder with images.
- **A2** The project root contains a `css` folder with a stylesheet file.
- **A3** All styles are written in a single `styles.css` file located in the `css` folder.
- **A4** File names do not contain uppercase letters, spaces, or transliteration. Names include only English letters and words.
- **A5** The source code is formatted using Prettier.
- **A6** All images and text content are taken from the layout.
- **A7** The style normalizer `modern-normalize` is connected.
- **A8** All raster images are optimized using Squoosh.
- **A9** The code follows the project guidelines.

### Markup
- **B1** The markup of the **Our Portfolio** section is written in the `index.html` file and includes all layout elements.
- **B2** HTML tags are used according to their semantic meaning.
- **B3** HTML passes validation without errors.
- **B4** Class names are descriptive and understandable for other developers.
- **B5** Class names do not contain uppercase letters, spaces, transliteration, or tag names. If a class name consists of multiple words, they are separated with hyphens.
- **B6** `<img>` tags include size attributes, at least `width`.
- **B7** Images are exported from the layout in **jpg** format.
- **B8** Groups of similar elements are organized into lists using `<ul>`.
- **B9** All required fonts and their variations are connected from Google Fonts with a single link.  
  Required weights: **Raleway – 700**, **Roboto – 400, 500, 700**.

### Styling
- **C1** Class selectors are used for styling.
- **C2** Styles do not contain `!important`.
- **C3** Interactive elements (buttons and links) have hover and focus states according to the style guide.
- **C4** Contact text in the header changes color on hover and focus.
- **C5** The `<body>` element has the `font-family` property set with **Roboto** as the primary font.
- **C6** Alternative fonts and the generic family (`sans-serif`) are specified at the end of the `font-family` list.
- **C7** The Roboto font family is explicitly set only for the `<body>` element; other elements inherit it.
- **C8** The `<body>` element has the main text color set using the `color` property.
- **C9** Font sizes match the layout values exactly.
- **C10** Line height values match the layout and are defined as a multiplier, not in `px`.
- **C11** Colors (`color` and `background-color`) match the layout exactly.
- **C12** Font weight values match the layout. They are specified only if different from browser defaults.
- **C13** Buttons have `cursor: pointer`.
- **C14** Styles do not repeat browser default values.
