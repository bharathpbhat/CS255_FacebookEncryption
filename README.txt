Project - Facebook Message Encryption

Team Members:
Bharath Bhat - bbhat@stanford.edu
Dimuth Kulasinghe - dimuthk@stanford.edu

Code Readme:

No special set up instructions

Behavior on entering wrong password:
Keeps re-prompting for the user to enter the correct password. The user has the option to cancel the prompt, in which case he/she won't be able to encrypt/decrypt messages or modify/load key database.

All encrypted messages carry the tag "encrypted:" at the beginning.

The script throws a generic "Cannot decrypt" error message when the decryption fails (might be due to group key not present/incorrect group key/user viewing the page without his key database password)
