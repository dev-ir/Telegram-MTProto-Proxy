
# Telegram MTProto Proxy Link Generator & Parser

A web tool for generating and parsing Telegram MTProto proxy links with support for all protocols.

## Features ✨

- **Generate proxy links** in all supported formats:
  - Normal (`tg://proxy` or `https://t.me/proxy`)
  - Secure (dd-prefixed secret)
  - Fake-TLS (both hex and base64 encoded)
- **Parse existing proxy links** to extract configuration
- **Copy parsed configurations** to generator
- **Random secret generator**

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

[View live demo](https://dev-ir.github.io/Telegram-MTProto-Proxy/)