# UUEnDecoder

A simple, standalone HTML tool to perform UUEncode (Unix-to-Unix Encoding) and UUDecode operations directly in your browser.

## Features
*   **Bidirectional Conversion**: Seamlessly switch between plaintext/binary and UUEncoded format.
*   **Standard Compliance**: Follows the traditional 6-bit encoding scheme used in legacy Unix systems and email attachments.
*   **Instant Processing**: Real-time encoding and decoding as you type or paste.
*   **100% Client-Side**: No data is sent to a server; all bit-shifting logic happens locally in your browser.
*   **Clean Interface**: A focused, two-way text area setup for quick input and output.

## Built With
*   **HTML5 / CSS3**: Minimalist, functional user interface.
*   **Vanilla JavaScript**: Custom bit-manipulation logic to handle the UUEncode algorithm without external libraries.

## How to Use
1.  Open `UUEnDecoder.html` in any modern web browser.
2.  **To Encode**: Paste your text into the "Plaintext" area to receive the UUEncoded string.
3.  **To Decode**: Paste a UUEncoded block (starting with `begin` or the header character) to retrieve the original data.
4.  **Copy** the result for use in legacy systems or debugging.

## License
This project is licensed under the [MIT License](LICENSE).
