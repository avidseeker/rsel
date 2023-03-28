# rsel
Simple Unix-like messaging system:
* Everything is a file. Even messages.
* Everything is modular and pipe-able
* Plain text format for managing contacts. No complex databases.
* Users see de/encryption happening and configure it as preferred.

Usage:
```
vipe | gpg -sear EMAIL | tg-send
```

## Dependencies
* `keepass-cli` for managing passwords
