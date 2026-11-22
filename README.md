# Password-Cracking-Using-John-the-Ripper-Johnny-HashCrack, NW Hash calculator & NW PW cracker
**W3-PM1 and W3-PM2  |  CYBERSECURITY  |  NETWORKWALKS**

**Project: Password Cracking and Hash Analysis**

**Environment: Windows**

**Status: Completed**
# 
**1. Project Overview**

During Week 3 of my Networkwalks Cybersecurity & Ethical Hacking Internship, I completed a practical password-cracking exercise focused on understanding PDF password protection, password hash extraction and password recovery techniques.

The assignment involved recovering passwords from three password-protected PDF files using different tools and approaches.

For the  three assigned PDF files, I used John the Ripper, Johnny (John the Ripper's graphical user interface) and HashCrack to perform password recovery.

After successfully recovering the passwords for all three PDFs, I selected one of the same documents and repeated the password-recovery exercise using the Networkwalks Hash Calculator and Password Cracker tools, as instructed.

This exercise helped me understand how password-cracking tools work, how password hashes are processed and why password strength is important in protecting sensitive documents.
#
**2. Project Objectives**

The objectives of this project were to:

- Understand the fundamentals of password cracking and password security.
- Explore password hash extraction from protected PDF documents.
- Install and configure John the Ripper and Johnny on Windows.
- Use HashCrack to extract password hashes for analysis.
- Perform wordlist-based password recovery using John the Ripper.
- Explore the Networkwalks Hash Calculator and Password Cracker tools.
- Document the password recovery process and results.
- Identify security lessons and recommend stronger password protection practices.
#
**3. Tools and Technologies Used**

| Tool | Purpose |
|---|---|
| John the Ripper	| Password recovery and hash testing
| Johnny        	| Graphical interface for John the Ripper
| HashCrack| 	    | PDF password hash extraction
| Networkwalks Hash Calculator	| Hash calculation and analysis
| Networkwalks Password Cracker	| Password recovery exercise
| Windows OS	    | Practical lab environment
| GitHub	        | Project documentation and reporting
#
**4. Lab Environment**
The practical exercise was performed on a Windows computer.

I installed John the Ripper and Johnny separately and configured Johnny to communicate with the John the Ripper executable.

To confirm that John the Ripper was functioning correctly, I executed the following command in Windows Command Prompt:
_john.exe --test_

The command successfully ran benchmark tests, confirming that the password-cracking engine was operational.

Next, I opened Johnny and navigated to its Settings section, where I configured the path to the John the Ripper executable.

Johnny successfully detected the installed John the Ripper version, confirming that both tools were connected.
#
**5. Methodology and Implementation**

**Task 1: Password Recovery for Three Protected PDF Files**

The first task involved recovering passwords from three assigned password-protected PDF documents.

**Step 1: Password Hash Extraction**

I used HashCrack to extract password hashes from the assigned PDF files.

The extracted hashes were saved in text files for subsequent analysis using Johnny and John the Ripper.

**Step 2: John the Ripper Installation and Verification**

I installed John the Ripper on Windows and located the executable within its installation directory.

I verified the installation by running the benchmark command and confirming that the tool completed its tests successfully.

**Step 3: Johnny Configuration**

I installed Johnny and configured its settings to point to the John the Ripper executable.

The application successfully detected John the Ripper, enabling me to perform password-recovery activities through the graphical interface.

**Step 4: Loading the Password Hashes**

I loaded the extracted password hash files into Johnny.

Johnny identified the PDF hash format, confirming that the files could be processed by the password-cracking engine.

**Step 5: Configuring the Password Attack**

I selected Wordlist mode and configured the wordlist file provided with John the Ripper.

This approach involved testing candidate passwords from a predefined list against the extracted PDF password hashes.

**Step 6: Password Recovery**

I initiated the password-recovery process and monitored the results through Johnny's interface.

During the practical exercise, I successfully recovered the password for one of the assigned PDF files.

The recovered password was displayed in Johnny's Password column, demonstrating that the wordlist-based approach had worked.

I continued the assigned exercises to complete the password-recovery activities for the three PDF files.
