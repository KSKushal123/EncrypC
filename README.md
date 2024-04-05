![102007940-19d68080-3d53-11eb-8518-d681586666e6](https://github.com/KSKushal123/EncrypC/assets/133742980/29331967-f187-4d1f-b72b-046f65e17c6c)
![103018817-d0184200-456b-11eb-8fd2-11893c3173cd](https://github.com/KSKushal123/EncrypC/assets/133742980/30fde9f4-d6a5-44a3-9673-8b824ba9a0cb)
![103018827-d1e20580-456b-11eb-8503-173356c1cde9](https://github.com/KSKushal123/EncrypC/assets/133742980/8534348d-518a-446f-9050-517442ee4c45)

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
* git clone https://github.com/KSKushal123/File-EncrypC.git
* ls
* cd EncrypC
* ls
* python setup.py
* python Encrypc.py
```
## Tutorial to Encrypt/Decrypt Files:
1. Open the Application and Click the SELECT FILE button to select your file e.g. "mydoc.pdf" (OR You can add path manually).
2. Enter your Key (This should be alphanumeric letters). Remember this so you can Decrypt the file later. (Else you'll lose your file permanently)
3. Click ENCRYPT Button to encrypt the file. A new encrypted file with ".encr" extension e.g. "mydoc.pdf.encr" will be created in the same directory where the "mydoc.pdf" is.
4. When you want to Decrypt a file you, will select the file with the ".encr" extension and Enter your Key which you chose at the time of Encryption. Click DECRYPT Button to decrypt. The decrypted file will be of the same name as before with the suffix "decrypted" e.g. "mydoc_decrypted.pdf".
5. Click CLEAR Button to reset the input fields and status bar.
