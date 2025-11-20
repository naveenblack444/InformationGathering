# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:

<img width="1220" height="630" alt="Screenshot 2025-11-20 204045" src="https://github.com/user-attachments/assets/3dd5dbba-1c5a-45b2-83b0-175f5a58227e" />


## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
## output

![Alt text](img/1.png)

## Finding Hosting Company
get further detail by using ip2location.com website.
## output

<img width="1544" height="774" alt="Screenshot 2025-11-20 204857" src="https://github.com/user-attachments/assets/2b378b67-6bb0-47ce-82a3-d7182549d008" />


## History of the website:
## output
https://web.archive.org/

<img width="1249" height="563" alt="Screenshot 2025-11-20 205539" src="https://github.com/user-attachments/assets/e9f2f752-6ea3-41b4-b2ea-09458afb6b14" />


# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com

### output

![Alt text](img/2.png)

## nmap:
### output

![Alt text](img/3.png)

## Whatweb
### output

![Alt text](img/4.png)
![Alt text](img/5.png)
![Alt text](img/6.png)

## httprint
### output

![Alt text](img/7.png)

![Alt text](img/8.png)

# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output

![Alt text](img/9.png)

## UDP Traceroute:
sudo traceroute -U www.google.com
## output

![Alt text](img/10.png)

## ICMP Traceroute:
sudo traceroute  www.google.com
## output

![Alt text](img/11.png)




## RESULT:
The information gathering techniques tools/procedure were  identified successfully
