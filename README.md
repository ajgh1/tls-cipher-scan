tls-cipher-scan 
===============

Use `tls-cipher-scan` to scan an HTTPS (or other TLS-based protocol) server
to determine which encryption ciphers it supports.  This can be used as a tool
to identify servers that need a better cipher configuration, or as a testing
tool to verify your server's cipher configuration is correct.

Command syntax
--------------

`tls-cipher-scan <server> [<port>]`

- The `<port>` option is optional; if not specified, 443 is the default.
- Make sure the `openssl` command is in your $PATH.

