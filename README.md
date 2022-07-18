# Mnemonic Code Converter
Use single mnemonic to create multiple pks.

For security reasons the mnemonic should be stored in cold wallet.
This tool enables the user to store only one mnemonic and create multiple pks from this mnemonic,
which facilitates the management of the cold storage.

Using the stored mnemonic the user can create the same pks if needed.

This tool uses tonweb-mnemonic to convert the mnemonic to multiple seeds by using hash function (SHA-512) to sign mnemonic key with an incremented number (starting with 0) as a password for each pk.

### how to use
1. Enter 24 word mnemonic or use the 'Generate New Mnemonic' button.
2. Enter the number of pks to generate.
3. Covert the mnemonic to pks and download zip files.
