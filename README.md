# AES_demo_basis
A simple AES calculator

This was not put together intelligently. It was a project started years ago, abandoned, and pulled out of the grave.

Thanks to @J-Faustus (speed competition) , I dug it out and improved it. He has his own [implementation](https://github.com/J-Faustus/Python-AES) which is probably more understandable.

Due to its weird history, it has a number of unexplained stuff.

It's currently missing other modes, but I will.
# Usage
The module provides:
* `AES_encrypt`: Encrypts bytes text, automatically pads
* `AES_decrypt`: Decryptes and removes the padding added by `AES_encrypt`
* `AES_encrypt_raw`: Encrypts 16 bytes of bytes.
* `AES_decrypt_raw`: Decrypts `AES_encrypt_raw`
