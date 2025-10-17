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

3. Open `index.html` in your web browser to view the application.

## Usage

- To view the Markdown from a local file (`input.md`), simply open `index.html` in your browser.
- To load Markdown from a URL, append `?url=YOUR_MARKDOWN_URL` to the `index.html` file path in your browser.

## Code Structure

- `index.html`: The main HTML file containing the structure and logic for rendering the Markdown content.
- `input.md`: The default Markdown file used when no URL is specified.
- The application uses the `marked` library for Markdown parsing and `highlight.js` for syntax highlighting.

## Functionality

- The application checks for a `?url=` query parameter to load Markdown from a specified URL.
- If no URL is provided, it defaults to loading the local `input.md` file.
- The interface includes tabs to switch between the rendered HTML and the raw Markdown source.
- The source of the Markdown content is displayed above the content area.