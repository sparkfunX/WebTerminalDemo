# WebTerminalDemo

This is a simple demo of the [Web Serial API](https://web.dev/serial/) which implements a bare-bones USB serial terminal.

![screenshot](https://github.com/sparkfunX/WebTerminalDemo/raw/main/img/scrot.png)

This demo uses TextEncoderStream and TextDecoderStream to encode/decode the serial stream, so it only deals in strings and not raw bytes.
Please see the comments in script.js for more detail on how the Web Serial API is being utilized. 

You can play with the live demo here:
https://sparkfunx.github.io/WebTerminalDemo/

It also accepts a query string to prefill the outgoing text box, like this:
https://sparkfunx.github.io/WebTerminalDemo/?prefill=This%20is%20prefilled%20text

Distributed as-is; no warranty is given.
