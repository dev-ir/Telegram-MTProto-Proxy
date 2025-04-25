
# Telegram MTProto Proxy Link Generator & Parser

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A web tool for generating and parsing Telegram MTProto proxy links with support for all protocols (Normal, Secure, Fake-TLS).

ابزاری تحت وب برای تولید و تجزیه لینک‌های پروکسی MTProto تلگرام با پشتیبانی از تمام پروتکل‌ها (عادی، امن، Fake-TLS).

## Features ✨

- **Generate proxy links** in all supported formats:
  - Normal (`tg://proxy` or `https://t.me/proxy`)
  - Secure (dd-prefixed secret)
  - Fake-TLS (both hex and base64 encoded)
- **Parse existing proxy links** to extract configuration
- **Copy parsed configurations** to generator
- **Random secret generator**
- **Mobile-friendly** responsive design
- **Clean modern UI** with Tailwind CSS

## Usage 🚀

### Generator
1. Enter your proxy details:
   - Server IP/domain
   - Port number
   - Secret key (or generate random)
   - (Optional) Fake-TLS domain
2. Choose URL format (`tg://` or `https://t.me`)
3. Click "Generate" to create all link variants

### Parser
1. Paste an existing proxy link
2. Click "Parse" to view configuration details
3. (Optional) Click "Parse and copy to generator" to modify the link

## Live Demo 🌐

[View live demo](https://your-demo-url-here.com)

## Installation 💻

To run locally:

```bash
git clone https://github.com/your-username/mtproto-proxy-generator.git
cd mtproto-proxy-generator
# Open index.html in your browser
```

## Screenshots 📸

![Generator Screenshot](screenshots/generator.png)
![Parser Screenshot](screenshots/parser.png)

## Contributing 🤝

Contributions are welcome! Please open an issue or submit a pull request.

## License 📜

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.