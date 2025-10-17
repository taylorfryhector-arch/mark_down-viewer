# Markdown Viewer

## Overview

The Markdown Viewer is a simple web application that converts a Markdown file (`input.md`) into HTML and displays it on a static webpage. It uses the `marked` library to parse Markdown and `highlight.js` to style code blocks. The application now includes a tabbed interface to switch between the rendered HTML and the original Markdown source.

## Setup and Installation

1. Clone the repository or download the project files.
2. Ensure that `input.md` is in the same directory as `index.html`.
3. Open `index.html` in a web browser to view the rendered Markdown.

## Usage

- Place your Markdown content in the `input.md` file.
- Open `index.html` in a web browser.
- Use the tabs to switch between the rendered HTML and the Markdown source.

## Code Structure

- **index.html**: The main HTML file containing the structure of the application, including the tabbed interface.
- **input.md**: The Markdown file containing the content to be rendered.
- **marked**: A library used to parse Markdown into HTML.
- **highlight.js**: A library used to apply syntax highlighting to code blocks.

## Functionality

- The application reads the Markdown content from `input.md` and uses `marked` to convert it to HTML.
- The HTML is displayed in the `#markdown-output` container.
- The original Markdown is displayed in the `#markdown-source` container.
- Users can switch between the rendered HTML and the Markdown source using the tabs.
