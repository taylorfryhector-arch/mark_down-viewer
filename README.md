# Markdown Viewer

## Overview

The Markdown Viewer is a simple web application that converts a Markdown file (`input.md`) into HTML and displays it on a static webpage. It uses the `marked` library to parse Markdown and `highlight.js` to style code blocks. The application includes a tabbed interface to switch between the rendered HTML and the original Markdown source. Additionally, it supports loading Markdown content from a URL specified in the `?url=` query parameter.

## Setup and Installation

1. Clone the repository to your local machine.
2. Open `index.html` in your preferred web browser.

## Usage

- Use the "Markdown" and "HTML" buttons to toggle between the Markdown source and the rendered HTML view.
- The application displays a live word count badge that updates after every render, using `Intl.NumberFormat` to format the numbers.

## Code Structure

- **index.html**: The main HTML file containing the structure and logic for rendering Markdown and HTML views.
- **input.md**: The Markdown file used for testing and demonstration purposes.
- **marked**: A library used to parse Markdown into HTML.
- **highlight.js**: A library used to apply syntax highlighting to code blocks within the rendered HTML.

## Functionality

- **showMarkdown()**: Displays the raw Markdown content and updates the word count.
- **showHTML()**: Converts the Markdown content to HTML, applies syntax highlighting, and updates the word count.
- **updateWordCount()**: Calculates and formats the word count using `Intl.NumberFormat` and updates the display.
