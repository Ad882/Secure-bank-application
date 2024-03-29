# Secure bank application

Simple cryptographically secure bank application.

The aim of the project was to create a "Secure Bank Application" (SBA): a client-server application that allows users to perform operations on their own bank account. Each user is represented by a username and a password, while each bank account is represented by an accountID and a balance. For simplicity, we assume that a user owns a single account and that an account is owned by a single owner.


> To run the program in a terminal, enter:

```
make clean    
make -s
```


For more information on usage, design choices, security measures, etc., please refer to the document [Documentation.pdf](Documentation.pdf).

⚠️ **Warning**: Before running the code, make sure the library *OpenSSL* is installed on your computer. ⚠️


> On Linux:

```
sudo apt-get update  
sudo apt-get install openssl
```


