---
layout: post
title: Encryption-Crypto101
---

![image](/assets/img/Crypto/1.png)

# Task 1 What will this room cover? 
## This room will cover:
  ## Why cryptography matters for security and CTFs
  ## The two main classes of cryptography and their uses
  ## RSA, and some of the uses of RSA
  ## 2 methods of Key Exchange
  ## Notes about the future of encryption with the rise of Quantum Computing
   
 # Task 2 Key terms  
 
 ### Q: Are SSH keys protected with a passphrase or a password?
 #### A: passphrase
 
  #### Passphrase - Separate to the key, a passphrase is similar to a password and used to protect a key.
   
 # Task 3 Why is Encryption important? 
   
   ### Q: What does SSH stand for?
   #### A: Secure Shell 
   
  #### SSH or Secure Shell is a network communication protocol that enables two computers to communicate 
   
   ### Q: How do webservers prove their identity?
   #### A: certificates
   
   ### Q: What is the main set of standards you need to comply with if you store or process payment card details?
   #### A: PCI-DSS
   
 # Task 4 Crucial Crypto Maths 
 
 ### Q: What's 30 % 5? 
 #### A: 0
 
 ### Q: What's 25 % 7
 #### A: 4
 
 ### Q: What's 118613842 % 9091
 #### A: 3565
 
 # Task 5 Types of Encryption 
   
 ### Q: Should you trust DES? Yea/Nay  
 #### A: Nay
 
 ### Q: What was the result of the attempt to make DES more secure so that it could be used for longer?
 #### A: Triple DES
 
 ### Q: Is it ok to share your public key? Yea/Nay
 #### A: Yea
 
 # Task 6 RSA - Rivest Shamir Adleman 
   
 ### Q: p = 4391, q = 6659. What is n? 
 #### A: 29239669
 
![image](/assets/img/Crypto/2.png)   
    
# Task 7 Establishing Keys Using Asymmetric Cryptography 

 ## Metaphor time                                                                                                                                            
 ### Imagine you have a secret code, and instructions for how to use the secret code. If you want to send your friend the instructions without anyone else being able   to read it, what you could do is ask your friend for a lock.

 ### Only they have the key for this lock, and we’ll assume you have an indestructible box that you can lock with it.

 ### If you send the instructions in a locked box to your friend, they can unlock it once it reaches them and read the instructions.

 ### After that, you can communicate in the secret code without risk of people snooping.

 ### In this metaphor, the secret code represents a symmetric encryption key, the lock represents the server’s public key, and the key represents the server’s private key.

 ### You’ve only used asymmetric cryptography once, so it’s fast, and you can now communicate privately with symmetric encryption.

# Task 8 Digital signatures and Certificates 

### Q: What company is TryHackMe's certificate issued to? 
#### A: CloudFlare

![image](/assets/img/Crypto/8.png)  

# Task 9 SSH Authentication 

### Q: What algorithm does the key use?
#### A: RSA

![image](/assets/img/Crypto/9.png) 

### Q: Crack the password with John The Ripper and rockyou, what's the passphrase for the key?
#### A: delicious

![image](/assets/img/Crypto/10.png) 

# Task 10 Explaining Diffie Hellman Key Exchange 

## What is Key Exchange?

### Key exchange allows 2 people/parties to establish a set of common cryptographic keys without an observer being able to get these keys. Generally, to establish common symmetric keys.
## How does Diffie Hellman Key Exchange work?

### Alice and Bob want to talk securely. They want to establish a common key, so they can use symmetric cryptography, but they don’t want to use key exchange with asymmetric cryptography. This is where DH Key Exchange comes in.

# Task 11 PGP, GPG and AES 

### Q: You have the private key, and a file encrypted with the public key. Decrypt the file. What's the secret word?
#### A: Pineapple

![image](/assets/img/Crypto/11.png) 
### AND
![image](/assets/img/Crypto/12.png) 
### AND
![image](/assets/img/Crypto/13.png) 
### AND
![image](/assets/img/Crypto/14.png) 





