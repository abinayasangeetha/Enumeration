# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

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

## site: 
This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com

![Screenshot 2024-04-09 132550](https://github.com/abinayasangeetha/Enumeration/assets/119393675/d9c8fa95-553d-41ba-9e83-74d68ceb1d30)
## filetype: 
This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com

![Screenshot 2024-04-09 132751](https://github.com/abinayasangeetha/Enumeration/assets/119393675/e7192550-22e9-47c3-8f65-99cad8523864)

## intext: 
This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.

![Screenshot 2024-04-09 132827](https://github.com/abinayasangeetha/Enumeration/assets/119393675/539574e9-72af-4aeb-9f5b-a17803f04d47)


## inurl: 
This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.

![Screenshot 2024-04-09 132923](https://github.com/abinayasangeetha/Enumeration/assets/119393675/bd3083ae-5c92-4a50-885a-531b0d24ea70)



## intitle:
This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.

![Screenshot 2024-04-09 133001](https://github.com/abinayasangeetha/Enumeration/assets/119393675/624369bc-1f95-44a2-aa59-499b78e7d78d)

## link: 
This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.

![Screenshot 2024-04-09 133033](https://github.com/abinayasangeetha/Enumeration/assets/119393675/20e2be24-261d-4678-885f-35baabf4c009)


## cache: 
This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

![Screenshot (267)](https://github.com/abinayasangeetha/Enumeration/assets/119393675/bd0bbab0-98c7-467c-8fa6-3aa237c734c7)

## DNS Recon
![image](https://github.com/abinayasangeetha/Enumeration/assets/119393675/a5399e02-31b5-4399-a2b6-3af5b2e526ac)
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion

## dnsenum
![image](https://github.com/abinayasangeetha/Enumeration/assets/119393675/93cd8155-aabf-4b59-a70a-d3e3c265ec32)
![image](https://github.com/abinayasangeetha/Enumeration/assets/119393675/64f5f227-b5e0-406d-bcc2-aba3e38fe4a6)
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.


## smtp-user-enum
![image](https://github.com/abinayasangeetha/Enumeration/assets/119393675/2dfdae60-39ef-40c0-9f9a-3fe9e61fa177)
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.
In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:
select any username in the first column of the above file and check the same
## Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.
![image](https://github.com/abinayasangeetha/Enumeration/assets/119393675/e4f109a4-8338-40e4-9c84-9001f89df56d)

## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

