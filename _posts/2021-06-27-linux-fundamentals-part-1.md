---
layout: post
title: Linux Fundamentals Part 1
---
![image](/assets/img/linux/1.1.png)

# Task 1 intro

This room is the first part in the Linux Fundamental rooms, in this room we will learn three topics

   Introduction To Linux
   Executing Commands and Man Pages
   Basic File Operators

# task 2 Methodology

After careful consideration, I've deemed the best way to go about this is to introduce various concepts in sections, with each section being more complex and requiring knowledge from the previous section. To better enable the transition between section, I've split each section into different users in the VM; when you finish a section you'll have to complete a challenge, and then you'll be able to move onto the next section.

# Task 3 Basic Command Execution

in this task we will learn about the first command (echo) echo used to output any words after it like ~$ echo b3t3tes the output will be b3t3tes

![image](/assets/img/linux/1.2.png)

# Task 4 Manual Pages and Flags

in this task we will learn about (man) man is the most helpful command in Linux it helps us to know about the command and how to use it like ls command we write man ls we will see ls manual page

![image](/assets/img/linux/1.3.png)

Q:How would you output hello without a newline

A:echo -n hello

![image](/assets/img/linux/1.4.png)

# Task 5 [Section 3: Basic File Operations] - ls

this task is about ls command it list all files and information in directory like this

![image](/assets/img/linux/1.5.png)

Q:What flag outputs all entries

A:-a

![image](/assets/img/linux/1.6.png)

Q:What flag outputs things in a "long list" format

A:-l

![image](/assets/img/linux/1.7.png)

# Task 6 [Section 3: Basic File Operations] - cat

this task is about cat command cat is Abbreviation for concatenate it output the data in files at terminal like this

![image](/assets/img/linux/1.8.png)

Q:What flag numbers all output lines?

A:-n

![image](/assets/img/linux/1.9.png)

# Task 7 [Section 3: Basic File Operations] - touch

in this task, we will learn about touch command touch create files if we want to create a file name b3t3tes we write touch b3t3tes.txt

![image](/assets/img/linux/1.10.png)

# Task 8 [Section 3: Basic File Operations] - Running A Binary

in this task we will learn about binary and relative path binaries are files that contain compiled source code

![image](/assets/img/linux/1.13.png)

Q:How would you run a binary called hello using the directory shortcut. ?

A:./hello

Q:How would you run a binary called hello in your home directory using the shortcut ~ ?

A:~/hello

Q: How would you run a binary called hello in the previous directory using the shortcut .. ?

A: ../hello

# Task 9 Binary - Shiba1

in this task, we have a challenge to create a file called noot.txt and run the binary to get the password for the user shiba2

Q:What's the password for shiba2

A:pinguftw

![image](/assets/img/linux/1.11.png)

# Task 10 su

this task is about su command it allow us to change the user without log out if I want to switch to shiba2 we type su shiba2

![image](/assets/img/linux/1.12.png)









