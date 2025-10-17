# Markdown Viewer

## Overview

The Markdown Viewer is a simple web application that converts a Markdown file (`input.md`) into HTML and displays it on a static webpage. It uses the `marked` library to parse Markdown and `highlight.js` to style code blocks. The application includes a tabbed interface to switch between the rendered HTML and the original Markdown source. Additionally, it supports loading Markdown content from a URL specified in the `?url=` query parameter.

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/markdown-viewer.git
   ```

2. Navigate to the project directory:
   ```bash
   cd markdown-viewer
   ```

3. Open `index.html` in your web browser.

## Usage

- To view the Markdown from a local file, simply open `index.html` in your browser. The application will load `input.md` by default.
- To load Markdown from a URL, append `?url=YOUR_MARKDOWN_URL` to the `index.html` file path in your browser.

### Example

- Local file: `file:///path/to/markdown-viewer/index.html`
- URL: `file:///path/to/markdown-viewer/index.html?url=https://example.com/your-markdown-file.md`

## Code Structure

- **index.html**: The main HTML file containing the structure and logic for rendering the Markdown.
- **input.md**: The default Markdown file used when no URL is provided.
- **README.md**: Documentation for the project.
- **LICENSE**: The MIT License for the project.

### Components and Functionality

- **Markdown Rendering**: Uses the `marked` library to convert Markdown to HTML.
- **Syntax Highlighting**: Uses `highlight.js` to apply syntax highlighting to code blocks.
- **Tabbed Interface**: Allows users to switch between the rendered HTML and the raw Markdown source.
- **Dynamic Loading**: Fetches Markdown content from a URL if provided, otherwise falls back to the local `input.md` file.
