# **Homework 3 Submission**

- Name: Jake Kim
- Class: Computer and Network Security
- Date: 14 September 2023


# 1. Completed in CNS repository 

# 2. Completed in CNS repository

# 3. Completed below:

We Selected Red Hat Enterprise Linux (RHEL) 7 as our Linux distribution. We obtained the RHEL 7 image from the Vagrant Cloud website using the "generic/rhel7" box. We created our Vagrantfile to configure and provision our RHEL 7 VM.

# 4. Completed below:

During the installation of the SCC tool on our RHEL 7 system, we encountered an issue with unzipping the downloaded archive file. To resolve this issue, we manually downloaded and installed the 'unzip' RPM package compatible with RHEL 7. We visited the CentOS repository website to find the 'unzip' package.
![Screenshot for unzip.](Screenshots/HW3cunzip.png)
![Screenshot for unzip.](Screenshots/HW3dunzip.png)

By manually downloading and installing the 'unzip' RPM package compatible with RHEL 7, we were able to overcome the issues with unzipping during the SCC tool installation process.

# 5. Completed below:

- Controls Passed vs. Failed:
- Controls Passed: 55
- Controls Failed: 105
- Controls Not Checked: 84
- Total Controls Assessed: 244

## CAT I Findings:

- There were 21 automated checks related to CAT I issues and there were 5 manual checks associated with CAT I findings. 
- These findings indicate that the system has a substantial number of controls that failed or were not checked, resulting in a low overall compliance score of 34.38%. Furthermore, the checks related to CAT I issues require attention to improve the system's security posture.

![Score related to the findings.](Screenshots/HW3g.png)

#6. Screenshot pictured below:

![Command line version of the SCC tool.](Screenshots/HW3i.png)

Screenshot of the command line version of the SCC tool running on machine.

