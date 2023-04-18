# Secure File Storage on Cloud Using Hybrid Cryptography 

A python package for hybrid file encryption and decryption. securefile is for n-layer file encryption. This package provides a basic two-way encryption algorithm for a file. It supports approximately all kind of file encoding. The package provides RSA, DES, AES and Shift Cipher and base64 algorithm for file encoding and decoding.


--Installation
type `pip install securefile` to install this package in native python

--Dependency
 - pyserial (use `pip install pyserial` for native python or `conda install -c anaconda pyserial` for anaconda pythom

#### Data Encryption Standard (DES) Algorithm
The DES algorithm works on 64-bit blocks of data and uses a 56-bit key for encryption and decryption. Here are the basic steps of the DES algorithm:
The Data Encryption Standard (DES) is a symmetric-key block cipher published by the National Institute of Standards and Technology (NIST). DES is an implementation of a Feistel Cipher. It uses 16 round Feistel structure. The block size is 64-bit. Though, key length is 64-bit, DES has an effective key length of 56 bits, since 8 of the 64 bits of the key are not used by the encryption algorithm.

--RSA Algorithm

The RSA algorithm works by using a pair of keys, one public and one private. The public key is used to encrypt data, while the private key is used to decrypt it. The keys are generated based on the mathematical properties of large prime numbers.

--Advanced Encryption Standard (AES) Algorithm

The AES algorithm works on 128-bit blocks of data and supports three key lengths: 128, 192, and 256 bits. Here are the basic steps of the AES algorithm:
The more popular and widely adopted symmetric encrypt algorithm likely to be encountered nowadays is the Advanced Encryption Standard (AES). It is found at least six time faster than triple DES.
A replacement for DES was needed as its key size was too small. With increasing computing power, it was considered vulnerable against exhaustive key search attack. Triple DES was designed to overcome this drawback but it was found slow.

--Base64

Base64 encoding schemes are commonly used when there is a need to encode binary data that needs be stored and transferred over media that are designed to deal with textual data. This is to ensure that the data remains intact without modification during transport.

>MANIBH SAIN 500082493
