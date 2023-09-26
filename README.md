# <p align="center">To perform information gathering techniques ...</p>


## AIM:

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

![k1](https://github.com/Vishwarathinam/InformationGathering/assets/95266350/814a55d7-34ec-460b-9e27-67c2ab142548)


## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
## Output:
![k2](https://github.com/Vishwarathinam/InformationGathering/assets/95266350/6cd6bfcd-11d1-4a3b-b62e-6c7ca12b5353)



## Finding Hosting Company
get further detail by using ip2location.com website.
## Output:
![k3](https://github.com/Vishwarathinam/InformationGathering/assets/95266350/16b21faf-aa69-4f4d-a1e3-cdcd1b0b61bc)



## History of the website:
## Output:
https://web.archive.org/

![k4](https://github.com/Vishwarathinam/InformationGathering/assets/95266350/2a947a4e-f4b0-4d76-a14a-ea3260b4a1a4)



# Webserver Fingerprinting:

## Netcat:
```
nc 172.17.52.118 80
```
## Output:

![k5](https://github.com/Vishwarathinam/InformationGathering/assets/95266350/6c09329d-101c-4e8c-abed-97484e241c32)




## nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## Output:

![k6](https://github.com/Vishwarathinam/InformationGathering/assets/95266350/d8a54b98-5baa-4fe5-ae64-7503d5be2b39)


## Whatweb:
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```
## Output:
![k7](https://github.com/Vishwarathinam/InformationGathering/assets/95266350/9daf8959-78cf-424f-a128-88517717a735)

![k8](https://github.com/Vishwarathinam/InformationGathering/assets/95266350/87bf2269-9946-4c25-8714-1ef26f645c70)

## httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## Output:

![k9](https://github.com/Vishwarathinam/InformationGathering/assets/95266350/bac139bf-0ee1-453a-b02a-9e8793c36acc)



# Tracing the Location
## TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
## Output:

![k10](https://github.com/Vishwarathinam/InformationGathering/assets/95266350/bfda418e-77c9-4dcd-9842-3f99e1e9a34a)





## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
## Output:

![k11](https://github.com/Vishwarathinam/InformationGathering/assets/95266350/b09ae2b4-6899-4507-8a24-dab55d3ae7b2)


## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## Output:
![k12](https://github.com/Vishwarathinam/InformationGathering/assets/95266350/4c393b7f-fdd0-4e7f-ad37-7b5daaf97db9)


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
