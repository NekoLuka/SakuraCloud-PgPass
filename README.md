# PgPass
A password manager server that encrypts passwords under the hood with pgp and your public key for automatic password generation.
Will make use of the python-gnupg package.

## Idea
The idea behind this system is that an automated system that needs to generate passwords can request a password for the new service, which will automatically be saved in the vault.  
This way you're not relient on default passwords, and they're not saved anywhere in cleartext.
