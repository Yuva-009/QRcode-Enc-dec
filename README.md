# QR Code Generator and Decryption Tool

This project is a simple web-based tool for generating QR codes from encrypted text and decrypting them back into normal text. It uses HTML, internal CSS for styling, and JavaScript for the encryption/decryption logic, along with QR code generation.

## Features

- **QR Code Generator**: Enter a plain text, encrypt it, and generate a QR code.
- **Decryption Page**: Enter the encrypted text or scan the QR code, and it will return the original plain text.

## How It Works

1. **Encryption**: The tool encrypts the given plain text using a simple encryption algorithm.
2. **QR Code Generation**: The encrypted text is converted into a QR code, which can be shared or scanned.
3. **Decryption**: The decryption page takes the encrypted text (either manually entered or scanned from the QR code) and converts it back to plain text.

## Project Structure

- **index.html**: The main page that allows users to enter plain text, encrypt it, and generate a QR code.
- **decrypt.html**: A page where users can enter encrypted text or scan the QR code to decrypt it back to plain text.
- **Internal CSS**: All the styles are embedded within the HTML files.
- **Internal JavaScript**: The encryption/decryption logic and QR code generation are done using internal JS.

## Usage

1. **Generating a QR Code**:
   - Open the `index.html` page.
   - Enter the plain text in the input field.
   - Click on the "Generate QR Code" button.
   - The tool will encrypt the text and generate a QR code that you can download or scan.

2. **Decrypting the Text**:
   - Open the `decrypt.html` page.
   - Enter the encrypted text or scan the QR code.
   - Click on the "Decrypt" button to reveal the original plain text.

## Technologies Used

- **HTML**: For the structure of the web pages.
- **CSS**: Internal CSS is used for styling the elements within the HTML files.
- **JavaScript**: Internal JS is used to implement encryption, decryption, and QR code generation.

## Future Improvements

- Add stronger encryption methods for enhanced security.
- Implement support for scanning QR codes directly via the camera.
- Improve the user interface for a better user experience.

## How to Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/Yuva-009/QRcode-enc-dec.git
