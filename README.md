# telegram-cache-decryption

~~**NOTICE**: this no longer works and I'm not planning any update in near future.~~
**Upd**: Dont worry brother, i will do it for you

Decrypt the media cache of Telegram Desktop.

This program will read encrypted Telegram Desktop's media cache and write decrypted data in current directory.

Read the code and adjust. It may not work for older or newer versions of Telegram Desktop. You should also be aware that the Telegram Desktop cache data is private to you and writing out decrypted data may be risky for leakage.

# Dependencies
* Python 3
* python-cffi
* PyQt5
* OpenSSL
* tgcrypto