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

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com
![image](https://github.com/karthika28112004/Enumeration/assets/128035087/a30d3dc2-3c1d-453f-bda7-87ff4183ea4a)


filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com
![image](https://github.com/karthika28112004/Enumeration/assets/128035087/cba210ce-ec5c-475b-93b7-9fd8567aabc3)



intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
![image](https://github.com/karthika28112004/Enumeration/assets/128035087/29267ac7-9669-4c2b-a7ca-d9a8e432871b)


inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
![image](https://github.com/karthika28112004/Enumeration/assets/128035087/30717c82-e7cc-4ec0-beda-a0e9c47788d0)

intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
![image](https://github.com/karthika28112004/Enumeration/assets/128035087/9e342596-60e7-4787-b061-bfa35f3b17fb)

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
![image](https://github.com/karthika28112004/Enumeration/assets/128035087/dcb45103-3578-480b-8c73-22b55a9d1bc1)

cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.
![image](https://github.com/karthika28112004/Enumeration/assets/128035087/2a3ffa41-d54b-4bea-831d-30a55a6d51a7)

 



##DNS Recon
![image](https://github.com/karthika28112004/Enumeration/assets/128035087/203faabe-cec6-460d-b924-d21b362b2b2d)

provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion








##dnsenum
![image](https://github.com/karthika28112004/Enumeration/assets/128035087/b4fd8cd4-5aaf-4a0c-b5b2-cbccbbc95da6)
![image](https://github.com/karthika28112004/Enumeration/assets/128035087/5bbcaf21-928d-45ef-90fb-6a274c98be99)

Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).Get the namservers (threaded).Get the MX record (threaded).Perform axfr queries on nameservers and get BIND versions(threaded).Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).Calculate C class domain network ranges and perform whois queries on them (threaded).Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).Write to domain_ips.txt file ip-blocks.This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.


##smtp-user-enum
![image](https://github.com/karthika28112004/Enumeration/assets/128035087/4c1f9fd7-8ed4-46c0-8250-16bd379da6cb)

Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same


#Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
  

## nmap –script smtp-enum-users.nse <hostname>
![image](https://github.com/karthika28112004/Enumeration/assets/128035087/dc43ed1d-be83-439a-9b3f-335e3c0a97f8)

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.





## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

