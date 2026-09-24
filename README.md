# Networkwalks-B083-Week-3-cybersecurity
PASSWORD CRACKING WITH JTR CYBERSECURITY &amp; ETHICAL HACKING PROJECT TASKS
<p align="center">
  <img src="https://img.shields.io/badge/Skill-Cybersecurity-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ver-Virtualbox%20v7.2-0070C0?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Kali%20Linux-v2026.2-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Linux-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Network-10.0.0.0%2F24-238F89?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Skill-Virtualization-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/GitHub-404040?style=flat-square&labelColor=0070C0&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Kali%20Linux-404040?style=flat-square&labelColor=C00000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/NetworkWalks-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ethical%20Hacking-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
</p>

# 1. Project Overview
The first phase focused on using John the Ripper, a password security auditing and password-cracking tool.

# 2. Project Objectives
The main objectives of this project are to:
* ➡️ Obtaining the authorized password-protected PDF files
* ➡️ Extracting the required hash information using OnlineHashCrack
* ➡️ Saving the extracted hash in a text file
* ➡️ Feeding the hash into John the Ripper
* ➡️ Performing password-cracking analysis
* ➡️ Recovering the password
* ➡️ Using the recovered password to access the protected PDF

# 3. Key Concepts I Practiced
Password hashing and hash extraction
* 🔹 PDF password protection
* 🔹 Password-cracking methodologies
* 🔹 John the Ripper
* 🔹 Online password-security assessment tools
* 🔹 Hash-based password recovery
* 🔹 Security testing methodology
* 🔹 Documenting technical findings and evidence
* 🔹 Understanding the risks associated with weak password

   Key Security Lesson

  # 4. Lab Setup Procedure
  # <sub> Step 1: Download John the Ripper from official website on your windows PC.
  
https://www.openwall.com/john/  
Or  
https://distro.ibiblio.org/openwall/projects/john/1.9.0/  
Or   
you can download from Google Drive: https://drive.google.com/drive/u/1/folders/1aHtgOh7U9mQhkN8VHU7ctTyaDg5KbuJx

<img width="1440" height="864" alt="Screenshot 2026-09-22 194322" src="https://github.com/user-attachments/assets/917cab10-f27f-4ae0-a12d-4c5d525b5790" />

# <sub> Step 2: Download Johnny GUI from official website

https://openwall.info/wiki/john/johnny  
Or 
you can download from Google Drive: https://drive.google.com/drive/u/1/folders/1aHtgOh7U9mQhkN8VHU7ctTyaDg5KbuJx
<img width="1440" height="900" alt="Screenshot 2026-09-22 195315" src="https://github.com/user-attachments/assets/5b55517f-f8ec-4d81-a697-c9d8bce7e822" />

# <sub> Run the setup file & install Johnny as shown in below:
<img width="118" height="59" alt="Screenshot 2026-09-22 195950" src="https://github.com/user-attachments/assets/40b2bf00-559c-4577-9eff-ef6bdf238609" />

# <sub> After installation, open Johnny:
<img width="218" height="125" alt="Screenshot 2026-09-22 200049" src="https://github.com/user-attachments/assets/9162fc4a-101e-4bb8-89ef-01db0aae8266" />

# <sub> Click on settings & browse:
<img width="301" height="236" alt="Screenshot 2026-09-22 200148" src="https://github.com/user-attachments/assets/6ffa9193-6f00-4718-b37b-3e1659ca3597" />

# <sub> Select John.exe:
<img width="1440" height="900" alt="Screenshot 2026-09-22 200704" src="https://github.com/user-attachments/assets/3c378f35-4ad7-4804-83e4-1a78a0380416" />
*john.exe file is located in the run folder as shown in this screenshot.

# <img width="690" height="355" alt="Screenshot 2026-09-22 200853" src="https://github.com/user-attachments/assets/e8ecaa60-21ee-48fe-8e0a-8311db7e0e29" />

# <sub> Step 3: Follow below steps to crack the password.

<img width="79" height="20" alt="Screenshot 2026-09-22 202002" src="https://github.com/user-attachments/assets/c703c49f-153c-4eba-b029-b70f9ad57710" />

Download the encrypted PDF file to your PC:

Open the hash website & upload your pdf file to find its hash:

https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php

<img width="1440" height="900" alt="Screenshot 2026-09-22 202527" src="https://github.com/user-attachments/assets/e241674b-396a-4bb4-bfc2-786ae4ce159b" />

Browse the PDF file & click on Upload:

<img width="1440" height="864" alt="Screenshot 2026-09-24 160534" src="https://github.com/user-attachments/assets/8efe690e-ec8a-4331-980a-e4e997c5b946" />

Select & copy the hash value:

<img width="1440" height="864" alt="Screenshot 2026-09-24 160554" src="https://github.com/user-attachments/assets/60c990ab-e946-4e94-8a61-d5246f1ba626" />

*Note: If your hash contains extra characters like b' in the start then make sure to remove those when saving in txt file (hash value should be in the format shown in above screenshot i.e. starting with $pdf$....).

Open notepad:

<img width="919" height="533" alt="Screenshot 2026-09-24 161424" src="https://github.com/user-attachments/assets/9b3905c4-a864-4cd2-96a7-883c6492f91f" />

Save as text file:

<img width="919" height="533" alt="Screenshot 2026-09-24 161456" src="https://github.com/user-attachments/assets/8b8d2ac5-db05-4bc1-b4ad-4a09bc179ec4" />

Click on ‘Open password file’:

<img width="438" height="350" alt="Screenshot 2026-09-24 161734" src="https://github.com/user-attachments/assets/2dd0b65a-ea1d-4e3c-a523-3af51bf4b961" />

Click on ‘Start new attack’:

<img width="438" height="350" alt="Screenshot 2026-09-24 161927" src="https://github.com/user-attachments/assets/073dd9eb-1f07-4cc1-8cba-1fc3a45456ee" />

Your PDF file password will be cracked (it might take some time depending on your computer speed & password complexity):

Enter password1 (which you have just cracked):

<img width="1440" height="864" alt="Screenshot 2026-09-24 160040" src="https://github.com/user-attachments/assets/6e29b045-8141-4846-9e1a-2f874fab7eea" />



# 👤 Author
**Rahul Rathore**

Cybersecurity Starter

LinkedIn: www.linkedin.com/in/rahul-rathore91

# Project Imformation

**Program Name:** Cybersecurity at Networkwalks | **Week: 03 | Project:** **Module 1** PASSWORD CRACKING WITH JTR CYBERSECURITY | 

**Repository:** GitHub.com












