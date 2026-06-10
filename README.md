# URL to QR Code Generator

A simple Node.js CLI tool that takes a URL as input and generates a QR code image along with saving the URL to a text file.

## Features

- Interactive CLI prompt to enter any URL
- Generates a QR code as a PNG image
- Saves the entered URL to a `URL.txt` file

## Prerequisites

- Node.js installed on your machine

## Installation

1. Clone the repository
```bash
   git clone https://github.com/sanskrutidalwadi/URL_img_nodejs.git
   cd URL_img_nodejs
```

2. Install dependencies
```bash
   npm install
```

## Usage

```bash
node index.js
```

You will be prompted to enter a URL. After entering it:
- A QR code image is saved as `qr_img.png`
- The URL is saved as `URL.txt`

## Dependencies

- [inquirer](https://www.npmjs.com/package/inquirer) — Interactive CLI prompts
- [qr-image](https://www.npmjs.com/package/qr-image) — QR code generation
- [fs](https://nodejs.org/api/fs.html) — Node.js built-in file system module

## Example

```
? Enter the URL: https://www.google.com
The file has been saved!
```

A `qr_img.png` will be generated in the project directory.

## License

MIT
