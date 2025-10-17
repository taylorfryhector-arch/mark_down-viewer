# Markdown Viewer

## Overview

The Markdown Viewer is a simple web application that converts a Markdown file (`input.md`) into HTML and displays it on a static webpage. It uses the `marked` library to parse Markdown and `highlight.js` to style code blocks. The application now includes a tabbed interface to switch between the rendered HTML and the original Markdown source. Additionally, it supports loading Markdown content from a URL specified in the `?url=` query parameter.

## Setup and Installation

1. Clone the repository or download the project files.
2. Ensure that `input.md` is in the same directory as `index.html` if you want to use the local file as a fallback.
3. Open `index.html` in a web browser to view the application.

## Usage

- To view a local Markdown file, simply open `index.html` in your browser.
- To load Markdown from a URL, append `?url=YOUR_MARKDOWN_URL` to the `index.html` URL in your browser.

### Example

- Local file: `file:///path/to/index.html`
- Remote file: `file:///path/to/index.html?url=https://example.com/your-markdown-file.md`

## Code Structure

- **index.html**: The main HTML file containing the structure and logic for the Markdown Viewer.
- **input.md**: The default Markdown file used when no URL is specified.
- **marked.js**: A library used to parse Markdown into HTML.
- **highlight.js**: A library used to apply syntax highlighting to code blocks.

### Components

- **Markdown Tabs**: Buttons to switch between the rendered HTML and the Markdown source.
- **Markdown Source Label**: Displays the source of the currently loaded Markdown file.
- **Markdown Output**: A container for the rendered HTML.
- **Markdown Source**: A container for the raw Markdown text.

### Functionality

- **URL Parameter Handling**: Checks for a `?url=` parameter to load Markdown from a specified URL.
- **Fetch API**: Used to retrieve Markdown content from either a URL or the local `input.md` file.
- **Dynamic Rendering**: Converts Markdown to HTML and applies syntax highlighting dynamically.