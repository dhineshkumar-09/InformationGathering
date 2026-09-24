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
![image](https://github.com/user-attachments/assets/19bd504c-a8a5-4598-8f57-37cc2e9bf01f)

## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of youtube .com

## OUTPUT:
![image](https://github.com/user-attachments/assets/bc3c108f-80d5-4ec8-a941-e4752482b876)


## Finding Hosting Company:
get further detail by using ip2location.com website.
## OUTPUT :
![image](https://github.com/user-attachments/assets/20279658-a27c-4476-8755-57f0e7af91ef)


## History of the website:
https://web.archive.org/

## OUTPUT :
![image](https://github.com/user-attachments/assets/1bbd2916-22f8-4056-8707-d4b3496442bf)
![image](https://github.com/user-attachments/assets/7cfbd5af-c934-46da-823f-d6c7cc968277)


## Webserver Fingerprinting:
## Netcat:
nc 172.17.52.118 80

## OUTPUT:
![image](https://github.com/user-attachments/assets/1498687d-e171-43ee-bc89-ecba11caab7e)


## nmap:

nmap -p 21 -sV --script=banner ftp.vim.org
## OUTPUT :
![image](https://github.com/user-attachments/assets/5f3c9a0e-8613-4c44-a3f2-2bc0009c1fb1)


## Whatweb:
## OUTPUT:
![image](https://github.com/user-attachments/assets/b22f49ac-8145-45f0-92e8-40f8dfc3eb7f)



## httprint:
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
## OUTPUT :
![420418073-ab3f61a1-c3f7-4787-8c4a-cc92f2b65b9d](https://github.com/user-attachments/assets/92a43e6a-8282-4bda-8d73-2501f25d3a5b)


## Tracing the Location:
## TCP Traceroute:
sudo traceroute -T www.instagram.com
## OUTPUT :
![image](https://github.com/user-attachments/assets/d359a095-0a39-45a0-afea-8e30f6410488)


## UDP Traceroute:
sudo traceroute -U www.instagram.com
## OUTPUT :
![image](https://github.com/user-attachments/assets/3209be79-e9b4-4bb8-ae84-bf3c4373e6c8)

## ICMP Traceroute:
sudo traceroute  www.facebook.com
## OUTPUT :
![image](https://github.com/user-attachments/assets/977aa607-6a83-46bc-8307-3963135d991f)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
