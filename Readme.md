# Parallel File Encrypter (C++)

A Linux-based file encryption and decryption tool built using
process-based parallelism.

## Features
- Recursive directory traversal
- Task abstraction for encryption/decryption
- Parent-child process execution using `fork()`
- Simple byte-level encryption using a numeric key

## Concepts Used
- C++
- fork()
- File I/O
- Process management
- Modular design

## How to Run
Go to Ubuntu terminal and run:
  cd /mnt/c/Users/abuba/OneDrive/Desktop/parallel-file-encrypter
  make clean
  make
2. Run the executable
  ./encrypt_decrypt test
3. Provide directory path and action (encrypt/decrypt)
  directory : "directory_path"
  action : "encrypt or decrypt"

