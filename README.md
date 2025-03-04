# AI Chat Export Viewer
A privacy-focused web app for locally processing and analyzing ChatGPT and Claude chat exports.

![GitHub release (latest by date)](https://img.shields.io/github/v/release/levysoft/ai-chat-export-viewer?label=latest) [![Github All Releases](https://img.shields.io/github/downloads/levysoft/ai-chat-export-viewer/total.svg)](https://github.com/levysoft/ai-chat-export-viewer/releases) [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-yellow.svg)](https://opensource.org/licenses/GPLv3) [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/levysoft/ai-chat-export-viewer/graphs/commit-activity) [![GitHub contributors](https://img.shields.io/github/contributors/levysoft/ai-chat-export-viewer.svg)](https://github.com/levysoft/ai-chat-export-viewer/graphs/contributors) [![made-with-html](https://img.shields.io/badge/Made%20with-HTML-orange.svg)](https://developer.mozilla.org/en-US/docs/Web/HTML) [![made-with-css](https://img.shields.io/badge/Made%20with-CSS-blue.svg)](https://developer.mozilla.org/en-US/docs/Web/CSS) [![made-with-javascript](https://img.shields.io/badge/Made%20with-JavaScript-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

[ [English](README.md) | [Italiano](README.it.md) ]

This repository provides a web application for viewing and analyzing chat exports from ChatGPT and Claude, with a strong focus on privacy. All data is processed locally in your browser, ensuring that personal information is never sent to external servers. If desired, you can download the HTML page to inspect the source code and verify the application’s functionality yourself.

## Contents

1. [Introduction](#introduction)
2. [Privacy and Security](#privacy-and-security)
3. [Requirements](#requirements)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Application Description](#application-description)
7. [File Structure](#file-structure)
8. [Screenshots](#screenshots)
9. [Feedback and Contributions](#feedback-and-contributions)
10. [Changelog](#changelog)
11. [Author](#author)
12. [License](#license)

## Introduction

**Privacy Chat Export Viewer** is a web application that allows you to load and analyze JSON files containing chat conversations exported from ChatGPT and Claude. Its intuitive interface makes it easy to search and view chats, offering a lightweight and fast solution without compromising data privacy.

## Privacy and Security

The application has been designed with utmost attention to privacy:
- **Local Processing**: All data is processed directly in your browser, with no information sent to external servers.
- **No Tracking**: Personal data and chat history remain completely on your device.
- **Source Code Inspection**: If you wish to delve deeper or verify its functionality, you can download the HTML page and inspect the source code.

## Requirements

- A modern web browser (Chrome, Firefox, Edge, Safari)
- An Internet connection for initial asset loading (optional; for offline use, all files must be downloaded)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/levysoft/ai-chat-export-viewer.git
    ```
2. Open the `index.html` file in your preferred web browser.
3. *(Optional)* For complete offline usage, download all assets included in the repository.

## Usage

1. Launch the application by opening the `index.html` file in your browser.
2. Drag and drop the JSON file (e.g., `conversations.json`) into the upload area or click to select it.
3. View the list of chats and select the one you wish to analyze.
4. Use the search bar to filter conversations by title or content.
5. Customize the interface by changing the language, toggling dark mode, or adjusting the scroll position via the settings.
6. If you wish to analyze the code, you can download the HTML page and inspect its source.

## Application Description

The application is built with HTML, CSS, and JavaScript, and offers the following features:
- **Local JSON File Processing**: Data is read and processed using the FileReader API without being transmitted online.
- **Chat Management**: Supports export formats from both ChatGPT and Claude, standardizing the order of chats.
- **Dynamic and Responsive Interface**: A sidebar for navigating between chats and a display area for messages, with search and customization support.
- **Multilingual and Dark/Light Mode**: The interface adapts to various languages and visual preferences.
- **Local Sharing**: You can copy the chat link for sharing, without data being stored externally.

## File Structure
ai-chat-export-viewer/ ├── index.html # Main application page ├── assets/ # Folder containing images and screenshots │ ├── screenshot0.jpg │ ├── screenshot1.jpg │ └── screenshot2.jpg ├── README.md # This file └── LICENSE # License file (GPL v3)


## Screenshots

Here are some screenshots of the application:

- **Upload Page**:
  ![Upload Page](assets/screenshot0.jpg)
- **Chat List**:
  ![Chat List](assets/screenshot1.jpg)
- **Conversation Detail**:
  ![Conversation Detail](assets/screenshot2.jpg)

## Feedback and Contributions

Your feedback is valuable! If you encounter issues or have suggestions, please open an [issue](https://github.com/levysoft/ai-chat-export-viewer/issues) or submit a pull request. Contributions and suggestions for improvements are always welcome.

## Changelog

All changes and updates to the application are documented in the [CHANGELOG.md](./CHANGELOG.md) file.

## Author

Antonio Troise

## License

This project is released under the [GNU GPL v3](https://www.gnu.org/licenses/gpl-3.0.en.html) license. See the LICENSE file for more details.

