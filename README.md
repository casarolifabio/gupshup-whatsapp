# Gupshup WhatsApp SDK

This package provides a simple interface for sending messages via the Gupshup WhatsApp API.
## Instalação.

```bash
pip install ghup-whatsapp
```
## Exemplo de uso.

```bash
from ghup import Client

client = Client(app_name="YOUR_APP", api_token="YOUR_TOKEN", app_number="5561987654321", api_id="YOUR_ID")
client.send_text(destination_number="5561987654321", destination_text="Olá, mundo!")
```
### ✅ `LICENSE` (MIT)

```text
MIT License

Copyright (c) 2025 Casaroli

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.