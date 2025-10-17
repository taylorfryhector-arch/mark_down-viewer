# Markdown Viewer

## Overview

The Markdown Viewer is a simple web application that converts a Markdown file (`input.md`) into HTML and displays it on a static webpage. It uses the `marked` library to parse Markdown and `highlight.js` to style code blocks.

## Setup and Installation

1. Clone the repository or download the project files.
2. Ensure that `input.md` is in the same directory as `index.html`.
3. Open `index.html` in a web browser to view the rendered Markdown.

## Usage

- Place your Markdown content in `input.md`.
- Open `index.html` in a browser to see the rendered HTML.

## Code Structure

- **index.html**: The main HTML file that includes the necessary scripts and styles.
- **input.md**: The Markdown file to be converted and displayed.
- **README.md**: This file, providing an overview and instructions.
- **LICENSE**: The MIT License for the project.

### Components and Functionality

- **marked**: A JavaScript library used to parse Markdown into HTML.
- **highlight.js**: A library for syntax highlighting of code blocks.
- The script fetches `input.md`, converts it to HTML using `marked`, and highlights code blocks using `highlight.js`.