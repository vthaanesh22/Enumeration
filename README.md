# Enumeration
Enumeration Techniques

# AIM:
To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1: 

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com
![image](https://github.com/user-attachments/assets/58216641-c0bd-4e89-a231-99faf7dbf9fc)


filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com
![image](https://github.com/user-attachments/assets/c11acf58-dcdf-43cb-9ca0-3d0fa7d2d75e)



intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
![image](https://github.com/user-attachments/assets/1318ee9f-e08d-4f22-b885-1b74cd05ea9d)


inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
![image](https://github.com/user-attachments/assets/fa009f86-18d4-46a7-97e4-c1ebbd4d3529)


intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
![image](https://github.com/user-attachments/assets/18f3bd31-bb7b-4e8e-a342-e6139b457800)

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
![image](https://github.com/user-attachments/assets/eba53b47-2d97-491e-96d7-40c3447b396a)

 
#DNS Enumeration



##DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
## OUTPUT:
![Screenshot 2025-03-14 083751](https://github.com/user-attachments/assets/b469a9e2-c9f2-4751-9b52-db844701dd2f)







## dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:
![Screenshot 2025-03-14 084332](https://github.com/user-attachments/assets/a5af77d2-e56d-47cc-9aee-f5e550033a89)




## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same


#Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
 ##Output
 ![WhatsApp Image 2025-03-14 at 09 15 27_6a0766c2](https://github.com/user-attachments/assets/ea63da02-914b-47db-917d-eb350732032c)

 
  

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


## OUTPUT:
![WhatsApp Image 2025-03-14 at 09 17 21_27505ca4](https://github.com/user-attachments/assets/b0dc8bd8-1793-4f23-8f0a-7c18c374c4b5)




## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

