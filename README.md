# asterisk-cnam-message
Send a cute message in Caller ID Name field.

This program abuses the CNAM or Caller ID Name field to send a message broken up over multiple calls.

Usage:

`asterisk-cnam-message <recipient-extension> and your message goes right here`

Make sure you pass your message to `asterisk-cnam-message` as multiple arguments. Each argument is a single call, which lasts one second. Each call should have about 0.3 seconds between.
