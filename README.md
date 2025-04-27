# ClippyNet 📎

A simple, client-side tool for transferring files between computers via base64-encoded terminal commands.

**Use it here: [https://smerty.github.io/clippynet/](https://smerty.github.io/clippynet/)**

## Features

- **Simple File Transfer**: Generate one-liner terminal commands to transfer files between computers
- **Cross-Platform Compatibility**: Supports both Linux/macOS and Windows PowerShell
- **Compression Option**: Automatically provides both standard and compressed versions for Linux commands
- **Size Comparison**: Shows you which command is more efficient for your specific file
- **Fully Client-Side**: All processing happens in your browser - files never leave your computer
- **No Installation Required**: Works offline by just opening the HTML file

## How It Works

1. Select a file you want to transfer
2. Click "Generate Command"
3. Copy the appropriate command for your target operating system
4. Paste and run the command on the destination computer
5. The file will be reconstructed exactly as the original

## Why Use ClippyNet?

- No need for file sharing services, email attachments, or USB drives
- Works across airgapped networks or standalone computers
- No internet connection required after initial page load (or save the page to use offline)
- Perfect for quick small file transfers

## Privacy & Security

- Your files never leave your computer
- No server-side processing
- No tracking or analytics

## Limitations

- Base64 encoding increases file size by ~33% (before compression)
- Larger files may cause performance issues
- Command-line knowledge required for file restoration

## License

This project is released into the public domain - see the [LICENSE](LICENSE) file for details.
