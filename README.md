# Media Query Snippets

## Overview

The **Media Query Snippets** extension for Visual Studio Code provides handy snippets for CSS media query breakpoints. These snippets help you write media queries more quickly and efficiently in your CSS, SCSS, or LESS files.

## Installation

1. Download the extension and unzip it if necessary.
2. Open Visual Studio Code.
3. Navigate to `Extensions` in the left menu.
4. Click on the three dots (...) at the top right and select `Install from VSIX...`.
5. Select the downloaded VSIX file and install it.

## Available Snippets

This extension provides the following media query breakpoints:

- `xs` - `screen and (max-width: 599px)`
- `sm` - `screen and (min-width: 600px) and (max-width: 959px)`
- `md` - `screen and (min-width: 960px) and (max-width: 1279px)`
- `lg` - `screen and (min-width: 1280px) and (max-width: 1919px)`
- `xl` - `screen and (min-width: 1920px) and (max-width: 5000px)`
- `lt-sm` - `screen and (max-width: 599px)`
- `lt-md` - `screen and (max-width: 959px)`
- `lt-lg` - `screen and (max-width: 1279px)`
- `lt-xl` - `screen and (max-width: 1919px)`
- `gt-xs` - `screen and (min-width: 600px)`
- `gt-sm` - `screen and (min-width: 960px)`
- `gt-md` - `screen and (min-width: 1280px)`
- `gt-lg` - `screen and (min-width: 1920px)`

## Usage

To use a snippet, simply type the corresponding prefix and select the suggestion from the autocomplete menu.

Examples:

- Type `xs` and select `screen and (max-width: 599px)`.
- Type `gt-md` and select `screen and (min-width: 1280px)`.

## Contributing

Contributions to this project are welcome. Just fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License.