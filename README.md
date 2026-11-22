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

1:1 **Task 1: Password Recovery for Three Protected PDF Files**

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

1:2 **Task 2: Password Recovery Using Networkwalks Hash Calculator and Password Cracker**

For the second part of my Week 3 assignment, I used the Networkwalks Hash Calculator and Password Cracker tools to perform another password-recovery exercise on one of the three previously assigned password-protected PDF documents.

The objective was to understand hash generation, password cracking using a wordlist and how different tools can be used to recover passwords from protected files.

**Step 1: Generating the Hash Using Networkwalks Hash Calculator**

I began by opening the Networkwalks Hash Calculator tool.

I selected one of the three assigned password-protected PDF documents and used the Hash Calculator to generate its hash value.

After the hash was successfully generated, I copied the resulting hash value for further analysis.

**Step 2: Saving the Generated Hash in a Text File**

After copying the generated hash, I opened Notepad on my Windows computer.

I pasted the copied hash into a new text document and saved it with a .txt extension.

This created a hash text file that I could upload to the password-cracking tool.

**Step 3: Uploading the Hash File to Networkwalks Password Cracker**

Next, I opened the Networkwalks Password Cracker tool.

I uploaded the saved .txt file containing the generated hash and initiated the password-recovery process.

However, the initial attempt was unsuccessful. The tool displayed an "Access Denied" message instead of recovering the password.

This indicated that the attempt had not produced the expected result.

**Step 4: Troubleshooting the Unsuccessful Attempt**

After receiving the "Access Denied" message, I reviewed the password-recovery process and considered an alternative approach.

I had been provided with a wordlist as part of the internship assignment, which contained potential password candidates.

I decided to use this wordlist for another password-cracking attempt.

**Step 5: Uploading the Provided Wordlist to Another Password-Cracking Tool**

I opened another password-cracking tool and uploaded the wordlist provided for the assignment.

The wordlist contained possible passwords that could be tested during the recovery exercise.

I proceeded with the password-cracking activity using the provided wordlist and the relevant password data.

**Step 6: Successful Password Recovery**

After performing the password-cracking exercise using the alternative tool and the provided wordlist, I successfully recovered the password.

This demonstrated how using an appropriate wordlist and an alternative password-recovery approach can help achieve the desired result when an initial attempt is unsuccessful.

**Result:** Password recovery exercise completed as instructed.
#

**6. Project Results**

| Task | Tools Used | Result |
|---|---|---|
| PDF 1 | HashCrack, John the Ripper, Johnny | Password recovered |
| PDF 2 | HashCrack, John the Ripper, Johnny | Password recovered |
| PDF 3 | HashCrack, John the Ripper, Johnny | Password recovered |
| Repeat Exercise | Networkwalks Hash Calculator, Password Cracker, Alternative Tool (worldlist) | Password recovered |
#

**7. Challenges Encountered and Solutions**

**Challenge 1:** Locating the John the Ripper Executable
After extracting John the Ripper, I initially had difficulty locating the john.exe executable.

**Solution:** I discovered that Windows was hiding known file extensions. The executable appeared as john with the file type displayed as Application.

**Challenge 2:** Configuring Johnny
I initially needed to establish the connection between Johnny and the John the Ripper engine.

**Solution:** I navigated to Johnny's Settings and specified the correct path to the John the Ripper executable. Johnny subsequently detected the installed version.

**Challenge 3:** Password Recovery Not Progressing
When I initially loaded the PDF hash, Johnny displayed zero recovered passwords.

**Solution:** I reviewed the attack configuration and discovered that the Wordlist file field was empty.

I selected the password.lst file, configured the Wordlist attack mode, and restarted the attack.

The tool subsequently recovered the password for the PDF being tested.
#

**8. Security Findings**

The practical exercise demonstrated several important password security concepts:

**_1. Password strength matters:_** Passwords that appear in commonly used wordlists may be vulnerable to dictionary attacks.

**_2. Password hashes can be tested offline:_** Where a supported PDF password hash can be extracted, password candidates may be tested without repeatedly opening the document.

**_3. Tool configuration affects results: _** Incorrect paths, missing wordlists and unsupported formats can prevent successful password recovery.

**_4. Password recovery is not guaranteed:_** The success of a wordlist attack depends on factors such as password complexity, the candidates available, and the PDF's encryption settings.

**_5. Document protection requires multiple safeguards:_** PDF passwords should be supported by appropriate access controls and secure document-handling practices.
#
**9. Security Recommendations**

Based on the exercise, I recommend the following practices:

- Use long, unique passwords or passphrases for sensitive PDF documents.
- Avoid common passwords and predictable patterns.
- Use a trusted password manager to generate and store strong passwords.
- Apply modern, supported PDF encryption settings.
- Restrict access to sensitive documents.
- Avoid sharing passwords through the same communication channel as protected documents.
- Perform password security assessments only on authorized files and systems.
#

**10. Key Lessons Learned**

This project improved my practical understanding of password security and password-recovery techniques.

I learned how to configure John the Ripper on Windows, integrate it with Johnny, extract PDF password hashes and perform wordlist-based password testing.

I also learned the importance of troubleshooting technical configurations before concluding that a tool is malfunctioning.

Most importantly, the exercise demonstrated how weak or predictable passwords can expose protected documents to unauthorized access.

The experience strengthened my problem-solving skills, technical documentation abilities and understanding of password-related cybersecurity risks.
#

**11. Evidence and Screenshots**
#
<img width="1065" height="487" alt="john exe" src="https://github.com/user-attachments/assets/63f769b0-d8b2-4f10-bc73-0a820eb0dbc8" />

<img width="590" height="188" alt="benchmarking result" src="https://github.com/user-attachments/assets/e8e7a34b-b922-4b34-8826-c65ff233a63f" />

<img width="1402" height="724" alt="johnny detect john ripper" src="https://github.com/user-attachments/assets/544cb15d-0480-4554-9b0d-a61f36b56132" />

<img width="1339" height="657" alt="worldlist config" src="https://github.com/user-attachments/assets/44196015-6ed1-43a0-824c-322e5ab5f3cd" />

<img width="979" height="577" alt="hash result 1" src="https://github.com/user-attachments/assets/fb33ae3f-d094-48ca-8df2-527b16ba9d60" />

<img width="1410" height="738" alt="suc PW result 1" src="https://github.com/user-attachments/assets/e6cb7f85-a624-4e6f-a723-735ba7e50d45" />

<img width="1018" height="489" alt="result 1" src="https://github.com/user-attachments/assets/66948189-d084-4fd6-9ad7-c3221b266641" />

<img width="991" height="619" alt="hash result 2" src="https://github.com/user-attachments/assets/1531fcfb-7463-4729-ba72-30abff08c72d" />


<img width="1378" height="612" alt="suc PW result 2" src="https://github.com/user-attachments/assets/0ec98a65-093f-4122-96fe-30727cc723a4" />

<img width="867" height="846" alt="result 2" src="https://github.com/user-attachments/assets/bbc92507-2378-41fe-8a8e-4be776d00046" />

<img width="997" height="618" alt="hash result 3" src="https://github.com/user-attachments/assets/3252623c-d527-4e64-bbfd-edb3b2e76d8f" />

<img width="1407" height="727" alt="suc PW result 3" src="https://github.com/user-attachments/assets/6613f923-61e5-4c94-932a-22747a990da3" />

<img width="886" height="837" alt="result 3" src="https://github.com/user-attachments/assets/2c0f3c9f-f3c4-438d-bfcd-4adb0680e441" />

<img width="1374" height="825" alt="NW hash result" src="https://github.com/user-attachments/assets/c1c441fe-6507-40d6-982f-26bfbfe7ed7a" />

<img width="1432" height="769" alt="NW pw result" src="https://github.com/user-attachments/assets/9d2d5974-bc85-4eeb-b9a5-22b872bc5df2" />
#

**12. Conclusion**
 
Week 3 of my Networkwalks Cybersecurity & Ethical Hacking Internship provided valuable hands-on experience in PDF password cracking, hash extraction, and password security assessment.

By working with John the Ripper, Johnny, HashCrack, and the Networkwalks password-related tools, I gained a better understanding of how password recovery works and the security risks associated with weak passwords.

The project also reinforced the importance of proper tool configuration, systematic troubleshooting, ethical cybersecurity practices, and clear technical reporting.
#

**Disclaimer**

All activities were performed as part of an authorized cybersecurity training exercise using assigned PDF documents.
#

👤 Author
Rukayat Sodiq
Cybersecurity Professional B084
linkedin.com/in/alaorukayatifeoluwa

----

📌 **Project Information**
**Program Name:** Cybersecurity program at Networkwalks | Week: 03 | Repository: GitHub

