## Hill Cipher

Hill cipher is a polygraphic substitution cipher based on linear algebra where each letter is represented by a number modulo 26. 

![1](https://user-images.githubusercontent.com/61264973/94856220-46b21180-044d-11eb-8b38-61ecea7305db.jpg)

### Encryption

To encrypt a message, each block of n letters is multiplied by an invertible n × n matrix, against modulus 26. 

### Decryption

To decrypt the message, each block is multiplied by the inverse of the matrix used for encryption.

The matrix used for encryption is the cipher key, and it can be chosen randomly from the set of invertible n × n matrices 

![img9-2](https://user-images.githubusercontent.com/61264973/94856214-4580e480-044d-11eb-8bca-918dc7bc6245.jpg)

