---
layout: posts
title:  "Password Hashing"
date:   2025-03-29 09:15:16 -0500
categories: memory lane
---
![Data Hashing Image](https://daytiffany-fs.github.io/memory-lane/images/hashimage.jpg)
Password hashing is a security process to help protect user credentials. The process of hashing alters the password from its plain text form to a unique cryptographed function that is hard to use and decipher should a database be breached.

Users input their password. The password is sent through the hashing process by using a program like bcrypt. When users enter their password to log in, it is hashed again and the hash is compared to grant or deny access to the user.

Hashing is safer than encryption because encrypted passwords can be deciphered so long as the hacker uses the right key to unlock the encryption code.