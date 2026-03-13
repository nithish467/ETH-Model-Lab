# ETH-Model-Lab

# InformationGathering
Information Gathering Techiques

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

http://www.whois.com/whois website

## OUTPUT:

<img width="1919" height="929" alt="image" src="https://github.com/user-attachments/assets/76df4227-73bf-4f94-b4dd-de86cc7da06d" />



## Finding IP address:
ping.sony.com
##output 

<img width="696" height="131" alt="image" src="https://github.com/user-attachments/assets/8884399b-d5a0-4972-bd81-2e417cbe26b0" />




## Finding Hosting Company
get further detail by using ip2location.com website.
## output
<img width="933" height="899" alt="image" src="https://github.com/user-attachments/assets/aae8b70c-fa5b-4286-89e8-d622653c0379" />



## History of the website:
## output
https://web.archive.org/
<img width="1901" height="927" alt="image" src="https://github.com/user-attachments/assets/38c0b556-d706-46f7-95dd-6d87b4d84771" />

<img width="1900" height="730" alt="image" src="https://github.com/user-attachments/assets/24b85087-e8e0-4d08-8eb1-7515af26463e" />


# Webserver Fingerprinting:

## Netcat:
sudo nc sony.com 80

<img width="656" height="146" alt="image" src="https://github.com/user-attachments/assets/b041196e-af10-4931-a98b-620a1897ee1e" />



## nmap:
### output
<img width="801" height="270" alt="Screenshot From 2026-01-31 12-18-35" src="https://github.com/user-attachments/assets/8fbfd33f-957a-4687-ab5a-cdfe86b93dfc" />


## Whatweb
### output
<img width="1689" height="141" alt="Screenshot From 2026-01-31 12-24-03" src="https://github.com/user-attachments/assets/9bbf4c33-889a-4d3e-8f84-674e333e8525" />


## httprint
### output
<img width="714" height="896" alt="image" src="https://github.com/user-attachments/assets/4f93517a-d8f3-4360-8e16-162927914026" />




# Tracing the Location
TCP Traceroute:
sudo traceroute -T sony.com
## output
<img width="844" height="116" alt="Screenshot From 2026-01-31 12-42-14" src="https://github.com/user-attachments/assets/8be46a61-5898-47ee-a83a-94059414b3d8" />


## UDP Traceroute:
sudo traceroute -U sony.com
## output
<img width="619" height="620" alt="Screenshot From 2026-01-31 12-17-08" src="https://github.com/user-attachments/assets/d1a2b275-c29c-40a7-91db-b83fac0c004d" />



## ICMP Traceroute:
sudo traceroute sony.com
## output
<img width="619" height="620" alt="Screenshot From 2026-01-31 12-16-52" src="https://github.com/user-attachments/assets/62ab1d72-e9b2-4936-8ba2-9d975e782b8b" />






## RESULT:
The information gathering techniques tools/procedure were  identified successfully
