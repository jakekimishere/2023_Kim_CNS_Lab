# **Homework 7 Submission**

- Name: Jake Kim
- Class: Computer and Network Security
- Date: 25 October 2023

# Exploit Name: Gitea Git Hooks Remote Code Execution
The exploit uses an insecure setting in Gitea, a web-based Git service that allows remote code execution on the target operating system. This vulnerability comes from improper permission handling, specifically, if a user (admin) is able to create Git hooks, the module can exploit this to run any command or code of the attacker's choice. The exploit needs a temporary repository, setting up a post-receive Git hook with a payload, and triggering the hook via creating a dummy file. This would be done through the Gitea web interface. This issue was resolved in Gitea version 1.12.0, which automatically disabled the feature by default. 



# Instructor Approval


# CWE/CVEs
![screenshot](HW6.png)



