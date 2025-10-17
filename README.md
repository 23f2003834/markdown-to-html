# Markdown to HTML Preview

This static web application allows you to load predefined Markdown content from an inline attachment and convert it to HTML using [marked.js](https://github.com/markedjs/marked). The resulting HTML is rendered inside a designated container, with syntax-highlighted code blocks provided by [highlight.js](https://highlightjs.org/).

## Features

- Load Markdown content stored as an attachment
- Convert Markdown to HTML client-side
- Render HTML inside the page
- Syntax highlight code blocks
- Styled with Bootstrap 5.3.3, with fallback styles

## Usage

1. Click the **Load Markdown** button to process the inline Markdown content.
2. The content is converted and displayed, with code blocks highlighted.

## Requirements

- The necessary scripts (`marked.js` and `highlight.js`) are included via CDN.
- The page uses a button for loading content, making it a straightforward client-side app.

## Notes

- The implementation checks for the presence of the scripts and verifies that headers exist in the output.
- Markdown content is simulated as an inline attachment for demonstration.

## License

This project is licensed under the MIT License.