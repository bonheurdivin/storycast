# StoryCast — Real Voices, Real Stories

StoryCast is a responsive storytelling website that shares human experiences, celebrates cultural heritage, and highlights personal growth and positive change both in Rwanda and beyond.

The project focuses on making stories accessible through readable content, video captions, transcripts, and a responsive user interface.

## Features

- Three pages: Home, Story Detail, and About & Accessibility.
- Responsive layouts for mobile, tablet, and desktop screens.
- Semantic HTML5 and modular Sass styling.
- Accessible keyboard navigation and visible focus indicators.
- Video playback with English captions and a text transcript.
- Consistent colors, typography, and reusable UI components.

## Pages

| Page | Description |
|---|---|
| `index.html` | Homepage with featured stories and navigation. |
| `story/story-one.html` | Story article with video & audio, captions, and transcript. |
| `about.html` | Project mission, storytelling approach, and accessibility information. |

## Technologies

- HTML5
- Sass (SCSS)
- CSS Grid and Flexbox
- Vanilla JavaScript

## Project Structure

```text
storycast/
├── index.html
├── about.html
├── story/
│   └── story-one.html
├── sass/
│   ├── main.scss
│   └── partials/
│       ├── _colors.scss
│       ├── _typography.scss
│       └── _spacing.scss
├── css/
│   └── style.css
├── js/
│   └── main.js
├── assets/
│   ├── images/
│   ├── audio/
│   ├── video/
│   └── transcripts/
├── docs/
└── README.md
```

## Run Locally

1. Clone or download this repository.
2. Open the project folder in VS Code.
3. Install the development dependencies:

   ```bash
   npm install
   ```

4. Compile Sass and watch for changes:

   ```bash
   npm run sass
   ```

5. Open `index.html` using the VS Code Live Server extension.

Keep the Sass watcher running while editing SCSS files so the compiled CSS updates automatically.

## Accessibility

The project includes semantic HTML, keyboard navigation, visible focus states, responsive layouts, video captions, and a text transcript. These features were checked during development.

## Media Attribution

The featured video concerns traditional Uyghur mulberry paper-making and is attributed to CGTN. See the accompanying project documentation for the source.

## Documentation and Design

Research, design decisions, testing results, and supporting evidence will be included in the project documentation.

**Figma design file:** https://www.figma.com/design/lNjYichzgNGr96Cdzeufq7/StoryCast-%E2%80%94-Research---Design?node-id=0-1&t=tRmShQqlI7fHToLM-1
