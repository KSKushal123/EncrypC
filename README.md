## Tech Stack Used:
* Python3
* Tkinter for GUI (Inbuilt)
* pycryptodomex for Cryptodome (AES Encryption)

### External Dependencies to be Installed:
* `pycryptodomex` (AES encryption)
```sh
pip install pycryptodomex
```
## Steps to follow
```windows shell
* cd Desktop
* git clone https://github.com/KSKushal123/EncrypC.git
* ls
* cd EncrypC
* ls
* python install setup.py
* python install Encrypc.py
```
## Tutorial to Encrypt/Decrypt Files:
1. Open the Application and Click the SELECT FILE button to select your file e.g. "mydoc.pdf" (OR You can add path manually).
2. Enter your Key (This should be alphanumeric letters). Remember this so you can Decrypt the file later. (Else you'll lose your file permanently)
3. Click ENCRYPT Button to encrypt the file. A new encrypted file with ".encr" extension e.g. "mydoc.pdf.encr" will be created in the same directory where the "mydoc.pdf" is.
4. When you want to Decrypt a file you, will select the file with the ".encr" extension and Enter your Key which you chose at the time of Encryption. Click DECRYPT Button to decrypt. The decrypted file will be of the same name as before with the suffix "decrypted" e.g. "mydoc_decrypted.pdf".
5. Click CLEAR Button to reset the input fields and status bar.
