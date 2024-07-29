# QR Code Generator

A simple QR code generator application built with Go. This tool encodes input data into a QR code and saves it as a PNG file.

## Features

- Converts text input into a QR code image
- Uses the `go-qrcode` library for QR code generation
- Saves the QR code as `qrcode.png` in the project directory

## How to Use

1. **Clone the Repository:**

   ```sh
   git clone https://github.com/yourusername/qr-code-generator.git
   cd qr-code-generator
    ```

    
2. **Run the Application:**

```sh
    go run . https://www.linkedin.com/in/hahahamid (replace with your own URL/text/data)
```

This command will create a qrcode.png file in the project directory with the QR code for the specified URL.

