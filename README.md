# Computer Forensics

## CFREDS ARCHIVE FOR DFIS CASES
https://cfreds-archive.nist.gov/

## Guide (ONLY SEEE WHEN NEEDED)
https://medium.com/@sshekhar01/cfreds-project-hacking-case-challenge-writeup-6a52883eac0b

# HACKING CASE :- encase img and 2nd part. use encase imager

## Evidences
* **1. What is the image hash? Does the acquisition and verification hash match?**
    ```Ans: aee4fcd9301c03b3b054623ca261959a```
* **2. What operating system was used on the computer?**
    ```Ans: Windows XP```
    ![Que2](/HackerCase%20imgs/que2.png)
    ![Que2_2](/HackerCase%20imgs/que2_2.png)
* **3. When was the install date?**
    ```Ans: Thursday, August 19, 2004 10:48:27 PM UTC```
    * FTK
    ![Que3](/HackerCase%20imgs/que3.png)
    * Autopsy
    ![Que3a](/HackerCase%20imgs/que3_a.png)
* **4. What is the timezone settings?**
    `Ans: Central Daylight Time`
    * FTK
    ![Que4](/HackerCase%20imgs/que4.png)
    * Autopsy
    ![Que4a](/HackerCase%20imgs/que4_a.png)
* **5. Who is the registered owner?**
    `Ans: Greg schardt`
    ![Que5](/HackerCase%20imgs/que5.png)
    * Autopsy
    `Refer Que 3 autopsy img`
* **6. What is the computer account name?**
    `Ans: Mr.Evil w.r.t autopsy, FTK shows N-1A9ODN6ZXK4LQ as computer name.`
    ![Que6](/HackerCase%20imgs/que6.png)
* **7. What is the primary domain name?**
    `Ans: N-1A9ODN6ZXK4LQ w.r.t autopsy, FTK show Mr.Evil`
* **8. When was the last recorded computer shutdown date/time?**
    `Ans: Reg Key:- ShutdownTime	REG_BIN	C4 FC 00 07 4D 8C C4 01 , TIME:- 2004-08-27 15:46:33.1092164 Z UTC`
    `Converter: https://www.digital-detective.net/dcode/`
* **9. How many accounts are recorded (total number)?**
    `Ans: 5, Administrator,Guest,HelpAssistant,Mr.Evil,SUPPORT_388945a0`

## 10. What is the account name of the user who mostly uses the computer?

## 11. Who was the last user to logon to the computer?

12. A search for the name of “G=r=e=g S=c=h=a=r=d=t” reveals multiple hits. One of these proves that G=r=e=g S=c=h=a=r=d=t is Mr. Evil and is also the administrator of this computer. What file is it? What software program does this file relate to?

13.  List the network cards used by this computer

14. This same file reports the IP address and MAC address of the computer. What are they?

15. An internet search for vendor name/model of NIC cards by MAC address can be used to find out which network interface was used. In the above answer, the first 3 hex characters of the MAC address report the vendor of the card. Which NIC card was used during the installation and set-up for LOOK@LAN?

16. Find 6 installed programs that may be used for hacking.

17. What is the SMTP email address for Mr. Evil?

18. What are the NNTP (news server) settings for Mr. Evil?

19. What two installed programs show this information?

20. List 5 newsgroups that Mr. Evil has subscribed to?

21. A popular IRC (Internet Relay Chat) program called MIRC was installed.  What are the user settings that was shown when the user was online and in a chat channel?

22. This IRC program has the capability to log chat sessions. List 3 IRC channels that the user of this computer accessed.

## 23. Ethereal, a popular “sniffing” program that can be used to intercept wired and wireless internet packets was also found to be installed. When TCP packets are collected and re-assembled, the default save directory is that users \My Documents directory. What is the name of the file that contains the intercepted data?
## 24. Viewing the file in a text format reveals much information about who and what was intercepted. What type of wireless computer was the victim (person who had his internet surfing recorded) using?

## 25. What websites was the victim accessing?

## 26. Search for the main users web based email address. What is it?

## 27. Yahoo mail, a popular web based email service, saves copies of the email under what file name?

## 28. How many executable files are in the recycle bin?

## 29. Are these files really deleted?

## 30. How many files are actually reported to be deleted by the file system?

## 31. Perform a Anti-Virus check. Are there any viruses on the computer?