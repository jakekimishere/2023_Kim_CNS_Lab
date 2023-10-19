# **Homework 6 Submission**

- Name: Jake Kim
- Class: Computer and Network Security
- Date: 19 October 2023

# Intro to Splunk (eLearning) 
In the Splunk training course, Intro to Splunk, I gained a foundational understanding of key concepts and skills. Some of the different search modes I learned about include "Smart mode" with its adaptive behavior. The course covered basic syntax, pipes (|), and Boolean operations (OR, NOT) for constructing more detailed search queries. I also became more familiar with using filters like time, host, and index to limit search results effectively, with a focus on the significance of the "time" filter. I also delved into the roles and permissions within Splunk (Admin, Power, User) and their implications for user access and capabilities. The training had us take a quiz to test our knowledge and emphasized the correct definition of time zones in user settings for accurate timestamp display. I also learned more about storing and retrieving data using Splunk indexed and managing saved searches and reports. Overall, the Splunk training equipped me with a basic understanding of essential skills within Splunk. 


# Task information from section #3 
In the Screenshot below, we created the key using ssh-keygen.

![Screenshot #9](Screenshots/HW5.3.1.png)

In the screenshot below, I used cat to copy send the public key direclty to the jump box from the NUC. After that, I was able to log in without having to type my password when trying to ssh into Kim@10.233.103.51.

![Screenshot #9](Screenshots/HW5.3.3.png)

# Task information from section #4
I was able to change the password using the passwd command and found a list of passwords that I would use for the section.

![Screenshot #9](Screenshots/HW5.4.1.png)

I had problems trying to run ssh-putty-brute due to our ExecutionPolicy settings but after some troubleshooting, I was able to bypass the restrictions to run the command. I used the script from putty and the list of passwords from github to brute force access into my jump box.

![Screenshot #9](Screenshots/HW5.4.2.png)
![Screenshot #9](Screenshots/HW5.4.3.png)






