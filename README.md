# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

## Step 1:
Install kali linux either in partition or virtual box or in live mode

## Step 2:
Investigate on the various categories of tools as follows:

## Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering


## OUTPUT:
```
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.
```
![exp3 1](https://github.com/AasrithSairam/InformationGathering/assets/139331438/8073bbb4-8096-4ea5-b869-13d74a01b22b)
```
## Finding IP address:
```
![exp3 22](https://github.com/AasrithSairam/InformationGathering/assets/139331438/16c88e57-eec7-4f05-a8f1-7063c3c0b713)
```
## Finding Hosting Company
```
![exp 3 2](https://github.com/AasrithSairam/InformationGathering/assets/139331438/2918045f-3d7f-4f53-8364-9354d950db9b)
```
## HISTORY OF WEBSITE:
https://web.archive.org/
```
![exp3 3](https://github.com/AasrithSairam/InformationGathering/assets/139331438/63655689-d409-4664-bf73-779001518888)
```
## Webserver Fingerprinting:
Netcat:
nc 172.17.52.118 80
```
![exp3 4](https://github.com/AasrithSairam/InformationGathering/assets/139331438/c3a3f1d3-0447-4bec-acc4-c0c9ed8bcf2e)
```
## nmap:
nmap -p 21 -sV --script=banner ftp.vim.org
```
![exp3 5](https://github.com/AasrithSairam/InformationGathering/assets/139331438/27a9cf22-8623-49c3-84a7-7f36f4e27c88)
```
## WHATWEB
command: whatweb zoho.com
```
![exp3 6](https://github.com/AasrithSairam/InformationGathering/assets/139331438/c8fb4fc5-8ae8-49e0-a7b0-fa570a2b0e3b)
```
## httprint:
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
![exp3 7](https://github.com/AasrithSairam/InformationGathering/assets/139331438/284f9fc4-7a08-42f7-8f05-82a0812377a6)
```
## Tracing the Location
TCP Traceroute:
sudo traceroute -T www.saveetha.ac.in
```
![exp3 8](https://github.com/AasrithSairam/InformationGathering/assets/139331438/3bf6c050-5b89-406a-9cb4-f4a3df8cbaad)
```
## UDP Traceroute:
sudo traceroute -U www.saveetha.ac.in
```
![exp3 9](https://github.com/AasrithSairam/InformationGathering/assets/139331438/809f6120-17e4-49e7-8b5b-bdd1d51e8b51)
```
## ICMP Traceroute:
sudo traceroute  www.saveetha.ac.in
```
![exp3 10](https://github.com/AasrithSairam/InformationGathering/assets/139331438/08e1c767-bbfc-412d-8082-918c10100a29)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
