# Asymmetric-Crypto
## Miguel Hernandez
### mig220@csu.fullerton.edu

Written in Python

To execute:
```
python signer.py <KEYFILEPATH> <SIGNATUREFILEPATH> <INPUTFILEPATH> <MODE>
```
Options:
```
<KEYFILEPATH> File containing public key (for verifying) or private key (for signing)

<SIGNATUREFILEPATH> File containing signature (when verifying) or file to write signature (when signing)

<INPUTFILEPATH> File to generate or verify signature

<MODE> Choose either `sign` or `verify` (without backticks)
```
Examples:
To Generate a signature for some file:
```
python signer.py myPrivateKey.pem mySigForMyFile.sig myFile.txt sign
```
To verify a signature for some file:
```
python signer.py myPublicKey.pem mySigForMyFile.sig myFile.txt verify
```
  
